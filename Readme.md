# Как влиться в робототехнику
спойлер -- не так сложно

1. Железо
2. Корпус
3. Софт

## Железо

В эту рубрику входят две подрубрики:
1. микроконтроллеры
2. схемы (в которых я сам пока не очень хорош)

Что я посоветую самым новичкам? - Установите ArduinoIDE и прогайте stm32, esp, и все остальные популярные контроллеры там.
Этот подход не так плох и его хватает, к тому же туториалов за глаза.
Кс, знающие люди говорят, что прогать esp через их официальную среду программирования (аналог cubemx) это тот еще гемор.

Если вы более серьезный человек, то читайте дальше:

Какие слова гуглить\вбивать в ютуб: bare metal programming, stm32 from scratch ...

Первое с чего я начинал -- это курс людей с РТ [link](https://youtube.com/playlist?list=PLhtMaaf_npBzsEQ94eGn5RnuE-VdGVObR&si=uz5jW3p8hJOfBUgp)
У этого курса есть гитхаб со всеми необходимыми туториалами для начала. Но предупереждаю -- они не используют никакой CubeMx и тому подобные среды программирования.
В этом есть свои плюсы и минусы:
1. "+" лучше понимаешь, что делаешь
2. "-" не подходит для нормального продакшна и больших проектов
   
В итоге я дошел до того, что смог подключить экранчик и на чистых битах закодить на нем всякие фразы, которые отсылал друзьям в тг.

Теперь по порядку: 
Первое что вам нужно, если вы хотите погрузиться чуть глубже -- это понять, с чем вы имеете дело. 
Для этого вам нужно понять из чего состоит контроллер и что он умеет, как в нем организованы память, сообщения между компонентами и тд ,что делает  makefile и линковщики, что такое bin и elf файлы...

Для второй части я советую [миникурс](https://youtube.com/playlist?list=PLERTijJOmYrDiiWd10iRHY0VRHdJwUH4g&si=zPJ_jImiIR5Sh4ST) в котором пишуттся самые простые штуки, необходимые для сборки проекта
(вы 1 раз в жизни это сделайте ручками, закройте гельштад и забудьте.)

По поводу первой части: каждого контроллера есть два документа -- reference manual и datasheet. Когда на форумах люди пишут "читайте даташит", то врут они не сильно.
Тут по ощущениям нужно прочесть столько, сколько нужно для +- понимания устройства мк

Теперь ссылки:


## CAD

На самом деле можно использовать любую программу, которую вы хотите: FreeCAD, Fusion360, Solidworks, Onshape, SiemensNx ...

Да простит меня (БОГ) Евгения Максимовна, но я считаю, что инструмент должен быть удобным. Мне удобно строить чертежи на планшете (samsung galaxy tab s6 lite), поэтому я просто установил onshape из гуглплэя и радуюсь жизни.

По каждой из этих программ есть уроки на ютубе вполне хорошие -- остается просто выдумать себе проект и начать набивать руку

