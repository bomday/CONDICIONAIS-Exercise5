<h2>PROBLEM STATEMENT: Mostra tua força Brasil!</h2>
---
<p>Depois de conseguir avançar na fase de grupos, a seleção de Tite chega como uma forte candidata a vencer o torneio, mas Tite não quis esperar o final da copa para saber se o brasil ia ser campeão ou não, então ele decidiu pedir para você fazer uma simulação com o mata-mata da seleção brasileira para ver o que ia acontecer.</p>
<p>Ele pediu para fazer de um jeito que o fator <b>Favoritismo</b>, sendo ele um numero inteiro, fosse ser algo muito presente na sua simulação.</p>
<p>Você vai receber os resultados que o brasil vai ter das fases do mata-mata, das oitavas até a semifinal (considerando que o Brasil vai chegar até lá). Nos resultados, o Brasil pode tanto avançar quanto ser eliminado em qualquer fase.</p>
- Caso o brasil perca antes de chegar a final, ele será eliminado, e você não receberá as entradas das fases seguintes consequentemente.
<br/>
- Caso ocorra um empate, aí é que o favoritismo começa a entrar em cena, porque ele é o fator de desempate nesse caso, ou seja, em caso de empate, passa a seleção com o maior favoritismo (caso elas empatem no favoritismo também, passa o Brasil porque Tite é clubista!).
<br/>
- Caso o Brasil vença a partida (sem contar a final) o seu favoritismo aumenta dependendo do placar do jogo. Se o brasil vencer por 1 gol de diferença, seu favoritismo aumenta em 10 pontos, se vencer por 2 gols de diferença, aumenta em 20 pontos o favoritismo, e caso vença por 3 ou mais gols, aumenta em 30 pontos o favoritismo brasileiro.
<br/><br/>
<p>A final já vai ser diferente, nela você não vai receber um resultado caso o brasil chegue nela, você só saberá o oponente do Brasil e o Favoritismo que ele chega, e só com o favoritismo, definir quem vai ser o campeão (caso haja empate no favoritismo, ganha quem tem mais copas do mundo ;) Ps. é o Brasil sempre).</p>
<p>OBS: 
<br/>
1. Das oitavas até a final são 4 partidas, mas lembre-se que a última (final), possui uma entrada diferente, e que não necessariamente o Brasil jogará as 4 partidas.
<br/>
2. As funções exit() e quit() não podem ser utilizadas nessa questão.</p>
<h3>Input</h3>
---
<p>Você primeiramente receberá um input, sendo ele um valor inteiro, que irá representar o favoritismo inicial da seleção brasileira.</p>
- FavoritismoBR
<br/><br/>
<p>Depois, você receberá em uma sequência padronizada, o oponente que o brasil irá enfrentar, o seu favoritismo, e o resultado da partida entre os dois, sendo o primeiro número os gols do Brasil, e o 2º o do adversário, mantendo o padrão abaixo até a final:</p>
1. NomeOponenteX
<br/>
2. FavoritismoOponenteX
<br/>
3. GolsBRX
<br/>
4. GolsOPOX
<br/><br/>
<p>Até chegar na final, onde você irá receber somente o nome e o favoritismo do oponente, como foi previamente dito.</p>
1. NomeOponente
<br/>
2. FavoritismoOponente
<br/><br/>
<h3>Output</h3>
---
<p>Caso o Brasil seja eliminado em qualquer fase que não seja a final, por conta de uma derrota no resultado, imprima:</p>
-> 'Infelizmente essa seleção dx {nome_adversario} era muito forte para o Brasil.’
<br/><br/>
<p>Caso o Brasil seja eliminado em qualquer fase que não seja a final, por conta de um empate no resultado, mas perdendo por causa do favoritismo, imprima:</p>
-> 'Foi no detalhe! Mas infelizmente o Brasil esta eliminado da copa...’
<br/><br/>
<p>Caso o Brasil avance de fase por conta de um empate no resultado, mas ganhando por causa do favoritismo, imprima:</p>
-> 'No sufoco, o Brasil conseguiu ganhar!!!’
<br/><br/>
<p>Caso o Brasil avance de fase, por conta de uma vitória no resultado, imprima:</p>
-> ‘Quem é que segura o Brasil???’
<br/><br/>
<p>Caso o Brasil perca a final, imprima:</p>
-> ‘O nosso Brasil foi vice, não conseguindo bater a seleção dx {nome_adversario} na simulação’
<br/><br/>
<p>Caso o Brasil seja campeão, imprima:</p>
-> 'O BRASIL VAI SER HEXAAAAAAAA’
