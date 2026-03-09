project #project/evangelho-no-lar
area #area/programming
type #raw 
related-notes

## Descrição
Esse projeto tem como intuito ser um projeto multiplataforma (web e mobile) que facilite, organize e provenha recursos para o evangelho no lar espirita. A UI deve ser acolhedora e agradável visualmente, sem muitos estímulos (minimalista). Deve ser possível organizar as etapas do evangelho de forma personalizada: prece inicial, leitura principal, leitura de mensagens (uma mensagem por integrante) e oração final. 
## Telas
Contexto geral de UI: Calma, relaxante, minimalista e acolhedora. Transições leves e encantadoras.
### 1. Tela inicial 
Tela que possui apenas um botão, "Começar".
### 2. Tela de configuração de etapas
Tela que permite adicionar, remover ou reordenar etapas do evangelho. Lista de etapas possíveis:
- prece inicial
- leitura principal
- leitura de mensagem
- prece final
Nela deve ser possível informar a quantidade de participantes do evangelho, que será usado pra determinar quantas mensagens serão lidas (um participante tira uma mensagem por vez).
### 3. Telas das etapas
#### 3.1 Tela da prece incial
Esta tela deve ter um design extremamente minimalista, onde só há o texto "Prece" e dois botões:
"Preces prontas" (bem discreto) e o nome da próxima etapa no botão. Ex. "Leitura principal" ou "Mensagens".

#### 3.2 Tela inicial da leitura principal
Esta tela deve ser uma tela mais chamativa e viva, sem perder a calma e o minimalismo.
Deve conter um menu dropdown que posso fazer a seleção de livros e um botão "Abrir"
#### 3.2 Tela da leitura principal
 Nessa tela deve ser possível rolar o texto para baixo para ler o trecho por completo, mas sempre deve estar aparente o botão com o nome da próxima etapa. Ex. "Mensagens" ou "Prece final". Ao final do trecho, deve ser possível ver um botão "Ler mais" que trará do servidor a continuação da passagem.
#### 3.3 Tela inicial de mensagens
Deve conter apenas o texto "Mensagem 1" e um botão "Abrir". Caso seja apenas um participante, o texto deve ser "Mensagem"
#### 3.4 Tela da leitura de mensagens
Deve conter a mensagem sorteada e um botão "Mensagem 2". Caso seja apenas um participante, o botão deve ter o nome da proxima etapa. Ex. "Prece final".
#### 3.5 Tela da prece final
Esta tela deve ter um design extremamente minimalista, onde só há o texto "Prece" e dois botões:
"Preces prontas" (bem discreto) e um botão de "Concluir", que navega de volta a tela inicial

## Tecnologias
O projeto deverá feito com React e Typescript, com arquivos css dedicados para cada componente do app que sigam a convenção de nomenclatura de css BEM. Utilize qualquer 