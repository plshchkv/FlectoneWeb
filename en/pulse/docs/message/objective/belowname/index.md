# Под ником
Путь `message.yml > objective.belowname`

## Пояснение
[ScoreBoard значение](https://ru.minecraft.wiki/w/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D1%81%D1%87%D1%91%D1%82%D0%B0_%D0%B8%D0%B3%D1%80%D0%BE%D0%B2%D1%8B%D1%85_%D1%81%D0%BE%D0%B1%D1%8B%D1%82%D0%B8%D0%B9) игрока под его ником
![below name](/belowname.png)

## Редактирование
```yaml
<message.objective.belowname>
```

### По умолчанию
```yaml
belowname:
  enable: false
  mode: PING
  ticker:
    enable: true
    period: 100
```

## Параметры

- [Права](/docs/permission/message/objective/belowname/)

<!--@include: @/parts/enable.md-->

### `mode`
- По умолчанию `PING`

Режим цифрового отображения значения из доступных

<!--@include: @/parts/objective.md-->

::: tip Например режим `PING`
Значит будет возвращаться пинг игрока
![below name](/belowname.png)
:::

<!--@include: @/parts/ticker.md-->

