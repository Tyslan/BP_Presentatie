##  Read repair

- Effectief herstellen van verouderde replica's
- 3 soorten:
  1. Synchrone read repair
  2. Asynchrone read repair
  3. Manuele read repair

note:
- sync:
  - controleren bij read
  - vergelijken via checksum
  - checksum verkeerd volledige replica ophalen en timestamp vergelijken
  - Oudste updaten
- async:
  - kans op controle instellen (standaard 10%)
  - verder gelijk aan sync
- manueel:
  - Volledige repair
  - regelmatig
  - nodetool repair
  - Instelling: standaard 10 dagen

- probleem bij verwijderen
  - tombstone marker
