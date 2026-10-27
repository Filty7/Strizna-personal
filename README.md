# Střižna

Osobní aplikace na přehled projektů, lidí, odpracovaných hodin, plateb a rozpočtů.

- Aplikace: jeden soubor `index.html`, běží na GitHub Pages.
- Data: nejsou v tomto repozitáři. Ukládají se do databáze Supabase a přístup k nim má jen přihlášený a ověřený účet vlastníka (Row Level Security).
- Klíč v `index.html` je veřejný „publishable“ klíč Supabase. Bez přihlášení k datům nic nezpřístupní.
