---
name: Lean Startup
description: Метод Эрика Риса — превращать предпринимательство в управляемый эксперимент через петлю Build-Measure-Learn, MVP и структурированный pivot
type: framework
tradition: [ries]
density: medium
related: [[build_measure_learn]], [[mvp]], [[pivot_or_persevere]], [[ries]]
---

# Lean Startup

Эрик Рис — предприниматель, сооснователь IMVU (2004). Книга *The Lean
Startup* (Crown Business, 2011) написана по опыту IMVU и нескольких
лет консультирования стартапов и корпораций. У Риса есть свой
словарь — MVP, pivot, cohort, vanity metrics, engine of growth, —
и этот словарь в 2010-х стал общеупотребительным языком индустрии.

Регистр — инженер-предприниматель. Короткие главы, каждая главa
начинается с конкретного кейса (IMVU, Votizen, Groupon/The Point,
Zappos, Dropbox, Wealthfront, Intuit SnapTax, Village Laundry в
Бангалоре), технический словарь, прямые отсылки к Lean Manufacturing
(Тайити Оно, У. Эдвардс Деминг) и к Customer Development Стива
Бланка. Аналогия — завод Toyota: партиями меньше, циклы быстрее,
ценностью измеряй научение, а не активность.

## Что такое стартап

Рис даёт широкое, специально не-отраслевое определение:

> A startup is a human institution designed to create a new product
> or service under conditions of extreme uncertainty.
> (raw/ries/lean-startup.epub, Introduction, раздел «The Lean
> Startup Method»)

Из этого определения у него следует вся методология. Под стартапом
не обязательно иметь в виду гаражное предприятие: подпадают и
корпоративные подразделения инноваций. Но предпосылки стандартного
менеджмента — стабильный рынок и знакомый продукт — в стартапе
отсутствуют. Значит, планирование по прогнозу, жёсткий
бренд-менеджмент и метрики выручки не работают как компас. Нужен
другой инструментарий.

## Пять принципов

Рис сам формулирует метод через пять пунктов, и эти пять пунктов
определяют структуру книги:

1. **Entrepreneurs are everywhere.** Стартап не привязан к гаражу
   и кремниевой долине.
2. **Entrepreneurship is management.** Стартап — это институция,
   значит ему нужен свой тип менеджмента, а не отсутствие оного.
3. **Validated learning.**
   > Startups exist not just to make stuff, make money, or even
   > serve customers. They exist to learn how to build a sustainable
   > business.
4. **Build-Measure-Learn.**
   > The fundamental activity of a startup is to turn ideas into
   > products, measure how customers respond, and then learn whether
   > to pivot or persevere. All successful startup processes should
   > be geared to accelerate that feedback loop.
5. **Innovation accounting.** Скучная бухгалтерия прогресса,
   специально устроенная для стартапов, чтобы удерживать
   инновационные команды подотчётными.
(raw/ries/lean-startup.epub, Introduction, раздел «The Lean Startup
Method»)

Оба ключевых определения — про «научение, подтверждённое реальным
поведением клиентов» и про петлю — Рис даёт сразу в Introduction и
затем возвращается к ним на протяжении всей книги.

## Центральная петля: Build-Measure-Learn

Единица работы стартапа — не «построить продукт», а пройти один
полный цикл: сделать что-то, измерить, научиться, решить, что
делать дальше. Подробно — в [[build_measure_learn]].

Ключевая деталь: петля не идёт линейно от идеи к продукту. Она
замкнута. Научение приводит к новой идее, которая порождает новый
MVP, который проверяется новым измерением. Единица прогресса —
*validated learning*: то знание, которое мы теперь имеем и которое
доказано поведением реальных клиентов.

Из этого следует практический вывод: оптимизировать нужно не
отдельные фазы, а время прохождения полной петли. Быстрее цикл —
больше научения за те же деньги.

## MVP

Первое, что создаётся в петле, — не «хороший продукт». Это *minimum
viable product*:

> A minimum viable product (MVP) helps entrepreneurs start the
> process of learning as quickly as possible. It is not necessarily
> the smallest product imaginable, though; it is simply the fastest
> way to get through the Build-Measure-Learn feedback loop with the
> minimum amount of effort.
> (raw/ries/lean-startup.epub, гл. 6 «Test», раздел «Minimum Viable
> Product»)

Ключевое слово — *fastest*. Не «самый маленький», не «приличный», не
«без багов». Самый быстрый способ получить реальное научение.
Подробно — в [[mvp]].

## Leap-of-faith assumptions

Любой стартап висит на нескольких непроверенных предпосылках. Рис
называет их *leap-of-faith assumptions*:

> To apply the scientific method to a startup, we need to identify
> which hypotheses to test. I call the riskiest elements of a
> startup's plan, the parts on which everything depends,
> leap-of-faith assumptions. The two most important assumptions are
> the value hypothesis and the growth hypothesis.
> (raw/ries/lean-startup.epub, гл. 5 «Leap», раздел «Strategy Is
> Based on Assumptions»)

**Value hypothesis** спрашивает: пользуются ли люди продуктом тем
способом, на который рассчитывает основатель? Получают ли они
ценность?

**Growth hypothesis** спрашивает: как новые клиенты приходят к
продукту — через удержание, через рекомендации, через платную
рекламу?

Метод существует ради того, чтобы обе эти гипотезы превратить в
эксперимент. До проверки — это красивые слайды и инвесторский
энтузиазм, не знание.

## Innovation accounting

Если единица прогресса — validated learning, то и учёт прогресса не
может быть тем же, что у зрелой компании. Рис предлагает *innovation
accounting* — систему из трёх шагов (гл. 7 «Measure», раздел «How
Innovation Accounting Works»):

1. Установить базовый уровень через MVP — «где мы сейчас».
2. Настраивать продукт маленькими изменениями и смотреть, как
   меняются ключевые cohort-метрики.
3. Решить: pivot или persevere, на основе того, движутся ли метрики
   в нужную сторону достаточно быстро.

Внутри — важное различение *vanity metrics* и *actionable metrics*
(подробно в [[build_measure_learn]]). Vanity-метрики — совокупные
числа, которые почти всегда растут и почти ничему не учат.
Actionable — cohort-метрики, которые позволяют отличить одну версию
продукта от другой и привязать результат к решению команды.

## Pivot или persevere

После каждого цикла стартап встаёт перед решением: данные
подтверждают гипотезу — *persevere* — или опровергают — *pivot*?

> A pivot is not just an exhortation to change. Remember, it is a
> special kind of structured change designed to test a new
> fundamental hypothesis about the product, business model, and
> engine of growth.
> (raw/ries/lean-startup.epub, гл. 8 «Pivot (or Persevere)», раздел
> «A Pivot Is a Strategic Hypothesis»)

Pivot — не отказ от видения и не смена идеи вообще. Это
структурированная смена одного конкретного элемента бизнес-модели
при сохранении остального. Рис выделяет около десяти типов pivot'ов
и перекраивает для них понятие *runway*. Подробно — в
[[pivot_or_persevere]].

## Engines of growth

Рост у Риса не универсален. Он идёт по одному из трёх механизмов
обратной связи (гл. 10 «Grow», раздел «The Three Engines of
Growth»):

- **Sticky engine** — удержание. Компания растёт, потому что темп
  прихода новых клиентов выше churn rate. Ключевая метрика —
  retention и churn.
- **Viral engine** — заражение. Клиенты приводят новых клиентов.
  Ключевая переменная — *viral coefficient*; если он больше единицы,
  рост экспоненциальный, и его не нужно «подталкивать».
- **Paid engine** — платный. Компания тратит на привлечение меньше,
  чем получает с клиента за его lifetime (CPA < LTV). Маржа между
  LTV и CPA определяет скорость роста.

Рис настаивает: стартап должен выбрать один движок и оптимизировать
под него:

> Successful startups usually focus on just one engine of growth,
> specializing in everything that is required to make it work.
> (raw/ries/lean-startup.epub, гл. 10 «Grow», раздел «Engines of
> Growth Determine Product/Market Fit»)

## Genchi gembutsu

Рис неожиданно много места отводит термину, который он берёт прямо
у Toyota — *genchi gembutsu*, «пойди и увидь сам»:

> You cannot be sure you really understand any part of any business
> problem unless you go and see for yourself firsthand. It is
> unacceptable to take anything for granted or to rely on the
> reports of others.
> (raw/ries/lean-startup.epub, гл. 4 «Experiment», раздел «Genchi
> Gembutsu»; Рис цитирует Taiichi Ohno и Jeffrey Liker)

Для предпринимателя это означает: не строить стратегию из чужих
отчётов и презентаций инвесторов. Первые встречи с клиентами MVP —
это не маркетинг, это ответ на вопрос «что из моих предположений
вообще правда?».

## Цена традиционного подхода

В Introduction Рис формулирует позицию, с которой спорит: миф о
«гениальном предпринимателе», которому достаточно страсти, упорства
и удачи. Этот миф, по Рису, удобен после победы и разрушителен до
неё:

> Entrepreneurship is a kind of management. No, you didn't read that
> wrong. We have wildly divergent associations with these two words,
> entrepreneurship and management. Lately, it seems that one is
> cool, innovative, and exciting and the other is dull, serious, and
> bland.
> (raw/ries/lean-startup.epub, Introduction, раздел «Origins of the
> Lean Startup»)

Весь метод — это перевод предпринимательства из режима «талант +
удача» в режим «эксперимент + измерение + решение». Это сознательная
оппозиция романтической мифологии стартапа.

## Что в книге неожиданно

- Книга написана не про кремниевую долину. В ней разбираются случаи
  Village Laundry Service в Бангалоре, SnapTax в Intuit как пример
  «семитысячечеловечного стартапа» внутри крупной компании, и даже
  попытка применить Lean Startup в правительстве США (гл. 4, раздел
  «A Lean Startup in Government?»).
- Рис прямо признаёт, что IMVU — компания, из опыта которой он
  вывел метод — была близка к провалу именно потому, что команда
  слишком долго верила в vanity-метрики (гл. 7 «Measure»,
  «Innovation Accounting at IMVU»).
- В финале Рис предлагает Long-Term Stock Exchange — альтернативную
  биржевую инфраструктуру, которая поощряла бы долгосрочные ставки
  акционеров (гл. 13 «Epilogue: Waste Not»). Это резко
  институциональная нота для книги, которая начинается с гаражного
  стартапа.

## Источник

- Ries, E. (2011). *The Lean Startup: How Today's Entrepreneurs Use
  Continuous Innovation to Create Radically Successful Businesses*.
  New York: Crown Business. EPUB в [raw/ries/](../../raw/ries/).
