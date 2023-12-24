Доповідь підготували:

студент 2-го курсу, групи ІМ-23 **Катинський Ілля** [Пошта illya2005y@gmail.com, [Телеграм](https://t.me/girostark)]
студент 2-го курсу, групи ІМ-23 **Стреля Ілля** [Пошта seylvin2005@gmail.com, [Телеграм](https://t.me/lashus)]

Керівник

доцент кафедри ОТ ФІОТ, к.т.н., доцент Андрій БОЛДАК

НТУУ "КИЇВСЬКИЙ ПОЛІТЕХНІЧНИЙ ІНСТИТУТ імені ІГОРЯ СІКОРСЬКОГО

Факультет інформатики та обчислювальної техніки

Кафедра обчислювальної техніки

Київ

# Нереляційна база даних MongoDB, конвеєр агрегації, багатохмарна служба баз даних MongoDB Atlas і GUI для керування даними MongoDB Compass

## Що таке нереляційна база даних?

Нереляційна база даних (NoSQL) – це база даних, яка зберігає дані без чітких зв'язків між собою та без чіткої структури. Бази даних NoSQL спеціально побудовані для конкретних моделей даних і мають гнучкі графіки побудови сучасних додатків. Бази даних NoSQL широко визнані своєю простотою розробки, функціональністю та продуктивністю для Великий даних. Вони використовують різноманітні моделі даних, включаючи документ, діаграму, значення ключа, в пам'яті та пошук.
Бази даних NoSQL використовують різноманітні моделі даних для доступу та керування даними, такими як документи, діаграми, значення ключів, у пам’яті та пошук. Крім того, ці типи баз даних спеціально оптимізовані для програм, які потребують великого обсягу даних, низька затримка і гнучкі моделі даних. Ми досягаємо цього, зокрема, полегшуючи деякі обмеження узгодженості даних, відомі в інших базах даних.

## Що таке MongoDB?

![](./Images/MongoDB.png)

**MongoDB** - це потужна, гнучка та високопродуктивна система керування базами даних (СКБД), яка базується на моделі документа. Її основна особливість полягає у зберіганні даних у вигляді документів у форматі JSON-подібних об'єктів. MongoDB розроблена таким чином, щоб працювати з великими об'ємами даних, забезпечуючи гнучкість у роботі з структурами даних та швидкодію в операціях зберігання та витягування інформації.

Історія MongoDB почалася у 2007 році, коли компанія 10gen (пізніше перейменована на MongoDB Inc.) розпочала розробку цієї бази даних. Вона була випущена у відкритий доступ у 2009 році. MongoDB швидко набула популярності завдяки своїй простоті використання, гнучкості схеми даних та здатності працювати з великими об'ємами інформації.

Ця система СКБД використовує механізм розподілення даних, що дозволяє їй масштабуватись горизонтально, тобто додавати нові сервери для обробки даних у реальному часі без значного збою в роботі. MongoDB також підтримує ряд функцій, таких як індексація, реплікація та геопросторові запити, що робить її популярним вибором для великої кількості застосувань, включаючи веб-розробку, аналітику, системи керування контентом та багато іншого.
