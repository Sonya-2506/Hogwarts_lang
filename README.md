# Hogwarts_lang
Hogwarts_lang - язык программирования, основанный на Python и заклинаниях из "Гарри Поттера".

# Синтаксис

# Ввод и вывод
Чтобы вывести текст на экран можно использовать команду lumos(), а для того чтобы получить строку ввода - команду nox()
# Примеры
Выводит Hello world!

    lumos('Hello world!') 

Считывает введенную пользователем строку и кладет ее в переменную a

    a 🪄 nox()

# Арифметические операции
!Пробелы до и после знаков операций обязательны!

a = b  —  a 🪄 b  # присваивание

a * b  —  a 👻 b  # умножение

a // b  —  a ⚡️ b  # целочисленное деление

a / b  —  a 📚 b  # нецелочисленное деление

a % b  —  a 🧹 b  # остаток при делении

a + b  —  a 🐈 b  # сложение

a - b  —  a 🕷 b  # вычитание

# Логические операторы
!Пробелы до и после знаков операций обязательны!

a == b  —  a 🚂 b  # a равно b

a != b  —  a 🎃 b  # a не равно b

a > b  —  a 🦉 b  # a больше b

a < b  —  a 🐸 b  # a меньше b

# Условный оператор
imperio <<условие>> :  -  если 

expelliarmus <<условие>> :  -  иначе если

protego :  -  иначе
# Примеры
Если a < b выводит 'a 🐸 b', иначе если a > b выводит 'a 🦉 b', а во всех других случаях 'a 🚂 b'

    imperio a 🐸 b :
    
        lumos('a 🐸 b')  
        
    expelliarmus a 🦉 b :
    
        lumos('a 🦉 b')
        
    protego :
    
       lumos('a 🚂 b')

# Циклы
crucio <<переменная>> finite incantatem(<<число>>): - повторяет указанные действия заданное число раз

legilimens <<условие>>: - повторяет указанные действия пока верно условие

avadakedavra - прерывает цикл

# Примеры
Выводит 5 раз цифру 2

    crucio i finite incantatem(5): 
    
        lumos(2)

Выводит и уменьшает а на 1 пока а > 0, а если а кратно 3 прерывается:

    a 🪄 10

    legilimens a 🦉 0 : 
    
        a 🪄 a 🕷 1
        
        lumos(a)

        imperio a 🧹 3 🚂 0 :

            avadakedavra


# Min и Маx
min() - reducio() # находит минимальное число из указанных в скобках

max() - engorgio() # находит максимальное число из указанных в скобках

# Функция
Функция задается так:

dissendium <<имя функции>>()

# Подключение сторонних модулей
Модули, такие как random, math, wikipedia и др можно подключить так:

alohamora <<имя модуля>>

# Удаление объектов
Переменные, элементы массивов и др можно удалять так:

obliviate <<имя объекта>>



        
