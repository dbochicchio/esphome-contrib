# esphome-contrib

My personal contribution for esp-home based projects.

## Bluerioot BT reader

Use *blueconnect.yaml* with a secret file like this:

```
blueriiot_mac: "00:A0:50:XX:XX:XX"
blueriiot_nameprefix: "Pool"
blueriiot_idprefix: "pool"
esphome_ha_api_key: "TODO"
esphome_ota_key: "TODO"
wifi_ssid: "mywifi"
wifi_password: "passwd"
blueriiot_fallback: "passwd"
```

You'll end up with these devices in your HA installation:

![image](https://github.com/dbochicchio/esphome-contrib/assets/31511185/bf73d4fa-6cbb-4c8b-a338-60dccf92bd55)

Follow ESPHome instructions on how to prepare your image.
