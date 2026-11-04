# patches/

Patches do `patch-package`, aplicados no `postinstall` e no build Docker (o Dockerfile copia esta pasta antes do `npm ci`).
Mantenha a pasta versionada mesmo sem patches: sem ela o `COPY ./patches` do Dockerfile falha.
