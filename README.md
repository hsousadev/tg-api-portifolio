# Projeto 1: 2019-2

### Parceiro Acadêmico
FATEC São José dos Campos - Prof. Jessen Vidal

![image](https://user-images.githubusercontent.com/54003876/133176135-5c0c4cf5-5bb2-40f9-84ae-2cea77a563d3.png)
##### *Figura 01. FATEC São José dos Campos - Prof. Jessen Vidal (Fonte: Centro Paula Souza)*

A FATEC (Faculdade de Tecnologia) Prof. Jessen Vidal de São José dos Campos, faz parte das importantes instituições brasileiras de ensino superior de tecnologia do estado de São Paulo pertencentes ao Centro Estadual de Educação Tecnológica Paula Souza (CEETEPS), possuindo excelência em seus cursos de graduação, tem como objetivo formar tecnólogos, profissionais nas quais as áreas de atuação são mais específicas comparado às demais modalidades de graduação (Licenciatura e Bacharelado).

Iniciando em 2019 com seu primeiro PI (Projeto Integrador), que mais tarde foi intitulado como  API (Aprendizado por Projeto Integrador) a FATEC Prof. Jessen Vidal se disponibilizou a ser a empresa parceira neste projeto pioneiro da própria instituição no qual tem como finalidade avaliar seus alunos por meio de um trabalho, recorrente semestralmente, que aborda problemas e soluções do mercado atual na área de especialização. 

### Visão do Projeto
O primeiro projeto integrador consistiu no desenvolvimento de um sistema de automação residencial. 

Dado o crescente nicho de mercado das automatizações residenciais, a viabilidade por sistemas que se enquadre neste aspecto são constantes e com uma alta demanda. A proposta do [SIGMA](https://github.com/justhenrique/sigma-sistema-inteligente-de-gerenciamento-manual-de-ambiente) é entregar a qualidade e conforto focando na simplicidade de uso.

O [SIGMA](https://github.com/justhenrique/sigma-sistema-inteligente-de-gerenciamento-manual-de-ambiente) (Sistema Inteligente de Gerenciamento Manual de Ambiente) é um sistema de automação simples desenvolvido pelos alunos da FATEC de São José dos Campos no primeiro semestre do curso de análise e desenvolvimento de sistemas em outubro de 2019. Com a funcionalidade de automatização de iluminação residencial personalizada e acionamento de refrigeração de um ambiente. 

Para a elaboração deste, observou como objetivos principais do sistema a facilidade de entendimento para o usuário; instalação simples do aplicativo; permitir ligar/desligar a iluminação dos cômodos individualmente; controle de cor da iluminação no quarto; ajuste do nível de luminosidade na sala; ligar/desligar climatização do quarto. <br/>

![sigma-app-screens](https://user-images.githubusercontent.com/54003876/133179045-a0ea1c0d-6713-4825-9dac-fd1a13a1c376.png)
##### *Figura 02. Interfaces da aplicação FIGMA (Fonte: https://github.com/justhenrique/sigma-sistema-inteligente-de-gerenciamento-manual-de-ambiente)*

### Tecnologias adotadas na solução
Para elaboração deste produto, cabe ressaltar que suas tecnologias se dividem em software e hardware. 

##### Hardware
###### MODULO ESP8266 NodeMCU Wi-Fi
Um microcontrolador, que oferece uma solução de rede WiFi e capaz também de executar aplicativos independentes, composto por um chip controlador, uma porta micro USB para alimentação e programação. Além de um conversor USB serial integrado e já possui Wi-Fi nativo.

![image](https://user-images.githubusercontent.com/54003876/133179844-c3ec65c6-c62d-4c03-abf1-004e1bbf9e18.png)
##### *Figura 03. NodeMCU ESP8266 (Fonte: www.handsontech.com)*

###### LED e LED RGB
Utilizado para simular a lâmpada dos cômodos de uma residência. Um componente eletrônico capaz de emitir luz visível transformando energia elétrica em energia luminosa.

![image](https://user-images.githubusercontent.com/54003876/133180170-73608bd8-5953-4c00-9493-992d27332c0e.png)
##### *Figura 04. Representação/Composição LED (Fonte: http://lczambon.blogspot.com/p/lampadas-led.htm)*

###### COOLER
Utilizado para simular o sistema de climatização. Cooler de 5V de potẽncia. Um componente utilizado para remover o calor excessivo de um determinado componente. 

![image](https://user-images.githubusercontent.com/54003876/133180350-036d149b-1f46-44a3-9e7e-c89295614188.png)
##### *Figura 05. Cooler (Fonte: https://www.autocorerobotica.com.br/cooler-5v-40x40mm)*

###### JUMPER
Uma ligação móvel entre dois pontos de um circuito eletrônico, podendo assumir vários formatos e tamanhos.

![image](https://user-images.githubusercontent.com/54003876/133180471-8df7e946-c85c-4a7b-819d-0789f259b0aa.png)
##### *Figura 06. Jumper Macho/Macho (Fonte: https://www.filipeflop.com/produto/kit-jumpers-macho-macho-x65-unidades/)*


##### Software
###### BLYNK
Blynk possui o “App Blynk” que possibilita a criação de interface de controle de forma simples, “Servidor Blynk”, responsável pela comunicação entre o dispositivo móvel e a plataforma, “Bibliotecas Blynk”, bibliotecas para todas as plataformas mais populares e compatíveis com o Blynk, permitindo a comunicação com servidor na nuvem (cloud) ou local, processando todos os comandos de entrada e saída.

![image](https://user-images.githubusercontent.com/54003876/133180682-5c162b86-34be-4812-bd5c-a2217a816fce.png)
##### *Figura 07. Blynk Logo (Fonte: blynk.io)*

###### Linguagem C++
Para a programação do NodeMCU ESP8266 foi utilizado a linguagem C++, no qual foi programado dentro do ambiente de desenvolvimento do artduino. 


### Contribuições pessoais
Para a contribuição deste, coube o desenvolvimento do código em linguagem C++ e a conexão com a tecnologia Blynk, como também a elaboração da documentação do projeto e pesquisas. 

### Aprendizados Efetivos HS
Um primeiro passo com o primeiro desafio. Individualmente e coletivamente um enorme aprendizado. Pesquisas e teorias aplicadas na prática. Todo o processo pode se resumir em "Aprendizado". Ainda que simples, comparado ao que iria vir pela frente. Parafraseando Neil Armstrong "Foi um pequeno passo como estudante e um enorme passo para um desenvolvedor". Utilizar uma linguagem de programação, na qual antes só se havia ouvido falar, sem quaisquer buscas a fundo e transformá-la na essência do produto foi o ponto forte de muito do que foi realizado. Em resumo: <br/>
Programação de placas (Arduino, NodeMcu e outras): Sei fazer com autonomia <br/>
Desenvolvimento por programação em blocos: Sei fazer com autonomia <br/>
Integrações com modulos Wi-fi: Sei fazer com ajuda <br/>
Integração com Blynk: Sei fazer com autonomia <br/>
Documentação do projeto: Sei fazer com autonomia <br/>
Montagem de peças e integração com a programaçã: Sei fazer com ajuda <br/>

