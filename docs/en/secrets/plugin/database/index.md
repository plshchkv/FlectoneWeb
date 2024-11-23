# База данных
Путь `secrets.yml > plugin.database`

## Пояснение
Эта категория отвечает за настройку доступа к базе данных

### По умолчанию
```yaml
database:
  name: "flectonepulse"
  host: "localhost"
  port: "3306"
  user: "root"
  password: "1234"
```

## Параметры

### `name`
- По умолчанию `flectonepulse`

Название базы данных

### `host`
- По умолчанию `localhost`

Адрес сервера, на котором расположена база данных

::: warning ПРЕДУПРЕЖДЕНИЕ
Настройка будет использоваться, если включен режим [MySQL](/en/config/plugin/#database)
:::

### `port`
- По умолчанию `3306`
Порт подключения к базе данных на сервере

::: warning ПРЕДУПРЕЖДЕНИЕ
Настройка будет использоваться, если включен режим [MySQL](/en/config/plugin/#database)
:::

### `user`
- По умолчанию `root`

Название пользователя, который будет использован для подключения к базе данных
::: warning ПРЕДУПРЕЖДЕНИЕ
Настройка будет использоваться, если включен режим [MySQL](/en/config/plugin/#database)
:::

### `password`
- По умолчанию `1234`

Пароль для подключения к базе данных
::: warning ПРЕДУПРЕЖДЕНИЕ
Настройка будет использоваться, если включен режим [MySQL](/en/config/plugin/#database)
:::

