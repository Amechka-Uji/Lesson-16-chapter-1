start
? Создание схематичного дизайна банковской карты с переменными

? Объявление переменных
new card_number string
new card_holder string
new expiry_date string
new cvv number

? Установка значений
set card_number "••••  ••••  ••••  5678"
set card_holder "IVAN  PETROV"
set expiry_date "12/30"
set cvv 921

? Вывод дизайна карты


log string "      CREDIT CARD DESIGN        "
log string "  Номер: " >> card_number >> "    "
log string "  Держатель: " >> card_holder >> "      *"
log string "  Срок: " >> expiry_date >> "           *"
log string "  CVV: ***                     "

finish
