# Unidade 01 Trabalho 02

* [link da explicação em video](https://www.loom.com/share/4fc5875077d6445cb31cc7869f490da8?sid=c91c5032-8062-441e-b9be-4c7a206723f0)

## Exportação de Dados:
* A partir da plataforma Scopus, vocês deverão extrair um arquivo .csv que contenha informações de artigos
publicados por autores da UFRN.Esse conjunto pode ser filtrado por uma área específica (como saúde,
engenharia, computação, etc.), por múltiplas áreas ou ainda por temas
de interesse, como "machine learning", "inteligência artificial", "redes
complexas", etc.
* O arquivo .csv deve conter, no mínimo, as seguintes colunas:
Nome dos autores
Identificadores únicos dos autores
Título do artigo
Ano de publicação

## Criação da Rede de Co-Autoria:
* Utilizando os dados extraídos, vocês deverão criar uma rede de
co-autoria. Neste grafo, os vértices serão os autores e as arestas
representarão a colaboração entre eles. Por exemplo, se um artigo foi
escrito por três autores (A1, A2, A3), as arestas (A1, A2), (A1, A3), e (A2, A3)
serão criadas no grafo.

## Análises na Rede:
* Com a rede criada, vocês deverão realizar as seguintes análises
utilizando o NetworkX (use as funções já implementadas na ferramenta):
- Densidade da Rede: Calcular a densidade, que mede o quão
conectados estão os autores em relação ao número máximo
possível de conexões.
- Sub-Grafo: Gerar um sub-grafo contendo apenas os vértices que
possuem pelo menos X vizinhos (X será um valor a ser definido por
vocês). Calcular a densidade desse sub-grafo.
- Histograma dos Graus: Criar um gráfico de histograma mostrando
a distribuição do grau dos vértices da rede. O grau de um vértice
representa o número de co-autores com os quais ele colaborou.

## Entrega e Avaliação:
* O trabalho deve ser entregue em formato de repositório no GitHub,
onde vocês deverão incluir todos os códigos utilizados, dados
processados e um arquivo README explicando o processo.
* Na submissão mencionar o link do repositório e inserir os códigos
desenvolvidos em um .zip no anexo.
* Além disso, cada grupo deverá gravar um vídeo explicativo de até 10
minutos na plataforma Loom ou software similar, descrevendo o que foi
feito e justificando as escolhas feitas durante o desenvolvimento.
* O trabalho vale 1,5 pontos na Unidade 1.