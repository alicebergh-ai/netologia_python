
help = ("""help - помощь
add - добавить задачу
show - показать список задач
exit - выход""")


today = []
tomorrow = []
other = []
run = True
print("Доступные команды: help, add, show, exit")

while run :
    command = input("Введите команду: ")

    if command == 'help':
        print(help)

    elif command == 'add':
        data = input("Введите дату(сегодня, завтра, другое): ")
        todo = input("Напишите задачу: ")
        if data == 'сегодня':
            today.append(todo)
            print(f"Задача {todo} добавлена!")
        elif data == 'завтра':
            tomorrow.append(todo)
            print(f"Задача {todo} добавлена!")
        elif data == 'другое':
            other.append(todo)
            print(f"Задача {todo} добавлена!")
        else:
            print("Некорректное значение даты!")


    elif command == 'show':
        print("Сегодня")
        print(today)
        print("Завтра")
        print(tomorrow)
        print("Другое")
        print(other)

    elif command == 'exit':
        run = False

    else:
        print( "Вы ввели некорректную команду")

print("До свидания")
