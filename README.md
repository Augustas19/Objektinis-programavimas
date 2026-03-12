<img width="702" height="337" alt="Screenshot 2026-03-11 205320" src="https://github.com/user-attachments/assets/0ece9600-a1bb-4ebc-895b-2336129698b7" />

Programa turi funkciją failų generavimui, kuri taip pat skaičiuoja failų generavimo laiką.
1000, 10000 ir 100000 yra sukuriami greitai ir neviršija 1,5 sekundžių. O štai milijono studentų failas jau yra generuojamas 8 sekundes, kas yra beveik 8 kartus ilgiau nei 
100 tūkstančių studentų failas. Tas pats vyksta ir su 10 milijonų studentų failu, jis yra generuojamas 62 sekundes, kas yra beveik 8 kartus daugiau nei 1 milijono failas.

<img width="532" height="724" alt="Screenshot 2026-03-12 205838" src="https://github.com/user-attachments/assets/11edfa22-95b2-4a9a-8e69-d6953ef6b2ea" />

Antra testavimo funkcija nuskaito kiekvieno failo duomenis, su jais atlieka skaičiavimus, surūšiuoja bei surikiuoja pagal vartotojo pasirinktą būda, ir vėl išveda į 2
skirtingus failus. Su 1000, 10000 ir 100000 studentų failais ši testavimo funkcija netrunka ilgiau nei sekundę prie kiekvienos testavimo dalies. Visgi su milijono studentų 
failu tas pasikeičia ir dabar kiekviena funkcijos dalis, išskyrus skaičiavimų dalį, yra atliekama tarp 5 ir 6 sekundžių. Su 10 milijonų failu programa užtrunka dar ilgiau. 
Skaičiavimo dalis vis tiek išlieka greita, tačiau nuskaitymas, rikiavimas ir rašymas į failą užtrunka beveik minutę, todėl visos programos veikimas gali užtrukti apie 3 
minutes.
