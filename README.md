# parallel_lab1


#**O/I**

| n \ Threads | 1 | 5 | 10 | 20 | 30 | 40 | 50 |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| **300** | 5.3377 | 1.1187 | 0.6749 | 0.5912 | 0.5407 | 0.5841 | 0.6484 |
| **400** | 6.8230 | 1.4468 | 0.9187 | 0.7480 | 0.7942 | 0.7062 | 0.7222 |
| **500** | 5.9601 | 1.7466 | 0.7303 | 0.8157 | 0.7501 | 0.5973 | 0.8371 |

#**CPU bound**
**monte carlo**

*--- Total points = 50000 ---*

Processes =  1 | pi ≈ 3.129040 | time = 1.2417s

Processes =  2 | pi ≈ 3.126480 | time = 1.0297s

Processes =  4 | pi ≈ 3.151200 | time = 1.0899s

Processes =  8 | pi ≈ 3.138000 | time = 1.1854s

Processes = 16 | pi ≈ 3.138240 | time = 1.7027s

*--- Total points = 500000 ---*

Processes =  1 | pi ≈ 3.142352 | time = 3.9234s

Processes =  2 | pi ≈ 3.140072 | time = 2.1215s

Processes =  4 | pi ≈ 3.143480 | time = 1.7402s

Processes =  8 | pi ≈ 3.143264 | time = 1.5780s

Processes = 16 | pi ≈ 3.140488 | time = 1.6782s

*--- Total points = 2000000 ---*

Processes =  1 | pi ≈ 3.140648 | time = 10.9432s

Processes =  2 | pi ≈ 3.142068 | time = 6.5871s

Processes =  4 | pi ≈ 3.143560 | time = 4.1543s

Processes =  8 | pi ≈ 3.142344 | time = 2.7560s

Processes = 16 | pi ≈ 3.143432 | time = 2.5523s

**prime**

 *for 1000000*

Running with 1 processes...
Processes =  1 | Primes found = 78498 | time = 2.79851s

Running with 2 processes...
Processes =  2 | Primes found = 78498 | time = 2.13844s

Running with 4 processes...
Processes =  4 | Primes found = 78498 | time = 1.74579s

Running with 8 processes...
Processes =  8 | Primes found = 78498 | time = 1.53832s

Running with 16 processes...
Processes = 16 | Primes found = 78498 | time = 1.47524s

 *for 2000000*

Running with 1 processes...
Processes =  1 | Primes found = 148933 | time = 6.50157s

Running with 2 processes...
Processes =  2 | Primes found = 148933 | time = 3.48889s

Running with 4 processes...
Processes =  4 | Primes found = 148933 | time = 2.52038s

Running with 8 processes...
Processes =  8 | Primes found = 148933 | time = 1.80793s

Running with 16 processes...
Processes = 16 | Primes found = 148933 | time = 1.85654s

 *for 3000000*
 
Running with 1 processes...
Processes =  1 | Primes found = 216816 | time = 9.65436s

Running with 2 processes...
Processes =  2 | Primes found = 216816 | time = 5.48571s

Running with 4 processes...
Processes =  4 | Primes found = 216816 | time = 3.55816s

Running with 8 processes...
Processes =  8 | Primes found = 216816 | time = 2.68222s

Running with 16 processes...
Processes = 16 | Primes found = 216816 | time = 2.35537s

**factorization**

*--- Factorizing 12345678 ---*

Processes =  1 | Factors found = 24 | time = 1.12541s

Processes =  2 | Factors found = 24 | time = 0.62423s

Processes =  4 | Factors found = 24 | time = 0.51730s

Processes =  8 | Factors found = 24 | time = 0.54806s

Processes = 16 | Factors found = 24 | time = 0.78451s

*--- Factorizing 123456789 ---*

Processes =  1 | Factors found = 12 | time = 6.82080s

Processes =  2 | Factors found = 12 | time = 3.06447s

Processes =  4 | Factors found = 12 | time = 1.98632s

Processes =  8 | Factors found = 12 | time = 1.42400s

Processes = 16 | Factors found = 12 | time = 1.30496s


*--- Factorizing 1234567891 ---*

Processes =  1 | Factors found = 2 | time = 71.25728s

Processes =  2 | Factors found = 2 | time = 39.18208s

Processes =  4 | Factors found = 2 | time = 26.16038s

Processes =  8 | Factors found = 2 | time = 19.27646s

Processes = 16 | Factors found = 2 | time = 12.09022s


#**Memory bound**
паралелізм не допомогає при memory bound задачах, 

так як всі процеси використовують одну пам'ять.

*--- Matrix size = 10000 x 10000 ---*

Threads =  1 | Time = 1.8068s | Correct = True

Threads =  2 | Time = 0.1985s | Correct = True

Threads =  4 | Time = 0.1149s | Correct = True

Threads =  8 | Time = 0.1018s | Correct = True

Threads = 16 | Time = 0.1232s | Correct = True

*--- Matrix size = 15000 x 15000 ---*

Threads =  1 | Time = 0.6404s | Correct = True

Threads =  2 | Time = 0.5132s | Correct = True

Threads =  4 | Time = 0.3064s | Correct = True

Threads =  8 | Time = 0.2448s | Correct = True

Threads = 16 | Time = 0.2409s | Correct = True

*--- Matrix size = 20000 x 20000 ---*

Threads =  1 | Time = 1.2779s | Correct = True

Threads =  2 | Time = 2.3089s | Correct = True

Threads =  4 | Time = 0.9910s | Correct = True

Threads =  8 | Time = 0.6944s | Correct = True

Threads = 16 | Time = 1.1738s | Correct = True



1. застосовувалися такі фреймворки, як Python threading, multiprocessing та Numba. Threading дозволяє виконувати кілька потоків у межах одного процесу, ефективно для I/O-bound задач, але через GIL не дає значного прискорення CPU-bound обчислень. Multiprocessing створює окремі процеси з власною пам’яттю, що дозволяє ефективно використовувати всі ядра для CPU-bound задач, але має більші накладні витрати на створення процесів. Numba компілює Python-код у машинний код за допомогою JIT, що значно прискорює чисельні обчислення без необхідності ручного переписування на C або C++.

2. CPU-bound задачі — це задачі, де обчислення займають основний час виконання, і обмеженням є швидкість процесора; Memory-bound задачі обмежуються пропускною здатністю пам’яті, коли процесор просто чекає дані з оперативної пам’яті . I/O-bound задачі затримуються операціями введення/виводу, такими як робота з файлами чи мережею, де процесор часто просто очікує завершення операцій.

3. Закон Амдала визначає максимальне прискорення програми при її паралельному виконанні і показує, що прискорення обмежується частиною коду, яку не можна розпаралелити. Формула: Speedup ≤ 1 / (1 − P + P/N), де P — частка паралельного коду, N — кількість процесорів. Це означає, що навіть з великою кількістю ядер ефективність обмежена непаралельною частиною задачі, і розпаралелювати все не завжди дає лінійний приріст швидкості.

4. I/O-bound задачі ефективно використовують більше потоків, ніж кількість ядер, тому що більшість часу потоки просто очікують завершення операцій введення/виводу, а не виконують обчислення. Додаткові потоки дозволяють покрити час очікування, щоб інші потоки могли працювати, збільшуючи загальну пропускну здатність системи без потреби в додаткових ядрах.

5. Overhead при створенні потоків — це накладні витрати на виділення пам’яті, планування та ініціалізацію нового потоку. Він впливає на продуктивність, особливо для дрібних задач, коли час на створення потоку може перевищувати час на виконання самої задачі, роблячи розпаралелення неефективним.

6. Пул потоків (thread pool) — це набір попередньо створених потоків, які повторно використовуються для виконання багатьох задач. Переваги включають зменшення накладних витрат на створення потоків, балансування навантаження між потоками та ефективніше використання ресурсів системи, особливо для багатьох дрібних задач або I/O-bound операцій.

7. У Memory-bound задачах багатопоточне виконання може призвести до проблем, таких як виснаження пропускної здатності пам’яті, конкуренція за кеш, що знижує ефективність додаткових потоків, та збільшення латентності доступу до даних. Навіть із більшою кількістю потоків прискорення може бути обмежене, бо процесори просто чекають дані з пам’яті.
