# SI_2025_lab2_211074
Име: Marija Stojoska  
Број на индекс: 211074
### Control Flow Graph (CFG)
![CFG diagram](CFG_checkCart.drawio.png)
### Statement Coverage

Потребни се минимум **3 тест случаи** за да се покријат сите statements во функцијата.

#### Тест случај 1
Влез: `null, "1234567812345678"`  
Излез: Исклучок – "allItems list can't be null!"

#### Тест случај 2
Влез: `[Item(null, 1, 100, 0)], "1234567812345678"`  
Излез: Исклучок – "Invalid item!"

#### Тест случај 3
Влез: `[Item("Телевизор", 1, 400, 0.1)], "1234567812345678"`  
Излез: 330.0
