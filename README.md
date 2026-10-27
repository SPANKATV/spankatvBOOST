# spankatvBOOST

Companheiro para AION 2 com interface SPANKATV, medidores, acompanhamento de coleção, rotas, overlays e minimapa separado de Hidden Cubes.

## Instalar e atualizar

Baixe o instalador da versão mais recente em **Releases**. Encerre o aplicativo antes de atualizar. O instalador verifica a integridade dos arquivos e preserva os perfis no AppData.

Quem usa a 0.5.1 precisa instalar a 0.5.2 manualmente uma vez. Depois, o botão **Atualizações** verifica as releases deste repositório, mostra as notas e permite baixar e instalar novas versões. O canal é `SPANKATV/spankatvBOOST`.

## Notas da 0.5.2

- Gerenciador de Tarefas: processo principal e subprocessos identificados como **spankatvBOOST**.
- Capturador identificado como **spankatvBOOST Áudio**.
- Painel de notas de correção e atualizações pelo GitHub Releases.
- Download de atualização com verificação SHA-256.
- Inclui detecção experimental do som de cubo, prévia de 45 segundos, notificações e minimapa separado.

## Som do cubo

Em **Som do cubo**, use **Testar notificação** e **Ativar escuta contínua**. A captura escuta a saída padrão inteira do PC, sem microfone e sem salvar áudio contínuo. Alterar o dispositivo de saída exige parar e reiniciar a escuta. Reconhecimento experimental: não há garantia de ausência de falsos alertas. Pontos possíveis no mapa não significam cubos presentes.

## Base e créditos

Adaptação local do a2finder por julusi, sob **GPL-3.0-only**, com módulos próprios em JavaScript e C#. Créditos e licenças acompanham a distribuição. A interface baseada no a2finder mantém a autenticação, os serviços e as permissões da conta original; o spankatvBOOST não substitui essa conta. Não há código do Shugo incorporado.

NAudio 1.10.0, Mark Heath e contribuidores, sob Microsoft Public License, é usado pelo capturador separado de áudio. Electron e demais componentes mantêm suas licenças originais. O aplicativo não é um produto oficial da NCSOFT.

Não executa caminhada automática nem missões completas. O módulo local de combate é experimental e inicia em simulação. Dados fictícios de testes não são apresentados como dados ao vivo.
