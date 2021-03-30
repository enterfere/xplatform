Хочу начать как @pervognsen, процитируя Фейнмена: 
>"_Что я не могу создать - я не понимаю_".

`xplatform` - это проект, который состоит из серии мини-проектов, которые в свою очередь формируют один большой проект. Каждый такой мини-проект я снимаю отдельным видео на своем [youtube](https://www.youtube.com/c/Winderton) канале.

Описание под проектом [bitwise](https://github.com/pervognsen/bitwise), Пьера Вогнсена, идеально подходит под то, что я делаю тут. В программировании меня мотивирует не изобретение чего-то нового, что само по себе круто, а разбор уже того, что имеется. Я считаю что на данный момент в IT сфере много крутых проектов, с которыми можно разбираться годами, и что создание чего-то нового происходит из понимания того, что старое работает не так как надо, что само по себе подразумевает твое приняте того, что ты знаешь как работает старое. Возможно я утрируют, но это мое виденье ситуации.
В проекте `xplatform` мы будем писать с нуля различные модули, которые интересны мне и вам. Если у вас есть пожелания по тому, чтобы вы хотели увидеть в формате видео-туториала на [youtube](https://www.youtube.com/c/Winderton), то пишите под последние видео ваши комментарии с темами, которые хотите видеть. На данный момент, сделано 4 модуля:
- [x] Serialization
- [x] Deserialization(Только интегральных типов)
- [x] Neworking module
- [x] Event System
- [ ] 
_Следующие темы будут варьироваться и меняться в зависимости от вашего желания их увидеть, а от моего - их делать, а предыдущие - будут расширяться и дополняться_
- [ ] Renderer(Raycaster/OpenGL)
- [ ] Compression(LZ, Huffman)
- [ ] Custom Data Structures(Dynamic Array, Hashtable, Static Array)
- [ ] Allocators(На канале есть часовое видео по разработке malloc, но оно сюда не вписывается, так как слишком абстрактно)
- [ ] ECS
- [ ] Interpreter(И вообще, весь тул-чейн, который я бы хотел вам показать. Дебагер, профайлер, Статический анализатор. Скриптовой язык хотя бы для эллементарных задач)
- [ ] Build System(Где будет использоваться наш интерпретатор)
- [ ] Logging System
- [ ] Test Framework
- [ ] Utils(Различного рода вспомогательные утилиты, вроде `Cat` или `dumpbin`)

Не смотря на то что я планирую написать все эти вещи с нуля, мы для примера, будем ползоваться готовыми, чтобы понимать что они из себя представляют, и для того чтобы показать вам какие-то техники и правила software engineering, о которых я узнал за свое время тут. Например, `premake/cmake` как билд-ситемы, `eliot` как логинг, готовые `arena` и другие кастомыне алгокаторы, `Lua/Python` или другие языки для скриптинга, `Google Test` для тестов и так далее.

## Расписание:
Я планирую делать 1 подобный модуль в месяц, с возомжными перерывами на другие видосы. От вашей активности под роликами будет в целом зависеть жинь этой серии, но я в любом случае планирую закончить хотя бы часть модулей, чтобы вам было с чем работать для обучения.

## Требования
Я постараюсь объяснять все, что я делаю в роликах на столько, на сколько могу, учитывая все, начиная от времени, вплоть до лени. Вам требуютеся понимание основы программирования на любом языке, и так же основа Computer Science, т.е общее представление о том, что это и из чего состоит. Это для того, чтобы мы могли разговаривать на одном языке.
Вы можете задавать свои вопросы в комментариях под видео на [youtube](https://www.youtube.com/c/Winderton), у модулей, которые вас интересуют. Я постараюсь отвечать как минимум на большую часть технических вопросов.

Для людей же, кому интересно разбираться во всем этом на более глубоком уровне, напрямую со мной, то связь [тут](https://www.instagram.com/winderton/). Там я вам расскажу о возможностях. В скором времени эти возможности появятся в открытом доступе на [patreon](https://www.patreon.com/winderton), но пока я не представляю всей картины целиком, поэтому уточняйте все моменты в ЛС [сюда](https://www.instagram.com/winderton/).



[![DONATE](https://img.shields.io/badge/patreon-tipme-orange.svg)](https://patreon.com/winderton)
