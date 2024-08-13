# SFV_OG_04-24

Zé Roberto Guimarães assumiu a seleção feminina de vôlei em 2003 e tem sido o treinador desde então, tendo participado das Olimpíadas de [Atenas 2004](https://women.volleybox.net/pt/women-the-olympics-2004-o612), [Pequim 2008](https://women.volleybox.net/pt/women-the-olympics-2008-o611), [Londres 2012](https://women.volleybox.net/pt/women-the-olympics-2012-o610), [Rio 2016](https://women.volleybox.net/pt/women-the-olympics-2016-o965), [Tóquio 2020](https://women.volleybox.net/pt/women-the-olympics-2021-o8363) e [Paris 2024](https://women.volleybox.net/pt/women-the-olympics-2024-o30223/classification). Ele, que já havia conquistado o ouro inédito com a seleção masculina em Barcelona 1992, conseguiu o mesmo feito com a feminina em Pequim 2008 e repetiu o feito em Londres 2012. No vôlei, ele é o primeiro treinador a ser campeão nos dois naipes e o primeiro tri-campeão olímpico do Brasil.

Este é o retrospecto dele com a seleção feminina nas Olimpíadas:
| Olimpíadas              | Posição                                               |
| ----------------- | ---------------------------------------------------------------- |
| Atenas 2004      | 4º Lugar|
| Pequim 2008     | 1º Lugar |
| Londres 2012      | 1º Lugar |
| Rio 2016       | 5º Lugar |
| Tóquio 2020      | 2º Lugar |
| Paris 2024     | 3º Lugar |

-----
## TECNOLOGIAS USADAS:
- Jupyter Notebook: 5.3.0
- Python: 3.11.5
  - Pandas: 2.0.3
  - Numpy: 1.24.3
  - Matplotlib.pyplot: 3.7.2
  - Seaborn: 0.12.2
 
## Instalação das bibliotecas
```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
```

## DESENVOLVIMENTO
- Carregamento dos arquivos no formato csv separados por Olimpíadas, todos tem o mesmo número de colunas e cabeçalhos contendo o número das jogadoras, nome, posição, altura, ano de nascimento, idade e participação olímpica;
- Concanetação dos arquivos em um só para facilitar a análise;
- Análise de idade e altura com pandas;
- Visualização Gráfica de Idade e Altura utilizando seaborn e matplotlib.pyplot;
- Análise Faixa Etária adotando um critério pessoal;
- Análise por participação olímpica.

## CONCLUSÃO
Ao longo deste estudo foi possível observar que não há um padrão para destacar a relação de idade e altura que influencie no resultado, entretanto foi interessante ver a evolução física da seleção feminina que tem montado times altos, chegando em Paris 2024 com 5 jogadoras com mais de 1,90. 
Seria pertinente fazer esse comparativo com outras seleções como Itália, a atual campeã olímpica, EUA, equipe que derrotou o Brasil na semifinal, Sérvia, atual campeã mundial e Rússia, uma seleção muito tradicional.
Na questão idade o que mais chamou a atenção foi em relação as levantadoras que sempre são as mais experientes do grupo, enquanto as ponteiras têm uma média de idade um pouco mais baixa, o que pode ser explicado pelo fato de normalmente irem 4 para essa posição, sendo opções que acabam indo mais pra ter rodagem.
Apesar de Rio 2016 e Tóquio 2020 terem a mesma média de idade, 30,50 anos, houve uma diferença significativa na composição do time: na primeira, o número de estreantes foi baixo (4 contra 8 com participações anteriores), enquanto na segunda, essa tendência se inverteu.
Também é incrível perceber que nesse intervalo de 20 anos, o Brasil esteve em 5 das 6 semifinais, mostrando ser uma equipe sempre competitiva, mesmo com a mudança de jogadoras ao longo do tempo.
