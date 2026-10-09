# 🤖 Ottobot

Um robozinho de mesa emocional: dois olhos animados numa telinha OLED, um sensor de toque na cabeça, um sensor de movimento e um buzzer. Ele tem humor, pede carinho, conta piadas, joga, canta e dança, mostra o clima, faz pomodoro com você e conversa pelo app Android com inteligência artificial.

<p align="center">
<img src="docs/telas/apaixonado.gif" width="200"> <img src="docs/telas/hipnotizado.gif" width="200"> <img src="docs/telas/festeiro.gif" width="200"> <img src="docs/reacoes/sunrise.gif" width="200">
</p>

> [!IMPORTANT]
> **Os direitos de criação são do projeto original [MONSTRIX - Robot Emotional Companion](https://makerworld.com/pt/models/1941340-monstrix-robot-emotional-companion), de Igor Belyi**, que por sua vez é um remix do [LDR Little Robot](https://makerworld.com/en/models/222658), de Max Kern. Os dois são publicados no MakerWorld sob a licença [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/deed.pt_BR). O Ottobot só aperfeiçoa o projeto: firmware novo, sensor de toque, buzzer, página web, app Android e os furos para ímãs na base.

**▶ [Veja todas as telas animadas no simulador online](https://felipeotto20.github.io/ottobot/)**: é a mesma página que o robô serve no Wi-Fi, com o simulador dos olhos.

**⬇ [Baixe a versão mais nova (firmware + app Android)](https://github.com/FelipeOtto20/ottobot/releases/latest)**

**🟦 Também existe uma versão com tela de toque colorida de 480 × 480 e o Diamond Rush original: [veja aqui](#ottobot-com-tela-480-esp32-s3)**

---

## O que ele faz

| | |
|---|---|
| 🎭 **49 telas** | caras e animações que ele sorteia sozinho (você escolhe quais no app) |
| 👄 **Boca** | uma caixinha que se transforma em cada emoção, e o rosto inteiro balança com uma molinha (item da loja) |
| 🥰 **Carinho** | segurar a cabeça dele = carinho; o "coração" esvazia com o tempo e ele fica carente |
| 🪙 **Moedas e loja** | jogos, coração cheio e conquistas dão moedas; a loja do app tem a boca, 20 acessórios e 20 músicas |
| 📋 **Menu** | 3 toques na cabeça: Jogos, Ferramentas e Acessórios |
| 🎮 **15 jogos** | jogados com toques na cabeça, chacoalhando ou inclinando ele |
| 🎩 **32 acessórios** | 12 das conquistas e 20 da loja, e eles combinam com a emoção (orelhas abaixam, auréola vira chifre, chapéu voa) |
| 🙃 **Sente o corpo** | de cabeça pra baixo = silêncio, deitado = dorme, no colo = feliz, inclinado = acha que vai cair |
| 🤝 **Amigos** | dois Ottobots perto um do outro se cumprimentam, conversam e sentem o humor um do outro |
| 🎶 **30 musiquinhas** | 10 de graça e 20 na loja, com coreografia no tempo da música |
| 🧠 **Personalidade** | muda com o jeito que você cuida dele, dia após dia |
| 📖 **Diário** | o que aconteceu em cada dia da semana, com gráfico no app |
| 🌦️ **Clima** | previsão do dia desenhada na tela, avisa quando vai chover, e o tempo muda a cara dele (calor, praia, frio, resfriado, neve) |
| 🍅 **Pomodoro** | 25 min de foco com ele quietinho, depois pausa |
| 💬 **Conversa com IA** | pelo app (Gemini grátis): ele responde e faz animações, caras e músicas |
| 📡 **Sabe quando você chega** | o app escuta o Bluetooth dele; festa quando você entra no quarto |
| ⏰ **Alarmes, cenas do dia, lembretes** | bom dia, meio-dia, boa noite, água, "como foi seu dia?" |
| 🏅 **Conquistas** | 12 medalhas, comemoradas na hora |
| 🎬 **Modo vídeo** | um show de 1 minuto para filmar |

## Telas

Cada tela é só um punhado de números (formato dos olhos, humor, para onde olham, animação que repete, efeito por cima e música). O app e a página do robô têm o catálogo; o robô só toca o que você escolheu.

<table>
<tr><td align="center"><img src="docs/telas/padrao.gif" width="160" alt="Padrão"><br><sub><b>Padrão</b></sub></td><td align="center"><img src="docs/telas/feliz.gif" width="160" alt="Feliz"><br><sub><b>Feliz</b></sub></td><td align="center"><img src="docs/telas/cansado.gif" width="160" alt="Cansado"><br><sub><b>Cansado</b></sub></td><td align="center"><img src="docs/telas/bravo.gif" width="160" alt="Bravo"><br><sub><b>Bravo</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/estressado.gif" width="160" alt="Estressado"><br><sub><b>Estressado</b></sub></td><td align="center"><img src="docs/telas/desconfiado.gif" width="160" alt="Desconfiado"><br><sub><b>Desconfiado</b></sub></td><td align="center"><img src="docs/telas/sonolento.gif" width="160" alt="Sonolento"><br><sub><b>Sonolento</b></sub></td><td align="center"><img src="docs/telas/sapeca.gif" width="160" alt="Sapeca"><br><sub><b>Sapeca</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/confuso.gif" width="160" alt="Confuso"><br><sub><b>Confuso</b></sub></td><td align="center"><img src="docs/telas/rindo.gif" width="160" alt="Rindo"><br><sub><b>Rindo</b></sub></td><td align="center"><img src="docs/telas/empolgado.gif" width="160" alt="Empolgado"><br><sub><b>Empolgado</b></sub></td><td align="center"><img src="docs/telas/dancando.gif" width="160" alt="Dançando"><br><sub><b>Dançando</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/piscadela.gif" width="160" alt="Piscadela"><br><sub><b>Piscadela</b></sub></td><td align="center"><img src="docs/telas/piscapisca.gif" width="160" alt="Pisca-pisca"><br><sub><b>Pisca-pisca</b></sub></td><td align="center"><img src="docs/telas/curioso.gif" width="160" alt="Curioso"><br><sub><b>Curioso</b></sub></td><td align="center"><img src="docs/telas/direcoes.gif" width="160" alt="8 direções"><br><sub><b>8 direções</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/comfrio.gif" width="160" alt="Com frio"><br><sub><b>Com frio</b></sub></td><td align="center"><img src="docs/telas/assustado.gif" width="160" alt="Assustado"><br><sub><b>Assustado</b></sub></td><td align="center"><img src="docs/telas/fofo.gif" width="160" alt="Olhos fofos"><br><sub><b>Olhos fofos</b></sub></td><td align="center"><img src="docs/telas/arregalado.gif" width="160" alt="Arregalado"><br><sub><b>Arregalado</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/olhinhos.gif" width="160" alt="Olhinhos"><br><sub><b>Olhinhos</b></sub></td><td align="center"><img src="docs/telas/espiando.gif" width="160" alt="Espiando"><br><sub><b>Espiando</b></sub></td><td align="center"><img src="docs/telas/apaixonado.gif" width="160" alt="Apaixonado"><br><sub><b>Apaixonado</b></sub></td><td align="center"><img src="docs/telas/vergonha.gif" width="160" alt="Envergonhado"><br><sub><b>Envergonhado</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/chorando.gif" width="160" alt="Chorando"><br><sub><b>Chorando</b></sub></td><td align="center"><img src="docs/telas/cantando.gif" width="160" alt="Cantando"><br><sub><b>Cantando</b></sub></td><td align="center"><img src="docs/telas/encantado.gif" width="160" alt="Encantado"><br><sub><b>Encantado</b></sub></td><td align="center"><img src="docs/telas/surpreso.gif" width="160" alt="Surpreso"><br><sub><b>Surpreso</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/pensando.gif" width="160" alt="Pensando"><br><sub><b>Pensando</b></sub></td><td align="center"><img src="docs/telas/furioso.gif" width="160" alt="Furioso"><br><sub><b>Furioso</b></sub></td><td align="center"><img src="docs/telas/tonto.gif" width="160" alt="Tonto"><br><sub><b>Tonto</b></sub></td><td align="center"><img src="docs/telas/furia.gif" width="160" alt="Fúria"><br><sub><b>Fúria</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/brilhando.gif" width="160" alt="Brilhando"><br><sub><b>Brilhando</b></sub></td><td align="center"><img src="docs/telas/oops.gif" width="160" alt="Oops!"><br><sub><b>Oops!</b></sub></td><td align="center"><img src="docs/telas/suspeito.gif" width="160" alt="Suspeito"><br><sub><b>Suspeito</b></sub></td><td align="center"><img src="docs/telas/hipnotizado.gif" width="160" alt="Hipnotizado"><br><sub><b>Hipnotizado</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/scanner.gif" width="160" alt="Scanner"><br><sub><b>Scanner</b></sub></td><td align="center"><img src="docs/telas/festeiro.gif" width="160" alt="Festeiro"><br><sub><b>Festeiro</b></sub></td><td align="center"><img src="docs/telas/timido.gif" width="160" alt="Tímido"><br><sub><b>Tímido</b></sub></td><td align="center"><img src="docs/telas/bugado.gif" width="160" alt="Bugado"><br><sub><b>Bugado</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/ninja.gif" width="160" alt="Ninja"><br><sub><b>Ninja</b></sub></td><td align="center"><img src="docs/telas/panico.gif" width="160" alt="Em pânico"><br><sub><b>Em pânico</b></sub></td><td align="center"><img src="docs/telas/zen.gif" width="160" alt="Zen"><br><sub><b>Zen</b></sub></td><td align="center"><img src="docs/telas/cifrao.gif" width="160" alt="Cifrão"><br><sub><b>Cifrão</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/estrela.gif" width="160" alt="Olhos de estrela"><br><sub><b>Olhos de estrela</b></sub></td><td align="center"><img src="docs/telas/ideia.gif" width="160" alt="Ideia!"><br><sub><b>Ideia!</b></sub></td><td align="center"><img src="docs/telas/nocaute.gif" width="160" alt="Nocaute"><br><sub><b>Nocaute</b></sub></td><td align="center"><img src="docs/telas/emburrado.gif" width="160" alt="Emburrado"><br><sub><b>Emburrado</b></sub></td></tr>
<tr><td align="center"><img src="docs/telas/lingua.gif" width="160" alt="Língua de fora"><br><sub><b>Língua de fora</b></sub></td></tr>
</table>

## Reações e cenas do dia

<table>
<tr><td align="center"><img src="docs/reacoes/boot.gif" width="160" alt="Abertura (ao ligar)"><br><sub><b>Abertura (ao ligar)</b></sub></td><td align="center"><img src="docs/reacoes/pet.gif" width="160" alt="Carinho (segurar)"><br><sub><b>Carinho (segurar)</b></sub></td><td align="center"><img src="docs/reacoes/shake.gif" width="160" alt="Chacoalhar: tonto, depois bravo"><br><sub><b>Chacoalhar: tonto, depois bravo</b></sub></td></tr>
<tr><td align="center"><img src="docs/reacoes/sleep.gif" width="160" alt="Sono e canção de ninar"><br><sub><b>Sono e canção de ninar</b></sub></td><td align="center"><img src="docs/reacoes/wifi.gif" width="160" alt="Wi-Fi conectou"><br><sub><b>Wi-Fi conectou</b></sub></td><td align="center"><img src="docs/reacoes/clock.gif" width="160" alt="Relógio"><br><sub><b>Relógio</b></sub></td></tr>
<tr><td align="center"><img src="docs/reacoes/sunrise.gif" width="160" alt="Bom dia"><br><sub><b>Bom dia</b></sub></td><td align="center"><img src="docs/reacoes/noon.gif" width="160" alt="Meio-dia"><br><sub><b>Meio-dia</b></sub></td><td align="center"><img src="docs/reacoes/night.gif" width="160" alt="Boa noite"><br><sub><b>Boa noite</b></sub></td></tr>
</table>

- **Toques rápidos**: cada quantidade (1 a 8 toques) faz o que você escolher no app. Padrão: 1 = alegria, 2 = dança, 3 = menu, 5 = hora, 6 = QR code da página.
- **Segurar**: carinho. Quanto mais tempo, mais derretido: "^ ^", olhos de coração, nas nuvens (com brilhos e notinhas).
- **Chacoalhar** (balançar pros lados várias vezes; um tranco ou deitar não conta): fica tonto (olhos em espiral) e depois bravo e suando. Duas vezes seguidas: **nocaute** (olhos em X, estrelinhas girando e o chapéu voa).
- **Sono**: dorme depois de um tempo parado, só à noite ou nunca. Dormindo, um toque canta canção de ninar e 3 toques rápidos acordam.

## Boca, clima no rosto e acessórios

Gravados direto da tela do robô.

<table>
<tr><td align="center" width="33%"><img src="docs/novidades/boca.gif" width="200" alt="👄 Boca"><br><b>👄 Boca</b><br><sub>canta, fala, sorri, fica triste, bravo, faz "o" e mostra a língua; o rosto balança com uma molinha</sub></td><td align="center" width="33%"><img src="docs/novidades/clima-no-rosto.gif" width="200" alt="🌡️ Clima no rosto"><br><b>🌡️ Clima no rosto</b><br><sub>calor, praia, frio, resfriado (atchim!) e neve: só quando o tempo pede</sub></td><td align="center" width="33%"><img src="docs/novidades/acessorios.gif" width="200" alt="🎩 Acessórios que sentem"><br><b>🎩 Acessórios que sentem</b><br><sub>a nuvem vira sol ou chove forte, orelhas abaixam, auréola vira chifre, o chapéu voa no nocaute</sub></td></tr>
</table>

- **Boca** (comprada na loja, liga e desliga no app): uma caixinha que muda de tamanho e escorrega de uma forma para outra, com pontinhas que sobem no sorriso e descem na tristeza. Ela segue tudo: o humor dos olhos, cada nota que toca, as falas, o sono, o susto e o carinho.
- **Clima no rosto**: as caras de clima não entram no rodízio de telas. O tempo traz elas: quente = calor e às vezes praia (com óculos escuros), frio = congelando e às vezes resfriado, nevando = neve (com gorro e cachecol). A IA do app comenta.
- **Emoções novas**: cifrão (quando ganha moedas), olhos de estrela, ideia (a lâmpada acende quando ele chama para brincar), nocaute, emburrado ("hmpf") e língua de fora.

## Moedas e loja

- **Ganhar**: jogos (até 20 moedas por partida e +10 ao bater um recorde, até 150 por dia), coração cheio com carinho (+30, uma vez por dia) e cada conquista (+50). Ele faz olhos de cifrão quando ganha.
- **Loja** (aba Loja do app): a boca (800), 20 acessórios de 250 a 1200 (tapa-olho de pirata, bruxa, viking, astronauta, nuvem de chuva, sobrancelhas que mudam com o humor, bigode, herói...) e 20 músicas clássicas de 150 a 350. Dá para provar no robô antes de comprar, e tudo fica salvo nele.
- **Caça-níquel** aposta 10 moedas de verdade: 7 7 7 paga 350 (raro!), trios de 30 a 120, dois 7 = 50, outro par = 12, um 7 sozinho devolve a aposta.

## Menu, acessórios e gestos

<table>
<tr><td align="center" width="33%"><img src="docs/novidades/menu.gif" width="200" alt="📋 Menu"><br><b>📋 Menu</b><br><sub>3 toques abrem; toque desce, segure até apitar e solte para escolher</sub></td><td align="center" width="33%"><img src="docs/novidades/roupas.gif" width="200" alt="🎩 Acessórios"><br><b>🎩 Acessórios</b><br><sub>experimente no rosto dele; os trancados mostram a medalha que libera</sub></td><td align="center" width="33%"><img src="docs/novidades/atualizando.gif" width="200" alt="📡 Atualizando"><br><b>📡 Atualizando</b><br><sub>a tela durante uma atualização pelo Wi-Fi</sub></td></tr>
</table>

- **Menu** (3 toques, dá para trocar no app): **Jogos** (com o seu recorde embaixo de cada um), **Ferramentas** (relógio, cronômetro, pomodoro, clima, dado), **Acessórios** (os das conquistas e os comprados) e **Sair**. Quando um jogo acaba ele volta para o rostinho.
- **De cabeça pra baixo** (1,5 s): liga ou desliga o silêncio.
- **Deitado de lado** (3 s): boceja e dorme; em pé de novo, acorda.
- **No colo** depois de um tempo parado: olha pra você feliz, com coraçõezinhos.
- **Inclinado pro lado**: acha que vai cair. Olhos arregalados e tremendo escorregam para o lado mais baixo, ele grita e as letras do grito caem com a gravidade. Reto de novo: "ufa!".
- **Amigos**: dois Ottobots no mesmo Wi-Fi (ou os dois sem Wi-Fi de casa) se falam por ESP-NOW. Eles se cumprimentam ("oi, robô do Fulano!"), de vez em quando um pergunta e o outro responde, e um sente o humor do outro: carinho vira coraçõezinhos, chacoalhão vira "tudo bem?", sono vira bocejo.

## Mais animações

Também gravadas direto da tela do robô.

<table>
<tr><td align="center" width="33%"><img src="docs/animacoes/abertura.gif" width="200" alt="✨ Abertura"><br><b>✨ Abertura</b><br><sub>com a contagem 3-2-1 do modo vídeo</sub></td><td align="center" width="33%"><img src="docs/animacoes/piada.gif" width="200" alt="🤡 Piada"><br><b>🤡 Piada</b><br><sub>pergunta, suspense, susto ou espanto e gargalhada</sub></td><td align="center" width="33%"><img src="docs/animacoes/festa.gif" width="200" alt="🎉 Festa de chegada"><br><b>🎉 Festa de chegada</b><br><sub>quando você entra no quarto</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/animacoes/clima.gif" width="200" alt="🌦️ Clima"><br><b>🌦️ Clima</b><br><sub>previsão do dia e o comentário dele</sub></td><td align="center" width="33%"><img src="docs/animacoes/musica.gif" width="200" alt="🎶 Música com coreografia"><br><b>🎶 Música com coreografia</b><br><sub>dança no tempo de cada batida</sub></td><td align="center" width="33%"><img src="docs/animacoes/modo-musica.gif" width="200" alt="🎧 Modo música"><br><b>🎧 Modo música</b><br><sub>dança e mostra as frequências da música do celular</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/animacoes/pomodoro.gif" width="200" alt="🍅 Pomodoro"><br><b>🍅 Pomodoro</b><br><sub>foco de 25 min com ele concentrado</sub></td><td align="center" width="33%"><img src="docs/animacoes/como-foi-seu-dia.gif" width="200" alt="🙂 Como foi seu dia?"><br><b>🙂 Como foi seu dia?</b><br><sub>responde com 1, 2 ou 3 toques</sub></td><td align="center" width="33%"><img src="docs/animacoes/agua.gif" width="200" alt="💧 Lembrete de água"><br><b>💧 Lembrete de água</b><br><sub>um toque = bebi</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/animacoes/contagem.gif" width="200" alt="📅 Contagem regressiva"><br><b>📅 Contagem regressiva</b><br><sub>dias que faltam para uma data</sub></td><td align="center" width="33%"><img src="docs/animacoes/qr-code.gif" width="200" alt="🔳 QR code"><br><b>🔳 QR code</b><br><sub>abre a página dele no celular</sub></td><td align="center" width="33%"><img src="docs/animacoes/relogio.gif" width="200" alt="🕒 Relógio"><br><b>🕒 Relógio</b><br><sub>hora grande e data</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/animacoes/carinho.gif" width="200" alt="🥰 Carinho"><br><b>🥰 Carinho</b><br><sub>coraçõezinhos e bochechas coradas</sub></td><td align="center" width="33%"><img src="docs/animacoes/tonto-e-bravo.gif" width="200" alt="😵 Tonto e bravo"><br><b>😵 Tonto e bravo</b><br><sub>depois de um chacoalhão</sub></td></tr>
</table>

## Carinho, humor e personalidade

- O **coração** vai de 0 a 100%: carinho e toques enchem, o tempo e chacoalhões esvaziam. Abaixo de 30% ele fica **carente**: coração vazio, pede carinho e **não obedece** ninguém até ganhar um carinho longo. Abaixo de 10% ele chora. O "modo carente" pode ser desligado.
- **Personalidade**: todo dia o dia anterior empurra um pouco. Muito carinho deixa ele **carinhoso** (o coração esvazia mais devagar e ele diz que gosta de você); muitos jogos e toques, **brincalhão** (chama para jogar); esquecido fica **carente**; dias quietos, **calmo**.
- **Diário**: carinhos, tempo de carinho, toques, jogos, piadas, pomodoros, copos de água, humor do dia e coração médio, 7 dias.
- **Piadas**: ele encena (pergunta, suspense, susto ou espanto, risada). Ele guarda 20; a IA do app troca as já contadas por novas, com trocadilhos que funcionam em português, e uma segunda IA faz de crítica e só deixa passar as boas. 3 vezes por dia ele conta uma quando você está no quarto.

## Mini jogos

Gravados direto da tela do robô.

<table>
<tr><td align="center" width="33%"><img src="docs/jogos/reflexo.gif" width="200" alt="⚡ Reflexo"><br><b>⚡ Reflexo</b><br><sub>3, 2, 1… toque quando aparecer o !</sub></td><td align="center" width="33%"><img src="docs/jogos/genius.gif" width="200" alt="🎶 Genius"><br><b>🎶 Genius</b><br><sub>Repita: toque = curto, segure = longo</sub></td><td align="center" width="33%"><img src="docs/jogos/adivinha.gif" width="200" alt="🔢 Adivinha"><br><b>🔢 Adivinha</b><br><sub>Ele pensou de 1 a 10: responda com toques</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/jogos/jokenpo.gif" width="200" alt="✊ Jokenpô"><br><b>✊ Jokenpô</b><br><sub>1 toque pedra, 2 papel, 3 tesoura</sub></td><td align="center" width="33%"><img src="docs/jogos/dino.gif" width="200" alt="🦖 Dino"><br><b>🦖 Dino</b><br><sub>Pule cactos e aves baixas; ave alta: fique no chão</sub></td><td align="center" width="33%"><img src="docs/jogos/pouso.gif" width="200" alt="🌙 Pouso"><br><b>🌙 Pouso</b><br><sub>Segure para ligar o motor e pouse devagar</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/jogos/alvo.gif" width="200" alt="🎯 Alvo"><br><b>🎯 Alvo</b><br><sub>Toque quando a barra estiver no meio</sub></td><td align="center" width="33%"><img src="docs/jogos/cronometro.gif" width="200" alt="⏱️ Cronômetro"><br><b>⏱️ Cronômetro</b><br><sub>Conte o tempo de cabeça e toque quando passar</sub></td><td align="center" width="33%"><img src="docs/jogos/snake.gif" width="200" alt="🐍 Snake"><br><b>🐍 Snake</b><br><sub>Toque = vira à direita, segure = à esquerda</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/jogos/dado.gif" width="200" alt="🎲 Dado"><br><b>🎲 Dado</b><br><sub>Chacoalhe ou toque para jogar o dado</sub></td><td align="center" width="33%"><img src="docs/jogos/caca-niquel.gif" width="200" alt="🎰 Caça-níquel"><br><b>🎰 Caça-níquel</b><br><sub>Aposta 10 moedas: 7 7 7 = 350, trios 30 a 120, par 12</sub></td><td align="center" width="33%"><img src="docs/jogos/cobras-e-escadas.gif" width="200" alt="🪜 Cobras e escadas"><br><b>🪜 Cobras e escadas</b><br><sub>1 toque: contra ele · 2 toques: duas pessoas · depois toque = dado</sub></td></tr>
<tr><td align="center" width="33%"><img src="docs/jogos/flappy.gif" width="200" alt="🐦 Flappy"><br><b>🐦 Flappy</b><br><sub>Toque para bater as asas e passe entre os canos</sub></td><td align="center" width="33%"><img src="docs/jogos/torre.gif" width="200" alt="🧱 Torre"><br><b>🧱 Torre</b><br><sub>Toque para soltar o bloco bem em cima da torre</sub></td><td align="center" width="33%"><b>🌀 Labirinto</b><br><sub>Incline o robô para rolar a bolinha até o buraco, contra o tempo; cada fase é um labirinto maior</sub></td></tr>
</table>

Durante um jogo nada mais funciona (comandos, cenas, chacoalhar). **Segure a cabeça 3 s para sair** (aparece a dica e uma barrinha; no Pouso segurar é o motor, então ele sai quando a nave bate). Perdeu: **GAME OVER** e volta para o rostinho; nenhum jogo recomeça sozinho. 10 s sem jogar, ele sai. Os recordes ficam salvos e as partidas dão moedas.

## Musiquinhas e dança

| | Música | Duração |
|---|---|---|
| 🤖 | Ottobot vibes | 0:20 |
| 🎹 | Para Elisa | 0:12 |
| 🎂 | Parabéns pra você | 0:18 |
| ⭐ | Brilha, brilha | 0:27 |
| 🎻 | Ode à alegria | 0:33 |
| 🦾 | Marcha do robô | 0:36 |
| ✨ | Chuva de estrelas | 0:43 |
| ⛰️ | Rei da montanha | 0:46 |
| 🌙 | Soninho | 0:48 |
| 🎉 | Festa 8-bit | 0:51 |

Mais 20 na loja do app, todas de domínio público: Bate o sino, Noite feliz, Cancan, Marcha turca, Danúbio azul, Lago dos cisnes, Guilherme Tell, The Entertainer, Canon em Ré, Frère Jacques, La cucaracha, Os santos, Greensleeves, Marcha nupcial, Oh! Susana, Ninar de Brahms, Pequena serenata, Minueto em Sol, Rema rema e Primavera.

A coreografia é calculada no app para o tempo exato de cada batida e o robô dança no mesmo relógio da música: pulinhos no tempo forte, olhos seguindo a melodia (nota aguda olha para cima), giros, piscadas, olhos crescendo, efeitos que trocam a cada 2 compassos e olhos de coração no fim. Também tem **modo música**: o celular escuta a música que está tocando (pelo microfone) e ele dança mostrando as frequências. Volume do bipe ajustável no app.

## Companhia no dia a dia

- 🌦️ **Clima** (só no Wi-Fi de casa): [Open-Meteo](https://open-meteo.com/), sem chave. Cidade escolhida no app ou descoberta pela internet. Mostra de manhã, quando vai chover e umas 2 vezes por dia. Em dia quente ele fica com calor (e às vezes sonha com a praia), no frio treme (e às vezes pega um resfriado), e com neve olha os flocos caindo.
- 🍅 **Pomodoro**: 25 min de foco (ele fica quieto e concentrado; um toque dá um incentivo), 5 min de pausa (15 a cada 4 rodadas) e depois chama você de volta.
- 🙂 **"Como foi seu dia?"** à noite, respondido com 1, 2 ou 3 toques. 💧 **Lembrete de água** durante o dia, um toque = bebi.
- 📅 **Contagem regressiva** para datas marcadas no app (prova, viagem, aniversário), com festa no dia.
- ⏰ **Alarmes** com dias da semana e soneca. 🌅 **Cenas do dia** em horários escolhidos. 🔇 **Silêncio** total ou em horários. 🌙 **Tela fraquinha à noite**.
- Tudo que é para ler (perguntas, lembretes, medalhas, datas, clima) **espera você estar perto**: celular no quarto (Bluetooth) ou logo depois de um toque.

### Conquistas

Cada medalha libera um acessório (menu → Acessórios) e dá 50 moedas.

🐻 **Abraço de urso**: um carinho longo, até ele ficar nas nuvens (uns 18 s segurando) → libera: orelhas de urso  
❤️ **Coração cheio**: encher o carinho dele até 100% → libera: laço  
📅 **Semana de carinho**: carinho nele 7 dias seguidos → libera: coroa  
🍅 **Foco de aço**: completar 10 pomodoros → libera: óculos  
📚 **Dia produtivo**: 4 pomodoros no mesmo dia → libera: faixa  
💧 **Hidratado**: 8 copos de água num dia (toque nele quando ele lembrar) → libera: boné  
🤡 **Plateia fiel**: ouvir 30 piadas dele → libera: nariz de palhaço  
🦖 **Dino veloz**: 500 pontos no Dino → libera: óculos escuros  
🎶 **Memória boa**: chegar na rodada 8 do Genius → libera: chapéu de mago  
⚡ **Rápido como raio**: reflexo abaixo de 250 ms → libera: fones  
📖 **Diário em dia**: contar como foi seu dia 5 vezes → libera: cartola  
🌟 **Dia completo**: no mesmo dia: carinho, jogo, pomodoro e água → libera: auréola

## App Android

- **Início**: o rosto dele ao vivo, coração, atalhos, foco, musiquinhas, modo vídeo, jogos, diário, personalidade, conquistas, datas, cenas, caras e recado na telinha.
- **Conversa**: IA grátis ([chave do Gemini](https://aistudio.google.com/apikey), fica só no celular). Ele responde em frases curtas, escolhe animações, inventa caras e músicas e reage quando você faz carinho nele.
- **Loja**: moedas, a boca, acessórios e músicas para provar e comprar, e escolher o que ele usa.
- **Perto**: radar do Bluetooth, festa quando você chega, aviso quando ele está carente, 3 piadas por dia.
- **Ajustes**: tudo do robô (telas, toques, horários, sono, som, Wi-Fi, senha, lembretes, clima) e as atualizações, com as etapas e a porcentagem na tela.

Instale pelo arquivo `ottobot.apk` da [última versão](https://github.com/FelipeOtto20/ottobot/releases/latest) ou pela página do robô (`http://ottobot.local`). Android 12 ou mais novo. Quando sai uma versão nova aqui, o app avisa e atualiza o robô e ele mesmo.

## Ottobot com tela 480 (ESP32-S3)

Uma segunda versão do Ottobot, numa placa pronta com tela colorida de toque: **GUITION ESP32-4848S040** (ESP32-S3, 16 MB de flash, 8 MB de PSRAM, tela ST7701 de 480 × 480 com toque GT911). É o mesmo Ottobot do OLED (emoções, reações, cenas, acessórios, moedas, loja, app e IA), com o rosto na tela grande e tudo comandado pelo toque na própria tela. Não precisa montar nada: a placa já vem com tela, toque e Wi-Fi.

**Como funciona**

- O rosto é o mesmo do OLED, ampliado no meio da tela. Tocar na tela é como tocar na cabeça dele: carinho, toques contados e jogos.
- O botão **≡** no canto de cima abre o menu tocável: toque num item para abrir; **Anterior** e **Próximo** trocam de página.
- A rede própria se chama **Ottobot-480** (senha inicial `ottobot1`) e a página é `http://ottobot-480.local` (só Wi-Fi e download do app; os comandos ficam no app).
- O app reconhece a placa sozinho e cuida de dois robôs (um OLED e um 480): **Ajustes › Cadastrar outro robô** e o botão **Robôs** na tela inicial.

**Diferenças e exceções**

| | OLED (ESP32-C3) | Tela 480 (ESP32-S3) |
|---|---|---|
| Toque | sensor na cabeça | a tela inteira, com botões |
| Sensor de movimento (MPU6050) | vem montado | opcional (I2C SDA 19 / SCL 45) |
| Sem o sensor de movimento | — | Batatinha frita sai do menu e do app; Labirinto, Snake, Corrida, Pouso e Diamantes mostram setas na tela |
| Som | buzzer | desligado por padrão |
| Jogos de toques contados | conta os toques | botões na tela: Jokenpô (Pedra, Papel, Tesoura), Adivinha (1 a 10), Genius (Curto, Longo) |
| Mini jogos | telinha 128 × 64 | tela inteira, coloridos e animados (Flappy com céu e canos, Dino de dia e de noite, Snake, Torre, Corrida, Caça-níquel, Jokenpô, Genius, Adivinha, Reflexo, Alvo, Tempo, Pouso na lua, Labirinto, Diamantes, Dado, Cronômetro e Cobras e escadas com escadas de madeira e cobras com olhos) |
| Rosto e animações | pixels da tela OLED | os mesmos, com bordas suavizadas, degradê azul e brilho, sem piscar |
| Menu | toque desce, segurar escolhe | itens tocáveis; Anterior e Próximo só quando há outra página |
| Brilho | — | 100% de dia, 70% à noite |
| Atualizações | pelo app (estas versões do GitHub) | pelo cabo USB; o app nunca oferece o firmware do OLED para ela |

**Exclusivo da tela 480: Diamond Rush**

O clássico de celular da Gameloft (2006) rodando o jogo Java original dentro da própria placa, numa máquina virtual Java ([Flint JVM](https://github.com/FlintVN/FlintESPJVM)) com a camada de jogos de celular do [ESP32-J2ME](https://github.com/bbnmn4800/ESP32-J2ME). O celular não é preciso: os 3 mundos (40 fases) e o progresso ficam na placa.

- Abre pelo menu **Jogos › Diamond Rush** ou pela lista de jogos do app (só aparece para a tela 480).
- Controle na tela: setas, **A** (ação), **B** (menu), **★** (voltar ao checkpoint); os cantos de baixo da imagem são o **Skip/OK** e o **voltar** do jogo. O controle do app também funciona (X = checkpoint).
- O botão **≡** no canto abre **CONTROLES** (mostra ou esconde o controle) e **SAIR** (volta ao Ottobot). A opção de sair do menu do jogo também volta, e qualquer reinício cai no Ottobot.
- Cada fase vencida pela primeira vez dá moedas para o Ottobot, fora do limite diário dos jogos: **Angkor** 50 a 350, **Baviera** 150 a 630, **Tibete** 300 a 1080 (17.330 no jogo todo). Elas entram quando você volta para ele, com os olhos de cifrão.
- O arquivo do jogo é da Gameloft e não é distribuído aqui.

## Hardware e montagem

**🔧 [Manual de montagem completo](MONTAGEM.md)**: peças, passo a passo das ligações com desenhos, como prender na caixa e problemas comuns.

**🖨️ [Modelo 3D (OttoBot.3mf)](modelo-3d/README.md)**: a caixa do MONSTRIX com furos para ímãs de 4 × 2 mm na base.

<p align="center"><img src="docs/montagem/mapa-de-pinos.svg" alt="Mapa de pinos" width="760"></p>

| Peça | Pino do ESP32-C3 |
|---|---|
| Tela OLED 0,96" SSD1306 (I2C 0x3C) | SDA → GPIO8, SCL → GPIO9 |
| MPU6050 (I2C 0x68) | SDA → GPIO8, SCL → GPIO9 (mesmos da tela) |
| Sensor de toque TTP223 | I/O → GPIO10 (colado com cola quente por dentro da cabeça) |
| Buzzer passivo | + → GPIO20 |
| Todos | VCC → 3V3, GND → GND |

A tela fica presa com mini parafusos.

Bibliotecas: Adafruit SSD1306 e GFX, [FluxGarage RoboEyes](https://github.com/FluxGarage/RoboEyes) 1.1.1, MPU6050_light. Placa: ESP32 core 3.3, partição "Minimal SPIFFS (com OTA)".

## Conectar

1. Conecte o celular no Wi-Fi **Ottobot** (senha padrão `ottobot1`; troque no app) e a página abre sozinha, ou abra `http://192.168.4.1`.
2. Pela página ou pelo app, coloque o robô no Wi-Fi de casa: aí é só abrir `http://ottobot.local` sem sair da sua internet.

Para quem quiser mexer, o robô tem uma API HTTP simples: `/api/state`, `/api/config`, `/api/do`, `/api/show`, `/api/say`, `/api/song`, `/api/diary`, `/api/jokes`, `/api/buy`, `/api/update`.

## Créditos e direitos

- **Projeto original e direitos de criação**: [MONSTRIX - Robot Emotional Companion](https://makerworld.com/pt/models/1941340-monstrix-robot-emotional-companion), de **Igor Belyi**, remix do [LDR Little Robot](https://makerworld.com/en/models/222658), de **Max Kern** (MakerWorld, CC BY-SA). O Ottobot é um aperfeiçoamento desse projeto.
- Olhos animados pela biblioteca [RoboEyes](https://github.com/FluxGarage/RoboEyes), da FluxGarage.
- Tela 480: [Arduino_GFX](https://github.com/moononournation/Arduino_GFX); Diamond Rush pela [Flint JVM](https://github.com/FlintVN/FlintESPJVM) e pelo [ESP32-J2ME](https://github.com/bbnmn4800/ESP32-J2ME) (MIT). Diamond Rush © Gameloft.
- Clima do [Open-Meteo](https://open-meteo.com/); localização aproximada do ip-api.com.
