# Random Data Generator

### Это задание Горбанёва Валерия по CS212(Ruby)
### Тема утверждена Горшковым Сергеем Андреевичем
Random Data Generator - это библиотека на Ruby для генерации случайных данных различных типов, таких как строки, числа, даты и многое другое

## Запуск и установка:

#### Перед использованием нужно установить bundle(!):
```ruby
bundle install
```

#### Запуск тестов:
```ruby
bundle exec rspec
```

#### Запуск вывода демонстрации вывода всех возможных методов:
```ruby
ruby src/demonstration.rb
```

## Пример использования библиотеки:

#### Подключение библиотеки
```ruby
require_relative '../lib/random_data_generator/address_generator'
require_relative '../lib/random_data_generator/other_generator'
require_relative '../lib/random_data_generator/social_generator'
require_relative '../lib/random_data_generator/string_generator'
```

#### Генерация случайной строки длиной 10 символов
```
puts RandomDataGenerator.random_string(10)
```

#### Генерация случайного числа в диапазоне от 1 до 100
```
puts RandomDataGenerator.random_number(1, 100)
```

#### Генерация случайной даты в диапазоне с 1 января 2020 по 31 декабря 2025
```
puts RandomDataGenerator.random_date(Date.new(2020, 1, 1), Date.new(2025, 12, 31))
```

### Дополнительные методы
#### Библиотека также предоставляет дополнительные методы для генерации случайных данных:

```RandomDataGenerator.random_alpha_numeric_string(length)``` генерирует случайную алфавитно-цифровую строку заданной длины

```RandomDataGenerator.random_letter_string(length)``` генерирует случайную строку буквенных символов заданной длины

```RandomDataGenerator.random_ip_address``` генерирует случайный IP-адрес

```RandomDataGenerator.random_email``` генерирует случайный адрес электронной почты

## Тесты и rubocop
![Screenshot 1](https://i.ibb.co/w6X64TB/photo-2024-04-25-21-10-48.jpg)

## Пример вывода
![Screenshot 2](https://i.ibb.co/jgFhbBM/photo-2024-04-25-21-12-08.jpg)

## Добавлены автоматические тесты в GitHub
![Screenshot 3](https://i.ibb.co/rGNkBcx/photo-2024-04-25-21-13-26.jpg)

