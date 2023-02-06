## SAUNA

- ESPHome configuration

### Dallas thermometer - saunafloor
- https://esphome.io/components/sensor/dallas.html?highlight=dallas

ESPHome config:

```
dallas:
  - pin: GPIO23

sensor:
  - platform: dallas
    index: 0
    name: "Teplomer"
```


### HTU21D thermometer and humidity sensor - sauna indoor and the room (fan control)
- https://esphome.io/components/sensor/htu21d.html?highlight=htu21d
