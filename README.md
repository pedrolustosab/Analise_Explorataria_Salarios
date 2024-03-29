# Análise Estatística de Dados 

Código desenvolvido para tratamento, limpeza, processamento, preparo, análise estatística e visualização de dados com a base de dados [Salary](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data/data) disponível no Kaggle.  

O projeto visou cumprir os requisitos de **Estatística**, do bootcamp de Dados da **Ada Tech**, patrocinado pelo **Potência Tech**, do **iFood**. 


O projeto foi realizado em março de 2024 e contou com a colaboração de 2 integrantes:
* Pedro Lustosa
* Rafael Guisso


# Análise Geral

## Tendências Gerais encontradas

**1. Correlação forte e possitiva:**

![Gráfico 1](cor_numeric.png)

**2. Homens ganham mais que as mulheres em qualquer nível de educação:**

![Gráfico 2](bar_education_salary_gender.png)

+ É possível notar também que um maior nível educacional costuma resultar um maior salário:

![Gráfico11](salary_education.png)

**3. O mesmo vale para anos de experiência:**

![Gráfico 3](bar_yoe_salary_gender.png)

+ Com relação aos anos de experiência, os homens em geral ganham mais, mas a tendência é igualar ou até diminuir com relação aos salarios das mulheres.

**4. Idades mais avançadas há um aumento na quantidade de anos de experiência e do nível de educação:**

![Gráfico 4](buble_age_yoy_education_salary.png)
![Gráfico 5](line_age.png)
![Gráfico 6](line_yoy.png)

**5. Homens ocupam cargos com melhores salários:**

![Gráfico 7](top5job_gender.png)

+ Em geral, os homens costumam ser a maioria em cargos com maiores salários, enquanto as mulheres costumam ser maioria em cargos com menores salários:

![Gráfico 12](salary_gender.png)

**6. Com relação a quantidade de ocupação por cargo:**

![Gráfico 8](ct_male.png) 
![Gráfico 9](ct_female.png)
![Gráfico 10](ct_others.png)

+ De maneira geral não existe uma forte distinção entre os cargos mais comuns ocupados por homens e mulheres.
+ Entre os cargos populares para ambos estão Data Scientist e Software Engineer que estão no top 3 para ambos os gêneros.
+ Porém, é possível notar que mulheres tendem a ocupar mais os cargos relacionados a marketing e costumam também a ser os lideres dessas áreas.
+ Enquanto que os cargos de liderança ou maior senioridade nas areas de programação ( como Software Engineer Manager e Senior Project Engineer) costumam ser ocupados por homens.

# Conclusão

+ Existe uma correlação forte e positiva entre Idade, Anos de Experiência e Salário.
+ O mesmo pode ser dito para o nível educacional. Quanto maior o nível educacional maior tende a ser a idade, experiência e salário.
+ De maneira geral os homens tendem a ocupar cargos com melhores remunerações.

# Ferramentas utilizadas

| Python | Numpy | Pandas | Seaborn | Matplotlib | Git | 
| ------ | ----- | ------ | ------- | ---------- | --- | 
| <img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/files/python-logo-only.svg" width="100"> | <img src="https://www.svgrepo.com/show/354127/numpy.svg" width="100"> | <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="180"> |<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="130"> | <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="110"> | <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg" width="100"> |

# Como rodar

> Clique [GitHub](https://github.com/pedrolustosab/Analise_Explorataria_Salarios).


