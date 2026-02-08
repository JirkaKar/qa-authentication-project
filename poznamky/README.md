# QA mini projekt – Autentizace uživatele

Tento repozitář slouží jako ukázka manuálního testování
webové aplikace se zaměřením na autentizační procesy.

## Cíl projektu
Ověřit správnou funkčnost přihlášení, registrace a obnovy hesla
včetně validací vstupních polí a chybových stavů.

## Testovaný rozsah
- Přihlášení uživatele
- Registrace nového uživatele
- Obnova zapomenutého hesla
- Validace vstupních polí
- Chybová hlášení

## Použité techniky
- Manuální testování
- Návrh testovacích případů
- Bug reporting
- Exploratorní testování
- Základní testovací dokumentace

## Mimo rozsah
- Výkonnostní testy
- Bezpečnostní testy
- Automatizované testy

qa-authentication-project/
│
├── README.md
├── testovaci-pripady/
│   ├── prihlaseni.md
│   ├── registrace.md
│   └── obnova_hesla.md
│
├── bug-reporty/
│   ├── BUG-001-validace-emailu.md
│   └── BUG-002-heslo-pravidla.md
│
└── poznamky/
    └── testovaci-poznamky.md
