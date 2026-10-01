# DynNetDiag - Desktop releases

Instaladores da aplicação desktop **DynNetDiag** (editor de diagramas de rede).

- **Download:** secção [Releases](../../releases/latest)
  - Windows x64: `DynNetDiag-Setup-<versão>.exe`
  - macOS Apple Silicon: `DynNetDiag-<versão>-arm64.dmg` · macOS Intel: `DynNetDiag-<versão>-x64.dmg`
- A aplicação instalada verifica atualizações automaticamente ao arrancar
  (este repositório é o feed de atualizações - `latest.yml` / `latest-mac.yml`).
- Windows: o instalador ainda não é assinado digitalmente; o SmartScreen pode
  mostrar "Editor desconhecido" → *Mais informações* → *Executar mesmo assim*.
- macOS: a app ainda não é notarizada pela Apple; na primeira abertura aparece
  "Apple could not verify…". Abrir em *Definições do Sistema → Privacidade e
  Segurança → Abrir na mesma* (ou `xattr -dr com.apple.quarantine /Applications/DynNetDiag.app`).

## Sobre "Source code (zip / tar.gz)"

O GitHub junta automaticamente esses dois ficheiros a todas as releases. Neste
repositório eles contêm **apenas este README** - não incluem o código-fonte da
aplicação. Este repositório contém apenas os binários publicados; o código-fonte
é privado.
