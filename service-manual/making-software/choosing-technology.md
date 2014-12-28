---
title: Вибір технологій
sub_title: Як обрати, які програмні засоби використовувати
category: making-software
type: guide
audience:
  primary: service-managers, tech-archs, developers
  secondary: web-ops, chief-technology-officers
status: draft
phases:
  - alpha
  - beta
  - live
permalink: /service-manual/making-software/choising-technology/
breadcrumbs:
  -
    title: Сервісна документація
    url: /service-manual/
  -
    title: Розробка Програмного Забезпечення
    url: /service-manual/making-software/
  -
    title: Вибір технологій
    url: /service-manual/making-software/choising-technology/
---

<h1 class="page-title">{{ page.title }}</h1>
<h2 class="page-sub_title">{{ page.sub_title }}</h2>

Це інформація тільки для довідки, не використовуйте її як керівництво до дій.

У різних частинах проекту, ви можете обирати різні технології, серед яких:

- Мови програмування;
- Бази данниї;
- Бібліотеки;
- Операційні системи;
- Невеликі інструменти для облегшення роботи команди;
- Комерційне (proprietary) та программне забезпечення з відкритим кодом, також допустимі.



Ви можете змінити своє рішення
------------------------
Припустимо, що більшість обраних технологій можуть або будуть змінюватися, особливо на ранніх стадіях розвитку, наприклад:

* Вибір мови програмування, в якій простіше і швидше створювати прототипи, переїзд на інші продукти для полегшення розробки для великих команд;
* Використовувати программне забезпечення з відкритим кодом для швидкого старту, розраховуючи придбати комерційний продукт для необхідного функціоналу.

На перший день проекту ви просто не зможете знати стільки щоб якумога найкраще обрати вірну технологію. Обгрунтованно експерементувати з технологіями на цьому етапі допустимо.

Переконайтеся що зможете знайти час на обгрунтування та перевірку свого вибору.



Почніть з можливостей
---------------------
Коли ви робите вибір яку технологію використовувати, дуже легко відразу ж перейти до певного продукту. Це, як правило, базується на минулому досвіді або на сучасних тенденціях.

1. Зробіть крок назад та обміркуйте необхідні можливості технологій - наприклад реляційні бази данних, або бази данних ключ/значення;
2. Обговоріть необхідні можливості, а не специфічну реалізацію їх. 
3. Після вибору можливостей, ознайомтеся з різними їх рішеннями;
4. Перевірте программне забезпечення в середовищі, яка дуже схожа на кінцеве, тобто в реальних умовах (у тому числі найбільше навантаження).

Після цього процессу переконайтеся що ви:

- Зрозуміти особливості програмного забезпечення;
- Виявили будь-які компроміси або потенційні проблеми з програмним забезпеченням;
- Переконайтеся що його заявленні можливості відповідають вашим потребам.



Ціна
----
При виборі програмного забезпечення, переконайтеся що ви врахували загальну вартість, а також всі додаткові внески.

Візміть до уваги витрати на такі речі як:

- Персонал;
- Ціна підтримкі;
- Ліцензування (якщо необхідне);
- Очікуванну продуктивність на робочому оточенні;
- Подальші витрати (особливо на міграцію данних при оновленні) які можуть бути спричиненні використання нестандартних форматів.

Переконайтеся, що врахували всі фінансові наслідки будь-яких незвично високих навантажень у виробничому оточенні.




Залучіть всіх
-------------
Залучіть всю команду вибір технологій. Це не означає, що вони відповідають за прийняття рішень, але що потрібна команда розробників (включаючи веб спеціалістів) щоб спільно використовувати свої знання на:

- Доступні параметри;
- Як це вплине на всю систему.

Очікувані варіації налаштування технологій, для обмірковування повинні бути розділенні при виборі технології.

FIXME: All things being equal, picking technologies that developers and operations staff like will typically result in improved productivity.



Тестування та розгортання
-------------------------
Ви зробете цей процес значно легшим, якщо:

- Розгорнете ваш сервіс як умога [раніше та частіше](/making-software/releasing-software/);
- Оберете компоненти котрі легко розгортаються так оновлюються як частина [автоматичного потоку](/making-software/continuous-delivery/);
- Уникните программне забезпечення, що ускладнює тестування в потоці, автоматичне тестування має велике значення в гнучкій розробці (Agile).




Фіксація
--------
Фіцсація технологій відбувається коли ваші попередні рішення обмежують можливість вибору майбутніх.

Наприклад, якщо ви обрали базу данних котра підтримє роботу тільки на одній операційній системі, ви обмежуєтесь в виборі інших. Якщо ціна роботи (придбання, підтримки) операційної системи виросте, ви не будете мати змоги змінити її.

Бути замкнутим на одному постачальнику, або способі обробці речей створить такі ускладнення:

- Непередбаченне збільшення вартості;
- Обмежить швидкість розробки продукту в майбутньому, наприклад якщо з’явиться ідеально підходяща технологія, котра не сумісна з вибором попередньої технології.

З часом ви можете опинитись в ситуації коли всі обранні технології тісно повязані між собою, і ви обмеженні на одному постачальникі або на одному способі рішення задач. Це може мати непередбачуванні фінансові витрати (як ночівля). Також це може обмежувати як швидко ви можете повторюватти етапи розробки.

Коли ви оберете певну технологію, чітко переконайтесь в витратах на підтримку або наслідки переходу від неї, щоб уникнути блокування, в міру можливостей. Це означає мінімізувати нестандартизованні технології (як протоколи, API, чи мови програмування) щоб мати можливість перейти на іншу технологію при необхідності та мінімальними витратами.

Взагалі уникніть прийняття довгострокових рішень щодо будь-якої конкретної технології, продукту або постачальника доки ви повністю не зрозумієте які проблеми вим необхідно вирішити. І навіть тоді переконайтеся що максимізували майбутрі варіанти вибору щоб уникнути блокування системи, якщо це можливо.



Нове проти існуючого программне забезпечення
-----------------------
Якщо є программне забезпечення котре вирішить вашу проблему, обовязкову обміркуйте його використання.

Якщо ви використовуєте программне забезпечення щоб задовольнити рідкі або нішові потреби, не очікуйте знаходження інструментів які будуть вирішувати і продовжуватимуть вирішувати ці потреби. Очікуйте що знадобиться створення свого программне забезпечення.

Однак, є багато ситуацій, де є сенс використовувати існуючі рішення, наприклад:

- FIXME: When you have a commodity need, because someone has probably already developed a solution to the common problem;
- FIXME: Facing a niche problem that’s peculiar to government, which has already been solved by another part of, or another, government and released as open source software.

У більшості випадків, багато проектів мають схожі потреби, тому є сенс перестворити колесо для деяких типів программне забезпечення, як:

- Інструменти розробки;
- Інструменти створення (Build tools);
- Допоміжні бібліотеки;
- Бази данних;
- Інструменти спостереження (monitoring tools).



Спільний доступ до программне забезпечення
---------------------
FIXME: Share software that’s developed to meet the needs of government wherever possible under a permissive, GPL-compatible open source licence (eg MIT/X11 or 3-clause BSD) unless doing so would:

- Створити недопустимі ризики для безпеки систем або процессів, з котрими можуть бути пов'язанні з зрозумілих причин;
- Перекривати існуючі контрактні узгодження;
- Безпосередньо загрожувати національній безпеці.

Відкритий доступ до программне забезпечення означає що він може бути використованний та/або полібшенний ким завгодно у світі, хто має схожі потреби. FIXME: It’s important that other governments in particular have the opportunity to reuse the software you’ve created, because everyone deserves to have [digital services so good that people prefer to use them](/digital-by-default/).

Наприклад [GovSpeak](https://github.com/alphagov/govspeak) та [unicorn herder](https://github.com/gds-operations/unicornherder) невеликі компоненти, котрі [використовані для розробки частини GOV.UK](https://gds.blog.gov.uk/govuk-launch-colophon/). Вони зараз використовуються кількома різними організаціями так отримали [публічні покращення](https://github.com/gds-operations/unicornherder/commits/master).

На практиці, під відкритим доступом мається на увазі:

- Вивантаження программного коду та документації до публічних Open Source серверів;
- Постійне оновлення коду з змінами котрі ви зробили (або прийдяли від інших людей);
- FIXME: putting in place [appropriate information security assurance to reduce and mitigate the risk of an exploit appearing in publicly-viewable software](/making-software/information-security).

> Помістіть ‘master’ версію вашого программне забезпечення на внутрішній сервер, та дублюйте останню версію на публічні репозиторії.



Причини не відкривати программне забезпечення
-----------------------------
Інколи неможливо підкривати программне забезпечення що розроблене для уряду третьою стороною, тому що третя сторона зберігає право власності на інтелектуальну власність закладенних в це программне забезпечення.

Тож, при співпрацці з третьою стороною уникайте контракти які:

- дозволяють третій стороні залишити право власності на программне забезпечення що було розробленно для уряду;
- забороняють уряду можливість відкрити программне забезпечення за, GPL-сумісною ліцензією з відкритим программне забезпечення.

В інших випадках команда має прийняти ймовірність неможливості відкриття деякіх программних рішень, котрі вони створили, наприклад щоб уникнути розкриття критичних деталей алгоритмів або процессів шірокій публіці.

Це гарна інженерна практика відокпемлювати программне забезпечення, та часто в цій ситуації велика кількість программне забезпечення всеодно може бути відкрита для публіки.



<!--
CESG
----
The default assumption should be in favour of coding in the open and sharing software widely. But if you have serious concerns about sharing source code in public, then CESG can provide you with advice based on your specific situation. See also the joint Cabinet Office / CESG statement on [Open Source Software and Security](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/78967/OSS_Toolkit_Security_Note_v1.0.pdf).
-->


Комерційне або программне забезпечення з відкритим кодом?
--------------------------
FIXME:
<!-- З ростом безкоштовного программного забезпечення, та програмного забезпечення з відкритим кодом, багато високо технологічних продуктів (бази данних, операційні системи, мови программування, інструменти для розробки та інші)... -->
With the growth of free/open source software, many high quality technology products (databases, operating systems, programming languages, development tools, etc) are freely available for government and its suppliers to use and improve.

Yet a large market still exists for commercial software products, and the availability of open source software doesn’t automatically mean that you can’t choose a proprietary technology if it meets your needs.

Still, the policy of government is that open source will be selected on the basis of its inherent flexibility. This is norm when there is no significant overall difference to cost between open and non-open source products that fulfil minimum and essential capabilities.

For more information on how to make sure there’s a level playing field between proprietary and open source software, see the:

- open source procurement toolkit;
- section of this manual covering the use of open standards.

> Make sure that any decision to use existing software, whether open source or proprietary, doesn’t stop you from sharing new software created under a permissive, GPL-compatible open source licence.



Coding in the open
------------------
A successful open source project will collect contributions from a large number of sources, both inside and outside of a single organisation. Allow developers time to review contributions, and answer issues and discussions raised by others using the software.

Make sure developers have:

- the ability to install and experiment with open source software;
- environments to easily publish prototype services on the web;
- convenient access to a wide variety of network connected devices for testing websites;
- unrestricted access to collaboration tools like [GitHub](https://github.com/), [Stack Overflow](https://stackoverflow.com/) and [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat).

Larger open source projects often develop an extension model that makes it possible for others to continue to use the service in a variety of often unexpected and possibly undesirable ways whilst keeping the core project coherent under the editorship of a small, trusted group of [committers](https://en.wikipedia.org/wiki/Committer).

Take every opportunity to contribute back to the open source projects you use, which can be in the form of:

- source code
- patches
- bug reports
- feature requests
- sponsorship of developers and support staff
- engaging in community discussion groups
- giving public attribution to projects

Cite the open source code you use, as in the [GOV.UK colophon](https://gds.blog.gov.uk/govuk-launch-colophon/) – you can read more about this approach on the [GDS blog entry about coding in the open](https://gds.blog.gov.uk/2012/10/12/coding-in-the-open/).



Security
--------
Keys, passwords and other secrets must always be stored safely and securely away from source code [following Kerckhoffs’s principle](https://en.wikipedia.org/wiki/Kerckhoffs%27s_principle). This separation of project code from deployed instances of a project is good development practice regardless of whether or not the software itself is shared in public.

It’s advisable for large, significant projects to have a private space to discuss security issues and develop a patch. This removes the risk of flagging a vulnerability before a fix has been deployed. This is especially advisable if there’s a small number of participating developers.



Why GDS do this
---------------
Choosing technology is important, but it’s probably not quite as important as you think. What’s important are the users of that technology and being able to produce quality at a sustainable pace and suitable cost. When making technology choices, and importantly as you develop your product and constantly reassess your selections, try and make decisions that:

- maximise developer productivity;
- minimise total cost of ownership;
- avoid lock-in;
- make it easy for the government to share software that it creates.



Further reading
------
[Open standards considerations](/service-manual/making-software/open-standards-and-licensing.html)
