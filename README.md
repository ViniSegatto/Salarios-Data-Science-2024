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

# Correlação e Significância

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/584f21b5-19f8-48a4-a253-faadecd6c7a3)

Os gráficos apresentados têm como objetivo visualizar a relação entre variáveis categóricas e numéricas, especificamente a relação entre as variáveis codificadas (categóricas transformadas em numéricas usando Label Encoding) e o salário em dólares americanos. Vamos detalhar cada conjunto de gráficos:

Relação entre Ano de Trabalho e Salário:

Gráfico de Regressão (Esquerda): Mostra a relação entre o ano de trabalho (work_year) e o salário em dólares americanos. A linha de regressão vermelha indica a tendência geral da relação entre essas variáveis.

Gráfico de Regressão (Direita): Apresenta a relação entre a codificação da experiência (experience_encoded) e o salário. Aqui, a codificação da experiência é uma representação numérica da variável categórica original.

Relação entre Tamanho da Empresa e Tipo de Contrato com o Salário:

Gráfico de Regressão (Esquerda): Exibe a relação entre a codificação do tamanho da empresa (company_size_encoded) e o salário em dólares americanos.

Gráfico de Regressão (Direita): Mostra a relação entre a codificação do tipo de contrato (employment_type_encoded) e o salário. Ambos os gráficos ajudam a entender como essas variáveis categóricas transformadas se relacionam com o salário.


Esses gráficos de regressão são valiosos para explorar visualmente as relações entre variáveis categóricas e salários na área de Ciência de Dados. Eles oferecem uma análise intuitiva das influências desses fatores nos salários, permitindo uma rápida identificação de padrões ou variações nos dados.

A presença da linha de regressão vermelha em cada gráfico destaca a tendência geral nas relações examinadas. Essa linha representa a direção e a intensidade média da relação entre a variável categórica e o salário. Notavelmente, a consistência nos padrões identificados nas análises anteriores é mantida mesmo quando aplicamos a análise de regressão. Isso reforça as observações feitas anteriormente sobre a influência das variáveis examinadas nos salários, reforçando a validade das tendências identificadas.

Dessa forma, os gráficos de regressão proporcionam uma abordagem adicional e complementar para compreender as dinâmicas entre variáveis categóricas e salários, corroborando as conclusões derivadas das análises exploratórias anteriores.

# Correlação de Pearson

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/0db9100a-10da-41d6-b8ad-1b14e2292675)

Uma análise de correlação de Pearson é uma medida estatística que avalia a relação linear entre duas variáveis contínuas. Fornecendo um coeficiente de correlação que varia de -1 a 1, indicando a força e a direção da relação entre as variáveis.

Coeficiente de Correlação (r):

	r = 1: Correlação perfeita positiva (à medida que uma variável aumenta, a outra também aumenta de maneira linear).
	r = -1: Correlação perfeita negativa (à medida que uma variável aumenta, a outra diminui de maneira linear).
	r = 0: Ausência de correlação linear.
Interpretação:

Quanto mais próximo de 1 (positivo) ou -1 (negativo), mais forte é a correlação.
Quanto mais próximo de 0, mais fraca é a correlação.
Direção:

Positiva: Aumento em uma variável está associado ao aumento na outra.

Negativa: Aumento em uma variável está associado à diminuição na outra.

Exemplo de Interpretação:

Se tivermos um coeficiente de correlação de 0.8 entre a experiência profissional e o salário, isso sugere uma correlação positiva forte. Ou seja, à medida que a experiência profissional aumenta, é provável que o salário também aumente.

A correlação de Pearson avalia apenas relações lineares.
Outliers podem influenciar significativamente o resultado.
Correlação não implica causalidade.
Ao realizar uma análise de correlação de Pearson, é essencial considerar o contexto, interpretar os resultados com cautela e explorar visualmente os dados para uma compreensão abrangente da relação entre as variáveis. Essa análise é valiosa para identificar padrões lineares e fornecer insights sobre a possível associação entre as variáveis em estudo.

# Correlação de Spearman

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/f90914d5-568f-4aee-a8ea-a782649a28c3)

Objetivo com essa avaliação de correlação é avaliar a relação monotônica (não necessariamente linear) entre duas variáveis. Que é recomendada quando as variáveis não têm uma relação linear, mas mantêm uma relação consistente, mesmo que não seja estritamente uma linha reta. Quanto mais próximo de 1 (positivo) ou -1 (negativo), mais forte é a correlação. Quanto mais próximo de 0, mais fraca é a correlação.
Coeficiente de Correlação (ρ - rho):
  ρ = 1: Correlação perfeita positiva monotônica.
  ρ = -1: Correlação perfeita negativa monotônica.
  ρ = 0: Ausência de correlação monotônica.

# Correlação de Kendall

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/3fd4cfff-64cb-4348-8bca-de148d38ecd3)

Objetivocom mais essa avaliação de correlação é medir a concordância entre duas variáveis, focando nos pares de dados que mantêm a mesma ordem na classificação.
É uma analise util quando a análise se concentra em identificar se há uma concordância na ordem dos dados entre as variáveis. Medir a concordância entre duas variáveis, focando nos pares de dados que mantêm a mesma ordem na classificação.
Quando usar: Útil quando a análise se concentra em identificar se há uma concordância na ordem dos dados entre as variáveis.
Coeficiente de Correlação (τ - tau):
  τ = 1: Concordância perfeita positiva.
  τ = -1: Concordância perfeita negativa.
  τ = 0: Ausência de concordância.


A análise de correlação de Spearman e Kendall é mais robusta a outliers em comparação com a correlação de Pearson. Essas medidas são particularmente adequadas para dados não lineares e são úteis quando a relação entre as variáveis não segue uma tendência linear clara.

Correlação de Spearman, essa medida avalia a relação monotônica entre duas variáveis, ou seja, se uma variável aumenta, a outra também aumenta (ou diminui) de maneira consistente, mas não necessariamente de maneira linear.
O coeficiente de correlação de Spearman também varia de -1 a 1, sendo 1 para uma correlação perfeita positiva, -1 para uma correlação perfeita negativa e 0 para ausência de correlação.


Correlação de Kendall, é similar à correlação de Spearman, a correlação de Kendall mede a concordância de classificações entre pares de observações.
Ela é especialmente útil quando os dados são ordinais e a relação entre as variáveis é mais facilmente expressa em termos de ordem do que de magnitude absoluta.
O coeficiente de correlação de Kendall também varia de -1 a 1, seguindo a mesma interpretação da correlação de Spearman.
Racional para Escolher Spearman e Kendall:

Ambas as correlações são mais robustas a outliers, o que significa que a presença de valores extremos não influenciará significativamente o resultado.
Em contextos onde não é possível mensurar ou quantificar características específicas, como o tamanho da empresa ou a importância do trabalhador, as correlações de Spearman e Kendall podem fornecer uma visão mais precisa da relação entre as variáveis.
Portanto, ao optar por utilizar Spearman ou Kendall, estamos priorizando uma análise mais resistente a desvios nos dados, especialmente em situações em que não temos uma compreensão completa das características subjacentes que podem impactar a relação entre as variáveis estudadas, pois não temos como medir o tamanho da empresa, a importancia do trabalhador para receber um salario maior ou menor do que a media, então não temos como garantir que são outliers para retira-los do dataset, podendo trazendo um maior desbalanço para os dados que estamos analisando. 

# Top 15 Skill 

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/9efa0342-eba9-4e54-a31f-603be7d31a00)

No gráfico acima, que utiliza um segundo conjunto de dados, são destacadas as 15 habilidades mais solicitadas para candidatos a vagas nas áreas de Ciência de Dados. 

Ao analisar a distribuição geral das habilidades necessárias, observamos que, em média, um profissional é esperado possuir aproximadamente 24 habilidades para atender a todos os requisitos das vagas disponíveis. Essa informação destaca a abrangência e diversidade de competências exigidas no campo da Ciência de Dados, enfatizando a importância da multifuncionalidade e da capacidade de os profissionais atenderem a uma ampla gama de requisitos específicos da área. 

Essa análise ressalta a complexidade e a variedade de habilidades demandadas no mercado de trabalho em Ciência de Dados, indicando a necessidade de profissionais versáteis e capacitados para lidar com uma variedade de tarefas e responsabilidades dentro desse campo dinâmico.

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/97fdaf20-f9d6-4d8a-a482-adef8c0b5014)

# Pytorch vs TensorFlow

Na análise abaixo, comparamos algumas das principais habilidades na área de dados, destacando a demanda entre duas das principais ferramentas, PyTorch e TensorFlow. Observamos que a habilidade "TensorFlow" é predominantemente requisitada, representando uma superioridade significativa de 52,7% em relação ao PyTorch. Essa comparação oferece insights valiosos sobre a preferência do mercado de trabalho em relação a essas duas tecnologias específicas, indicando que a proficiência em TensorFlow é mais solicitada e amplamente reconhecida pelas empresas que buscam profissionais qualificados em Ciência de Dados. 

Essa análise pode orientar profissionais e estudantes na priorização de suas habilidades, destacando a importância de investir em competências específicas que são altamente valorizadas no cenário atual da área de dados.

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/bdf0b72b-9736-4a20-bad4-1c69594611af)

# Tableau vs PowerBI 
Na comparação entre ferramentas de Business Intelligence, observamos que a demanda por profissionais com conhecimento em Tableau é superior, representando 55% das solicitações, enquanto o PowerBI alcança 45%. Essa análise destaca a preferência do mercado por profissionais familiarizados com o Tableau, indicando que essa ferramenta específica é mais requisitada pelas empresas em comparação com o PowerBI. Essa informação é crucial para os profissionais da área de dados que buscam se especializar em uma ferramenta de Business Intelligence específica, direcionando suas habilidades para atender às demandas do mercado de trabalho. A compreensão dessas preferências auxilia na tomada de decisões estratégicas sobre o desenvolvimento de competências para se destacar e atender às expectativas do setor.

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/32aeb508-83da-462b-9f21-31ee830fbefe)


# Python vs R 

Na análise comparativa entre as linguagens de programação Python e R, percebemos uma clara preferência do mercado, com Python liderando significativamente. Cerca de 75% das vagas exigem conhecimento em Python, enquanto R representa 25.3%. Essa disparidade destaca o domínio e a versatilidade da linguagem Python no cenário da ciência de dados. Profissionais que buscam oportunidades nesse campo podem priorizar o aprendizado e o aprimoramento das habilidades em Python, dado o seu amplo uso e alta demanda no mercado de trabalho. Essa informação é valiosa para orientar a preparação e o desenvolvimento de competências, alinhando-as com as exigências do setor e ampliando as oportunidades de emprego na área de ciência de dados.

![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/8ac0accd-fad7-44d9-871a-17ad878f54e6)

# Machine Learning Vs Deep Learning vs GenAI


![download](https://github.com/ViniSegatto/Salarios-Data-Science-2024/assets/117327390/07011f6b-2e0b-4968-9667-7094c67ceb65)
