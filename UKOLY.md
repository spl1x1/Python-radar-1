# Objektivně měřitelné úkoly projektu: Nízko frekvenční radar s počítačovou aplikací

## Milník 1: Pořízení radarových modulů a kabeláže (Splněno)

- [x] **Nákup komponent:** Objednán radarový modul Hi-Link LD2450, převodník UART na USB a potřebná propojovací kabeláž.

- [x] **Fyzická kontrola:** Hardware byl doručen a byla úspěšně provedena jeho vizuální kontrola.

- [x] **Sestavení:** Modul LD2450 a převodník jsou fyzicky zapojeny a propojeny s počítačem.

## Milník 2: Testování komunikačních protokolů (Splněno)

- [x] **Zkušební skript:** Vytvořen základní testovací skript v Pythonu pro připojení k sériové lince.

- [x] **Úspěšné spuštění:** Skript byl spuštěn v konzoli bez chybových hlášení.

- [x] **Potvrzení detekce:** Je prokazatelně ověřeno, že senzor detekuje cíle v reálném prostředí a odesílá data do počítače.

## Milník 3: Vývoj aplikační logiky (Termín: do 31. 12. 2026)

- [ ] **Analýza protokolu:** Zanalyzována dostupná dokumentace datového protokolu senzoru LD2450 pro extrakci souřadnic.

- [ ] **Parsovací logika:** Naprogramován čtecí skript, který bez chyb dekóduje surová UART data na konkrétní hodnoty os X a Y.

- [ ] **Code review:** Provedena revize kódu potvrzující čistotu řešení a správnost izolace dat.

## Milník 4: Naprogramování 2D vizualizace (Termín: do 29. 1. 2027)

- [ ] **Základ UI:** Vygenerováno grafické uživatelské rozhraní pro 2D vizualizaci pomocí knihovny pygame.

- [ ] **Integrace dat:** Poziční data ze senzoru (X a Y) jsou přímo navázána na grafické body/cíle, které se reálně vykreslují v aplikaci.

- [ ] **Zátěžový test:** Potvrzeno plynulé překreslování dat bez drastických záseků či poklesů FPS, a to i při sledování více (1–3) cílů současně.

- [ ] **Fyzická demonstrace:** Proběhlo úspěšné finální testování kompletní funkčnosti celé aplikace s hardwarově připojeným radarem.
