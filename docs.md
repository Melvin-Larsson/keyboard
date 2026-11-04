# SoC:
nRF52833 - QFN40

nRF52840-QFN48


# Battery?
Will go with Li-Po I think, Li-Ion seems better except that it has
less flexibility in sizes.

E.g. This is too fat:
https://www.electrokit.com/batteri-li-ion-21700-3.7v-5300mah-16.8a

Maybe this LiPo?
https://www.electrokit.com/batteri-lipo-3.7v-1200mah-1

# Charger IC:
BQ24026DRCR: https://www.digikey.se/sv/products/detail/texas-instruments/BQ24026DRCR/684805

This one is newer and more complicated:
BQ24032ARHLR: https://www.digikey.se/en/products/detail/texas-instruments/BQ24032ARHLR/807592

# Buck boost:
Lets just go with this one:
TPS63001DRCR: https://www.digikey.se/sv/products/detail/texas-instruments/TPS63001DRCR/1016476

TPS63051RMWR: https://www.digikey.se/sv/products/detail/texas-instruments/TPS63051RMWR/5418962

Expensive:
LTC1754ES6-3.3#TRPBF: https://www.digikey.se/sv/products/detail/analog-devices-inc/LTC1754ES6-3-3-TRPBF/960920

# Fuel gauge
MAX17303G+: https://www.digikey.se/sv/products/detail/analog-devices-inc-maxim-integrated/MAX17303G/17885206


# MOSFET
I think this:
https://www.digikey.se/sv/products/detail/goford-semiconductor/03N06L/16499561


# Switch
https://www.digikey.se/en/products/detail/c-k/JS202011SCQN/2094299

# LEDs
APT1608CGCK
https://www.digikey.se/sv/products/detail/kingbright/APT1608CGCK/1747514


# Crystal
ECS-320-8-37B-CKY-TR
https://www.digikey.se/sv/products/detail/ecs-inc/ECS-320-8-37B-CKY-TR/9838854

# Diode
1N4448WS
https://www.digikey.se1.25mV resolution (0 to 3.875A with 0.125A resolution using 10mΩ sense resistor). The OD and OC comparators have a/sv/products/detail/shenzhen-slkormicro-semicon-co-ltd/1N4448WS/26112891

# Shift
SN74HC595PWR


# Thersmistor 
- MF52C1103F3380

We get range 3.7C - 43C when charging ish. Good enough since battery can handle 0C-45C

1/R2 + 1 / (R1 + NTC)

(R1 + NTC + R2) / (R1 + NTC)R2

V = I(1/R2 + 1 / (R1 + NTC))

I = 94-106uA

0.5-2.5

0.485, 0.515
2.465, 2.535

V < 0.485
RI < 0.485
R < 0.485 / I <

R > 3039.19 -> V < 0.485
With 1% error
R > 3070 -> V < 0.485
U/I > 3070 -> U < 0.485

U/I=R


3133.45

28223.7


