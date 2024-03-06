# Salarios-Data-Science-2024

# Desafio Universidade dos Dados

No desafio proposto por André Yukio, integrante do grupo "Universidade dos Dados", fui estimulado a realizar uma Análise Exploratória de Dados (EDA) sobre o conjunto de dados "Salários de Cientistas de Dados 2024", disponível na plataforma Kaggle.

Esta EDA visa oferecer insights reveladores sobre a evolução da área de dados ao longo dos anos, identificando as áreas mais promissoras, os países de destaque e outros aspectos relevantes. Através da criação de gráficos, buscaremos aprimorar a visualização das informações contidas nos dados, permitindo-nos extrair insights profundos e significativos. O objetivo é proporcionar uma compreensão clara das tendências no mercado de trabalho, em uma área tão dinâmica como a ciência de dados.

Seu envolvimento, feedback e apoio desempenham um papel crucial nesta jornada. Juntos, exploraremos as fascinantes nuances do mercado de ciência de dados e desvendaremos as valiosas lições que esse universo promissor tem a nos oferecer!

# Sobre o Dataset 

O conjunto de dados focado nos salários de diversas áreas de Ciência de Dados visa revelar tendências e padrões cruciais tanto para profissionais iniciantes como para os mais experientes, além de ser uma valiosa fonte de informações para as empresas do setor. A análise abrange os salários nas áreas de dados ao longo dos anos de 2020 a 2024.

Estas análises são de grande relevância para profissionais da área, entusiastas e indústrias, proporcionando insights valiosos sobre valores salariais, variáveis regionais e outros aspectos essenciais. Explore este conjunto de dados comigo e descubra as informações que podem impulsionar sua compreensão do mercado de Ciência de Dados.

# Conteudo e estrutura do Dataset 

Bem-vindo ao conjunto de dados de Salários em Ciência de Dados, abrangendo os últimos cinco anos, de 2020 a 2024. Este conjunto de dados é uma fonte valiosa de informações sobre diversas áreas relacionadas à Ciência de Dados.

Colunas Principais:

job_title: Cargo ou função do profissional.

experience_level: Nível de experiência do trabalhador.

employment_type: Modelo de empregabilidade (tempo integral, meio período, etc.).

work_models: Modelo de trabalho (Remoto, Híbrido ou Presencial).

work_year: Ano específico em que o salário foi registrado.

employee_residence: Local de residência do empregado.

salary: Remuneração original na moeda local.

salary_currency: Moeda do país em que o funcionário atua (BRL, USD,...).

salary_in_usd: Remuneração convertida em Dólares Americanos (USD).

company_location: Localização geográfica da empresa.

company_size: Tamanho da empresa considerando o número de funcionários.

Explore as nuances dos salários em Ciência de Dados ao longo dos anos e tire insights valiosos para profissionais e empresas do setor.

# Iniciando com uma breve analise dos salários

Iniciamos nossa análise com um histograma, proporcionando uma compreensão mais aprofundada dos valores salariais oferecidos nas posições relacionadas à "Data Science". O gráfico permite uma visão clara da distribuição, destacando faixas salariais predominantes e fornecendo insights valiosos sobre a estrutura salarial nesse campo específico.


![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/d59ebd6e-fe63-4248-b2d2-5f626240fd5d)

O histograma acima exibe a distribuição dos salários em USD no conjunto de dados. As linhas pontilhadas representam medidas estatísticas centrais:

Média (Média Aritmética): A linha vermelha pontilhada indica a média dos salários, que é a soma total dos salários dividida pelo número de observações.

Mediana: A linha azul pontilhada representa a mediana, que é o valor central quando todos os salários estão organizados em ordem crescente.

Moda: A linha verde pontilhada destaca a moda, que é o valor ou intervalo de valores que ocorre com mais frequência nos salários.

O histograma proporciona uma representação visual abrangente da distribuição salarial, permitindo identificar tendências, concentrações e dispersões nos dados. Uma análise mais detalhada revela que a maioria dos salários se concentra no intervalo de 100.000 a 200.000 dólares, indicando uma faixa salarial comum na amostra. Essa faixa sugere uma tendência central nos salários, enquanto as caudas do histograma podem indicar a presença de alguns valores atípicos ou extremos.


# Vagas oferecidas em Data Science

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/a530bb54-940d-41e6-bf15-afb1382f8d62)

Após uma análise mais aprofundada, decidimos consolidar vagas com modificações mínimas para obter uma compreensão mais clara. Essa abordagem visa reduzir a dispersão de dados, permitindo uma análise mais eficiente das principais áreas dentro da Ciência de Dados. Identificamos as cinco principais áreas, a saber, "Data Engineer", "Data Scientist", "Data Analyst", "Machine Learning Engineer" e "Machine Learning Manager", que representam 4.757 vagas, totalizando 72,21% de todas as posições em nosso conjunto de dados. Essa concentração nos proporciona uma visão mais focada e significativa das oportunidades de emprego nesse campo.

# Lugares com mais oportunidades

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/022912f7-2d41-4834-90c7-a4e1cc280e21)

Após a abordagem aplicada no gráfico anterior, decidi consolidar o local de residência dos trabalhadores por região. Essa escolha visa evitar a sobrecarga visual de um gráfico com inúmeros valores de cada país. Ao agrupar por região, destacamos uma notável discrepância nos dados da América do Norte, que totaliza 5.564 vagas, representando 84,45% do total para uma única região. Apesar dessa disparidade concentrada em uma região, ainda podemos extrair insights valiosos sobre o mercado de Ciência de Dados. A predominância dos dados da América do Norte reflete uma tendência significativa no setor de tecnologia, evidenciando a influência marcante dessa região no mercado global.


# Niveis de experiencia 

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/fa5329b5-df8e-450c-9fb0-4257cf7c4b64)

A análise do número de vagas por nível de experiência emerge como um indicador crucial para compreender as demandas do mercado. Notavelmente, observamos uma predominância clara de vagas destinadas a profissionais classificados como "seniors", totalizando mais de 4.100 oportunidades. Em seguida, profissionais de nível "Pleno" apresentam uma presença significativa, com 1.675 vagas. Apesar da menor demanda para profissionais "juniors" ou estagiários em comparação com os seniors, a parcela de cerca de 10% do total ainda indica um mercado aberto a novos talentos. Esse cenário sugere um crescimento positivo e promissor na área, com oportunidades consideráveis para profissionais em diferentes estágios de suas carreiras.

# Salario medio por experiencia

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/26795ba1-4348-4616-a6eb-c4ae808773bb)

Conforme esperado, a análise salarial revela uma correlação positiva entre o nível de experiência e o salário médio no dataset. Os profissionais classificados como "executivos" da área de dados ostentam o maior salário médio, atingindo a marca de 184.560 USD. Na sequência, os profissionais "seniors" apresentam um salário médio de 153.600 USD, representando uma diferença de 16,77% entre essas categorias de níveis mais elevados. No segmento de profissionais "mid-level" (considerados "pleno" no Brasil), o salário médio é de 106.500 USD, enquanto os profissionais "juniors" recebem, em média, 75.000 USD, refletindo uma diferença de 29,57%. Essa análise reforça a tendência comum de que o aumento na experiência está associado a salários mais elevados.


# Relação remuneração e ano de trabalho. 

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/84e72393-340d-4848-bd23-5d949f1c9fb7)

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/5685467c-e445-4148-be9c-1d05bebb0405)

Ao comparar os dois papéis, "Data Scientist" e "ML Engineer", percebemos que, apesar da relativa estabilidade nos valores médios de remuneração para "Data Scientists", essa função possui uma quantidade considerável de vagas e salários acima da média. Essa constância pode indicar uma forte demanda contínua para profissionais qualificados nessa área, apesar das variações anuais.

Portanto, embora a média salarial para "Data Scientists" não tenha aumentado expressivamente ao longo dos anos, a quantidade significativa de vagas e a presença de salários acima da média sugerem que essa área continua sendo altamente demandada e valorizada no mercado de trabalho nos Estados Unidos.,

A análise da remuneração ao longo dos anos para a função de "ML Engineer" nos Estados Unidos revela um cenário interessante. Observamos um aumento notável na média dos valores pagos para essa área, indicando uma valorização crescente ao longo do tempo. Esse aumento é especialmente evidente no ano de 2023, onde ocorre uma variação significativa nos valores.

É importante destacar que, nos anos anteriores, a disponibilidade de dados para a função de "ML Engineer" pode ter sido limitada, mas, mesmo assim, a tendência de valorização é clara. Esse aumento pode sugerir uma demanda crescente por profissionais qualificados nessa área, refletindo a importância contínua da aprendizagem de máquina e engenharia de dados no mercado de trabalho.
Portanto, a análise aponta para uma valorização substancial da função de "ML Engineer" ao longo dos anos, indicando uma tendência positiva para profissionais que atuam nesse campo específico.


![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/76041bd4-c003-434e-9585-a82db32fb2fc)

Tipo da Vaga:

Gráfico de Barra (Esquerda): Mostra a média da remuneração para cada tipo de vaga (Remoto, Híbrido, Presencial). Cada barra representa a média salarial em dólares americanos para os respectivos tipos de vaga.
Gráfico de Boxplot (Direita): Exibe a distribuição dos valores salariais para cada tipo de vaga, permitindo visualizar medidas estatísticas como mediana, quartis e possíveis outliers.

Tamanho da Empresa:

Gráfico de Barra (Esquerda): Apresenta a média da remuneração para diferentes tamanhos de empresas. Cada barra representa a média salarial em dólares americanos para as respectivas categorias de tamanho de empresa.
Gráfico de Boxplot (Direita): Ilustra a distribuição dos valores salariais em relação ao tamanho das empresas, proporcionando insights sobre a variabilidade salarial dentro de cada categoria de tamanho.

Tipo de Contrato:

Gráfico de Barra (Esquerda): Indica a média da remuneração para diferentes tipos de contrato de emprego (Tempo Integral, Meio Período, etc.). Cada barra representa a média salarial em dólares americanos para as categorias de contrato.
Gráfico de Boxplot (Direita): Mostra a distribuição dos valores salariais para cada tipo de contrato, destacando a variabilidade salarial dentro de cada categoria.
Essa abordagem visual permite uma compreensão rápida e comparativa da remuneração em relação a diferentes variáveis, oferecendo insights sobre como esses fatores podem influenciar os salários na área de Ciência de Dados.

teste8
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/584f21b5-19f8-48a4-a253-faadecd6c7a3)

teste9
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/0db9100a-10da-41d6-b8ad-1b14e2292675)

teste10
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/f90914d5-568f-4aee-a8ea-a782649a28c3)

teste11
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/3fd4cfff-64cb-4348-8bca-de148d38ecd3)

teste12
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/9efa0342-eba9-4e54-a31f-603be7d31a00)

teste13
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/97fdaf20-f9d6-4d8a-a482-adef8c0b5014)

teste14
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/bdf0b72b-9736-4a20-bad4-1c69594611af)

teste15
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/32aeb508-83da-462b-9f21-31ee830fbefe)

teste16
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/8ac0accd-fad7-44d9-871a-17ad878f54e6)

teste17
![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/07011f6b-2e0b-4968-9667-7094c67ceb65)
