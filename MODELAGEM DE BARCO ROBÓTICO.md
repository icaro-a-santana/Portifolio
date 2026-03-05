- SITUAÇÃO: No âmbito da robótica simulações são uma ferramenta de extrema importância para a validação de algoritmos sem a necessidade do possível gasto com materiais em um teste empírico. Isso, de tal modo que o projeto de barco robótico que coordeno na SBC RAS UFC ainda não possuía um modelo em simulador.
- OBJETIVO: 
Desenvolver o modelo de um barco robótico no ambiente CoppeliaSim afim de possibilitar o teste de algortimos de controle a serem aplicados na navegação do barco.
- METODOLOGIA: 
Confecção de Modelo 3d da estrutura do robô via SolidEdge, importação do modelo para o ambiente de simulação CoppeliaSim, simulação da flutuação, viscosidade, coleta de dados de posição, velocidade, aceleração lineares, e velocidade angular, e entradas de controle para duas turbinas tudo via linguagem Lua(Linguagem Nativa do Simulador), utilização de API para troca de dados entre simulação no ambiente CoppeliaSim e controlador externo programado em Python.
- RESULTADO:
