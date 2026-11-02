# wyswietlacz

Ekran przepływu energii (PV, sieć, dom, magazyn, woda) dla ESP32 + ST7796 320×480 w ESPHome.

## Wgrywanie

1. W ESPHome otwórz urządzenie `wyswietlacz` → **Edit**.
2. Wklej `wyswietlacz.yaml`. Obrazki pobiorą się same z tego repo.
3. Do `secrets.yaml` w ESPHome dodaj:
   ```yaml
   wyswietlacz_api_key: "twój klucz api"
   wyswietlacz_ota_password: "twoje hasło ota"
   wyswietlacz_ap_password: "hasło hotspota"
   ```
4. Podmień encje `sensor.ZMIEN_...` na swoje.
5. **Install** → **Wirelessly**.
