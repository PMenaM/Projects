# Pablo Mena's project portfolio
List of projects completed in the field of Data Science and its various subfields.

| Project field/year | Project name | Description | Contributions | Stack and methods | 
| -------------------| -------------| ------------| ------------- | ----------------- |
|  |  |  |  | Предложения CASE (WHEN, THEN), Агрегатные функции (EXTRACT, SUM, ROUND), Функции фильтрации (WHERE, GROUP BY, ORDER BY) |
| Machine Learning/2023 | [Assessing Customer Churn Using Machine Learning](https://github.com/PMenaM/Projects/blob/main/Assessing%20Customer%20Churn%20Using%20Machine%20Learning%20(Jupyter%20Notebook)/Assessing%20Customer%20Churn%20Using%20Machine%20Learning%20(Jupyter%20Notebook).ipynb) | Использование Pandas и машинного обучения для изучения наборов данных ведущих индийских телекоммуникационных компаний, выявления демографических моделей и моделей использования. Прогнозирование удержания клиентов, объединение анализа данных и прогнозного моделирования. |  | Pandas, Sklearn, машинное обучение, анализ данных, предварительная обработка, создание экземпляров, StandardScaler, обучение, подгонка, train_test_split, проверка, прогнозирование, LogisticRegression, RandomForestClassifier, оценка, classification_report, confusion_matrix |
| AI - Prompt Engineering/2023 | [OpenAI API for Tourism](https://github.com/PMenaM/Projects/blob/main/OpenAI%20API%20for%20Tourism%20(Jupyter%20Notebook)/Planning%20a%20Trip%20to%20Paris%20with%20the%20OpenAI%20API.ipynb) | Использование возможностей языковой обработки OpenAI для интеллектуального ответа на заранее заданные вопросы, связанные с поездками, и предоставления индивидуальных рекомендаций для знакомства с Парижем. |  | Искусственный Интеллект, OpenAI API, Prompt engineering, циклы for, извлечение признаков, списки словарей |
| Computer Vision/2023 | [Sign Language Recognition with Keras](https://github.com/PMenaM/Projects/blob/main/Sign%20Language%20Recognition%20with%20Keras%20(Jupyter%20notebook)/Sign%20Language%20Recognition%20with%20Keras%20(Jupyter%20notebook).ipynb) | Построение сверточной нейронной сети (CNN) для классификации изображений букв американского языка жестов (ASL). После загрузки, проверки и предварительной обработки данных сеть обучается, и ее производительность проверяется на соответствие ее точности при предсказании букв ASL из изображений. |  | Классификация изображений, Tensorflow/Keras, Numpy (argmax, where), Matplotlib, Convolutional Neural Networks (CNN), Conv2D, MaxPooling2D, Flatten, Dense, Sequential, compile, to_categorical, fit, evaluate, predict |
| NLP/2023 | [Topic Trend Analysis](https://github.com/PMenaM/Projects/blob/main/Topic%20Trend%20Analysis%20(Jupyter%20notebook)/Topic%20Trend%20Analysis%20(Jupyter%20notebook).ipynb) | Использование методов обнаружения темы NLP в коллекции исследовательских работ с конференций Neural Information Processing Systems (NIPS) за 10 лет. Цель этого проекта — выяснить, какие темы стали более модными, учитывая рост популярности машинного обучения. |  | Обнаружение темы, Pandas, Numpy, Matplotlib, data pre-processing, Гистограмма, Регулярное выражение (regex), WordCloud, CountVectorizer, Латентное Размещение Дирихле (LDA) |
| NLP/2023 | [Tweet Classifier](https://github.com/PMenaM/Projects/blob/main/Tweet%20Classifier%20(Jupyter%20notebook)/Tweet%20Classifier%20(Jupyter%20notebook).ipynb) | Построение ML модели классификации с использованием методов NLP для классификации и анализа текста. Данные, которые необходимо классифицировать, соответствуют твитам, написанным двумя американскими политиками. Цель модели — точно классифицировать, был ли твит написан одним политиком или другим, на основе содержания твита. |  | Numpy, CountVectorizer, TfidfVectorizer, train_test_split, MultinomialNB, LinearSVC, sklearn_metrics, confusion_matrix |
| SQL/2023 |  |  |  | Агрегатные функции (SUM, COUNT, MAX), Предложения CASE (WHEN, THEN), Сопоставление с образцом (LIKE), Операции соединения (INNER JOIN), Предложения фильтрации (WHEN, HAVING), Оконные функции (RANK, OVER), Подзапросы, CTE |
| SQL/2023 |  |  |  | Агрегатные функции (COUNT, AVG, ROUND), Операции соединения (LEFT JOIN, INNER JOIN), Набор операций (EXCEPT, INTERSECT) |
| Computer Vision/2023 | [YOLOv8 People Detector](https://github.com/PMenaM/Projects/blob/main/YOLOv8%20People%20Detector%20(Jupyter%20notebook)/YOLOv8%20People%20Detector%20(Jupyter%20notebook).ipynb) | Система обнаружения объектов на основе алгоритма YOLO. Модель обучалась на датасета, состоящем из снимков, сделанных дроном. На изображениях показан лесной ландшафт с возможным присутствием людей, которые будут обнаружены моделью. |  | OpenCV, ultralytics, YOLOv8, data preprocessing, training, testing, Numpy, glob, os, re, shutil, yaml, pickle, xml.etree |
| NLP/2022 | [Book Recommendations from Charles Darwin](https://github.com/PMenaM/Projects-en-/blob/main/Book%20Recommendations%20from%20Charles%20Darwin%20(Jupyter%20Notebook)/Book%20Recommendations%20from%20Charles%20Darwin%20(Jupyter%20Notebook).ipynb) | NLP system for content-based book recommendation. It uses Charles Darwin's bibliography to identify books that may be of interest based on similarities to *On the Origin of Species*. The final dendrogram reflects a state-of-the-art recommendation engine. | Performed index searching to find the target text. Used list comprehensions for tokenization and removing stopwords. Performed stemming on the corpus and built a bag-of-words model. Transformed the model's result into a DataFrame, adding columns for number, index, and token. Built a tf-idf model for generating vectors and sorting them. (3rd - 9th step of the project) | Pandas, Tfidf, Matplotlib, Gensim, SciPy, glob, re, os, pickle |
| NLP/2022 | [Finding Movie Similarities from Plot Summaries](https://github.com/PMenaM/Projects-en-/tree/main/Finding%20Movie%20Similarities%20from%20Plot%20Summaries%20(Jupyter%20Notebook)) | An NLP clustering system that quantifies movie similarities based on plot summaries available on IMDb and Wikipedia. The final dendrogram reflects a state-of-the-art recommendation engine. | Created a filtered tokenizer object based on custom list comprehensions. Used the Snowball Stemmer algorithm for merging words with similar semantic values. Defined a function that includes the previous two steps, saving 50% of coding time and processing time. Defined a TfidfVectorizer object and used its fit-transform method to transform text into numeric vectors and remove English stopwords. (3rd - 7th step of the project) | NLTK, TfidfVectorizer, KMeans, cosine_similarity, Numpy, Pandas, Matplotlib, SciPy, linkage, dendrogram, BeautifulSoup, requests, re |


# [LinkedIn profile](https://www.linkedin.com/in/pablomenamnlp)
