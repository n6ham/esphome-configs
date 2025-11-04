1. Update configs
```
git pull
```
2. Start ESPHome dashboard
```  
esphome dashboard .
```
3. Open [dashboard](http://0.0.0.0:6052)
4. Click three dots on the config, click Install and mannually download the binary
5. Open [web.esphome.io](https://web.esphome.io/)
6. Install the binary

Note: if replacing custom Tasmota firmware via web - install the [minimum tasmota firmware](	http://ota.tasmota.com/tasmota/release/tasmota-minimal.bin.gz) before installing the ESPHome binary. Otherwise update will fail due to lack of a free space.
