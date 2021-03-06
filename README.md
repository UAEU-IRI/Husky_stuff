# Login Credentials


- User: ``` administrator ```
- Host Name: ``` CPR-A200-0501 ```
- Password: ``` clearpath ```

# Husky Router Settings

- SSID: ``` UAEU_Husky ```
- Password: ``` clearpath ```
- DHCP: Disabled (static IPs).
- GateWay: 192.168.0.1
- Robot IP: 192.168.0.10

# Battery Saftey
- The husky lead acid battery is considered to have 7% left when its at 22volts.

- As a general rule, charge it at 22 volts. You risk damaging the battery if it goes below 19V.

- 18V is considered completely dead (down to 0.5% capacity). But its hard to charge a lead acid battery if it goes that far. It might not charge up to the same capacity.

- The Lead acid battery in our Husky will charge up to around 26.4V, whereas the Lithium Ion battery upgrade is capable of going up to around 29.4V. This is why the LED indicator will never reach full. To know the battery voltage, you can either subscribe to the ```/diagnostics``` ROS topic, or measure the battery's voltage directly (the 24 V outlet is directly connected to the battery, so you can measure it from there without taking the battery out).

# Host PCs and IPs Table

| Host          | IP           | Description  |
| ------------- |:-------------:| -------------:|
| CPR-A200-0501     | 192.168.0.10 | The Husky robot |
| iri01    | 192.168.0.201 | Hassan Ubuntu Desktop |
| iri02    | 192.168.0.202 | AlienWare Ubuntu laptop |
| imacUbuntu    | 192.168.0.223 | Mac all-in-PC ubuntu (hassan Mac) |
| hassandell    | 192.168.0.200 | Hassan dell personal laptop |
| hassan    | 192.168.0.140 | Hassan lenovo personal laptop |
