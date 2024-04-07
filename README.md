# Golf 3D
Това е препис и преподредба на [този документ](https://docs.google.com/document/d/16p9J5z5qNvp8KJ165S-BUk74BaFtBCcgIXOfSPorjF8/edit?usp=sharing), но направено на markdown файл и сложено в репото за удобство (много ме мързи да влизам на сайта)
### 1. Настройване
- Ще ви е нужен node.js, свалете го [тук](https://nodejs.org/en/download)
 - Създаване на fork
	 1. Цъкнете на бутона "fork" в горния десен ъгъл
	 2. Нацъкайте yes, confirm и така нататък
- Сваляне на dependency-та и полезни команди
	1. Като вече сте pull-нали репото си във папка на вашия компютър, отворете терминал
	2. В този терминал напишете 	`npm install`, тази команда ще свали всичко нужно, за да може да работи играта
	3. Полезни команди
	- `npm run prodbuild` - за финални билдове на играта
	- `npm run debugbuild` - прави подобно на горната команда, но позволява за дебъгване
	- **`npm run watch`** - тази команда автоматично ребилдва играта когато е засечена някаква промяна във файл
### 2. Основни dependency-та
- Three.js - за 3д графика -> [Docs](https://threejs.org/docs/)
- Cannon-es - за физика -> [Docs](https://pmndrs.github.io/cannon-es/docs/)
- Ако не ви се занимава да търсите из документациите, ChatGPT винаги е на ваше разположение
### 3. Задачи
- Без назначен човек
	- Разработване на Level Browser
- В разработка
	- Създаване на различни нива - Сашо
	- Разработване на Level Editor - Венци
	- Функционалност на Start Menu/ Настройки (без картинки) - Митко trepa4a
	- Audio програмиране - Димитър
	- BuildingBlock-ове
		- Дебелимитър
		- Сашо
		- Митко trepa4a
		- Ивайло
		- Деян
	- Да може да има различни скинове на топчето/ Скин браузър- Венци
- Готови, но или не работят напълно, или трябва да бъдат рефакторирани
	-  Митко trepa4a- мърдащ building block
	- Виктор - цилиндричен building block
	- Логиката за изстрелване на топчето - Венци **(ОБЕЩАНО)**
- Готови, работят безпроблемно
	- Да се направи триене на топчето - Сашо
	- Дебелимитър - 3d ramp
	- Skybox и текстури - Матвей