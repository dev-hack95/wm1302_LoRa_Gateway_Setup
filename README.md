# wm1302_LoRa_Gateway_Setup
A sx1302 lora gateway docker setup for indian zone


```bash
git clone https://github.com/Lora-net/sx1302_hal
cd sx1302_hal/
make
```

* Move `global_conf.json.sx1250.IN865.USB` packet forwarder directory

```bash
./lora_pkt_fwd -c global_conf.json.sx1250.IN865.USB
```
