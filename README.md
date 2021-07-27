![Desktop CI](https://github.com/EvilBeaver/sleeper-1c/workflows/Desktop%20CI/badge.svg)
![Mobile CI](https://github.com/EvilBeaver/sleeper-1c/workflows/Mobile%20CI/badge.svg)

# Та самая Пауза в платформе 1С:Предприятие 8

Внешняя компонента для метода Пауза в платформе 1С:Предприятие 8.
Решение целиком и полностью основано на плагине от @Infactum и, по-сути, является им же (просто удалены ненужные методы).

## Использование

```bsl
ПодключитьВнешнююКомпоненту("ОбщийМакет.Sleeper", "Sleeper", ТипВнешнейКомпоненты.Native);
Паузятор = Новый("AddIn.Sleeper.Sleep");
Паузятор.Приостановить(3000);
// english version
Sleeper = Паузятор;
Sleeper.Sleep(3000);
```

## Supported platforms

*Infactum says it's true, then it's true*

✔ Windows  
✔ Linux  
⚠ MacOS (compiled but not tested)  
✔ Android  
❌ iOS  
❌ Browser Extenstions

## License exclusions

In case of embedding add-in based on this template inside 1C:Enterprise configuations, external processors, configuration extensions etc, it's allowed not to apply AGPL terms to whole application part, but only add-in itself.
