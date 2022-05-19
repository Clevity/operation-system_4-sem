# KTSO-04-20-Vantsov-D.A.-Network-operating-systems

## Лекторные материалы
В данном проекте находятся коды программ с лекций. Для каждой лекции была создана отдельная папка. Коды программ могут быть скомпилированы с помощью *makefile* или же вручную с помощью  *gcc compiler*. Также для каждой программы был собран установочный *deb-пакет*, который устанавливает ее в выбранную директорию. 

Для ручной установки программ, необходимо открыть через консоль директорию, в которой хранится код программы, и вызвать компилятор с помощью команды gcc `LecN/ProgramN/main.c -o LecN/ProgramN/main.out`

Также для установки можно использовать *makefile*. Для этого вам необходимо находиться в корне репрозитория. С помощью команды `makeLN`, _где L - номер лекции, N - номер программы_, можно скомпилировать каждую программу в отдельности. 

В репозитории есть директория _Deb-pockets_ , в которой хранятся установочные пакеты, которые устанавливают программы в выбранную директорию. 

Данные программы могут быть установлены на семейство Unix-подобных операционных систем.
