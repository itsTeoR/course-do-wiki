**Задача:** написать одну статью tension на ось **via negativa vs via positiva**. Авторы — Taleb, Fogg, Amabile (Amabile усиливает сторону via negativa эмпирикой). Проект — `/Users/teorusak/Projects/course-wiki/`. Работаем прямо в `main`, без worktree.

Запусти в **свежем чате Claude Code**.

**Методика — полностью по [tech-promts/bridge-tension-prompt.md](tech-promts/bridge-tension-prompt.md).** Прочти его первым. В частности — жёсткая граница Фазы A (только авторы, `raw/` + основное тело wiki-статей, черновик) и Фазы B (filing в `wiki/index_do_course.md`).

**Хэндл кандидата** — в `wiki/index_do_course.md`, раздел Tensions → Кандидаты, строка «Via negativa vs via positiva (Taleb vs Fogg; Amabile усиливает via negativa-сторону)». Держи свободно: если после чтения `raw/` операция формулируется иначе — переформулируй, это нормально. Саму формулировку кандидата не давай себе анкерить до того, как прочёл оригинал.

# Что есть в wiki и raw/

**Опорные статьи** (все `ready`, не `seed`):

- Taleb: `wiki/people/taleb.md`, `wiki/frameworks/antifragile.md`, `wiki/concepts/via_negativa.md`, `wiki/concepts/iatrogenics.md`, `wiki/concepts/barbell_strategy.md`, `wiki/concepts/fragile_robust_antifragile_triad.md`, `wiki/concepts/optionality_and_convexity.md`, `wiki/concepts/skin_in_the_game_taleb.md`, `wiki/concepts/lindy_effect.md`, `wiki/concepts/ecological_vs_ludic.md`.
- Fogg: `wiki/people/fogg.md`, `wiki/frameworks/tiny_habits.md`, `wiki/concepts/fogg_behavior_model.md`, `wiki/concepts/tiny_habits_recipe.md`, `wiki/concepts/celebration_wires_habit.md`, `wiki/concepts/ability_chain.md`.
- Amabile: `wiki/people/amabile.md`, `wiki/frameworks/progress_principle.md`, `wiki/concepts/inner_work_life.md`, `wiki/concepts/catalysts_and_nourishers.md`, `wiki/concepts/meaningful_work_amabile.md`, `wiki/concepts/progress_loop.md`.

Не читай всё подряд — в Фазе A выбирай под формулируемую операцию, оригинал из `raw/` важнее.

**Raw/-источники:**

- `raw/taleb/Antifragile ... .epub`. Ключевые места: Book VI (Via Negativa), разделы Subtractive Knowledge, Where Is the Charlatan?, Less Is More.
- `raw/fogg/Tiny Habits ... .pdf`. Ключевые: гл. 1 (в т.ч. раздел «B=MAP Applies to All Human Behavior»), главы про anchor → tiny behavior → celebration, механика формирования привычки через добавление.
- `raw/amabile/The Progress Principle ... .mobi`. Ключевые: разделы про силу inner work life, progress principle, ингибиторы/токсины vs катализаторы/nourishers, формулу «first, do no harm».

# Особое для этого tension

**Старт от Taleb.** У Fogg и Amabile — современные методологии. Taleb апеллирует к апофатической теологии Псевдо-Дионисия и скептико-эмпирической медицинской традиции — у него самый старший традиционный фон из троих. Формулируй операцию via negativa на его языке (субтрактивная эпистемология, iatrogenics), потом смотри, как Fogg её противоположным образом реализует в индивидуальной практике, и как Amabile эмпирически подтверждает Taleb-сторону.

**Прямая цитата у Taleb должна быть** — «Charlatans are recognizable in that they will give you positive advice, and only positive advice» (raw/taleb/Antifragile..., Book VI, Where Is the Charlatan?). Это почти буквально адресовано жанру Fogg.

**Fogg-сторону цитируй прямо.** Его тезис: B=MAP универсальна, поведение собирается через anchor + tiny behavior + celebration — чистое добавление. Не ужимай его в пересказ; дай цитату из книги, покажи, как устроен его центральный ход. Tiny Habits — архетип via positiva-жанра, на который Taleb прямо нападает как на класс.

**Amabile — третья нога, эмпирическая.** Из 12 000 дневниковых записей: способность негативных событий (setbacks, inhibitors, toxins) подрывать inner work life более чем вдвое сильнее способности позитивных (progress, catalysts, nourishers) её строить. Отсюда операциональный вывод — сначала убрать ингибиторы и токсины, только потом добавлять катализаторы. В терминах Taleb — эмпирическое подтверждение, что via negativa предшествует via positiva. Дай прямую цитату из книги.

**Соотношение с [[bridges/via_negativa_goldratt_gallwey]].** Тот bridge строит via negativa как общую операцию (Taleb, Goldratt, Gallwey). Этот tension — его оборотная сторона: показывает, с чем эта операция *несовместима*. Упомяни соседство явно в «Открытых вопросах», не в основном теле.

# Тест tension до того, как начинаешь писать

1. **Реальное противоречие или артефакт сборки?** Fogg действительно строит на добавлении (читай `raw/fogg/` напрямую, не wiki-пересказ — да, это центральный ход книги). Taleb действительно диагностически считает positive advice признаком шарлатана — да, прямая цитата. Противоречие не сборка.
2. **Выдерживает ли смену масштаба?** Taleb разворачивается до портфелей и систем, Fogg сжат до индивида. Есть ли общий масштаб, где tension держится? Индивидуальная практика действия и обучения — оба там. Проверь при чтении, не распадается ли противоречие, если сузить Taleb до индивидуального уровня.
3. **Авторы знают друг о друге?** Fogg о Taleb — вряд ли. Taleb о Tiny Habits напрямую — скорее всего нет, но via positiva как жанр он атакует систематически. Это близко к «авторы возражают» уровню, не «сборка наша». В статье отметь прямо.

# Что запрещено (напоминание)

- Никакой курс-связки в основном теле: «для CEO», «как применить в курсе», «в J-модусе / в P-модусе», «самоконтроль», «участники», «инициирование дел», «продуктивность». Только словарь самих авторов.
- Секцию `## В линзе гипотез курса` **не добавляй** по своей инициативе.
- Блоки `## В линзе гипотез курса` в существующих статьях wiki **не читай** — останавливайся на `---` перед этим заголовком.
- Файлы из `course/` **не читай**.
- Самопроверка перед Фазой B: вычитай черновик на слова курс-словаря, которых нет у самих авторов в `raw/`. Каждое такое слово — след загрязнения.

# Обновить в Фазе B

1. Создай `wiki/tensions/via_negativa_vs_via_positiva.md` (имя файла при необходимости уточни под итоговую формулировку). Frontmatter: `type: tension`, `tradition: [taleb, fogg, amabile]`, `related: [[...]]`, `density: medium` (или high — реши по Taleb), `status: ready`.
2. `wiki/index_do_course.md`, раздел Tensions: перенеси строку из «Кандидаты» в «Готовые». Формат: `- [[tensions/via_negativa_vs_via_positiva]] — одно-двух-предложное саммари.` Пометки `(H1, H2, …)` не ставь.
3. `wiki/README.md`: добавь ссылку в секцию tensions.
4. В `wiki/concepts/via_negativa.md`, `wiki/frameworks/tiny_habits.md`, `wiki/frameworks/progress_principle.md`, `wiki/concepts/iatrogenics.md`, `wiki/concepts/catalysts_and_nourishers.md` (и возможно у других задетых концепт-статей) — добавь новую статью в `related` frontmatter и естественную ссылку в тексте там, где она проясняет (часто в «Открытых вопросах» или в конце тематического раздела). Не раздувать.

# Коммит

`Tension: via negativa vs via positiva` (или уточнённое имя). Тело 1–2 строки: какие авторы, какая ось, что проверено в тесте. Trailer: `Co-Authored-By: Claude Opus 4.7 (1M context) <noreply@anthropic.com>`. Затем `git push origin main`.

# Короткий отчёт в конце

По пунктам из `tech-promts/bridge-tension-prompt.md`, раздел «Короткий отчёт в конце». Обязательно:

- Если хэндл кандидата переформулировался — сказать, как было и как стало.
- Какие статьи у опорных авторов задеты (где обнаружилось, что wiki-пересказ сглаживает акцент оригинала) — не править в этой сессии, но назвать.
