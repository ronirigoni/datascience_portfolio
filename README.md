# Roni Rigoni - Portfólio de Ciência de Dados

Olá! Aqui você encontra os meus projetos pessoais de Ciência de Dados. Para mais informações sobre mim, visite meu [LinkedIn](https://www.linkedin.com/in/ronirigoni/).


## Projetos

### Classificador de Dígitos ASL (Linguagem de Sinais Americana)

- Projeto: [https://github.com/ronirigoni/ds_digitos_asl](https://github.com/ronirigoni/ds_digitos_asl)
- Tópicos: *Machine Learning; Deep Learning; Convolutional Neural Networks (CNNs); Image Processing.*

Neste projeto criamos um classificador de dígitos (de 0 a 9) para a linguagem de sinais americana (*ASL - American Sign Language*). Para isso utilizamos uma base de dados de 5.000 imagens disponível no Kaggle ([aqui](https://www.kaggle.com/datasets/rayeed045/american-sign-language-digit-dataset)) para treinar uma rede neural. O modelo desenvolvido atingiu uma acurácia de 99,10%.


### Preditor de Preços de Casas (Palmas - TO)

- Projeto: [https://github.com/ronirigoni/ds_preditor_preco_casas](https://github.com/ronirigoni/ds_preditor_preco_casas)
- Teste On-line: [https://ronirigoni.github.io/ds_preditor_preco_casas/](https://ronirigoni.github.io/ds_preditor_preco_casas/)
- Tópicos: *Machine Learning; Linear Regression; Web Scraping; Python.*

Neste projeto eu criei um preditor de preços de casas para a cidade de Palmas - TO. Os dados utilizados para treinar o modelo foram coletados diretamente do site www.zapimoveis.com.br, através de um script python. O preditor tem como entradas: Área construída da casa; Quantidade de quartos; Quantidade de banheiros; Quantidade de garagens e o Endereço (que deve ser da cidade de Palmas). Através de uma regressão linear, o modelo retorna o preço previsto para a casa.


### Recomendador de Filmes do Imdb

- Projeto: [https://github.com/ronirigoni/ds_imdb_recommender](https://github.com/ronirigoni/ds_imdb_recommender)
- Teste On-line: [https://ronirigoni.github.io/ds_imdb_recommender/](https://ronirigoni.github.io/ds_imdb_recommender/)
- Tópicos: *Natural Language Processing (NLP); Cosine Similarity; Web Scraping; Python.*

Como eu percebi que no site imdb.com não existe (até o momento) a função de buscar filmes semelhantes de um certo título, desenvolvi este projeto pessoal. Neste projeto eu utilizo como base de dados os 1.000 filmes mais bem ranqueados no Imdb (que eu coletei via script python) e utilizo técnicas de NLP para comparar os títulos desta base com o título informado pelo usuário. O modelo considera na comparação: diretor, gêneros e a sinopse dos filmes. Como resultado o modelro retorna os 15 filmes que aparentam ser mais semelhantes ao informado.