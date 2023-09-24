Проект «Проект для «Викишоп»». Описание: предобработка, анализ данных, машинное обучение для текстов. Для проведения анализа представлен файл, содержащий комментарии пользователей интернет-магазина. Цель:

- для интернет-магазина «Викишоп» обучить модель классифицировать комментарии на позитивные и негативные для осуществления поиска токсичных комментариев и отправки их на модерацию.
Технологии: numpy, pandas, matplotlib, matplotlib.pyplot, torch, transformers (BertModel, AutoTokenizer, AutoModel), tqdm, sklearn (cross_val_score, GridSearchCV; модели: RandomForestClassifier, LogisticRegression), catboost (модель CatBoostClassifier), lightgbm (модель LGBMClassifier)
