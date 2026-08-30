NATRAPPORT – VERSION 4

Filer:
- index.html
- manifest.json
- sw.js

V4 retter især:
1. Mailteksten bruger rigtige linjeskift i stedet for at vise "\n".
2. Billeder sendes som rigtige filer via iOS Share Sheet, når den valgte mail-app understøtter Web Share-filer.
3. Der er en ekstra knap "Del kun billeder".
4. Service Worker-cache er opdateret til v4.

GitHub Pages:
Upload/erstat de tre filer i repositoryets main/root.
GitHub Pages skal fortsat være sat til main + /(root).

Test:
Åbn https://abdullah5-ops.github.io/natrapport/
Lav en test med mindst ét billede.
Tryk Mail -> Del mail + billeder.
Vælg Outlook/Mail i Del-menuen.
