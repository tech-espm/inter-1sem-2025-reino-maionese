# Projeto Integrado I - Sistemas de Informação ESPM

<p align="center">
    <a href="https://www.espm.br/cursos-de-graduacao/sistemas-de-informacao/"><img src="https://raw.githubusercontent.com/tech-espm/misc-template/main/logo.png" alt="Sistemas de Informação ESPM" style="width: 375px;"/></a>
</p>

# Mundo de Minecraft sobre a vida de princesas no Reino da Maionese

### 2025-01

## Integrantes
- [Pablo Schmekel](https://github.com/Dregoncry)
- [Gustavo Gomes](https://github.com/GustavoG0m3s)
- [Luccas Toffano](https://github.com/toffan0)
- [Julia Egute](https://github.com/juliaegute)
- [Ana Proenca](https://github.com/anaproenca02)
- [Pedro Perroni](https://github.com/PedroPerroni)

## Descrição do Projeto

O Reino da Maionese (também chamado Maionésia) é um projeto criativo e surreal desenvolvido dentro do universo do Minecraft, com forte inspiração em humor absurdo, estética pastel e referências alimentares. A ideia central gira em torno de um mundo onde tudo está relacionado à maionese e seus ingredientes, criando um ambiente fantasioso que combina o nonsense com o visual leve e colorido.

O ponto focal do reino é o Castelo da Maionese Real, uma construção imponente feita Com sua estrutura ampla e estilo realista pastel, o castelo domina a paisagem e serve como sede do poder no Reino da Maionese.
Próxima ao castelo ergue-se a imponente Catedral Ketchup, uma construção grandiosa feita em tons de vermelho escuro e carmesim. Suas colunas são espessas e lembram fluxos de molho escorrido, enquanto vitrais com tons quentes criam jogos de luz que enchem o interior com um brilho avermelhado dramático. A catedral é um espaço simbólico dentro do reino, celebrando a importância do ketchup como um dos condimentos sagrados da Maionésia. Ela é usada para eventos cômico-religiosos, como a "Bênção dos Lanches" e a "Procissão dos Molhos".

Nas redondezas da catedral, destaca-se também o Moinho da Mostarda, uma estrutura amarela vibrante com pás giratórias feitas de lã dourada e detalhes em madeira clara. Localizado no alto de uma colina condimentar, o moinho gira continuamente como símbolo da energia agridoce que move o reino. Seu interior abriga engrenagens decorativas e tonéis de sementes de mostarda fictícias. É um ponto turístico popular e frequentemente associado a festivais temáticos, como a "Colheita de Molhos" e o "Carnaval da Mostarda Picante".

Entre as construções notáveis do reino estão:

O Barco Azeitona: uma embarcação temática atracada ao lado do vilarejo, feita com blocos verdes escuros e detalhes em verde oliva, evocando o tom das azeitonas maduras. Seu mastro principal é adornado com uma escultura de palito espetado em uma enorme azeitona cúbica, representando o clássico aperitivo. O convés possui pequenos barris de conserva e mesas com petiscos cenográficos. O interior abriga um restaurante flutuante especializado em pratos fictícios à base de azeitona, sendo um ponto de encontro inusitado para os habitantes do reino.

A Torre Cenoura: uma torre laranja com o topo verde, construída para se parecer com uma enorme cenoura fincada no solo. Ela serve como um ponto de observação e também como farol. No interior, escadas em espiral e vitrines com itens decorativos remetem a vegetais, reforçando o vínculo com os ingredientes da maionese e seus acompanhamentos.

O projeto Reino da Maionese propõe uma fusão entre criatividade arquitetônica e humor pastel, sendo um espaço ideal para aventuras leves, vídeos cômicos e explorações visuais que rompem com o convencional dentro do Minecraft.

## Areas do mapa

### Castelo da Maionese Real:

• Estrutura central e símbolo do reino

• Construído com blocos brancos e amarelos

• Representa a maionese pura e cremosa

• Sede do poder e residência da realeza maionesal

<p>
<img src="https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/castelo_maionese.png" style="width: 375px;"/>
</p>   

### Catedral Ketchup:

• Edifício sagrado com temática vermelha

• Vitrais e colunas remetem ao ketchup escorrendo

• Palco de eventos como a "Procissão dos Molhos"

• Espaço para celebrações e cerimônias cômico-religiosas


<p>
<img src="https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/Castelo%20ketchuupss.png" style="width: 375px;"/>
</p>   

### Moinho da Mostarda:

• Construção vibrante com pás douradas

• Localizado no alto de uma colina

• Produz simbolicamente a “energia agridoce” do reino

• Sede de festividades como a "Colheita de Molhos"


<p>
<img src="https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/Rodamuilnho.png" style="width: 375px;"/>
</p>   

### Vilarejo dos Condimentos:

• Conjunto de casas temáticas ao redor do castelo

• Cada casa representa um condimento: ketchup, mostarda, picles, etc.

• Cores vivas e formatos inspirados em embalagens de molho

• Centro de convivência e comércio local


<p>
<img src="https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/Vilarejo%20ketchup.png" style="width: 375px;"/>
</p>   

### Barco Azeitona:

• Embarcação temática atracada nas margens do reino

• Construída com blocos verde escuro e verde oliva

• Mastro simula uma azeitona espetada em um palito

• Interior abriga um restaurante flutuante fictício com pratos à base de azeitona


<p>
<img src="https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/Barco%20Azeitonas.png" style="width: 375px;"/>
</p>   

### Torre Cenoura:

• Torre laranja com topo verde, semelhante a uma cenoura gigante

• Funciona como farol e ponto de observação

• Interior com escadas em espiral e decoração vegetal

• Representa os ingredientes naturais do reino


<p>
<img src="https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/torre%20cenoura.png" style="width: 375px;"/>
</p>   

## DESENVOLVIMENTO

- Ao quebrar um bloco de PURPUR, ele diz "teste 4" e coloca carpetes vermelhos ao redor

def on_block_broken_purpur():
    player.say("teste 4")
    blocks.fill(RED_CARPET, pos(-1, 0, 0), pos(1, 0, 0), FillOperation.REPLACE)
    blocks.fill(RED_CARPET, pos(0, 0, 1), pos(0, 0, -1), FillOperation.REPLACE)

- Comer carne cozida dá efeito de náusea por 6 segundos

def on_item_interacted_cooked_beef():
    mobs.apply_effect(NAUSEA, mobs.target(LOCAL_PLAYER), 120, 7)

- Se o jogador estiver com o capacete especial ativado, ao nadar ele perde energia do capacete e ganha visão noturna por 0,1s

def on_travelled_swim_water():
    global Capacete_Ket
    if Capacete_Ket >= 0:
        Capacete_Ket += -0.5
        mobs.apply_effect(NIGHT_VISION, mobs.target(LOCAL_PLAYER), 2, 3)

- Equipar o capacete de ferro ativa o efeito especial com duração/energia de 8000 unidades.

def on_item_interacted_iron_helmet():
    global Capacete_Ket
    if Capacete_Ket == 0:
        Capacete_Ket = 8000

- Se as botas estiverem ativadas (ketchup > 0), ao andar o jogador deixa blocos de quartzo no chão.

def on_travelled_walk():
    global ketchup
    if ketchup > 0:
        ketchup += -1
        blocks.place(BLOCK_OF_QUARTZ, pos(0, -1, 0))

- Comer cookie dá um super pulo por 6 segundos.

def on_item_interacted_cookie():
    mobs.apply_effect(JUMP_BOOST, mobs.target(LOCAL_PLAYER), 120, 5)

- Ativa o peitoral especial com energia de 2000.

def on_item_interacted_iron_chestplate():
    global peito_kat
    if peito_kat == 0:
        peito_kat = 2000

- Ativa as botas especiais com 50 de energia (para o efeito de andar e deixar blocos).

def on_item_interacted_iron_boots():
    global ketchup
    if ketchup == 0:
        ketchup = 50

- Ativa a calça especial com 2000 de energia.

def on_item_interacted_iron_leggings():
    global calca_ket
    if calca_ket == 0:
        calca_ket = 2000

- Enquanto agacha, se o peitoral especial estiver ativo, aplica Resistência nível alto (quase invencível) e gasta energia lentamente.

def on_travelled_sneak():
    global peito_kat
    if peito_kat >= 0:
        peito_kat += -0.3
        mobs.apply_effect(RESISTANCE, mobs.target(LOCAL_PLAYER), 1, 9)

- Correr com a calça ativa dá velocidade por 48 segundos, e consome energia da calça.

def on_travelled_sprint():
    global calca_ket
    calca_ket += -1
    mobs.apply_effect(SPEED, mobs.target(LOCAL_PLAYER), 960, 3)

- Comer cenoura causa cegueira por 6 segundos.

def on_item_interacted_carrot():
    mobs.apply_effect(BLINDNESS, mobs.target(LOCAL_PLAYER), 120, 5)

## Conclusão

O Reino da Maionese, também conhecido como Maionésia, é um universo Minecraft único e surreal, que mistura humor absurdo, estética pastel e temas alimentares para criar um mundo fantástico e cômico. Com construções icônicas como o Castelo da Maionese Real, a Catedral Ketchup, o Moinho da Mostarda, o Barco Azeitona e a Torre Cenoura, o reino combina arquitetura criativa com narrativas divertidas baseadas em condimentos e ingredientes clássicos.

Cada estrutura tem uma função simbólica ou lúdica, reforçando a ideia de um mundo onde a comida é cultura, religião e diversão. As mecânicas de jogo que você criou — com armaduras especiais, efeitos inusitados e interações alimentares — ampliam ainda mais o caráter nonsense e interativo desse projeto.

Maionésia é, acima de tudo, uma paródia visual e jogável, feita para divertir, surpreender e encantar dentro dos limites (ou fora deles) do Minecraft.


# Licença

Este projeto é licenciado sob a [MIT License](https://github.com/tech-espm/inter-1sem-2025-reino-maionese/blob/main/LICENSE).
