start
? Вывод таблицы умножения для числа 1

new base number
set base 1
new multiplier number
set multiplier 1

loop table (10 >= multiplier)
    log string base >> " x " >> multiplier >> " = " >> base * multiplier ? Убраны лишние скобки
    set multiplier multiplier + 1
end table

finish
