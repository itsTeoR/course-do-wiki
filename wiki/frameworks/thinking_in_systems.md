---
name: Системное мышление (Meadows)
description: Учебник системного мышления от Донеллы Медоуз — запасы, потоки, обратные связи, ловушки и точки воздействия
type: framework
tradition: [meadows]
density: medium
related: [[stocks_and_flows]], [[feedback_loops]], [[leverage_points]], [[system_traps]], [[meadows]]
---

# Системное мышление (thinking in systems)

*Thinking in Systems: A Primer* (Chelsea Green, 2008) — посмертно
опубликованный учебник Донеллы Медоуз, собранный редактором Дианой Райт
из её рукописей и конспектов лекций. Не академическая монография и не
манифест: Медоуз пишет как преподаватель. Открывает каждое
понятие ощутимым примером — Slinky, ванна, кофейная чашка, термостат —
и поднимает рассуждение постепенно.

Центральное утверждение книги — во введении: *поведение системы
определяется её структурой*. Медоуз иллюстрирует это Slinky-пружиной,
которая колеблется, когда нижнюю руку убирают, и не колеблется, если
подвесить коробку от неё таким же способом.

> The hands that manipulate it suppress or release some behavior that is
> latent within the structure of the spring. That is a central insight
> of systems theory. (raw/meadows/thinking-in-systems.epub, Introduction)

Смысл книги — научить видеть в проблеме не цепочку внешних причин
(«президент вызвал спад», «конкуренты отняли долю рынка», «вирус
напал»), а структуру, которая это поведение порождает. Отсюда Медоуз
перечисляет во введении несколько «еретических» следствий: политики не
вызывают спадов — спады встроены в рыночную экономику; конкуренты редко
отнимают долю — компания сама теряет её своей политикой; вирус не
атакует — ты сам создаёшь условия, в которых он разрастается
(raw/meadows/thinking-in-systems.epub, Introduction).

## Что такое система

> A system is an interconnected set of elements that is coherently
> organized in a way that achieves something.
> (raw/meadows/thinking-in-systems.epub, гл. 1 «The Basics», раздел
> «More Than the Sum of Its Parts»)

Три составляющих: **элементы** (люди, клетки, молекулы, материальное и
нематериальное), **взаимосвязи** (часто — потоки информации), **функция
или цель**. Функция выводится не из деклараций, а из наблюдения: «если
лягушка поворачивает направо, налево, назад и каждый раз ловит муху —
цель лягушки не в поворотах, а в ловле мух». То же про правительства:
если объявлен курс на защиту природы, а бюджет минимален — защита
природы не является целью системы (raw/meadows/thinking-in-systems.epub,
гл. 1, раздел «Look Beyond the Players to the Rules of the Game»).

Важнейшее наблюдение Медоуз в этой главе: элементы — часто самая
заметная, но и самая малозначимая часть системы.

> A system generally goes on being itself, changing only slowly if at
> all, even with complete substitutions of its elements—as long as its
> interconnections and purposes remain intact. The least obvious part
> of the system, its function or purpose, is often the most crucial
> determinant of the system’s behavior.
> (raw/meadows/thinking-in-systems.epub, гл. 1, раздел «Look Beyond the Players»)

Замени всех футболистов — команда останется командой. Замени правила
игры — получишь другую игру. Замени цель — получишь неузнаваемое нечто,
даже если игроки и правила формально те же.

## Стоки и потоки

Базовая пара понятий — stock и flow. Разобраны в [[stocks_and_flows]];
здесь — только то, что нужно для движения дальше.

Стокы меняются через потоки; на этом строится всё остальное:

> A stock, then, is the present memory of the history of changing flows
> within the system.
> (raw/meadows/thinking-in-systems.epub, гл. 1, раздел «Bathtubs 101»)

Два важных следствия, которые Медоуз подчёркивает отдельно:
**запасы меняются медленнее потоков** (из-за этого системы имеют
инерцию и буферы), и **запас можно наращивать, не только увеличивая
приток, но и уменьшая отток** — «there’s more than one way to fill a
bathtub» (raw/meadows/thinking-in-systems.epub, гл. 1, «Bathtubs 101»).
Человеческий ум этого чаще всего не замечает.

## Обратные связи

Когда изменение в запасе влияет на потоки, которые его меняют, возникает
обратная связь. Это механизм, порождающий устойчивое поведение системы
во времени.

> If you see a behavior that persists over time, there is likely a
> mechanism creating that consistent behavior. That mechanism operates
> through a feedback loop.
> (raw/meadows/thinking-in-systems.epub, гл. 1, раздел «How the System
> Runs Itself — Feedback»)

Медоуз различает балансирующие (стабилизирующие, стремящиеся к цели) и
усиливающие (самоподдерживающие, экспоненциальные) контуры. В большинстве
реальных систем действует несколько контуров одновременно, и поведение
определяется тем, какой из них в данный момент доминирует.
Доминирование переключается — и этим объясняется, почему системы ведут
себя сначала так, а потом иначе. Подробнее — в [[feedback_loops]].

## Почему системы нас удивляют

Четвёртая глава книги — реестр источников системного удивления. Медоуз
посвящает ему отдельную главу, потому что это и есть главный практический
разрыв между «понять систему» и «вмешиваться в систему».

**Нелинейность.** Удвоение удобрений не удваивает урожай; после порога
добавка перестаёт работать, а потом начинает разрушать почву. «Nonlinear
relationships cause drastic shifts in the relative strengths of feedback
loops» — именно поэтому системы прыжком меняют поведение
(raw/meadows/thinking-in-systems.epub, гл. 4 «Why Systems Surprise Us»,
раздел «Nonlinearities»).

**Отсутствие жёстких границ.** Границы, которыми мы режем реальность на
системы, — инструмент рассмотрения, а не свойство мира. «There are no
separate systems. The world is a continuum. Where to draw a boundary
around a system depends on the purpose of the discussion»
(raw/meadows/thinking-in-systems.epub, гл. 4, раздел «Boundaries»).

**Слои ограничений.** Рост никогда не снимает ограничений, он их
смещает. Фермер наращивает урожай внесением азота — лимитом становится
вода. Увеличивает полив — лимитом становится калий. И так дальше. «The
most limiting input is the one that most constrains growth»
(raw/meadows/thinking-in-systems.epub, гл. 4, раздел «Layers of
Limits»).

**Повсеместные задержки.** Задержка между решением и последствием,
между информацией и реакцией — источник колебаний, выбросов и провалов.
«When there are long delays in feedback loops, some sort of foresight is
essential» (raw/meadows/thinking-in-systems.epub, гл. 4, раздел
«Delays»). Медоуз передаёт совет Форрестера: «спросите всех в системе,
как долго длится задержка. Умножьте на три».

**Ограниченная рациональность.** Термин Герберта Саймона, который
Медоуз использует как мост к Адаму Смиту: люди в системе действуют
разумно в пределах своей информации, но эта информация локальна и
запаздывает. Сумма индивидуально-рациональных решений даёт коллективно
абсурдный результат. Медоуз приводит эксперимент с электрическими
счётчиками в голландском пригороде: в части домов счётчики стояли в
подвале, в части — в прихожей, на виду. При одинаковых прочих условиях
дома со счётчиком в прихожей потребляли электричество на 30% меньше.
Изменилась не рациональность — изменился информационный поток
(raw/meadows/thinking-in-systems.epub, гл. 4, раздел «Bounded
Rationality»).

## Ловушки и возможности

Пятая глава — каталог повторяющихся структурных конфигураций, которые
Медоуз называет *ловушками*, добавляя «и возможностями»: распознанная
ловушка может быть перепроектирована. Её логика:

> Blaming, disciplining, firing, twisting policy levers harder, hoping
> for a more favorable sequence of driving events, tinkering at the
> margins — these standard responses will not fix structural problems.
> That is why I call these archetypes “traps.” But system traps can be
> escaped—by recognizing them in advance and not getting caught in them,
> or by altering the structure.
> (raw/meadows/thinking-in-systems.epub, гл. 5 «System Traps . . . and
> Opportunities», вступление)

Восемь архетипов: сопротивление политике, трагедия общин, смещение к
низкой эффективности, эскалация, успех — успешным, перекладывание
бремени (зависимость), обход правил, неправильная цель. Разбор каждой — в
[[system_traps]].

## Точки воздействия

Главное практическое предложение Медоуз — список двенадцати мест, в
которых можно вмешаться в систему, упорядоченных от слабых к сильным.

Саму метафору Медоуз предваряет предупреждением: интуиция о точках
воздействия есть почти у всех, кто глубоко работает с системой, но она
системно ошибочна.

> Although people deeply involved in a system often know intuitively
> where to find leverage points, more often than not they push the
> change in the wrong direction.
> (raw/meadows/thinking-in-systems.epub, гл. 6 «Leverage Points»,
> вступление)

Классический пример — вывод модели Римского клуба: рост (и экономический,
и демографический) сам является точкой воздействия, но мировые лидеры
«correctly fixated on economic growth as the answer to virtually all
problems» давят на него в обратную сторону (там же).

Сам список и её комментарий к нему — в [[leverage_points]]. Медоуз
настаивает, что список не рецепт: «What you read here is still a work
in progress; it’s not a recipe for finding leverage points. Rather, it’s
an invitation to think more broadly about system change»
(raw/meadows/thinking-in-systems.epub, гл. 6, вступление).

## Жить в мире систем

Седьмая глава — не техника, а признание ограничений техники. Медоуз
пишет её в более личном регистре.

> We gave learned lectures on the structure of addiction and could not
> give up coffee. We knew all about the dynamics of eroding goals and
> eroded our own jogging programs. We warned against the traps of
> escalation and shifting the burden and then created them in our own
> marriages.
> (raw/meadows/thinking-in-systems.epub, гл. 7 «Living in a World of
> Systems»)

Её вывод: системный анализ не даёт ни предсказания, ни контроля;
самоорганизующиеся нелинейные системы с обратной связью по природе
непредсказуемы и неконтролируемы. Но это не конец, а начало другого
отношения к миру.

> Self-organizing, nonlinear, feedback systems are inherently
> unpredictable. They are not controllable. They are understandable only
> in the most general way. [...] We can’t control systems or figure them
> out. But we can dance with them!
> (raw/meadows/thinking-in-systems.epub, гл. 7)

Дальше она перечисляет не правила, а *практики танца*. Они важны именно
в её формулировке — не как «14 принципов», а как голос человека,
который много раз наступил на свои грабли и говорит о них без
назидания:

- **Почувствуй ритм системы прежде, чем её тронуть.** Смотри на её
  историю, а не на свою теорию о ней.
- **Выведи свои ментальные модели на свет.** «Remember, always, that
  everything you know, and everything everyone knows, is only a model.
  Get your model out there where it can be viewed».
- **Уважай, поддерживай и распространяй информацию.** «Thou shalt not
  distort, delay, or withhold information».
- **Используй язык аккуратно; обогащай его системными понятиями.** «We
  don’t talk about what we see; we see only what we can talk about»
  (Фред Кофман, которого она цитирует).
- **Обращай внимание на важное, а не только на измеримое.** «If
  something is ugly, say so. If it is tacky, inappropriate, out of
  proportion, unsustainable, morally degrading, ecologically
  impoverishing, or humanly demeaning, don’t let it pass».
- **Делай политики обратными связями для систем обратных связей.**
  Политика должна менять себя в ответ на состояние системы.
- **Целься в благо целого.** Иерархии существуют, чтобы служить
  нижним слоям, а не верхним.
- **Слушай мудрость системы.** Замечай, что уже работает, прежде чем
  вмешиваться.
- **Располагай ответственность внутри системы.** Пилот сидит впереди
  самолёта — значит, переживает последствия своих решений.
- **Будь смиренным. Оставайся учеником.** «The thing to do, when you
  don’t know, is not to bluff and not to freeze, but to learn».
- **Празднуй сложность.** Мир нелинейный, турбулентный, динамический;
  это не баг, а его природа.
- **Расширяй временные горизонты.** «A society which loses its identity
  with posterity [...] soon falls apart».
- **Нарушай дисциплинарные границы.** Следуй за системой, а не за
  академической специализацией.
- **Расширяй границы того, о ком заботишься.**
- **Не размывай цель доброты.** Один из самых разрушительных примеров
  «смещения к низкой эффективности» — постепенная эрозия морали в
  индустриальной культуре через медийную нормализацию худшего. «Don’t
  weigh the bad news more heavily than the good. And keep standards
  absolute» (все цитаты — raw/meadows/thinking-in-systems.epub, гл. 7).

Заканчивает книгу одной фразой — она задаёт тон всему:

> In the end, it seems that mastery has less to do with pushing leverage
> points than it does with strategically, profoundly, madly, letting go
> and dancing with the system.
> (raw/meadows/thinking-in-systems.epub, гл. 6, заключение)

## Источник

Meadows, D. H. (2008). *Thinking in Systems: A Primer*. Edited by
Diana Wright. White River Junction, VT: Chelsea Green. EPUB в
[raw/meadows/](../../raw/meadows/).
