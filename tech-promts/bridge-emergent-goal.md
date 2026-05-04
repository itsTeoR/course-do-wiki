**Задача:** написать одну статью bridge на операцию **цель как артефакт процесса, а не предусловие**. Три традиции, три домена: Flores (conversations for action, conditions of satisfaction складываются в разговоре), Sarasvathy (эффектуация — bird in hand, affordable loss; цель эмерджентна), Csikszentmihalyi (пятифазный творческий процесс; цель уточняется insights-ами в ходе elaboration).

Проект — `/Users/teorusak/Projects/course-wiki/`. Работаем прямо в `main`, без worktree. Запусти в **свежем чате Claude Code**.

**Методика — полностью по [tech-promts/bridge-tension-prompt.md](tech-promts/bridge-tension-prompt.md).** Жёсткая граница Фазы A и Фазы B.

**Хэндл кандидата** — в `wiki/index_do_course.md`, раздел Bridges → Кандидаты, строка «Эмерджентная цель как артефакт процесса (Sarasvathy, Flores, Csikszentmihalyi)». Держи свободно.

# Что есть в wiki и raw/

**Опорные статьи** (все `ready`):

- Flores: `wiki/frameworks/conversations_for_action.md`, `wiki/people/flores.md`, `wiki/frameworks/ontology_of_language.md`, `wiki/concepts/speech_acts.md`, `wiki/concepts/conditions_of_satisfaction.md`, `wiki/concepts/conversations_for_possibilities.md`, `wiki/concepts/four_types_of_conversation.md`, `wiki/concepts/moods_and_trust.md`, `wiki/concepts/personal_declarations.md`, `wiki/concepts/the_ask.md`, `wiki/concepts/observer_and_interpretation.md`.
- Sarasvathy: `wiki/frameworks/effectuation.md`, `wiki/people/sarasvathy.md`, `wiki/concepts/affordable_loss.md`, `wiki/concepts/bird_in_hand.md`, `wiki/concepts/crazy_quilt.md`, `wiki/concepts/control_vs_prediction.md`, `wiki/concepts/lemonade_principle.md`.
- Csikszentmihalyi: `wiki/frameworks/creativity_csikszentmihalyi.md`, `wiki/people/csikszentmihalyi.md`, `wiki/concepts/creative_process_five_phases.md`, `wiki/concepts/domain_field_person.md`.

**Raw/-источники:**

- Flores: `raw/flores/Conversations for action ... .epub`. Ключевое: главы про речевые акты, conditions of satisfaction, commitment как речевой акт; про то, как запрос/обещание конституируют цель в разговоре.
- Sarasvathy: `raw/sarasvathy/sarasvathy_2001_causation_and_effectuation.pdf` (академическая статья, ключевая) + `raw/sarasvathy/Effectual Entrepreneurship ... .epub`. Ключевое: определение effectuation vs causation, bird-in-hand, affordable loss, endogenous goals (опора на March 1982).
- Csikszentmihalyi: `raw/csikszentmihalyi/Creativity ... .epub`. Ключевое: пятифазный процесс (preparation → incubation → insight → evaluation → elaboration), рекурсивность — insights возникают в elaboration и меняют направление.

# Особое для этого bridge

**Старт от Flores.** У него самая глубокая философская рамка (через Хайдеггера и Сёрла): цель не *существует* до речевого акта, она им *конституируется*. Conditions of satisfaction складываются в разговоре между просящим и обещающим, не фиксируются заранее. Это самый ранний по силе философский регистр из троих — старт отсюда.

**Csikszentmihalyi** добавляет эмпирический материал. 50 лет интервью с креативами: творческий процесс рекурсивен, не линеен; insights в ходе elaboration постоянно меняют направление работы. Цель того, что создаётся, уточняется по мере создания. Дай прямую цитату.

**Sarasvathy** переносит ту же операцию в предпринимательскую методологию. Effectuation явно отказывается от predetermined goals: стартуй со средств, цель складывается. Цитата — её формулировка endogenous goals (со ссылкой на March 1982). Прямая цитата: «effectuation is suggested here as a viable and descriptively valid alternative to the STP process — not as a normatively superior one.»

**Разные уровни — главный риск теста.**
- Flores: онтологический (речь, акт).
- Csikszentmihalyi: феноменологический (опыт творческого процесса, 50 лет эмпирики).
- Sarasvathy: методологический (предпринимательская практика).

Уровни разные. Решение — формулировать операцию на самом абстрактном уровне («цель конституируется действием, а не предшествует ему»), и в «Где сходство кончается» разводить регистры явно. Проверь в Фазе A, держится ли операция при таком абстрагировании, или это мы её натянули сверху.

**Разные масштабы времени — вторая ось расхождения.** Речевой акт у Flores: минуты. Creative process у Csikszentmihalyi: годы. Предпринимательство у Sarasvathy: месяцы-годы. Что именно складывает цель в каждом случае — тоже разное (прямой диалог / рекурсивные insights / ресурсы и обязательства). Раздел «Где сходство кончается» — обязательный.

**Соседство** — с готовой `wiki/tensions/effectuation_vs_goal_setting.md`. Та tension противопоставляет effectuation классическому goal-setting (Locke & Latham, SMART, OKR). Этот bridge — положительный оборот: показывает, что эмерджентная цель — общая структурная операция, а не только особенность Sarasvathy. Упомянуть в «Открытых вопросах».

# Тест bridge до письма

1. **Общая операция или общая тема?** Операция: цель конституируется действием, не предшествует ему. Структурная. *Но*: три разных типа «действия» — речевой акт, творческий процесс, предпринимательство. Проверь в Фазе A, удерживается ли общая структура (а не просто общее слово «эмерджентная»).
2. **Разные уровни?** Онтологический / феноменологический / методологический. Риск реальный — см. выше. Стратегия: абстрагировать операцию, в «Где сходство кончается» развести регистры явно.
3. **Что в разделе «Где сходство кончается»?** Что именно конституирует цель; масштаб времени; что первично — средства, отношения, или insight; как возвращаются к начальному намерению (или не возвращаются).

# Запрещено

- Никакой курс-связки в основном теле.
- Секцию `## В линзе гипотез курса` не добавлять.
- Блоки `## В линзе гипотез курса` в существующих статьях — не читать.
- Файлы `course/` — не читать.

# Обновить в Фазе B

1. Создай `wiki/bridges/emergent_goal.md` (имя уточни под итог). Frontmatter: `type: bridge`, `tradition: [flores, sarasvathy, csikszentmihalyi]`, `related: [[...]]`, `density: medium` (или high — реши по итоговой плотности цитат), `status: ready`.
2. `wiki/index_do_course.md`, раздел Bridges: строка из «Кандидаты» → «Готовые».
3. `wiki/README.md`: ссылка в секцию bridges.
4. В `wiki/frameworks/effectuation.md`, `wiki/frameworks/conversations_for_action.md`, `wiki/concepts/conditions_of_satisfaction.md`, `wiki/concepts/creative_process_five_phases.md` и других задетых — `related` frontmatter + естественная ссылка в тексте. Также в `wiki/tensions/effectuation_vs_goal_setting.md` — перекрёстная ссылка, раз это её положительный оборот.

# Коммит

`Bridge: emergent goal as artifact of process`. Тело 1–2 строки. Trailer `Co-Authored-By: Claude Opus 4.7 (1M context) <noreply@anthropic.com>`. Push.

# Отчёт

По пунктам из `bridge-tension-prompt.md`. Обязательно: как переформулировался хэндл; где уровни авторов не совпадают и что с этим сделано; где wiki-пересказ сглаживает оригинал (Flores плотный).
