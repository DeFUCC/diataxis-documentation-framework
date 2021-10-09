Об инструкциях
===================

**Инструкции** — это указания, которые ведут читателя через шаги, необходимые для решения реальных проблем. Инструкции ориентированы на **цели**.

* * * * *

![image](/images/overview-how-to.png)

Инструкции можно рассматривать как рецепты, указания, ведущие читателя через этапы для достижения конкретного результата.

Примерами могут служить: "как откалибровать радиолокационную решетку", "как использовать fixtures в pytest", "как сконфигурировать переприсоедниение политик отступления". С другой стороны, "как построить веб-приложение" — не может, т.к. не направлено на конкретную цель или проблему, а является чрезвычайно открытой сферой навыков.

Инструкции важны не только потому, что пользователям нужно иметь возможность получать результат: список инструкций в вашей документации помогает увидеть картину того, что ваш продукт в действительности **делает**. Богатый список инструкций — обнадеживающее предположение о возможностях продукта.

Если они хорошо написаны и обращены к правильным темам, вы скорее всего обнаружите, что именно инструкции являются самым часто изучаемыми разделами вашей документации.

* * * * *

Инструкции и руководства
--------------------------

**Инструкции принципиально отличаются от руководств**. Они легко сливаются воедино, т.к. оба описывают последовательности практических шагов, ведущих к выполнению некоторой задачи. Однако потребности пользователей, которые они обслуживают, заметно отличаются и такие слияния становятся корнем многих трудностей, поражающих документацию.

Стоит отметить, что в большей части программной документации инструкции обычно написаны достаточно хорошо — намного лучше, чем руководства. Разработчики программ часто особенно хороши в написании их, потому что инструкции соответствуют опыту реального пользователя и разделяют ту же направленную на решение задач перспективу, что есть и у разработчика в процессе написания самой программы.

* * * * *

Еда и кулинария
----------------

![image](/images/old-recipe.jpg)

Рассмотрим рецепт как отличную модель инструкции. Рецепт ясно определяет, что будет достигнуто в результате следования ему и **обращается к конкретному вопросу** ("Как мне сделать...?", "Что я могу сделать с...?").

В обязанности рецепта не входит *учить* вас, как что-то сделать. Профессиональный шеф-повар, который делал то же самое множество раз может по прежнему следовать рецепту — даже если он сам *создал* рецепт для самого себя — чтобы убедиться, что он делает все правильно.

Даже следование рецепту **требует как минимум базовых компетенций**. Не стоит предполагать, что тот, кто никогда не готовил раньше, сможет успешно следовать рецепту, то есть рецепт не является заменой уроку по кулинарии.

Тот, кто ожидал получить рецепт, а вместо этого получил урок по кулинарии, будет расстроен и раздражен. Аналогично, как бы ни было интересно почитать о контексте и истории конкретного блюда, самое неподходящее время, чтобы с этим столкнуться — как раз когда вы в середине попытки его сделать. Хороший рецепт соответствует устоявшемуся формату, который исключает и обучение и обсуждение, а фокусируется только на том, **как**  сделать блюдо соответствующим.

* * * * *

Написание хорошей инструкции
---------------------------

> **Характеристики инструкции**
>  - фокусируется на задачах или проблемах
>  - предполагает, что пользователь знает, что хочет получить
>  - действие и только действие
>  - никаких отступлений, объяснений, поучений.


### Describe a sequence of actions

Like a tutorial, a **how-to guide contains a sequence of actions, that
have an order**. Unlike a tutorial, you don't have to start at the
beginning of the whole story and take your reader right to the end. Most
likely, your user will also be in the middle of something - so you only
need to provide a starting-point that they know how to reach, and a
conclusion that actually answers a real question.

How-to guides should be reliable, but they don’t need to have the
cast-iron repeatability of a tutorial.

### Solve a problem

The problem or task is the concern of a how-to guide: **stick to that
practical goal**. Anything else that's added - unnecessary explanation,
for example - distracts both you and the user and dilutes the useful
power of the guide.

### Don't explain concepts

An explanation doesn't show you how to do something - so **a how-to
guide should not try to explain things.** Explanation here will simply
get in the way of the action. If explanations are important, link to
them.

### Be flexible

A tutorial needs to be didactic in nature, but **a how-to guide needs to
be adaptable to real-world use-cases**. A how-to guide that is useless
for any purpose except *exactly* the narrow one you have addressed is
rarely valuable.

### Omit the unnecessary

In how-to guides, **practical usability is more helpful than
completeness.** Whereas a tutorial needs to be a complete, end-to-end
guides, a how-to guide does not. It should start and end in some
reasonable, meaningful place, and require the reader to join it up to
their own work.

### Pay attention to naming

**Choose titles that say exactly what a how-to guide shows.**

-   good: *How to integrate application performance monitoring*
-   bad: *Integrating application performance monitoring* (maybe the
    document is about how to decide whether you should, not about how to
    do it)
-   very bad: *Application performance monitoring* (maybe it's about
    *how* - but maybe it's about *whether*, or even just an explanation
    of *what* it is)

Note that search engines appreciate good titles just as much as humans
do.

* * * * *

The language of how-to guides
-----------------------------

*This guide shows you how to...*
:   Describe clearly the problem or task that the guide shows the user
    how to solve.

*If you want x, do y. To achieve w, do z.*
:   Use conditional imperatives.

*Refer to the x reference guide for a full list of options.*
:   Don't pollute your practical how-to guide with every possible thing
    the user might do related to x.


