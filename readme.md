## Вступ

Шаблони проектування це рішенням для повторюваних проблем; рекомендації щодо вирішення певних проблем. Це не класи, пакети чи бібліотеки які ви можете підключити до своєї програми та чекати що "станеться магія". Це, швидше, вказівки щодо того, як вирішувати певні проблеми в певних ситуація. 

## Будьте обережними

- Дизайн-патерни не вирішать всіх ваших проблем.
- Не намагайтеся використовувати їх примусово.
- Майте на увазі що дизайн-патерни є рішеннями до проблем, а не рішеннями у пошуку проблем; тож не обдумуйте надмірно.
- При правильному використанні та у правильних випадках вони можуть виявитися рятівником; інакше вони можуть призвести до жахливого безладу у коді.

> Також зверніть увагу що наведені нижче приклади використовують PHP 7, однак це не повинно вас зупиняти, оскільки концепції всеодно однакові.


## Типи дизайн-патернів

- Породжуючі
- Структурні
- Поведінкові

## Породжуючі патерни

> Породжуючі патерни сфокусовані на те як створити екземпляр об'єкта або групи пов'язаних об'єктів.

### Проста фабрика

Приклад з реального світу

> Уявіть, що ви будуєте будинок і вам потрібні двері. Ви можете надіти свій теслярський одяг, принести трохи дерева, клею, цвяхів та всіх інструментів, необхідних для побудови дверей і почати їх будівництво в себе вдома, або можете просто зателефонувати на завод який доставить вам готові двері, щоб у вас не було потрібно нічого дізнаватися про виготовлення дверей.

Простими словами

> Проста фабрика генерує екземпляр для клієнта, не відкриваючи клієнту жодної логіки щодо створення екземпляра.

Приклад коду

Перш за все, ми маємо інтерфейс дверей та його реалізацію

```php

```