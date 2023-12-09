Bernie Info System Biztonsági Irányelvek
1. Felhasználói Bevitel Ellenőrzése

Minden felhasználói bemenetet alaposan validálunk, különös tekintettel az SQL és XSS támadásokra. Használunk paraméterizált lekérdezéseket az adatbázisba történő kommunikációhoz, és alkalmazunk megfelelő szűrőket a beviteli mezőkben.
2. Hibakezelés és Naplózás

A program hibakezelése a felhasználónak minimális információt szolgáltat a hibáról, miközben részletes naplózást alkalmazunk a rendszer működéséről. A naplók rendszeres ellenőrzésre kerülnek, és csak jogosultsággal rendelkező személyek férhetnek hozzá.
3. Jogosultságkezelés

Az alkalmazás szigorú jogosultságkezelési mechanizmusokkal rendelkezik. A felhasználói jogokat rendszeresen ellenőrizzük és frissítjük. Csak a minimális szükséges jogokkal rendelkező felhasználóknak engedélyezzük a hozzáférést bizonyos funkciókhoz.
4. Harmadik Féltől Származó Források

Az alkalmazás csak megbízható forrásokból fogad el adatokat, például a weboldal és API-k. A külső forrásokra történő kapcsolatok során minden adatot validálunk és szűrünk, hogy elkerüljük a rosszindulatú beavatkozásokat.
5. Frissítések és Biztonsági Rések

A használt függőségeket és könyvtárakat rendszeresen ellenőrizzük biztonsági rések és frissítések szempontjából. Csak biztonságos, támogatott verziókat alkalmazunk, és dokumentáljuk az alkalmazott változásokat.
6. Adatvédelem

Az alkalmazás érzékeny adatait kriptografikusan védjük. Jelszavakat sózunk és hash-elünk, és mind a tárolás, mind az átvitel során alkalmazunk erős kriptográfiai eljárásokat.
7. Külső Források Ellenőrzése

A külső forrásokat, beleértve a weboldalakat és API-kat, rendszeresen monitorozzuk és ellenőrizzük. Az adatokat megbízható forrásokból szerezzük be, és minden külső forrással csak biztonságos kapcsolatokat építünk ki.
8. Fejlesztői Eszközök és Környezet

A fejlesztői környezetet biztonságosan konfiguráljuk, és kerüljük a kulcsok és érzékeny információk nyilvános elhelyezését. A fejlesztőknek be kell tartaniuk a biztonságos kódolási gyakorlatokat, és csak engedélyezett eszközöket használniuk.
9. Rendszerbiztonság

A rendszert rendszeresen ellenőrizzük a biztonsági rések és sebezhetőségek szempontjából. A biztonsági frissítéseket gyorsan alkalmazzuk, és a rendszer biztonságát folyamatosan felülvizsgáljuk.
10. Felhasználói Felvilágosítás

A felhasználókat tájékoztatjuk a biztonsági eljárásokról, beleértve a jelszóvédelmi gyakorlatokat és a fiók védelmi lehetőségeket. A felhasználókat rendszeresen értesítjük a biztonsági frissítésekről és új funkciókról.
