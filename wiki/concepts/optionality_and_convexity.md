---
name: Оптциональность и convexity
description: Талебовское понятие опции как вектора антихрупкости; выигрыш не требует предсказания, если payoff выпуклый; анекдот о Фалесе как прообраз
type: concept
tradition: [taleb]
density: high
related: [[antifragile]], [[fragile_robust_antifragile_triad]], [[barbell_strategy]], [[affordable_loss]]
---

## Анекдот о Фалесе

Талеб строит понятие оптциональности через историю Фалеса
Милетского, пересказанную Аристотелем. Фалес, уставший от
насмешек торговцев, заранее арендовал все оливковые прессы
в округе Милета и Хиоса за малую плату. Урожай оказался
обильным, и он передал прессы обратно владельцам — уже на
своих условиях, собрав значительное состояние
(raw/taleb/antifragile.epub, Book IV, Thales' Sweet Grapes).

Аристотель объясняет успех Фалеса «превосходным знанием
астрономии», по которой тот якобы предсказал хороший урожай.
Талеб считает это толкование противоположным истине:

> Thales put himself in a position to take advantage of his lack
> of knowledge — and the secret property of the asymmetry. The key
> to our message about this upside-downside asymmetry is that he
> did not need to understand too much the messages from the stars.
> Simply, he had a contract that is the archetype of what an
> asymmetry is, perhaps the only explicit asymmetry you can find
> in its purest form. It is an option, "the right but not the
> obligation" for the buyer
> (raw/taleb/antifragile.epub, Book IV, Thales' Sweet Grapes).

> *Перевод:* Фалес поставил себя в позицию, в которой выигрывал
> от собственного незнания — и от тайного свойства асимметрии.
> Ключ нашего тезиса об этой асимметрии upside-downside в том,
> что ему не нужно было слишком хорошо понимать послания звёзд.
> Просто у него был контракт — архетип того, что такое
> асимметрия, возможно, единственная явная асимметрия в её чистом
> виде. Это опцион — «право, но не обязательство» для
> покупателя.

> The option is an agent of antifragility.

> *Перевод:* Опцион — это агент антихрупкости.

## Формула

Талебовская компактная формула:

> antifragility equals more to gain than to lose equals more
> upside than downside equals asymmetry (favorable) equals likes
> volatility
> (raw/taleb/antifragile.epub, Book IV, Option and Asymmetry).

> *Перевод:* антихрупкость = больше выиграть, чем потерять =
> больше upside, чем downside = асимметрия (в твою пользу) =
> любит волатильность.

Если ты выигрываешь больше, когда прав, чем теряешь, когда
неправ — в долгосроке ты выигрываешь от волатильности. Ты
страдаешь только если систематически переплачиваешь за опцию.
Но большинство интересных опций в природе и технологии —
бесплатные или почти бесплатные; финансовые опции дороги,
потому что на рынке есть продавец, назначающий цену.

## Центральное следствие

> We just don't need to know what's going on when we buy
> cheaply — when we have the asymmetry working for us. But this
> property goes beyond buying cheaply: we do not need to
> understand things when we have some edge. And the edge from
> optionality is in the larger payoff when you are right, which
> makes it unnecessary to be right too often
> (raw/taleb/antifragile.epub, Book IV, Option and Asymmetry).

> *Перевод:* Нам просто не нужно понимать, что происходит, когда
> мы покупаем дёшево — когда асимметрия работает на нас. Но это
> свойство шире, чем «купить дёшево»: нам не нужно разбираться в
> вещах, когда у нас есть преимущество. А преимущество от
> опциональности — в большем payoff'е, когда ты прав, и это
> избавляет от необходимости быть правым слишком часто.

Это прямой удар по идее прогноза как основания для действия.
Фалес не предсказывал урожай. Он купил право на малые деньги.
Если бы урожай был плохой — он потерял бы аренду. Если хороший
— получил upside.

## Free options повсеместно

Талеб приводит примеры опций без видимого прайса:

- Приглашение на вечеринку в Кенсингтоне в субботу в
  Лондоне — «drop by if you want»: не обязывает, но даёт
  возможность улучшить вечер. Это бесплатная опция.
- Аренда с rent-control в Нью-Йорке: арендатор может
  остаться надолго при фиксированной ставке, но может
  съехать в любой момент с уведомлением. Если цены вырастут,
  он защищён; если упадут — он переедет. Асимметрия в пользу
  арендатора
  (raw/taleb/antifragile.epub, Book IV, Options of Sweet Grapes).

Финансовая независимость сама по себе — опция: у тебя
появляется возможность выбирать, от чего ты можешь отказаться,
что проявляет твои реальные предпочтения. «Freedom is the
ultimate option» (рус.: «Свобода — это предельная опция»).

## Option любит дисперсию

Важное свойство опции: её интересует не среднее, а хвостовое
распределение. Автор, у которого несколько тысяч фанатичных
читателей, антихрупче автора с миллионом равнодушных: у него нет
«отрицательной покупки», зато есть upside от интенсивных
сторонников. Wittgenstein, у которого было небольшое число
культовых последователей (Рассел, Кейнс), иллюстрирует это
(raw/taleb/antifragile.epub, Book IV, Things That Like Dispersion).

> Your work and ideas, whether in politics, the arts, or other
> domains, are antifragile if, instead of having one hundred
> percent of the people finding your mission acceptable or
> mildly commendable, you are better off having a high
> percentage of people disliking you and your message (even
> intensely), combined with a low percentage of extremely loyal
> and enthusiastic supporters.

> *Перевод:* Твоя работа и твои идеи — в политике, искусстве или
> любой другой области — антихрупки, если тебе лучше не от того,
> что сто процентов людей находят твою миссию приемлемой или
> слегка похвальной, а от того, что большой процент тебя и твоё
> послание не любит (порой сильно), при низком проценте крайне
> лояльных и горячих сторонников.

## Convexity

Convexity — математическое имя той же асимметрии: функция
payoff'а выпукла (concave-up), то есть prirost отдаёт больше,
чем equivalent убыток отнимает. Нелинейность, в которой upside
растёт быстрее, чем downside (либо downside ограничен).

Вся правая колонка [[fragile_robust_antifragile_triad|триады]]
— convex к источнику случайности. Хрупкое — concave (вогнутое):
малые шоки проходят, большие разрушают непропорционально.

Talebова мантра: не предсказывать события — ловить convex
exposures к событиям.

## Jensen's inequality

Математическая техника, стоящая за идеей: для выпуклой функции
средний input даёт меньший output, чем среднее output от
разбросанных inputs. Это объясняет, почему одинаковое среднее
количество алкоголя может быть по-разному безопасно в зависимости
от расписания, или почему усреднённая доза лекарства отличается
от суммы эффектов индивидуальных доз
(raw/taleb/antifragile.epub, Book II, footnote / Book V, Medicine,
Convexity, and Opacity).

## Теолеология против тинкеринга

Talebова контр-тезис об инновации: большинство крупных
технологий пришло от tinkerers (ремесленников, практиков) с
оптциональной стратегией, а не от «teleological» планирования.
Практик ходит по многим дешёвым опциям и берёт ту, которая
«сработала»; академик пишет об уже произошедшем. Талеб называет
академическую нарративизацию «lecturing birds how to fly» (рус.:
«читать птицам лекции о том, как летать»)
(raw/taleb/antifragile.epub, Book IV, History Written by the
Losers).

## Почему это не тривиально

Талеб подчёркивает: люди путают Фалеса с сильной прогностикой.
Но сильная прогностика и конечная выгода — разные вещи.
«Suckers try to be right, nonsuckers try to make the buck» (рус.:
«Лохи пытаются быть правы, не-лохи пытаются заработать бабла»)
(raw/taleb/antifragile.epub, Book VII, Stiglitz Syndrome).

## Связь с другими статьями

- [[affordable_loss]] — заранее ограниченный downside — это
  ровно левый конец опциональности.
- [[bird_in_hand]] — старт с того, что есть, и есть первая
  дешёвая опция.
- [[lemonade_principle]] — сюрприз как ресурс: использовать
  незапланированное — это опциональность в отношении
  случайности.
- [[mvp]] у Риса — одна из форм дешёвой опции, если
  downside действительно ограничен.
- [[horizon_vs_boundary|Карс: границы vs горизонты]] — у Карса
  граница это то, что определяет конечную игру; opt-ion в
  бесконечной игре — это и есть горизонт, открытый за любой
  границей.
