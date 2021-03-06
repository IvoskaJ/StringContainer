# StringContainer
Atliekama užduotis su string konteineriu

    Iki šiol dažniausiai naudojome sekos/nuoseklaus tipo (angl. sequence containers) konteinerius, t.y. juose išlaikoma tokia tvarka, kokia mes tuos elementus sudėjome (pvz. naudodami insert ar push_back()) į konteinerius. Tačiau tam tikroms užduotims kito tipo konteineriai yra labiau tinkami. Pavyzdžiui, norėdami įsitikinti ar tam tikras skaičius (pvz. 100) egzistuoja konteineryje, naudojant sekos konteinerius iš esmės turime du pasirinkimus:

    kiekvieno konteinerio elementą lyginti su 100 tol kol surasime, kad toks elementas iš tiesų egzistuoja, arba patikrinsime visus elementus ir įsitikinsime, kad toks elementas neegzistuoja;
    surūšiuoti konteinerį naudojant rūšiavimo algoritmą ir tuomet naudojant kokią gudresnę strategiją greitai patikrinti, ar toks elementas egzistuoja konteineryje. Tačiau tokiu atveju įterpus naujus elementus privalome konteinerį iš naujo surūšiuoti.

    Akivaizdu, kad abiems atvejams realizacija veiks gana lėtai ir neefektyviai.

    Ši užduotis skirta patyrinėti, kad tokio tipo užduotims asociatyvūs konteineriai, t.y. tokie, kurie elementų į konteinerį įrašymo metu juos   "surūšiuoja" yra labiau tinkami ir efektyvesni lyginant su sekos konteineriais.

    Užduoties formuluotė

    Suskaičiuokite, kiek kartų kiekvienas skirtingas žodis pasikartoja Jūsų tekste. Tekstą galite paimti iš bet kur, pvz.: Vikipediją straipsnį apie Vilnių (Geriau kad būtu kitoks tekstas, ne mažiau 1000 žodžių). Tuomet realizacijos output'e (išoriniame faile) išveskite skirtingus žodžius (kableliai, taškai ir kiti skyrybos ženklai nėra žodžiu dalis!), kurie pasikartojo dažniau negu 1 kartą, o taip pat ir count'erį, nurodantį kiek kartų konkretus žodis pasikartojo.
    Sukurkite cross-reference tipo lentelę kurioje būtų nurodyta, kurioje teksto vietoje (kurioje(-iose) teksto eilutėse) kiekvienas iš daugiau negu vieną kartą pasikartojantis žodis buvo paminėtas.
    URL adresų suradimas Jūsų tekste. Kaip ir pirmos užduoties atveju, tekstą galite paimti iš bet kur, račiau būtina, kad tame tekste būtų bent keli URL'ai, pateikti "pilnu" https://www.vu.lt/ ar "sutrumpintu" pavidalu: www.vu.lt. Jūsų tikslas, iš to teksto išrinkti visus šiuos URL'us ir grąžiai atspausdinti ekrane (ar išvesti į failą)!
    Repozicija turi būti parengta pagal visus ankstesnių darbų galutinėms versijoms galiojančius reikalavimus.
