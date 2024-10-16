# Как влиться в робототехнику
спойлер - не так сложно

1. Железо
2. Корпус
3. Софт

## Железо

В эту рубрику входят две подрубрики:
1. ### микроконтроллеры
2. ### схемы (в которых я сам пока не очень хорош)

### микроконтроллеры:
Что я посоветую самым новичкам? - Установите ***ArduinoIDE*** и прогайте stm32, esp, и все остальные популярные контроллеры там.
Этот подход не так плох и его хватает, к тому же туториалов за глаза.
Кс, знающие люди говорят, что прогать esp через их официальную среду программирования (аналог cubemx) это тот еще гемор.

Если вы более серьезный человек, то читайте дальше:

Какие слова гуглить\вбивать в ютуб: _ _bare metal programming, stm32 from scratch_ _ ...

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

По поводу первой части: каждого контроллера есть два документа -- reference manual и datasheet, например в bluepill стоит контроллер STM32F103C8T6, поэтому гуглить надо "STM32F103C8T6 refernce manual" \ "STM32F103C8T6 datasheet".

Когда на форумах люди пишут "читайте даташит", то врут они не сильно.
Тут по ощущениям нужно прочесть столько, сколько нужно для +- понимания устройства мк

Теперь ссылки:
1. [link](https://vk.com/away.php?to=https%3A%2F%2Fvivonomicon.com%2Fcategory%2Fstm32_baremetal_examples%2F&post=-188153424_218&cc_key=&track_code=) хороший сайт, стоит по нему полазить

2. [youtube1](https://www.youtube.com/playlist?list=PLtVUYRe-Z-mfKO0lg_-MBvwWl6VjWT8Dt)
3. [youtube2](https://www.youtube.com/playlist?list=PLmXXQ1iFwiyJFM2NJW1ybWX5Fu_9Oo7p1)
4. [youtube3](https://www.youtube.com/playlist?list=PLtVUYRe-Z-mcjXXFBte61L8SjyI377VNq)
5. [youtube4](https://www.youtube.com/watch?v=gdRmETe4QEo)
6. [youtube5](https://www.youtube.com/playlist?list=PL4cGeWgaBTe155QQSQ72DksLIjBn5Jn2Z)
7. [youtube6](https://www.youtube.com/playlist?list=PLmY3zqJJdVeNIZ8z_yw7Db9ej3FVG0iLy)
8. [youtube7](https://www.youtube.com/playlist?list=PLP29wDx6QmW7HaCrRydOnxcy8QmW0SNdQ)
9. [youtube8](https://www.youtube.com/@voidloopRobotechAutomation)
10. [youtube9](https://www.youtube.com/@EnjoyMechatronics/videos)

    Как говорится, на вкус и цвет. В общем, смотреть всё не обязателььно. Всё равно всё, что надо, науглите сами.

    
### схемы:

Ну, говорить про закон Ома и базовый курс электричества и магнетизма физтеха я не буду. 
Люди очень советуют трёхтомник Хоровиц и Хилл "Искусство схемотехники". Чего-то более я не нашел. Найдеде - пишите)

По хорошему просто найдите какой-ниудь сайт по типу [радиокот](https://www.radiokot.ru/) и во вкладке "схемы" смотрите и разбирайте их по частям.

Если хочется создавать микросхемы на платах, то установите **Altium Design** или **KiCAD**. Вообще это называется ***PCB design***, поэтому, что гуглить, думаю, вы понимаете.

По каждой из этих программ есть уроки на ютубе вполне хорошие -- остается просто выдумать себе проект и начать набивать руку


## CAD
Да простит меня ~~БОГ~~ Евгения Максимовна, но я считаю, что инструмент должен быть _ _удобным_ _. Поэтому я установил Onshape на свой планшет [app link](https://play.google.com/store/apps/details?id=com.onshape.app)  и радуюсь жизни. (Да, сейчас оно требует vpn, но тем не менее)

На самом деле можно использовать любую программу, которую вы хотите: _ _FreeCAD, Fusion360, Solidworks, Onshape, SiemensNx__ ...

Первый мой тестовый проект был простым [гриппером](https://www.youtube.com/watch?v=Hlei0rlXW7o&list=PL92ZgDzlhlZaoRAn_zmuPWPW4MQhSS_je)

### Грядет
C++ пояса яндекса

python 

хирьянов

робототехника: самая простая теория forvard and inverse kinematics. Может кватернионы какие-нибудь, но не факт

control theory from scratch + тот курс + [control bootcamp от Стива](https://www.youtube.com/watch?v=Pi7l8mMjYVE&list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m)

perception

ros urdf и тд


ml
dl


### Не знаю, куда включить:

Изучите всякие фильтры по типу Калмана. Это поможет при работе с данными

АКОС [Физтеховский курс](https://www.youtube.com/playlist?list=PL4_hYwCyhAva4dDOnyddyvkAs_jWVr624) крутой, чтоб понять, что такое ОС. Кстати, переходите на Linux - Ubuntu хорошая ос для юзеров.

[Docker](https://www.youtube.com/watch?v=O8N1lvkIjig&t=95s) изучите еще [docker compose](https://roboticseabass.com/2021/04/21/docker-and-ros/)  по ссылке находится сборка для ros, но суть, в принципе, понятна.

Еще очень полезным бывает Pyenv, когда нужно сменить версию питона для какого-то проекта
