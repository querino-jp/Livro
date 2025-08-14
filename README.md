# Projeto de Estatística Aplicada

## 🧑‍💻 Autores  
- João Pedro Oliveira Querino (202421250012) - joao.querino@academico.ifpb.edu.br  
- Guilherme Melo de Ataíde (202421250021) - guilherme.ataide@academico.ifpb.edu.br 

## 🎯 Tema e Motivação  
Nosso projeto irá investigar o hábito da leitura de livros no Brasil, fazendo uso dos dados da Câmara Brasileira do Livro (CBL). Escolhemos o tema motivados pelo desejo de entender quais os impactos tecnológicos, econômicos e sociais na escolha dos livros e no modo como o importante hábito da leitura é mantido pelos brasileiros. 

A leitura é um hábito essencial para o desenvolvimento de habilidades cognitivas que transparecem a qualidade da educação de uma nação. A partir da pesquisa estatística, podemos refletir sobre a eficácia de políticas públicas voltadas para a independência intelectual dos cidadãos.

## 📊 Conjunto de Dados Selecionado  
- **Nome do conjunto de dados:**  
  CBL
- **Fonte:**  
  https://cbl.org.br/o-que-fazemos/#div_block-123-101

- **Descrição breve:**  
 A Câmara Brasileira do Livro apresenta estudos anuais do mercado editorial em parceria com o Sindicato Nacional dos  Editores de Livros (SNEL). As pesquisas são realizadas pela Nielsen Brasil e trazem um panorama do mercado do livro no país. São estas: Produção e Vendas do Setor Editorial Brasileiro e sua Série Histórica, e o Conteúdo Digital do Setor Editorial Brasileiro. Há, ainda, a pesquisa Retratos da Leitura no Brasil, coordenada pelo Instituto Pró-Livro.  

- **Justificativa para a escolha:**  
 A base de dados nos possibilita analisar tanto o mercado quanto o leitor, além de permitir observar o comportamento dos leitores brasileiros de maneira ampla.

---

## ❓ Perguntas ou Hipóteses  

Como a taxa de leitura varia por escolaridade?
Qual a relação entre classe social e taxa de leitura?
Quais são os principais motivos declarados para ler?
Quais são as principais atividades de tempo livre segundo o nível de escolaridade?

## 🔍 Metodologia  
Organização e ordenação de dados categóricos, cálculo de estatísticas descritivas, comparações entre grupos, análise de frequência acumulada, interpretação de tendências.


## 🛠️ Ferramentas Utilizadas  
A biblioteca pandas da linguagem python.

## 📈 Resultados  

Tabela ordenada por nível de escolaridade:
   Fundamental I:     40.0%;
  Fundamental II:     49.0%;
    Ensino Médio:     48.0%;
        Superior:     63.0%;

Tendência: o percentual de leitura aumenta com o nível de escolaridade.
Média dos percentuais: 50.00%
Desvio padrão: ≈ 9.56%

Classe Social | Percentual (%)
A	              62
B	              60
C	              46
D/E	            35

Média: 50.75%
Mínimo: 35%
Máximo: 62%
Desvio padrão: ≈ 12.25%

Motivação para leitura:
Ordem |	          Motivação       	  |  Percentual |	Acumulada
1	                Gosto	                 24%	        24%
2	               Distração	             15%	        39%
3	          Atualização cultural ou 
              Conhecimento geral	       15%	        54%
4	           Crescimento pessoal	       13%	        67%
5	          Aprender algo novo ou
        desenvolver alguma habilidade	   10%          77%

Frequência relativa acumulada dos cinco primeiros: 77% 


## 📌 Conclusões  
A leitura é impulsionada majoritariamente por razões pessoais e culturais, como prazer, distração e crescimento, enquanto os motivos profissionais e escolares aparecem em menor escala, evidenciando uma preferência por motivações internas e voluntárias. Observa-se que a taxa de leitura tende a crescer com o aumento do nível de escolaridade, embora haja variações, e que a formação acadêmica avançada influencia fortemente os hábitos de leitura. Além disso, há uma queda progressiva no percentual de leitores à medida que a classe social diminui. Pessoas com nível superior também apresentam uma adesão muito maior a tecnologias digitais e redes sociais no tempo livre em comparação àquelas com apenas o Fundamental I.


## ⚠️ Limitações e Trabalhos Futuros  
Limitações do Estudo:
Escopo limitado dos dados Os dados utilizados parecem se concentrar em percentuais agregados por escolaridade, classe social e motivações, sem detalhamento regional, faixa etária ou gênero.

Ausência de análise temporal Não há indicação de séries históricas que permitam observar mudanças ao longo dos anos.

Falta de testes estatísticos inferenciais A análise é descritiva, sem aplicação de testes como correlação, regressão ou ANOVA para validar relações entre variáveis.

Representatividade da amostra A fonte principal (CBL e Instituto Pró-Livro) é confiável, mas não foi discutido se os dados representam todas as regiões e grupos sociais do Brasil.

Dados sobre leitura digital Embora o tema mencione impactos tecnológicos, não há análise específica sobre leitura em e-books, audiobooks ou plataformas digitais.


O que poderia ser feito com mais tempo ou dados adicionais:
Análise multivariada Aplicar modelos estatísticos para entender como escolaridade, renda, idade e região interagem na formação do hábito de leitura.

Segmentação demográfica Investigar como o hábito de leitura varia entre jovens, adultos e idosos, ou entre homens e mulheres.

Estudo longitudinal Incorporar dados de diferentes anos para observar tendências e impactos de políticas públicas ou mudanças tecnológicas.

Integração com dados educacionais e econômicos Cruzar com dados do IBGE, INEP ou PNAD para enriquecer a análise com indicadores de educação e renda.

Visualizações interativas Criar dashboards que permitam explorar os dados por filtros como região, faixa etária ou tipo de leitura.

---


