# Header
Path `config.yml > module.server.tab.header`

## Explanation
Module for text at top of TAB
![header](/header.png)

## Edit
```yaml
<config.module.server.tab.header>
```

### Default
```yaml
header:
  enable: true
  random: true
  permission:
    name: "flectonepulse.module.server.tab.header"
    type: TRUE
  ticker:
    enable: true
    period: 100
```

## Options

- Message changes here [Header](/en/messages/en_us/module/server/tab/header/)

### `enable`
- Default `true`

Enables or disables the functionality of the module

### `random`
- Default `true`

If enabled, message will be selected randomly, otherwise in order

### `permission`
- Name `flectonepulse.module.server.tab.header`
- Type `TRUE`

[Permission](/en/config/module/#explanation) to use the module

### `ticker`
- `enable: true`

Whether message needs to be updated once every certain period of time

- `period: 100`

How often the name in [ticks](https://minecraft.wiki/w/Tick) needs to be updated