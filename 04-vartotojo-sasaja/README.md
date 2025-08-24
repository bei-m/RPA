## 4 darbas - Vartotojo sąsaja
Eiga: <br>
1. Robotukas naršyklėje atveria ACME tinklalapį (https://acme-test.uipath.com/).
2. Patikrina, ar naudotojas yra prisijungęs prie ACME:
    * Naudotojas neprisijungęs:
      * Paprašo naudotojo nurodyti el. paštą ir slaptažodį (nepamirškite pažymėti);
      * Į laukus įveda pateiktas reikšmes;
      * Spusteli mygtuką Prisijungti.
    * Naudotojas prisijungęs: vykdo toliau pateiktus žingsnius.
3. Nueina į puslapį `Employees`.
4. Nuskaito iššokusiame lange esančio kandidato vardą ir langą uždaro.
5. Paima nurodyto kandidato informaciją: vardą, pavardę, telefono numerį, gimimo datą ir el. paštą. Langą uždaro.
6. Atidaro žiniatinklio formą naujame lange/skirtuke.
7. Įveda kandidato informaciją ir ją pateikia.
8. Tą pačią informaciją supildo ir excel dokumente.
9. Atnaujina ACME Employees langą ir taip pat supildo kito kandidato duomenis. Reikia supildyti 5 kandidatų duomenis.
10. Pereina į puslapį `Work Items`.
11. Nuskaito Work Items esančią lentelę. Lentelė turi susidaryti iš stulpelių: WIID, Description, Type, Status ir Date (nuskaitymą apsirašykit su Table Extraction)
12. Išsaugo duomenis į anksčiau sukurto Excel dokumento kitą puslapį.
13. Abi lenteles Excel dokumente suformatuoja.