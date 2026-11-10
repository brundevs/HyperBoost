# <img src="assets/logo.svg" alt="" width="32" height="32" valign="middle"> HyperBoost

Otimize seu PC para jogar, limpe o Windows e acompanhe o desempenho em um só lugar. Revise cada ajuste antes de aplicar e use a Recuperação para desfazer alterações compatíveis.

## Baixar para Windows

**[Baixar o instalador oficial (.exe) — v1.0.12](https://github.com/brundevs/HyperBoost/releases/download/v1.0.12/HyperBoost-Setup-1.0.12.exe)**

Windows 10 e 11, 64 bits · Comece grátis, sem conta.

[Versão estável mais recente e notas da versão](https://github.com/brundevs/HyperBoost/releases/latest) · [Checksums SHA-256 da v1.0.12](https://github.com/brundevs/HyperBoost/releases/download/v1.0.12/HyperBoost-1.0.12-SHA256SUMS.txt) · [Site oficial](https://www.hyperboostapps.com)

Para verificar o instalador, execute `Get-FileHash .\HyperBoost-Setup-1.0.12.exe -Algorithm SHA256` no PowerShell, na pasta do download. Compare o resultado com o hash do instalador no arquivo de checksums.

1. Execute o instalador. O Windows solicitará permissão de administrador.
2. Abra o HyperBoost, siga a introdução e aguarde a confirmação do ponto de restauração. Se aparecer um erro, confira a orientação do aplicativo antes de continuar.

O aplicativo verifica atualizações e preserva suas configurações e seu histórico. O download e o reinício respeitam suas preferências e as operações em andamento. [Como atualizar](RELEASES.md).

## Modo Jogo

**Incluído no Pro e no Founder.** Escolha um perfil e ative a detecção automática. Ao abrir um jogo compatível, o HyperBoost aplica as ações que você escolheu para a partida. Ao encerrar o jogo, ele restaura as ações temporárias que oferecem recuperação.

![Tela principal do Modo Jogo do HyperBoost, com perfis e ajustes para a partida](assets/screens/1.0.12/pt/games-main.webp)

<sub>HyperBoost 1.0.12 · Tela principal do Modo Jogo.</sub>

O monitor é opcional e começa desligado. Quando a captura é compatível com o jogo, ele permite acompanhar FPS e uso de recursos. [Veja como configurar o Modo Jogo](https://www.hyperboostapps.com/ferramentas/modo-jogo?lang=pt).

## Gratuito, Pro e Founder

| Plano | O que está incluído |
| --- | --- |
| **Gratuito** | Limpeza de temporários e caches, gerenciamento da inicialização, monitoramento de CPU, memória e disco, teste de internet, diagnóstico de periféricos e recuperação de alterações compatíveis. |
| **Pro** | Tudo do Gratuito, mais **PC Boost**, **Modo Jogo e biblioteca de jogos**, ajustes de apps e latência, limpeza automática de memória, ajustes de rede e DNS, Tweaks, ajustes do Windows e ferramentas de Hardware e BIOS. Assinatura mensal, trimestral ou anual. |
| **Founder** | Ferramentas do Gratuito e do Pro com acesso vitalício, em pagamento único, conforme disponibilidade no site. |

A disponibilidade dos ajustes depende do Windows, do hardware e dos drivers. Limpezas e algumas remoções são irreversíveis. [Compare os planos e consulte os preços da sua região](https://www.hyperboostapps.com/precos?lang=pt).

## Guias das ferramentas

Veja as capturas e saiba quando usar cada recurso. [Português](docs/ferramentas.md) · [English](docs/tools.en.md) · [Español](docs/herramientas.es.md)

<details>
<summary>Veja a tela inicial do HyperBoost</summary>

![Tela Início do HyperBoost, com monitoramento e acesso às ferramentas](assets/screens/1.0.10/pt/home-r3.webp)

<sub>HyperBoost 1.0.10 · Tela inicial do aplicativo.</sub>

</details>

## Ajuda e comunidade

- [Perguntas frequentes](https://www.hyperboostapps.com/faq?lang=pt)
- [Guia para começar](https://www.hyperboostapps.com/como-usar?lang=pt)
- [Suporte oficial](https://www.hyperboostapps.com/suporte?lang=pt)
- [Comunidade no Discord](https://discord.gg/wZn9XebX5B)
- [Avaliações de usuários](https://www.hyperboostapps.com/avaliacoes?lang=pt)
- [Sugerir uma melhoria](https://github.com/brundevs/HyperBoost/issues/new?template=improvement.yml)

Para uma falha no aplicativo, use **Reportar erro** na notificação: contas grátis e Pro conectadas podem revisar o relato antes de enviá-lo ao suporte. Você também pode [abrir um problema público](https://github.com/brundevs/HyperBoost/issues/new?template=bug.yml) neste repositório. Informe as versões do HyperBoost e do Windows e não publique senhas, tokens ou dados pessoais.

## Sobre este repositório

Este é o canal público de distribuição e documentação do HyperBoost. Os instaladores e arquivos de verificação estão em [Releases](https://github.com/brundevs/HyperBoost/releases); o código-fonte do aplicativo é privado.

HyperBoost é um software proprietário. As licenças e atribuições dos componentes utilizados acompanham a instalação.
