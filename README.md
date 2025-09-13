# homewizard_emulator
Open de add-on, vul onder `Options` je `token` (Long-Lived Access Token) en controleer of de entity-namen kloppen.
Start de add-on. Je add-on draait op poort zoals in options (standaard 80) en exposeert `/api/v1/data`.
Test via `http://<HA_IP>/api/v1/data` in je browser — je zou JSON moeten zien.
Voeg dit IP/poort toe in de Alfen configuratie als HomeWizard P1 meter.
