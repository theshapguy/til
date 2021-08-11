# Understanding Network Subnetting


Subnetting is the process of diving networks into smaller segments. A IPv4 address is a 32 bit number divided into 8 bit numbers.

```
            10.10.10.10               ← (deminal)
                ↓
    10.       10.     10.      10     ← (decimal spaced)
                ↓
  00001010 00001010 00001010 00001010 ← (binary)
```

#### Examples

1. A subnet of 255.255.255.255 or 10.10.10.0/32 can have 1 address.
    * 11111111 11111111 11111111 11111111


2. A subnet of 255.255.255.252 or 10.10.10.0/30 can have 2 addresses.
    * 11111111 11111111 11111111 1111111<ins>0</ins>


3. A subnet of 255.255.255.0 or 10.10.0.0/24 can have 256 addresses.
    * 11111111 11111111 11111111 <ins>00000000</ins>


4. A subnet of 255.255.254.0 or 10.10.0.0/23 can have 512 addresses.
    * 11111111 11111111 1111111<ins>0</ins> <ins>00000000</ins>


The difference between **3** & **4** is that the third part of the IPv4 can be 0 or 1, i.e 10.10.<ins>0</ins>.*[1-255]* or 10.10.<ins>1</ins>.*[1-255]*


#### Sources

1. https://www.ripe.net/about-us/press-centre/IPv4CIDRChart_2015.pdf
2. https://www.aelius.com/njh/subnet_sheet.html
3. http://jodies.de/ipcalc?host=10.10.10.1&mask1=21 - IP/Subnet Calculator
4. https://www.calculator.net/ip-subnet-calculator.html - IP/Subnet Calculator