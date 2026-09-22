Aufgabe 1
- Noel hat repo geforkt
- Ron hat das Repo von Noel geklont
- Dann haben wir das .github/workflows/ci-1.yml erstellt
- Problem: Wir haben die Action gestartet und sie failte.
  - Lösung: Wir haben vergessen den Code in das ci-1.yml  einzufügen
  - Darum failte die erste Action

Aufgabe 2
- ci-1.yml haben wir zu ci-1.yml-done umbenennt, das macht, dass die Action nicht mehr ausgeführt wird. Weil wir haben ja die neue ci-2.yml
- ci-2.yml erstellt
- ESLint hinzugefügt
- Jest und Testing library installiert
- Problem: React Version war nicht kompatibel mit der Testing Library
  - Lösung: Auf React 19.0.0 gewechselt 
- Problem: Pushen wurde abgelehnt. Wir wissen ehrlich gesagt nicht warum
  - Lösung: Mit "git pull --rebase" ging es dann doch
- Wir haben die Action gestartet und sie lief 
- Wir haben ci-2.yml zu ci-2.yml-done umgeändert

Aufgabe 3
- wir haben die neue ci-3.yml erstellt
- Pipeline in 3 verschiedene Jobs aufgeteilt

