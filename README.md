# ZodiacoLurk Releases

Repositório oficial dos instaladores do **Zodíaco Viewer** para Windows.

O workflow deste repositório compila o projeto principal [`EditoraFX/ZodiacoLurk`](https://github.com/EditoraFX/ZodiacoLurk) em um runner Windows com o toolchain nativo necessário e publica os artefatos NSIS na release correspondente.

## Publicação

- Versão publicada: `v1.0.1` (também disponível: `v1.0.0`)
- Plataforma: Windows 10/11 x64
- Pacote: instalador NSIS
- Origem do código: branch `main` do repositório principal

Instalador desta versão: `Zodiaco-Viewer-1.0.1-x64-setup.exe`

O manifesto `latest.json` e o arquivo `.sig` acompanham a release para permitir o auto-update assinado do aplicativo.

Para futuras versões, o repositório precisa dos secrets `ZODIACO_SOURCE_TOKEN`, `TAURI_SIGNING_PRIVATE_KEY` e `TAURI_SIGNING_PRIVATE_KEY_PASSWORD`. A chave privada nunca deve ser commitada.

O site aponta sempre para a página de releases, que é a fonte oficial do download:
https://github.com/EditoraFX/ZodiacoLurk-Releases/releases
