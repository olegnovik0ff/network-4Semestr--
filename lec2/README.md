# ОПИСАНИЕ ПРОГРАММЫ
Сначала программа просит указать длину массива (8-9 строчки). После проверки на ввод, приложение выделяет память для массива (14ая сточка). Если по каким-либо причинам память не выделилась, функция malloc вернёт NULL, что программа и проверяет в той же строчке. После этого приложение выведет количество байтов, которое было выделено(18ая строчка). Если всё прошло успешно, программа очистит выделенную память (25-27 строчки).
# Отладка
oleg@oleg-virtual-machine:~ /Desktop/network-4Semestr/lec2$ ./a.out
Enter length of array: 24
Allocated 96 bytes
oleg@oleg-virtual-machine:~ /Desktop/network-4Semestr/lec2$ ./a.out
Enter length of array: -1
Error: can't allocate memory
oleg@oleg-virtual-machine:~ /Desktop/network-4Semestr/lec2$ ./a.out
Enter length of array: 100
Allocated 400 bytes
oleg@oleg-virtual-machine:~ /Desktop/network-4Semestr/lec2$ ./a.out
Enter length of array: -0
oleg@oleg-virtual-machine:~ /Desktop/network-4Semestr/lec2$ 
