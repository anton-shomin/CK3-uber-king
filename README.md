English

# CK3 Cheat Mod: Overpowered Traits and Realm Buffs

## Description

This mod for Crusader Kings 3 introduces a set of powerful cheat traits and a realm-wide modifier, designed to give the player character and their realm significant advantages across various aspects of the game, including combat, economy, scheming, and character development. Use these cheats to make your playthroughs easier or simply to experiment with extreme bonuses.

## Features

The mod adds the following:

### Traits

These traits can be added to your character via in-game events (see usage instructions below). They are designed to be mutually exclusive with AI rulers to prevent the AI from gaining the same advantages.

- **`blessed_core_traits`**: A core set of significant character buffs.

  - Health: +8
  - Monthly Income: +35%
  - Character Travel Speed: +55
  - Stress Loss: +70% (multiplicative, meaning stress loss is significantly increased)
  - Parochial Opinion: +25
  - Enemy Hostile Scheme Success Chance: -80%
  - Personal Scheme Power: +85% (multiplicative)
  - Enemy Hard Casualty Modifier: +75%
  - No Water Crossing Penalty: Yes
  - Build Speed: -30% (faster building)
  - Holding Build Speed: -30% (faster building)
  - Build Gold Cost: -91% (cheaper building)
  - Holding Build Gold Cost: -91% (cheaper building)
  - Attraction Opinion: +80
  - No Prowess Loss from Age: Yes
  - Stress Gain: -100% (no stress gain)
  - **Massive Scheme Boosts**:
    - Scheme Power: +1000
    - Scheme Resistance: +1000
    - Scheme Secrecy: +1000
    - Scheme Success Chance: +1000%
    - Hostile Scheme Power (Mult/Add): +1000% / +1000
    - Personal Scheme Power (Mult/Add): +1000% / +1000
    - Hostile Scheme Resistance: +1000%
    - Diplomacy Scheme Power: +1000
    - Intrigue Scheme Power: +1000
    - Scheme Discovery Chance: +1000%
    - Max Personal Schemes: +10
    - Max Hostile Schemes: +10
    - Owned Hostile/Personal Scheme Success Chance: +1000%
    - Enemy Personal/Hostile Scheme Success Chance: -1000%
    - Murder, Abduct, Befriend, Claim Throne, Convert to Witchcraft, Courting, Elope, Fabricate Hook, Seduce, Sway Scheme Power (Mult/Add): +1000% / +1000

- **`warfare_genius`**: Focused on massive military and levy enhancements for the ruler.

  - Mercenary Hire Cost: -90%
  - Levy Size: +100%
  - Levy Reinforcement Rate: +10000% (across all types and territories)
  - Knight Effectiveness: +10000%
  - Men-at-Arms Limit: +50000

- **`combat_genious`**: Provides extreme combat bonuses for a character, typically used as a commander trait (though the event applies it to the player character).
  - Hard Casualty Modifier: -99%
  - Enemy Hard Casualty Modifier: +31%
  - Garrison Size: +300%
  - Supply Duration: +600%
  - Siege Phase Time: -80% (faster sieges)
  - Supply Limit/Capacity: +100%
  - Additional Fort Level: +21
  - Siege Morale Loss: +100%
  - Retreat Losses: -100%
  - Raid Speed: +100%
  - Minimum Combat Roll: +20
  - Maximum Combat Roll: +40
  - Siege Weapon Max Size: +300%
  - Hostile County Attrition: -100%
  - Defender Advantage: +100
  - Attacker Advantage: +100
  - **Terrain Mastery**: +50 Advantage in Forest, Taiga, Hills, Jungle, Plains, Farmlands, Mountains, Desert, Desert Mountains, Oasis, and against enemy terrain advantage.
  - Movement Speed: +150%
  - Naval Movement Speed: +100%
  - **Extreme Unit Boosts**: +10000% Toughness, +700% Damage, +400 Pursuit, +100 Screen for Light Cavalry, Heavy Cavalry, Archer Cavalry, Archers, Skirmishers, Pikemen, Heavy Infantry, Crossbowmen, Siege Weapons, Camel Cavalry, and Elephant Cavalry.

### Realm Modifier

This modifier applies powerful combat and logistical bonuses across your entire realm.

- **`combat_genius_realm`**:
  - Hard Casualty Modifier: -99%
  - Enemy Hard Casualty Modifier: +31%
  - Garrison Size: +300%
  - Supply Duration: +600%
  - Siege Phase Time: -80%
  - Supply Limit/Capacity: +100%
  - Additional Fort Level: +21
  - Siege Morale Loss: +100%
  - Retreat Losses: -100%
  - Raid Speed: +100%
  - Hostile County Attrition: -100%
  - Movement Speed: +150%
  - Naval Movement Speed: +100%
  - Generic Army Damage: +700%
  - Generic Army Toughness: +1000%
  - Generic Army Pursuit: +400
  - Generic Army Screen: +100
  - Generic Army Siege Value: +50%
  - Defender Advantage: +100
  - Attacker Advantage: +100

## Usage

The traits and realm modifier are applied and removed via special in-game events.

1.  Ensure the mod is installed and enabled in the Crusader Kings 3 launcher.
2.  Start or load a game.
3.  Open the in-game debug console. This usually requires launching the game with `-debug_mode`. The console is typically opened by pressing the `~` or `` ` `` key.
4.  Use the `event` command followed by the event ID to trigger the desired effect.

- **To manage `blessed_core_traits`:**

  - To add the trait: `event blessed_traits.0001`
  - To remove the trait: Use the event again and select the remove option.

- **To manage `warfare_genius`:**

  - To add the trait: `event cheat_warfare_genious_traits.0001`
  - To remove the trait: Use the event again and select the remove option.

- **To manage `combat_genious`:**

  - To add the trait: `event cheat_combat_genious_traits.0001`
  - To remove the trait: Use the event again and select the remove option.

- **To manage the `combat_genius_realm` modifier:**
  - To add the realm modifier (lasts for 100 years by default, can be permanent if `years = 100` is changed to `duration = -1` in the mod files): `event cheat_combat_genius_realm.0001`
  - To remove the realm modifier: Use the event again and select the remove option.

When you trigger an event, an in-game notification will appear allowing you to choose whether to add or remove the associated trait or realm modifier.

## Installation

(Standard Crusader Kings 3 mod installation instructions - usually involves placing the mod folder in the `mod` directory in your Crusader Kings 3 user files and enabling it in the launcher.)

## Compatibility

This mod modifies traits, realm modifiers, and adds new events. It may conflict with other mods that heavily alter these same aspects of the game.

## Disclaimer

This mod is intended for cheating and experimentation. It is not balanced for a regular playthrough and will trivialize most challenges.

---

Russian

# Чит-мод для CK3: Сверхумные черты характера и бонусы для державы

## Описание

Этот мод для Crusader Kings 3 добавляет набор мощных читерских черт характера и модификатор для всей державы, разработанные, чтобы дать игровому персонажу и его владениям значительные преимущества в различных аспектах игры, включая бой, экономику, интриги и развитие персонажа. Используйте эти читы, чтобы упростить прохождения или просто поэкспериментировать с экстремальными бонусами.

## Возможности

Мод добавляет следующее:

### Черты характера

Эти черты характера могут быть добавлены вашему персонажу через внутриигровые события (см. инструкции по использованию ниже). Они разработаны так, чтобы быть взаимоисключающими с правителями ИИ, чтобы предотвратить получение ИИ тех же преимуществ.

- **`blessed_core_traits`**: Основной набор значительных усилений персонажа.

  - Здоровье: +8
  - Ежемесячный доход: +35%
  - Скорость перемещения персонажа: +55
  - Потеря стресса: +70% (мультипликативный, что означает значительное увеличение потери стресса)
  - Мнение окружающих: +25
  - Шанс успеха враждебных интриг противника: -80%
  - Мощь личных интриг: +85% (мультипликативный)
  - Модификатор тяжелых потерь противника: +75%
  - Отсутствие штрафа при переправе через воду: Да
  - Скорость строительства: -30% (более быстрое строительство)
  - Скорость строительства владений: -30% (более быстрое строительство)
  - Стоимость строительства (золото): -91% (более дешевое строительство)
  - Стоимость строительства владений (золото): -91% (более дешевое строительство)
  - Мнение от привлекательности: +80
  - Отсутствие потери доблести от возраста: Да
  - Получение стресса: -100% (отсутствие получения стресса)
  - **Огромные усиления интриг**:
    - Мощь интриг: +1000
    - Сопротивление интригам: +1000
    - Секретность интриг: +1000
    - Шанс успеха интриг: +1000%
    - Мощь враждебных интриг (мульт/доп): +1000% / +1000
    - Мощь личных интриг (мульт/доп): +1000% / +1000
    - Сопротивление враждебным интригам: +1000%
    - Мощь дипломатических интриг: +1000
    - Мощь интриг в интриге: +1000
    - Шанс обнаружения интриги: +1000%
    - Макс. личных интриг: +10
    - Макс. враждебных интриг: +10
    - Шанс успеха собственных враждебных/личных интриг: +1000%
    - Шанс успеха вражеских личных/враждебных интриг: -1000%
    - Мощь интриг убийства, похищения, дружбы, претензии на трон, обращения в колдовство, ухаживания, побега, фабрикации крюка, соблазнения, расположения (мульт/доп): +1000% / +1000

- **`warfare_genius`**: Сфокусирован на массивных военных усилениях и усилениях ополчения для правителя.

  - Стоимость найма наемников: -90%
  - Размер ополчения: +100%
  - Скорость пополнения ополчения: +10000% (для всех типов и территорий)
  - Эффективность рыцарей: +10000%
  - Лимит отрядов: +50000

- **`combat_genious`**: Предоставляет экстремальные боевые бонусы для персонажа, обычно используется как черта командующего (хотя событие применяет ее к игровому персонажу).
  - Модификатор тяжелых потерь: -99%
  - Модификатор тяжелых потерь противника: +31%
  - Размер гарнизона: +300%
  - Длительность снабжения: +600%
  - Время фазы осады: -80% (более быстрые осады)
  - Лимит/вместимость снабжения: +100%
  - Дополнительный уровень форта: +21
  - Потеря боевого духа при осаде: +100%
  - Потери при отступлении: -100%
  - Скорость набега: +100%
  - Минимальный бросок в бою: +20
  - Максимальный бросок в бою: +40
  - Максимальный размер осадного оружия: +300%
  - Истощение во враждебных графствах: -100%
  - Преимущество защитника: +100
  - Преимущество атакующего: +100
  - **Мастерство местности**: +50 Преимущества в лесах, тайге, холмах, джунглях, равнинах, пахотных землях, горах, пустыне, пустынных горах, оазисах и против преимущества вражеской местности.
  - Скорость перемещения: +150%
  - Скорость морского перемещения: +100%
  - **Экстремальные усиления юнитов**: +10000% Стойкости, +700% Урона, +400 Преследования, +100 Скрытности для легкой кавалерии, тяжелой кавалерии, конных лучников, лучников, застрельщиков, пикейщиков, тяжелой пехоты, арбалетчиков, осадных орудий, верблюжьей кавалерии и слоновьей кавалерии.

### Модификатор державы

Этот модификатор применяет мощные боевые и логистические бонусы ко всей вашей державе.

- **`combat_genius_realm`**:
  - Модификатор тяжелых потерь: -99%
  - Модификатор тяжелых потерь противника: +31%
  - Размер гарнизона: +300%
  - Длительность снабжения: +600%
  - Время фазы осады: -80%
  - Лимит/вместимость снабжения: +100%
  - Дополнительный уровень форта: +21
  - Потеря боевого духа при осаде: +100%
  - Потери при отступлении: -100%
  - Скорость набега: +100%
  - Истощение во враждебных графствах: -100%
  - Скорость перемещения: +150%
  - Скорость морского перемещения: +100%
  - Общий урон армии: +700%
  - Общая стойкость армии: +1000%
  - Общее преследование армии: +400
  - Общая скрытность армии: +100
  - Общая ценность осадных орудий армии: +50%
  - Преимущество защитника: +100
  - Преимущество атакующего: +100

## Использование

Черты характера и модификатор державы применяются и удаляются с помощью специальных внутриигровых событий.

1.  Убедитесь, что мод установлен и включен в лаунчере Crusader Kings 3.
2.  Начните или загрузите игру.
3.  Откройте внутриигровую отладочную консоль. Обычно для этого требуется запустить игру с параметром `-debug_mode`. Консоль обычно открывается нажатием клавиши `~` или `` ` ``.
4.  Используйте команду `event` с последующим ID события, чтобы вызвать желаемый эффект.

- **Для управления `blessed_core_traits`**:

  - Чтобы добавить черту: `event blessed_traits.0001`
  - Чтобы удалить черту: Используйте событие снова и выберите опцию удаления.

- **Для управления `warfare_genius`**:

  - Чтобы добавить черту: `event cheat_warfare_genious_traits.0001`
  - Чтобы удалить черту: Используйте событие снова и выберите опцию удаления.

- **Для управления `combat_genious`**:

  - Чтобы добавить черту: `event cheat_combat_genious_traits.0001`
  - Чтобы удалить черту: Используйте событие снова и выберите опцию удаления.

- **Для управления модификатором державы `combat_genius_realm`**:
  - Чтобы добавить модификатор державы (длится 100 лет по умолчанию, может быть постоянным, если в файлах мода изменить `years = 100` на `duration = -1`): `event cheat_combat_genius_realm.0001`
  - Чтобы удалить модификатор державы: Используйте событие снова и выберите опцию удаления.

При запуске события появится внутриигровое уведомление, позволяющее вам выбрать, добавить или удалить связанную черту или модификатор державы.

## Установка

(Стандартные инструкции по установке модов Crusader Kings 3 - обычно включают размещение папки мода в директории `mod` в пользовательских файлах Crusader Kings 3 и включение его в лаунчере.)

## Совместимость

Этот мод изменяет черты характера, модификаторы державы и добавляет новые события. Он может конфликтовать с другими модами, которые сильно изменяют те же аспекты игры.

## Отказ от ответственности

Этот мод предназначен для читерства и экспериментов. Он не сбалансирован для обычного прохождения и существенно упростит большинство испытаний.
