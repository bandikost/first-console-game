# RPG-битва с инвентарем и системой прогрессии

**Этот проект реализует консольную игру в жанре RPG**, где игрок управляет персонажем, сражается с монстрами, собирает опыт и золото, а также улучшает свои характеристики и инвентарь. В проекте представлены механики прокачки персонажа, покупки и продажи предметов, а также симуляции пошаговых сражений. Все события сопровождаются текстовыми описаниями, создающими атмосферу приключений в фантазийном мире.

## 🛠 Основные возможности

- **Персонажи**: Три разных персонажа — Огр, Незнакомец и Гоблин. Каждый обладает уникальными характеристиками: уровень, здоровье, опыт, золото и базовый урон.
- **Система сражений**: Пошаговые бои с динамическим отображением урона, здоровья и опыта, полученного за победы.
- **Прокачка уровня**: Персонажи накапливают опыт за победы, что позволяет им повышать уровень и улучшать характеристики.
- **Магазин предметов**: Возможность покупки оружия для усиления урона, управление инвентарем и продажа предметов за золото.
- **Инвентарь и продажа предметов**: Отслеживание купленных предметов с возможностью их продажи за половину стоимости.
- **Динамическое повествование**: Диалоги и текстовые описания добавляют атмосферу и погружают в фантазийный мир игры.

## 🚀 Использование

### Старт игры
При запуске игры вы оказываетесь в пещере, где персонажи вступают в диалоги, после чего начинаются пошаговые сражения.

### Сражения
Персонажи обмениваются ударами до тех пор, пока здоровье одного из них не иссякнет. За каждую победу вы получаете опыт и золото, которые можно использовать для улучшения характеристик.

### Инвентарь и магазин
Магазин позволяет покупать различные виды оружия для усиления базового урона персонажа. Также можно продавать предметы за золото.

## 💻 Пример использования

```csharp
// Создаем персонажа "Незнакомец" и начинаем серию сражений
Characters stranger = new Person2();
Battle battle = new Battle(stranger, new Person1()); 
await battle.Start();
```
📋 Требования<br>
  .NET Core 5.0 и выше<br>

📄 Лицензия<br>
  Проект распространяется под лицензией <a href="[https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt](https://github.com/bandikost/first-console-game?tab=MIT-1-ov-file)">MIT License.</a>
