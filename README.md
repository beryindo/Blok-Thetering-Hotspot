# Blok-Thetering-Hotspot
```
/ip firewall mangle
add action=change-ttl chain=postrouting comment="BLOK TETHERING  HOTSPOT" \
    new-ttl=set:1 out-interface=VLAN-102 passthrough=no
```
