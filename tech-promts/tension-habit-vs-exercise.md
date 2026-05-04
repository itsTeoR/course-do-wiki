**Задача:** написать одну статью tension на ось **привычка (hexis, рутинизация) vs возобновляемое упражнение (askēsis, каждый раз заново)**. Авторы: Fogg vs Hadot/стоики.

Проект — `/Users/teorusak/Projects/course-wiki/`. Работаем прямо в `main`, без worktree. Запусти в **свежем чате Claude Code**.

**Методика — полностью по [tech-promts/bridge-tension-prompt.md](tech-promts/bridge-tension-prompt.md).** Жёсткая граница Фазы A и Фазы B.

**Хэндл кандидата** — в `wiki/index_do_course.md`, раздел Tensions → Кандидаты, строка «Привычка (hexis, рутинизация) vs возобновляемое упражнение (askēsis, каждый раз заново) (Fogg vs Hadot/стоики)». Держи свободно.

# Что есть в wiki и raw/

**Опорные статьи** (все `ready`):

- Hadot/стоики: `wiki/frameworks/philosophy_as_way_of_life.md`, `wiki/people/hadot.md`, `wiki/concepts/spiritual_exercises.md`, `wiki/concepts/philosophical_discourse_vs_way_of_life.md`, `wiki/concepts/view_from_above.md`, `wiki/frameworks/enchiridion_epictetus.md`, `wiki/people/epictetus.md`, `wiki/concepts/dichotomy_of_control.md`, `wiki/concepts/judgments_not_things.md`.
- Fogg: `wiki/frameworks/tiny_habits.md`, `wiki/people/fogg.md`, `wiki/concepts/fogg_behavior_model.md`, `wiki/concepts/tiny_habits_recipe.md`, `wiki/concepts/celebration_wires_habit.md`, `wiki/concepts/ability_chain.md`.

**Raw/-источники:**

- Hadot: `raw/hadot/Philosophy as a way of life ... .pdf` + `raw/hadot/hadot.txt`. Ключевое: разделы «Spiritual Exercises», «Philosophy as a Way of Life», «Philosophical Discourse and the Way of Life» — про *askēsis* как акт, а не состояние; про возобновляемость упражнения; цитата Саллюстия «philosophia для человека невозможна»; «пусто слово философа, которое не исцеляет».
- Эпиктет (вспомогательно): `raw/epictetus/epicench.1b.txt`. Античный контекст для Hadot.
- Fogg: `raw/fogg/Tiny Habits ... .pdf`. Ключевое: определение привычки как автоматизма (behavior automaticity), anchor → tiny behavior → celebration, B=MAP, раздел про закрепление через celebration, целевое состояние — поведение без решения.

# Особое для этого tension

**Старт от Hadot/античных.** Они старше на 2000 лет и дают концепцию *askēsis*, на которой держится одна сторона tension. Операция у Hadot/стоиков: упражнение (*askēsis*) — акт *каждый раз заново*, мудрость принципиально *не* рутинизируется, философия как *bios* предполагает постоянное возобновление усилия. Цитата Саллюстия и развёртывание её Hadot — опора.

**Fogg на противоположном полюсе.** Цель Tiny Habits — *behavior automaticity*: поведение перестаёт требовать решения, закрепляется на якоре, автоматически запускается. Цитату из книги — где он прямо формулирует автоматизм как целевое состояние. B=MAP — универсальная механика.

**Структурная несовместимость.** Fogg целит в состояние, где поведение *снимает* сознательное усилие. Hadot настаивает: *askēsis* структурно не может стать рутиной, это упражнение *по определению* возобновляемо. Это не спор о правильности подхода — это спор о *типе практики*: автоматизируемое поведение (Fogg) и возобновляемое упражнение (Hadot) — разные объекты, хотя оба отвечают на вопрос «как не забыть делать».

**«Авторы прямо возражают или сборка наша?»** Напрямую — нет; их разделяют 2000 лет. Но структуры их операций взаимно исключают: то, что Fogg называет успехом (автоматизация), Hadot называет концом философии как *bios*. В статье прямо отметить: tension не между авторскими позициями, а между *структурами практики* — это не ослабляет его, просто делает другого типа.

**Соседство:** с кандидатом «Philosophia как bios vs современные how-to-фреймворки» (Hadot vs Fogg, Ries, Rubin) — тот шире по составу авторов и затрагивает более общую тему онтологии практики; этот узкий, операциональный. С кандидатом «Автоматизм без воли vs повторение с удержанным 'ради чего'» (Fogg vs Strozzi-Heckler) — третий угол на той же паре практик. Оба назови в «Открытых вопросах».

# Тест tension до письма

1. **Реальное противоречие или артефакт?** Fogg прямо целит в автоматизм (цитата из книги). Hadot прямо отрицает рутинизуемость *askēsis*. Противоречие структурное, не сборка.
2. **Выдерживает ли масштаб?** Оба — про индивидуальную практику. Масштаб общий. Tension держится.
3. **Сборка наша или авторы спорят?** Напрямую не спорят (разделены веками); структурно взаимно исключают. Отметь это в статье явно — tension типа «структурная несовместимость», не «прямой спор».

# Запрещено

- Никакой курс-связки в основном теле. Никаких «самоконтроль», «для CEO», «в J-модусе», «инициирование».
- Секцию `## В линзе гипотез курса` не добавлять.
- Блоки `## В линзе гипотез курса` в существующих статьях — не читать.
- Файлы `course/` — не читать.

# Обновить в Фазе B

1. Создай `wiki/tensions/habit_vs_spiritual_exercise.md` (имя уточни под итог). Frontmatter: `type: tension`, `tradition: [fogg, hadot, stoics]`, `related: [[...]]`, `density: high` (Hadot), `status: ready`.
2. `wiki/index_do_course.md`, раздел Tensions: строка из «Кандидаты» → «Готовые».
3. `wiki/README.md`: ссылка в секцию tensions.
4. В `wiki/frameworks/tiny_habits.md`, `wiki/concepts/celebration_wires_habit.md`, `wiki/frameworks/philosophy_as_way_of_life.md`, `wiki/concepts/spiritual_exercises.md`, `wiki/concepts/philosophical_discourse_vs_way_of_life.md` — `related` frontmatter + естественная ссылка в тексте.

# Коммит

`Tension: habit vs spiritual exercise`. Тело 1–2 строки. Trailer `Co-Authored-By: Claude Opus 4.7 (1M context) <noreply@anthropic.com>`. Push.

# Отчёт

По пунктам из `bridge-tension-prompt.md`. Обязательно: если хэндл переформулировался — как было и как стало; где wiki-пересказ сглаживает оригинал (Hadot особенно плотный).
