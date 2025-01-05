# Упоминание
Путь `permission.yml > message.format.mention`

## Пояснение
Категория, отвечающая за настройку прав у форматирования упоминаний в сообщениях игрока

## Редактирование
```yaml
<permission.message.format.mention>
```

### По умолчанию
```yaml
mention:
  name: "flectonepulse.module.message.format.mention"
  type: TRUE
  bypass:
    name: "flectonepulse.module.message.format.mention.bypass"
    type: OP
  sound:
    name: "flectonepulse.module.message.format.mention.sound"
    type: TRUE
```

## Параметры

- [Сообщения](/docs/message/format/mention/)
- [Локализация](/docs/localizations/ru_ru/message/format/mention/)

<!--@include: @/parts/permission/permissionTier3.md-->

### `bypass`

Право для игнорирования упоминания

::: details Настройка
<!--@include: @/parts/permission/permissionTier4.md-->
:::

<!--@include: @/parts/permission/sound.md-->
