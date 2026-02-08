# Testovací případy – Přihlášení uživatele

---

## TC-AUTH-LOGIN-001 – Přihlášení s platnými údaji

**Předpoklad:**  
Uživatel má existující účet

**Kroky:**
1. Otevřít stránku přihlášení
2. Zadat platnou e-mailovou adresu
3. Zadat platné heslo
4. Kliknout na tlačítko „Přihlásit se“

**Očekávaný výsledek:**
- Uživatel je úspěšně přihlášen
- Zobrazí se klientská zóna

---

## TC-AUTH-LOGIN-002 – Neplatné heslo

**Kroky:**
1. Otevřít stránku přihlášení
2. Zadat platnou e-mailovou adresu
3. Zadat neplatné heslo
4. Kliknout na tlačítko „Přihlásit se“

**Očekávaný výsledek:**
- Zobrazí se chybová hláška
- Uživatel zůstane na stránce přihlášení

---

## TC-AUTH-LOGIN-003 – Neexistující uživatel

**Kroky:**
1. Otevřít stránku přihlášení
2. Zadat e-mail, který není registrován
3. Zadat libovolné heslo
4. Kliknout na tlačítko „Přihlásit se“

**Očekávaný výsledek:**
- Zobrazí se chybová hláška
- Uživatel není přihlášen
