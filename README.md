QUESTÃO 1

Um motorista de aplicativo recebeu uma corrida para realizar. A localização atual do motorista é representada a seguir pelo vértice número 1 (um) e a corrida está no vértice de número 5 (cinco). 

![image](https://user-images.githubusercontent.com/73788864/181633020-e138253f-5fbf-4ef3-98bb-7bc4c02305f1.png)


O grafo acima exibe todas as rotas para alcançar o destino a partir do ponto de partida. O destino da corrida é o vértice indicado pelo número 5 (cinco). As possíveis rotas são representadas pelos demais vértices que vão de 1 (um), que é a origem, a 4 (quatro).  

Desenvolva um algoritmo que ajude o motorista de aplicativo a tomar a melhor decisão de rota, pois devido ao aumento consecutivo do valor do combustível, o motorista quer uma estimativa de qual é a melhor rota até o destino da corrida. Para isso, foi feito um levantamento histórico do consumo médio das viagens passando por cada ponto de origem até o destino final.   

Na figura do grafo, os vértices 1, 2, 3, 4 e 5 representam, respectivamente as rotas em que o motorista deve passar para chegar ao destino. O trajeto é representado pelas arestas que liga (1 a 2), (1 a 3), (2 a 4), (2 a 5), e assim por diante. O consumo médio (peso) entre cada conexão está representado por X. Você deve substituir o X pelos 7 primeiros dígitos do seu RA (indo da esquerda para direita) multiplicado por 6,596, que é o valor do litro da gasolina nesse momento, na sequência: (1-2), (1-3), (2-4), (2-5), (3-2), (3-5), (4-5).   

  

Exemplo:   

  

RA 2045703-5 = Será utilizado os seguintes números do seu RA 2045703   

RA 204570-5 = Em caso de 6 dígitos, acrescentar o dígito 1 ao final 2045701   

  

(1-2) = 2 * 6,596 = 13,192 

(1-3) = 0 * 6,596 = 0 

(2-4) = 4 * 6,596 = 26,384 

......   

Utilize o algoritmo de Dijkstra para resolver o problema e informe o caminho de menor custo saindo de 1 (que é o ponto de partida da corrida) e chegando em 5 (que é o destino da corrida). O resultado do seu programa deverá indicar as rotas que poderão ser utilizadas pelo motorista e o seu respectivo peso.   

 

Passos para realizar o Mapa:   

 

1. Desenvolva um programa em linguagem C, salvar com a extensão (.c) que informe os caminhos saindo de 1 e chegando em 5.   

1.1. Neste código, usuário deverá excetuar as seguintes ações: 

   - informar o número de vértices (ponto de rota), 

   - informar as arestas com suas respectivas rotas de origem e destino, 

   - informar o custo correspondente ao seu RA para todas as rotas. 

1.2. Calcular rotas.   

1.3. Apresentar na tela todos os destinos com os seus respectivos pesos.  

2.   Após a impressão (item 1.3) tirar um print da sua tela de forma que pegue todos os destinos. 

   - Neste print marque o(s) caminho(s) de menor custo saindo de 1 e chegando em 5 (usar qualquer programa de edição de imagem) 

   - Salve com extensão (.doc), (.docx), (.pdf), (.png) e (.jpg)  

* Indicação de IDE para desenvolver sua atividade MAPA (DEV C++, Code::Block, https://replit.com/) 
