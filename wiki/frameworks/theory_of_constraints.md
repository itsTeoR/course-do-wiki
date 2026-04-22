---
name: Теория ограничений (Theory of Constraints)
description: Производственная дисциплина Голдратта — управлять системой через её самое узкое место и тройку метрик throughput/inventory/operating expense
type: framework
tradition: [goldratt]
density: medium
related: [[five_focusing_steps]], [[throughput_inventory_operating_expense]], [[bottleneck_and_drum_buffer_rope]], [[goldratt]]
---

# Теория ограничений (Theory of Constraints)

Элияху Голдратт (1947–2011) — израильский физик, ставший
производственным консультантом. *The Goal: A Process of Ongoing
Improvement* (1984, с соавтором Джеффом Коксом) написана не как
учебник и не как бизнес-книга — это производственный *роман*.
Главный герой — Алекс Рого, директор заводской площадки UniCo,
которого корпоративное руководство предупредило, что у него три
месяца на то, чтобы вывести завод из убытков, иначе площадка будет
закрыта (гл. 1–2). В самолёте Алекс случайно встречает своего
старого профессора физики Ёну — и тот, в сократическом стиле, не
даёт ответов, а задаёт вопросы, постепенно вынуждая Алекса самому
увидеть, что на заводе происходит.

Голдратт объясняет этот выбор формы в интервью, включённом в
юбилейное издание 2004 года:

> The only way we can learn is through our deductive process.
> Presenting us with final conclusions is not a way that we learn.
> At best it is a way that we are trained.
> (raw/goldratt/the-goal.epub, «An Interview with Eli Goldratt»)

Из этого следует важное для нас: Theory of Constraints — не набор
рецептов. Это способ думать про любые системы, в которых есть
поток, ограничение и цель.

## Цель

Первый вопрос Ёны, на который Алекс не может сразу ответить внятно:
*какова цель вашего предприятия?* Алекс перебирает варианты —
технологии, эффективность, качество, доля рынка, занятость, —
Ёна каждое отвергает (гл. 4, разговор в терминале O'Hare). Позже,
в машине, Алекс сам приходит к ответу:

> The plant wasn't built just so it could break even. UniCo is not
> in business just so it can break even. The company exists to make
> money. I see it now. The goal of a manufacturing organization is
> to make money.
> (raw/goldratt/the-goal.epub, гл. 5)

Для Голдратта этот ответ универсален для коммерческой компании и
опасен одновременно — потому что «making money» в корпоративной
культуре подменяется сотнями локальных KPI, которые с целью как раз
не связаны.

Ёна сразу ставит критерий практичности: чтобы цель работала на уровне
цеха, нужны метрики, которые *ежедневно* измеряют движение к ней:

> Those conventional measurements you use to express the goal do
> not lend themselves very well to the daily operations of the
> manufacturing organization. In fact, that's why I developed a
> different set of measurements.
> (raw/goldratt/the-goal.epub, гл. 8, ночной разговор Алекса с
> Ёной по телефону)

Голдратт предлагает три метрики и только три — подробно в
[[throughput_inventory_operating_expense]]:

- **Throughput** — «the rate at which the system generates money
  through sales».
- **Inventory** — «all the money that the system has invested in
  purchasing things which it intends to sell».
- **Operating Expense** — «all the money the system spends in order
  to turn inventory into throughput».
(raw/goldratt/the-goal.epub, гл. 8)

Любое решение на заводе — любое решение в любой системе —
оценивается через эти три. Увеличивает ли оно throughput? Уменьшает
ли inventory? Уменьшает ли operating expense? Если на все три ответ
«нет или не знаем», решение бессмысленно, какой бы локальной
эффективностью оно ни обосновывалось.

## Сбалансированная мощность — миф

Ключевое прозрение Алекса идёт не через расчёты, а через поход с
сыном-бойскаутом (гл. 14–15). Колонна идёт по лесу, самый медленный
мальчик — Herbie. Алекс наблюдает, что впереди Herbie'а образуются
пустоты (ушедшие вперёд ждут), а между Herbie'ом и задними скучивается
очередь. Он формулирует для себя два явления:

- **Dependent events** — каждый участник ждёт предыдущего.
- **Statistical fluctuations** — каждый идёт с переменной скоростью.

> My maximum speed is the rate at which Herbie is walking. My rate
> is throughput. Herbie's rate governs mine. So Herbie really is
> determining the maximum throughput.
> (raw/goldratt/the-goal.epub, гл. 15)

Перенеся этот образ на производство, Алекс видит: есть *bottleneck* —
участок, чья мощность меньше или равна рыночному спросу. Он и
определяет throughput всего завода. Попытка «нагрузить равномерно все
участки» означает, что не-bottleneck'ам позволено производить быстрее,
чем может потреблять bottleneck. Это не увеличивает throughput — оно
только превращается в inventory, который копится перед bottleneck'ом.

Подробнее про Herbie и Drum-Buffer-Rope — в
[[bottleneck_and_drum_buffer_rope]].

## Пять шагов фокусировки

Отсюда — *Five Focusing Steps*, главная операциональная процедура
TOC. К 37-й главе команда Алекса формулирует её на доске в
переговорной:

> 1. IDENTIFY the system's constraint(s).
> 2. Decide how to EXPLOIT the system's constraint(s).
> 3. SUBORDINATE everything else to the above decision.
> 4. ELEVATE the system's constraint(s).
> 5. WARNING!!!! If in the previous steps a constraint has been
>    broken, go back to step 1, but do not allow INERTIA to cause
>    a system's constraint.
> (raw/goldratt/the-goal.epub, гл. 37)

Подробно — в [[five_focusing_steps]]. Большинство менеджеров у
Голдратта начинают с четвёртого шага («увеличим мощность»),
пропуская второй и третий. Это обычно стоит денег и редко даёт
эффект, потому что без Exploit и Subordinate bottleneck не работает
на своих текущих возможностях.

## Drum-Buffer-Rope

Инструмент, которым у Голдратта оперативно управляется завод после
того, как bottleneck идентифицирован. Подробно — в
[[bottleneck_and_drum_buffer_rope]].

- **Drum.** Ритм, который задаёт bottleneck. Весь остальной завод
  работает в этом ритме, а не в своём.
- **Buffer.** Запас материалов *перед* bottleneck'ом, защищающий
  его от случайных остановок на участках выше по потоку.
- **Rope.** Сигнал, связывающий выпуск нового материала в
  производство со скоростью bottleneck'а. Не запускать больше, чем
  bottleneck может переварить.

## Физическое ограничение и ограничение-политика

В финальной главе Алекс и Лу обсуждают, что пять шагов не до конца
работают, когда ограничение — не станок, а *политика*:

> If the constraint is not physical this step is meaningless.
> (raw/goldratt/the-goal.epub, гл. 40, разговор о применимости пяти
> шагов к division-level constraints)

Физический bottleneck (печь, NCX-10) можно посчитать, защитить
буфером, разгрузить. Ограничение-политика (правило премирования,
метрика эффективности, договор с поставщиком) сначала нужно *увидеть*
как ограничение, потому что оно замаскировано под «как всегда
делали». Отсюда у Голдратта в последующих работах — акцент на
техниках обнаружения core problem, которые потом развиваются в его
*Thinking Processes* и книге *It's Not Luck*.

## Применимость за пределами производства

В *The Goal* Голдратт пишет про завод, но уже в ней становится ясно:
структура переносима. Любая система, в которой есть поток (задач,
клиентов, идей, разговоров), dependent events (одно зависит от
другого) и statistical fluctuations (скорость непостоянна), имеет
ограничение, которое определяет общую производительность.
Последующие книги Голдратта (*Critical Chain*, *It's Not Luck*) и
его ученики распространили TOC на проект-менеджмент, продажи,
дистрибуцию, разработку.

Для индивидуального работника логика та же: твой ограничитель — не
то, что ты делаешь дольше всего, а то, что ограничивает *твой поток
ценности*. Увеличивать мощность на не-ограничителе — значит
накапливать inventory. Увеличивать мощность на ограничителе — значит
увеличивать throughput.

## Что в книге неожиданно

- Голдратт прямо сталкивает TOC с традиционным стандартным учётом
  издержек (cost accounting). Лу, бухгалтер завода, в конце книги
  признаёт, что вся его профессиональная подготовка по существу
  неверно ставит вопрос (гл. 40). Для Голдратта это не педагогическая
  иллюстрация, а ядерный конфликт его метода с корпоративной
  практикой.
- Книга кончается не победой, а переводом Алекса в дивизион, где он
  должен применить те же пять шагов к *политическим* ограничениям
  компании. Алекс открытым текстом признаётся: он не знает, как это
  делать. Пять шагов остаются, техники к ним — ещё только предстоит
  разработать (гл. 40). Это финал, намеренно оставленный открытым.
- Интервью с Робертом Левиттом (US Marine Corps, ret.),
  приложенное к изданию 2004, применяет те же понятия к военной
  логистике и полевым госпиталям в Южной Африке. Голдратт явно хочет
  показать, что TOC — не про производство, а про класс систем.

## Источник

- Goldratt, E. M., & Cox, J. (1984, 4th rev. ed. 2004). *The Goal:
  A Process of Ongoing Improvement*. Great Barrington, MA: North
  River Press. EPUB в [raw/goldratt/](../../raw/goldratt/).
