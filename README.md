### Build status:  [![Build status](https://ci.appveyor.com/api/projects/status/3urjcm3j2ivhupj4/branch/master?svg=true)](https://ci.appveyor.com/project/Sergius92739/ra-4-2-forms-steps/branch/master)


### Deployment:  <a href="https://sergius92739.github.io/ra-4.1-forms-steps/">Github Pages</a>

# Учёт тренировок

---

Вы решили реализовать небольшое приложение, которое хранит данные о тренировках (прогулках), которые вы совершаете в течение недели.

Общий интерфейс должен выглядеть следующим образом:

![Steps](./assets/steps.png)

## Добавление данных

У вас должна быть форма ввода в которую вводится дата и количество пройденных километров. Добавленные значения добавляются в таблицу при отправке формы.

_Особенности добавления_:
1. Новые значения добавляются не в конец, а согласно сортировке по дате, т.е. если мы добавим 21.07.2019, то значение встанет на первую позицию (согласно скриншоту), а если 17.07.2019 - то на последнюю
2. Если мы добавляем значения, указывая уже существующую дату, то значения суммируются с теми, что хранятся в таблице, например, если добавить 20.07.2019 и 10км, то для даты 20.07.2019 будет отображаться 15.7км

## Удаление данных

С помощью иконки ✘ должна быть возможность удалить строку. Удаляется вся строка целиком и данные, связанные с ней.

## Редактирование данных

Дополнительное (не обязательное) задание: вы можете реализовать кнопку редактирования ✎ - при нажатии на которую происходит перенос данных в форму ввода с последующим сохранением (при нажатии кнопки Ok).
