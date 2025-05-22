# Challenge IOT, IOB and Generative IA

Projeto que utiliza machine learning e visão computacional na solução de redução de sinistros do Challenge Odontoprev.


## Funcionalidades ( Digital Cop )

- Predição de pacientes suspeitos
- Predição de dentistas suspeitos
- Predição que diz qual a probabilidade do paciente aparecer na consulta

Nessa versão, nossa solução está bem simples, é apenas um teste de quais serão as métricas de avaliação e qual o melhor modelo para treino do nosso dataset.


Estamos utilizando o ML.NET. O modelo já está conectado à API desenvolvida em .NET, porém ainda não está integrado ao banco de dados, pois nem todas as tabelas necessárias foram criadas.

Os dados utilizados não são 100% confiáveis, pois foram gerados por inteligência artificial. Atualmente, o modelo é treinado com base em um arquivo CSV, que poderá ser substituído futuramente por dados mais precisos, visando melhorar os resultados.

## Funcionalidades (Face Authentication)

- Autenticador facial em consultas

O autenticador realizará uma verificação entre as imagens enviadas pelo usuário no sistema pelo aplicativo e dirá se é a mesma pessoa ou não retornando True ou False e a similaridade entre eles. Caso for True, o paciente poderá iniciar a consulta tranquilamente, caso seja False a consulta não será iniciada e será um indicador de fraude.


## Devs

- [Celeste Tanaka](https://www.github.com/celestemayumi)
- [Livia Mariana Lopes](https://github.com/LiviaMarianaLopes)
- [Celeste Tanaka](https://www.github.com/luanavss)
