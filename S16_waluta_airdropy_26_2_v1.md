# S16 SMP 2 — Waluty + Airdropy — Minecraft 26.2

Paczka ZIP: https://raw.githubusercontent.com/manius20/S16_money/main/S16_waluta_airdropy_26_2_v1.zip

Przy wyłączonym serwerze podmień te linie w server.properties:
```properties
resource-pack=https://raw.githubusercontent.com/manius20/S16_money/main/S16_waluta_airdropy_26_2_v1.zip
resource-pack-id=508ed131-a120-43ad-8d64-516000000005
resource-pack-prompt=S16 SMP 2 - Waluty i Airdropy
resource-pack-sha1=106b710b6c8f76a9d9ea8e66adb134f610f331a0
```

Użyj manius_events 1.3.2-rc1. Wersja rozpoznaje paczkę z server.properties, wybiera RESOURCE przy pierwszym wykryciu i ponawia żądanie w fazie gry z tym samym UUID. Nie wpisujesz URL w GUI. Stary adres w GUI nie zastąpi paczki serwera przy tym UUID. Odmowa/błąd pobrania = uproszczony model.

Format zasobów 88.0, wyłącznie Minecraft 26.2. Wszystkie 13 modeli wczytane prawdziwym loaderem klienta 26.2. Geometria i PNG walut zachowane; naprawiono brakujące odwołanie particle echo_shard. Dołożono 10 modeli airdropa. Animacje i cząsteczki odtwarza plugin.

HTTP 200 i SHA-1 pobranego ZIP-a sprawdzone bez logowania.
SHA-256: 706d1f067d28bcdc7779bb1f57db03c4d8eb7803d783a243352f28f5099e6185
Maven 23 testy, lokalny Paper 26.2: 44 kontrole. Bez oględzin wizualnych w kliencie i wdrożenia na IceHost.
