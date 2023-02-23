#README pro program na extrakci e-mailových adres z textu

Popis:
Tento program je určen k extrakci e-mailových adres z textového řetězce pomocí regulárního výrazu. Program používá standardní formát e-mailové adresy pro vyhledání a extrakci všech e-mailových adres v zadaném textu.

Jak program funguje:

Regulární výraz, definovaný v proměnné "email_regex", je použit k nalezení všech řetězců odpovídajících standardnímu formátu e-mailové adresy v zadaném textu.
Funkce "extract_emails()" vezme text jako vstup a najde pomocí definovaného regulárního výrazu všechny e-mailové adresy v textu.
Extrahované e-mailové adresy jsou uloženy v proměnné "emails" a jsou vypsány v konzoli pomocí cyklu for a funkce "print()".

Jak používat program:

Stáhněte si soubor s kódem a otevřete ho v prostředí pro vývoj Pythonu.
Spusťte program a výsledky budou vypsány v konzoli.
Pokud chcete program použít v rámci svého vlastního kódu, jednoduše zavolejte funkci "extract_emails()" s vlastním textem jako vstupem a získáte tak extrahované e-mailové adresy.
