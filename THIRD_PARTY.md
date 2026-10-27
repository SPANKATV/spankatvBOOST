# Componentes e atribuição

## a2finder / Badezir Tracker

- Autor declarado no pacote: **julusi**.
- Versão integrada: **0.29.1**. A versão anterior **0.28.21** foi mantida como backup dos módulos.
- Licença declarada em `package.json`: **GPL-3.0-only**.
- Repositório indicado pelo atualizador original: https://github.com/chrystianismo-lang/badezir-tracker
- Fonte utilizada: JavaScript empacotado da instalação local fornecida pelo usuário. O repositório consultado contém apresentação do produto; não afirmamos possuir os arquivos TypeScript originais completos.
- Origem, hash e alterações: `resources/app/vendor/provenance.json`.
- Arquivo original analisado: `resources/app/vendor/upstream-main.js`.
- Módulos adaptados: `vendor/engine.cjs`, `vendor/captureWorker.js`, `vendor/chunks/tcp-CuQ5DJ4y.js`.

Alterações em 27/10/2026: separação dos módulos puros de análise; interface SPANKATV própria; persistência própria; integração com serviço nativo; janelas compactas; transparência por janela; integração de DPS, radar, coleção, buffs, recargas e replay. Atualização para 0.29.1 e incorporação do módulo Farm; calculadora de spots própria; barra e radar separados; energia estimada. Os serviços de autenticação, VIP e atualização originais não são chamados por esta aplicação. Recursos com gating VIP no app original, como radar de cubos e análise de concorrência, não são ativados aqui.

## Dados do jogo e catálogos

O README original atribui dados de mascotes, spawns e drops a **metabot.gg**: https://metabot.gg . Conteúdo de AION 2 pertence aos respectivos titulares, incluindo NCSOFT. A adaptação preserva nomes e dados dos catálogos. Mapas e ícones foram extraídos da instalação fornecida pelo usuário para uso na interface local; permanecem recursos de terceiros em `assets/game`, fora da reivindicação de autoria do código e sem concessão de direitos adicionais sobre a arte.

## Electron, Chromium e dependências

O runtime Electron e suas dependências são reutilizados da instalação local. Avisos preservados: `LICENSE.electron.txt`, `LICENSES.chromium.html`. Os componentes nativos **koffi** e **@koromix/koffi-win32-x64** mantêm seus próprios arquivos de licença em `resources/app/node_modules`.

Npcap é uma dependência instalada separadamente, não redistribuída: https://npcap.com .

## Imagem SPANKA

`resources/app/assets/spanka.png` foi fornecida pelo usuário por sua conta conectada do Google Drive, arquivo SPANKA.png. É utilizada por solicitação do usuário para sua interface local. Os direitos sobre a imagem, personagens e marcas pertencem aos respectivos titulares. A licença GPL do código não concede direitos sobre essa imagem.

## Shugo

Referência de organização visual: https://shugo.gg/app . Código e imagens do Shugo não foram incluídos no aplicativo.

## Atreia Lens

Referência de interação: barra compacta com atalhos, Hub e trava de cliques, observados na interface e nas capturas do usuário. Site indicado pelo executável: https://atreialens.hartmannlab.xyz . Repositório público consultado: https://github.com/ThomasHartmannDev/atreia-lens-releases . O repositório afirma disponibilizar somente instaladores e manifestos, sem código-fonte; nenhuma licença de reutilização foi localizada na pasta instalada. A barra e a navegação do spankatv foram implementadas de forma independente. Nenhum código ou recurso visual do Atreia Lens foi copiado.
