# Tarefa 1
* <b>Carregue um corpus (conjunto de textos)</b>;
* <b>Extraia todas as palavras únicas do corpus e insira-as em uma árvore AVL</b>;
* <b>Implemente uma função que receba um prefixo (parte inicial de uma palavra) e retorne
uma lista com as possíveis palavras completas encontradas na árvore</b>;
* <b>Realizar uma comparação de desempenho</b>
* <b>Implementar um front-end mínimo</b>

## Instalação

Faça o download "tarefa_1.ipynb" e "jokes.csc". Caso queira utilizar outro Corpus, certifique-se de ajustar o diretorio do pd.read_cs() na parte de "Conjuntos de dados" no notebook. Por fim, pode exercutar todo o notebook e visualizar os resultados das tabelas com as comparações.
Caso queira visualizar o resultado em um front, siga para o tópico do notebook "Streamlit", rode os três blocos de código; no ultimo bloco onde está "! streamlit run app.py & npx localtunnel --port 8501" entre no url disponibilizado na parte de "your url is:". Pegando o ipv4 do segundo bloco e colocando no "Tunnel Password" do url disponibilizado, você tera acesso ao auto complet que utiliza a AVL.