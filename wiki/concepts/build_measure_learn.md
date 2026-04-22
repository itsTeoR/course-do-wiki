---
name: Build-Measure-Learn
description: Центральная петля в методе Риса — научение через цикл «сделать → измерить → научиться», а не через линейное производство продукта
type: concept
tradition: [ries]
week: []
p-j-stance: unclear
density: medium
related: [[lean_startup]], [[mvp]], [[pivot_or_persevere]], [[ries]]
---

# Build-Measure-Learn и validated learning

Центральная петля в методе Эрика Риса. Единица работы стартапа — не
«построить продукт», а пройти один полный цикл: сделать что-то,
измерить поведение реальных клиентов, извлечь из этого знание,
которое будет двигать следующий цикл.

> The fundamental activity of a startup is to turn ideas into
> products, measure how customers respond, and then learn whether
> to pivot or persevere. All successful startup processes should be
> geared to accelerate that feedback loop.
> (raw/ries/lean-startup.epub, Introduction, раздел «The Lean
> Startup Method»)

## Три фазы

**Build.** Из идей строится продукт. Не окончательный, а минимально
достаточный для проверки конкретной гипотезы — см. [[mvp]]. Рис
переносит сюда лексикон Lean Manufacturing: всё, что сделано сверх
необходимого для научения, — *waste*:

> The lesson of the MVP is that any additional work beyond what was
> required to start learning is waste, no matter how important it
> might have seemed at the time.
> (raw/ries/lean-startup.epub, гл. 6 «Test», раздел «Minimum Viable
> Products: From Jay-Z to the House of Wisdom»)

**Measure.** Продукт попадает к клиентам, их поведение измеряется.
Ключевое различение Риса — *vanity metrics* против *actionable
metrics* (гл. 7 «Measure», раздел «Vanity Metrics: A Word of
Caution»).

- **Vanity metrics:** совокупное число пользователей, общее число
  скачиваний, выручка за год. Эти числа почти всегда растут — и
  потому почти ничему не учат. «Мы выросли с 1000 до 10000
  пользователей» не отвечает на вопрос, работает ли продукт.
- **Actionable metrics:** cohort-метрики. Одна группа клиентов,
  пришедшая в одно время, сравнивается с другой, пришедшей позже.
  Видно, как ведёт себя именно эта группа именно в этой версии
  продукта — удерживается ли, покупает ли, возвращается ли. Эти
  метрики умеют отличать продукт A от продукта B.

Split-тесты (A/B) — дополнительный инструмент: одна и та же когорта
разделена случайно, одна половина получает вариант X, другая — Y.
Только такое сравнение даёт чистый сигнал о том, что именно
изменение, а не время или внешние факторы, сдвинуло метрику.

**Learn.** На основе данных — сформулировать, что теперь известно,
чего раньше не было известно. Это *validated learning*.

## Validated learning

Главная метрика стартапа у Риса — не выпущенные фичи, не деньги, не
новости в прессе. Это научение, подтверждённое поведением клиентов:

> Startups exist not just to make stuff, make money, or even serve
> customers. They exist to learn how to build a sustainable
> business. This learning can be validated scientifically by running
> frequent experiments that allow entrepreneurs to test each
> element of their vision.
> (raw/ries/lean-startup.epub, Introduction, раздел «The Lean
> Startup Method»)

Научение валидировано тогда, когда его можно описать как «у нас
была гипотеза H, мы провели эксперимент E, получили результат R, и
из этого следует Z». Без эксперимента — это мнение. Без метрики —
это впечатление. Без зафиксированной заранее гипотезы — это
послефактное объяснение.

## Петля, не линия

Рис подчёркивает: Build-Measure-Learn — не линейная
последовательность, а замкнутая петля. Результат одного цикла — это
новая гипотеза или уточнение старой, которая запускает следующий
цикл.

Из этого следует ключевой практический вывод: оптимизировать нужно
не отдельные фазы, а *время прохождения полной петли*. Быстрее
цикл — больше научения за те же деньги. Рис сразу переопределяет
понятие *runway*: это не оставшиеся деньги, а число pivot'ов,
которые стартап ещё может успеть сделать (гл. 8 «Pivot (or
Persevere)», раздел «A Startup's Runway Is the Number of Pivots It
Can Still Make»):

> The true measure of runway is how many pivots a startup has left:
> the number of opportunities it has to make a fundamental change
> to its business strategy.
> (раздел и файл там же)

## Scientific method

Рис переводит петлю на язык научного метода (гл. 4 «Experiment»,
раздел «From Alchemy to Science»):

> This is one of the most important lessons of the scientific
> method: if you cannot fail, you cannot learn.

Если эксперимент устроен так, что не может дать негативного
результата, это не эксперимент. Это ритуал. Рис жёстко различает
«смотреть, что получится» и «проверить, верна ли гипотеза»: первое
всегда даёт результат («что-то получилось»), но не даёт validated
learning.

## Пример: Votizen

Рис подробно разбирает Votizen — политический стартап Дэвида Бинетти
(гл. 8 «Pivot (or Persevere)»). За четыре года — шесть pivot'ов.
Первый MVP собирался 8 месяцев, следующий — 4, потом 3, потом 1.
Ускорение пришло не от накопленной инфраструктуры (много кода как
раз приходилось выбрасывать при каждом pivot'е), а от того, что
команда училась: каждая петля давала более точный вопрос и более
прицельный эксперимент.

## Источник

- Ries, E. (2011). *The Lean Startup*. Introduction и гл. 3 «Learn»,
  7 «Measure».
