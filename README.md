### This project create for BackLog issue in Android Development

#### Begin

1. Как сделать игнорирование Системных настроек Android шрифта

Нужно добавить в MainActivity в колбек attachBaseContext код:

'''Kotlin

var override = Configuration(newBase.resources.configuration)
override.fontScale = 1.0f
applyOverrideConfiguration(override)

'''