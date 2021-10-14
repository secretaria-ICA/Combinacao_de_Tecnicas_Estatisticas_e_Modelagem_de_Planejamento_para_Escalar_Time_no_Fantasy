# Combinacao_de_Tecnicas_Estatisticas_e_Modelagem_de_Planejamento_para_Escalar_Time_no_Fantasy_Game_Cartola_FC

#### Aluno: [Francimário Alves de Lima](https://github.com/francimariolima)
#### Orientador(/a/es/as): [Felipe Borges](https://github.com/FelipeBorgesC).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

### Resumo

Não é novidade que futebol é uma paixão do brasileiro e está presente em nosso dia a dia. Além da transmissão dos jogos do campeonato brasileiro entre tv aberta e pay-per-view, a Rede Globo encontrou uma outra forma de transformar em negócio esse amor pelo esporte: através do Fantasy Game Cartola FC. De forma resumida, no game, o usuário escala seu time ideal com uma quantidade limitada que tem de patrimônio, visando maximizar a pontuação do time. A grande sacada é que tal pontuação é advinda, justamente, do que os jogadores fazem em campo na vida real, por exemplo, se um atacante faz um gol, soma 8 pontos, se sofre uma falta, mais 0,5, e assim sucessivamente.

O trabalho em questão utiliza de diversos conceitos lecionados no Curso [BI MASTER](https://ica.puc-rio.ai/bi-master) para auxiliar na escalação do que seria o time ideal (maior pontuação possível com o patrimônio da rodada). Primeiramente, para acessar a base da pontuação, preço, jogos, e outros dados, utilizamos o software R para acessar uma API do game e, no próprio R, fazemos o tratamento dos dados. Então, uma segunda matéria que foi utilizada é o Método Estatístico para Apoio a Decisão. Preferimos não "reinventar a roda" e utilizamos o site [Chance de gol](https://www.chancedegol.com.br/) para considerar na previsão da pontuação de cada jogador a probabilidade de seu time vencer na rodada. Para essa probabilidade, é considerada o fator mando de campo, a fase do time, dentre outros, e quanto maior a chance de vencer, maior a chance do jogador se dar bem na rodada.

Por fim, com a pontuação estimada para cada jogador, a tabela é extraída para o Excel. Como dito a cima, fica claro que o Cartola FC trata de um problema de Otimização e Planejamento, em que temos uma quantidade finita de recurso (patrimônio) e temos milhares de possibilidades de escalar um time. Assim, no Excel, modelou-se o problema com suas respectivas restrições e função objetivo e, com o apoio do Solver - o otimizador do Excel-, conseguimos em poucos segundos chegar em um time competitivo (não podemos garantir que seria a solução ótima!).

---

Matrícula: Francimário Alves de Lima (192.671.059)

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
