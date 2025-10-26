# Bandit

### Wiring Explaination
Bandit's physical hardware can be interpreted via the top of the code with most of the "#define"s. For a quicker look, we'll go through them together.

**OLED Display**
VCC: VIN
GND: esp32's GND pin
SCL: D22
SDA: D21

**Buttons**
LifeButton: D12
FunButton: D14

### What is the NEXT Step?
I plan to keep working on this project and implement a "Streetpass-like" system where if two or more are in Bluetooth range, they will connect and exchange data. However, making the assets proved to be a longer process than expected.
