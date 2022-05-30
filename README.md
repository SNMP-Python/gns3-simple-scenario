<h1 align="center">
Simple OSPF scenario 🌐
</h1>

<h2 align = center> <img align="center" src="https://github.com/SNMP-Python/gns3-simple-scenario/ospf-simple.png" /> </h2>

## Configure tap0 interface
    
```
tunctl -t tap0 -u username
ip link set tap0 up
ip addr add 10.0.0.3/8 dev tap0
```