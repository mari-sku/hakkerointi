## H0 Compile and analyze

Käytössäni on virtuaalikone, jossa on Debian. Tein nanolla `nano h0.c` c-tiedoston, jossa on yksinkertainen "Hello world" -ohjelma C-kielellä.

<img width="806" height="433" alt="image" src="https://github.com/user-attachments/assets/091ed70e-8df3-4762-9d30-a6eebda1afd9" />

Käytin komentoa `gcc h0.c -o h0`. GCC (GNU Compiler Collection) on kääntäjä, ja gcc komennolla käänsin h0.c-tiedoston suoritettavaksi ohjelmaksi nimeltä "h0". Ajoin ohjelman komennolla `./h0`.

<img width="572" height="177" alt="image" src="https://github.com/user-attachments/assets/ff1122a6-bb7f-40e1-b232-a611fe4f42c6" />

Jotta näen ohjelman binäärimuodossa, asensin xxd-työkalun.

<img width="802" height="451" alt="image" src="https://github.com/user-attachments/assets/543d5076-9672-4bf6-959e-230cbb35da46" />

Käytin komentoa `xxd -b h0.c`, jolla näin c-ohjelman binäärimuodossa:

<img width="728" height="268" alt="image" src="https://github.com/user-attachments/assets/6d2efb13-cc4b-480e-b792-8094691be356" />



## Lähteet

- GeeksForGeeks 2026. C Hello World Program. Luettavissa: https://www.geeksforgeeks.org/c/c-hello-world-program/ Luettu 21.08.2026
- GeeksForGeeks 2026. xdd Command in Linux. Luettavissa: https://www.geeksforgeeks.org/linux-unix/xxd-command-in-linux/ Luettu 21.08.2026
- Wikipedia s.a. GCC. Luettavissa: https://fi.wikipedia.org/wiki/GCC Luettu 21.08.2026
