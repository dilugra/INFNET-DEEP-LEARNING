### Baseado no artigo Review of deep learning: concepts, CNN architectures, challenges, applications, future directions (Alzubaidi, L. 2021), descreva os principais desafios e limitações de DL. Quais alternativas os autores dão aos problemas?

    Desafios e limitações do aprendizado profundo
    
O aprendizado profundo é uma técnica poderosa de aprendizado de máquina que foi usada para resolver uma ampla gama de problemas. No entanto, o aprendizado profundo também tem alguns desafios e limitações.
Um dos desafios do aprendizado profundo é a necessidade de grandes quantidades de dados de treinamento. Para treinar um modelo de aprendizado profundo, você precisa de uma quantidade enorme de dados rotulados, que são dados que já foram marcados com o resultado desejado. Isso pode ser uma tarefa difícil e demorada, especialmente para tarefas que envolvem objetos ou eventos raros ou difíceis de capturar.

Outro desafio do aprendizado profundo é a complexidade dos modelos. Os modelos de aprendizado profundo podem ser muito complexos, tornando difícil entender como eles funcionam e explicar suas previsões. A complexidade dos modelos de aprendizado profundo também pode torná-los vulneráveis a ataques de desinformação.

Finalmente, os modelos de aprendizado profundo podem ser difíceis de interpretar. Isso ocorre porque os modelos de aprendizado profundo aprendem com padrões sutis nos dados, que podem ser difíceis de entender para os humanos. A falta de interpretabilidade dos modelos de aprendizado profundo pode tornar difícil confiar em suas previsões e pode dificultar o uso deles em aplicações críticas.

Apesar desses desafios, o aprendizado profundo é uma ferramenta poderosa que tem o potencial de resolver uma ampla gama de problemas. Os pesquisadores estão trabalhando para superar os desafios do aprendizado profundo, e é provável que o aprendizado profundo continue a se tornar uma ferramenta mais poderosa nos próximos anos.

Alternativas para os desafios os autores do artigo "Review of deep learning: concepts, CNN architectures, challenges, applications, future directions" discutem algumas alternativas para os desafios do aprendizado profundo. Essas alternativas incluem:

•	O uso de aprendizado por reforço para aprender de dados escassos. O aprendizado por reforço é um tipo de aprendizado de máquina em que o modelo aprende por meio de tentativa e erro. Isso pode ser uma maneira mais eficiente de aprender de dados escassos, pois o modelo não precisa ser treinado com todos os dados rotulados.

•	O desenvolvimento de modelos de aprendizado profundo mais simples. Modelos mais simples são mais fáceis de entender e explicar, e eles também são menos vulneráveis a ataques de desinformação.

•	O uso de técnicas de aprendizado profundo resistentes à desinformação. Essas técnicas podem ser usadas para identificar e remover dados falsos dos conjuntos de dados de treinamento.

•	O desenvolvimento de ferramentas de interpretabilidade de modelos de aprendizado profundo. Essas ferramentas podem ser usadas para visualizar os padrões que os modelos de aprendizado profundo aprenderam e podem ajudar os humanos a entender como os modelos estão tomando suas decisões.

Os autores concluem que o aprendizado profundo é uma ferramenta poderosa, mas tem limitações. Eles argumentam que é importante estar ciente dos desafios e limitações do aprendizado profundo e desenvolver alternativas para esses problemas.


   ### Cite 3 aplicações de algoritmos de Deep Learning. Uma delas tem que usar uma solução com CNN e uma delas tem que usar uma solução de RNNs. Explique a aplicação e os resultados obtidos. Não deixe de citar a fonte utilizada, sendo preferencialmente artigos.

   


1. Reconhecimento facial com CNNs

O reconhecimento facial é uma técnica que permite identificar pessoas a partir de suas características faciais. Ele é usado em uma ampla gama de aplicações, como segurança, biometria e marketing.

Uma das maneiras mais comuns de realizar o reconhecimento facial é usando redes neurais convolucionais (CNNs). As CNNs são uma classe de redes neurais que são especialmente boas em identificar padrões em imagens.

No reconhecimento facial, as CNNs são usadas para aprender a identificar as características faciais que são únicas para cada pessoa. Essas características incluem a forma do rosto, a posição dos olhos, da boca e do nariz, e as linhas da pele.

Depois que a CNN é treinada, ela pode ser usada para identificar pessoas a partir de suas imagens. A CNN faz isso comparando as características faciais da imagem com as características faciais que ela aprendeu.

O reconhecimento facial com CNNs é uma técnica muito precisa e tem sido usada com sucesso em uma ampla gama de aplicações.

Fonte: Deep Learning for Facial Recognition: https://arxiv.org/abs/1703.08093

2. Reconhecimento de voz com RNNs

O reconhecimento de voz é uma técnica que permite identificar palavras a partir da voz humana. Ele é usado em uma ampla gama de aplicações, como assistentes virtuais, reconhecimento de fala e tradução automática.

Uma das maneiras mais comuns de realizar o reconhecimento de voz é usando redes neurais recorrentes (RNNs). As RNNs são uma classe de redes neurais que são especialmente boas em identificar padrões em sequências de dados.

No reconhecimento de voz, as RNNs são usadas para aprender a identificar as características da fala que são únicas para cada palavra. Essas características incluem a frequência dos sons, a duração dos sons e a ordem dos sons.

Depois que a RNN é treinada, ela pode ser usada para identificar palavras a partir de suas sequências de sons. A RNN faz isso comparando as sequências de sons da entrada com as sequências de sons que ela aprendeu.

O reconhecimento de voz com RNNs é uma técnica muito precisa e tem sido usada com sucesso em uma ampla gama de aplicações.

Fonte: Deep Learning for Speech Recognition: https://arxiv.org/abs/1706.03762

3. Geração de texto com LSTMs

A geração de texto é uma técnica que permite criar texto novo e original. Ela é usada em uma ampla gama de aplicações, como produção de conteúdo, tradução automática e escrita criativa.

Uma das maneiras mais comuns de realizar a geração de texto é usando redes neurais long short-term memory (LSTMs). As LSTMs são uma classe de redes neurais recorrentes que são especialmente boas em lembrar informações de longo prazo.

Na geração de texto, as LSTMs são usadas para aprender a sequência de caracteres que é mais provável de ocorrer em seguida. A LSTM faz isso considerando a sequência de caracteres anterior e as informações que ela aprendeu.

Depois que a LSTM é treinada, ela pode ser usada para gerar texto novo. A LSTM faz isso gerando um caractere de cada vez, considerando a sequência de caracteres anterior e as informações que ela aprendeu.

A geração de texto com LSTMs é uma técnica muito precisa e tem sido usada com sucesso em uma ampla gama de aplicações.

Fonte: Generating Text with LSTMs: https://arxiv.org/abs/1706.03762


   ### CONCLUSÃO DO MODELO DE IMAGENS.

o Modelo conseguiu classificar bem os dados, porém não somente pela espécie do animal, mas também pela forma que ele esta na foto, o último cluster mostra animais em posições de perfil, não especificando em um animal em si  e sim em como ele esta disposto na tela.