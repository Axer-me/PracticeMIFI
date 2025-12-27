# Automatic Seagull Detection and Counting on Utashud Island (PracticeMIFI)
## Описание проекта
**Automatic Seagull Detection and Counting** - это алгоритм для автоматического учета и распознавания тихоокеанских чаек на фотоснимках, получаемых с репродуктивного участка острова Уташуд. Система позволяет выявлять и выделять птиц на изображениях, подсчитывать их количество и формировать структурированные данные для анализа популяции. Алгоритм упрощает обработку больших массивов фотографий, снижает трудозатраты на ручной учет и обеспечивает возможность мониторинга динамики численности и поведения чаек в естественной среде.
## Порядок установки(при работе с colab)
##### Ссылка на датасет: https://www.kaggle.com/datasets/kapturovalexander/seagulls-images/data
##### Ссылка на Google Colab: https://colab.research.google.com/drive/1CSmtPExtXWZa08joSd6gxxtPJKHLYaZX?usp=sharing
1. Первым делом скачиваем датасет на Caggle <img width="934" height="609" alt="image" src="https://github.com/user-attachments/assets/22ca172b-dae6-4a12-9d01-f05a1234a579" />
2. Скачиваем yaml файл с репозитория
3. Переходим по ссылке на гугл колаб
4. Разархивируем датасет себе на рабочий стол и потом переносим в Colab(следим, чтобы общая папка называлась "seagulls-images")
5. Выполняем код из ноутбука(пропускаем третью ячейку с кодом(там где od.download))
##### Необходимые python библиотеки
- opendatasets
- pandas
- seaborn
- matplotlib.pyplot
- os
- ultralytics
- cv2
- PIL
- tqdm
### Готово!

