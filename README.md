# Опис ситуації
Вас залучили у якості експерта для допомоги у слідчих діях.
Події відбувались у великому магазині електроніки в секторі телевізорів.
Під час події велика кількість телевізорів була включена.
Постраждала сторона надала запис з камери смартфону, що стосується до подій.
Прийняття рішення ґрунтовно залежить від визначення часу.
Запис зі смартфону з незрозумілих причин не має відміток часу.
На запису не видно зображень телевізорів, щоб можна було прив’язатись за часом телепередач.
Але на запису смартфона чітко видна зміна освітлюваності картинки залежно від зовнішніх джерел світла до яких відносяться телевізори, що в різнобій показували різні телепередачі, лампи освітлення, що в цей час хаотично включались-виключались тощо.
Є запис з камери спостереження, яка фіксувала зображення простору буквально поряд з місцем подій. Отже на запису з камери спостереження має бути така ж саме динаміка зміни освітлювання, як і на запису зі смартфону. Камери спостереження мають чітку прив’язку за часом.
Проблема полягає в тому, що різні камери мають різну чутливість до світла та розташовані по різному. Отже амплітуда рівня освітлення має суттєво відрізнятись. Крім того є постійні додаткові сигнали щодо освітлення від ламп, які встановлені в зонах спостереження та в зоні подій, що забезпечує збільшення загальної величини освітлення на однакову постійну величину в різних зонах.

# Метод
Пропонується використати ковариаційний та кореляційний аналіз. 

Для цього позначимо 
залежність освітлення від часу в зоні смартфона   
залежність освітлення від часу в зоні камер спостереження   

Тривалість запису зі смартфону набагато менше ніж тривалість запису з камер спостереження. 
Потрібно по черзі вирізати з запису камер спостереження ділянки що за довжиною співпадають з тривалістю запису на смартфоні і порівнювати їх за допомогою критерію на основі коваріаційної або кореляційної функції (або обох). Ділянка, яка надасть найкраще значення критерію, відповідатиме моменту часу, що потрібно було визначити. 
Якщо у всіх випадках будуть дуже невеликі значення критерію, то, можливо на запису з камер спостереження відсутня потрібна частина запису.
