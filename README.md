# marias-rozlosovani
Program na rozlosování turnaje v mariáši a to trojky i čtyřky. Rozlosování je uděláno tak, aby se hráči v žádném kole nepotkali dvakrát.
Tato Streamlit aplikace slouží k generování a ověřování rozlosování hráčů do skupin pro turnaje, zejména s ohledem na karetní hry jako mariáš, kde je důležité, aby se hráči během turnaje nepotkávali opakovaně ve stejné skupině. Program umožňuje definovat různá schémata rozlosování a ověřit jejich platnost.

## Funkce

* **Definice rozlosování:** Předdefinovaná schémata rozlosování pro různé počty hráčů a velikosti skupin (např. Kirkman Triple Systems).
* **Vlastní konfigurace turnaje:** Možnost zadat počet hráčů a počet odehraných kol.
* **Zadávání jmen hráčů:** Intuitivní zadávání jmen pro každého hráče.
* **Detekce duplicitních jmen:** Aplikace automaticky upozorní na duplicitní jména hráčů.
* **Ověření rozlosování:** Kontrola, zda se v rámci zvoleného schématu a počtu kol nevyskytují duplicity, tj. zda se žádní dva hráči nepotkají ve stejné skupině vícekrát (pokud to schéma umožňuje).
* **Zobrazení rozlosování:** Přehledné zobrazení rozlosování pro jednotlivá kola, včetně jmen hráčů.

## Podporovaná rozlosování

Aplikace obsahuje předdefinovaná schémata rozlosování pro různé počty hráčů a velikosti skupin.

## Jak používat

1.  **Spuštění aplikace: a)**
    * Ujistěte se, že máte nainstalovaný [Streamlit](https://streamlit.io/) (`pip install streamlit`).
    Poté spusťte aplikaci z terminálu:
    ```bash
    streamlit run rozlosovani.py
    ```
    **Spuštění aplikace: b)**
    * Jděte na webovou adresu: https://marias-rozlosovani.streamlit.app/ 
3.  **Konfigurace turnaje:**
    * Vyberte počet hráčů z rozbalovacího menu.
    * Zvolte počet kol, která se budou hrát.
4.  **Zadání jmen hráčů:**
    * Do textových polí zadejte jména jednotlivých hráčů.
    * Aplikace vás upozorní, pokud zadáte duplicitní jméno.
5.  **Zobrazení a ověření rozlosování:**
    * Klikněte na tlačítko "Zobraz rozlosování".
    * Aplikace provede kontrolu duplicit ve skupinách. Pokud jsou nalezeny chyby (např. dva hráči se potkají vícekrát, ačkoli by neměli), zobrazí se chybové zprávy. V opačném případě se zobrazí zpráva o platnosti rozlosování.
    * Následně se zobrazí rozlosování pro každé kolo s přiřazenými jmény hráčů.


## Licence

Tento software ("Program") je poskytován **pouze pro soukromé, nekomerční použití**. To znamená, že smíte používat tento Program pro své osobní účely bez jakéhokoli komerčního zisku nebo účelu. Jakékoli použití Programu pro komerční účely, prodeje, pronájmy, distribuce za úplatu nebo jakékoli jiné použití, které generuje zisk, je přísně zakázáno bez předchozího písemného souhlasu autora.

Program smíte volně studovat, upravovat a sdílet pouze za předpokladu, že tyto licenční podmínky zůstanou nedotčeny a že jakákoli upravená verze bude rovněž poskytována pouze pro soukromé, nekomerční použití.

---

## Zřeknutí se odpovědnosti

TENTO PROGRAM JE POSKYTOVÁN "TAK JAK JE", BEZ JAKÉKOLI ZÁRUKY, VÝSLOVNÉ NEBO PŘEDPOKLÁDANÉ, VČETNĚ, ALE NEJEN, PŘEDPOKLÁDANÝCH ZÁRUK PRODEJNOSTI, VHODNOSTI PRO KONKRÉTNÍ ÚČEL A NEPORUŠENÍ PRÁV. AUTOR ANI ŽÁDNÝ Z PŘISPĚVATELŮ NENESE V ŽÁDNÉM PŘÍPADĚ ODPOVĚDNOST ZA JAKÉKOLI NÁROKY, ŠKODY NEBO JINOU ODPOVĚDNOST, AŤ UŽ V RÁMCI SMLOUVY, PŘEČINU ČI JINAK, VYPLÝVAJÍCÍ Z NEBO V SOUVISLOSTI S PROGRAMEM NEBO JEHO POUŽITÍM NEBO JINÝMI OBCHODY S PROGRAMEM.

Jste výhradně zodpovědní za veškeré výsledky plynoucí z použití tohoto Programu. Autor nenese žádnou odpovědnost za jakékoli chyby, opomenutí nebo nepřesnosti v rozlosování generovaném Programem, ani za jakékoli důsledky plynoucí z takových chyb. Je vaší odpovědností ověřit správnost a vhodnost generovaného rozlosování pro vaše konkrétní účely.
