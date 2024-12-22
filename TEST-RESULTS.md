# TEST-RESULTS.md
## Observații și defecte identificate

### 1. Aritmetică de bază
- **Expresie:** `3+5` 
- **Rezultat:** Programul returnează `8` corect . 
- **Sugestie:** Nu. 

### 2. Împărțirea la zero
- **Expresie:** `4/0` 
- **Rezultat:** Programul returnează `Infinity`. 
- **Sugestie:** Ar trebui să returneze `ERROR` sau `Division by zero`. 

### 3. Ordinea operațiilor
- **Expresie:** `3+5*2` 
- **Rezultat așteptat:** 13 
- **Rezultat obținut:** 13 

### 4. Expresii invalide
- **Expresie:** `abc+8` 
- **Rezultat:** `ERROR` 
- **Sugestie:** Oferirea unui mesaj clar: `Invalid characters in expression`. 

### 5. Marginalizare
- **Expresie:** `-5+10` 
- **Rezultat:** 5 
- **Sugestie:** Funcționează corect. 
