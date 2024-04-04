# goit-algo-hw-07

## Розробіть систему для управління адресною книгою.

### Сутності:

1. **Field**: *Базовий клас для полів запису.*
2. **Name**: *Клас для зберігання імені контакту. Обов'язкове поле.*
3. **Phone**: *Клас для зберігання номера телефону. Має валідацію формату (10 цифр).*
4. **Record**: *Клас для зберігання інформації про контакт, включаючи ім'я та список телефонів.*
5. **AddressBook**: *Клас для зберігання та управління записами.*

### Функціональність:

AddressBook:
- Додавання записів.

`add Den 0504541223`

`add Den +380504541223`

- Вивід усіх запиів.

`all`

- Пошук записів за іменем.

`contact Den`

- Видалення записів за іменем.

`del Den`

- Збереження у файл.

`load`

- Завантаження з файлу.

`save`

Record:
- Додавання телефонів.

`addphone Den +380671232323`

`addphone Den 0671232323`

- Видалення телефонів.

`delphone Den +380671232323`

`delphone Den 0671232323`

- Редагування телефонів.

`change Den 0671232323 0681232399`

`change Den +380671232323 +380681232399`

- Пошук телефону.

`phone 0671232323`

`phone +380671232323`
