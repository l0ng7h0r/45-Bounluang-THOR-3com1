# Arduino Starter Kit Component Guide

## ວຽກບ້ານ 22.10.25

---

## ▼ Core Boards & Interfaces

### 1. Arduino Uno Board

**ຄຳອະທິບາຍ:** Arduino Uno ແມ່ນບອດໄມໂຄຣຄອນໂທຣເລີທີ່ນິຍົມທີ່ສຸດ ໃຊ້ຊິບ ATmega328P ມີ 14 ຂາ digital I/O ແລະ 6 ຂາ analog input.

**ການໃຊ້ງານ:** ເປັນສະໝອງກາງຂອງໂປຣເຈັກ Arduino ທຸກປະເພດ ສາມາດຂຽນໂປຣແກຣມຜ່ານ USB ແລະຄວບຄຸມອຸປະກອນຕ່າງໆໄດ້.

![Arduino Uno](./images/Arduino_Uno_Board.webp)

**Pinout ແລະສ່ວນປະກອບ:**

- **Digital Pins (0-13):** ສໍາລັບ input/output ແບບດິຈິຕອນ
- **Analog Pins (A0-A5):** ອ່ານຄ່າແອນາລັອກ 0-5V
- **Power Pins:** 5V, 3.3V, GND, VIN
- **USB Port:** ເຊື່ອມຕໍ່ກັບຄອມພິວເຕີ
- **Reset Button:** ລີເຊັດບອດ

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໂປຣເຈັກກະພິບໄຟ LED ຢ່າງງ່າຍດ້ວຍການຕໍ່ LED ເຂົ້າ pin 13 ແລະຂຽນໂຄດໃຫ້ມັນກະພິບທຸກໆ 1 ວິນາທີ.

---

### 2. Breadboard

**ຄຳອະທິບາຍ:** ເປັນແຜ່ນທົດລອງທີ່ບໍ່ຕ້ອງບັດກີ ມີຮູເຊື່ອມຕໍ່ພາຍໃນເຮັດໃຫ້ສາມາດສ້າງວົງຈອນຊົ່ວຄາວໄດ້.

**ການໃຊ້ງານ:** ສໍາລັບທົດລອງວົງຈອນກ່ອນບັດກີຖາວອນ ສາມາດຕໍ່ອຸປະກອນຕ່າງໆເຂົ້າກັນໄດ້ງ່າຍ.

![Breadboard](./images//Breadboard.webp)

**ໂຄງສ້າງ:**

- **Power Rails:** ແຖວບວກ (+) ແລະລົບ (-) ເຊື່ອມຕໍ່ຍາວ
- **Terminal Strips:** ແຖວກາງເຊື່ອມຕໍ່ແນວຕັ້ງ 5 ຮູ
- ມີຈໍານວນຫລາຍຂະໜາດ: mini, half, full

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງວົງຈອນ LED ພ້ອມ resistor ໂດຍຕໍ່ສ່ວນປະກອບເຂົ້າ breadboard ແທນທີ່ຈະບັດກີ.

---

### 3. USB Cable

**ຄຳອະທິບາຍ:** ສາຍ USB Type A ຫາ Type B ສໍາລັບເຊື່ອມຕໍ່ Arduino ກັບຄອມພິວເຕີ.

**ການໃຊ້ງານ:** ໃຊ້ອັບໂຫລດໂຄດ (programming) ແລະສະໜອງໄຟຟ້າໃຫ້ Arduino Uno (5V).

![USB Cable](./images/a.jpg)

**ຄຸນສົມບັດ:**

- Type A: ຕໍ່ກັບຄອມພິວເຕີ
- Type B: ຕໍ່ກັບ Arduino
- ສາມາດສົ່ງຂໍ້ມູນແລະໄຟຟ້າໄດ້ພ້ອມກັນ

**ຕົວຢ່າງການນໍາໃຊ້:** ເຊື່ອມຕໍ່ Arduino ເຂົ້າກັບ Arduino IDE ເພື່ອອັບໂຫລດໂປຣແກຣມແລະເບິ່ງຜົນການທໍາງານ.

---

## ▼ Wiring & Connectors

### 4. Jumper Wires (Male-to-Male)

**ຄຳອະທິບາຍ:** ສາຍສັ້ນມີຫົວເປັນເຂັມສອງຂ້າງ ໃຊ້ເຊື່ອມຕໍ່ອຸປະກອນໃນ breadboard.

**ການໃຊ້ງານ:** ຕໍ່ລະຫວ່າງຈຸດຕ່າງໆໃນ breadboard ຫລືຈາກ Arduino ໄປ breadboard.

![Jumper Wires MM](./images/Jumper_Wires.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ຕໍ່ GND ຈາກ Arduino ເຂົ້າກັບ power rail ຂອງ breadboard.

---

### 5. Jumper Wires (Male-to-Female)

**ຄຳອະທິບາຍ:** ສາຍມີຫົວເປັນເຂັມຂ້າງໜຶ່ງ ແລະຮູອີກຂ້າງໜຶ່ງ.

**ການໃຊ້ງານ:** ເຊື່ອມຕໍ່ລະຫວ່າງ Arduino pins ກັບ sensors ຫລືໂມດູນທີ່ມີຫົວເຂັມ.

![Jumper Wires MF](./images/Jumper_wires_male_to_female.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ຕໍ່ sensor DHT11 ເຂົ້າກັບ Arduino ໂດຍກົງ.

---

### 6. Jumper Wires (Female-to-Female)

**ຄຳອະທິບາຍ:** ສາຍມີຮູສອງຂ້າງ.

**ການໃຊ້ງານ:** ຕໍ່ລະຫວ່າງໂມດູນທີ່ມີຫົວເຂັມສອງອັນ.

![Jumper Wires FF](./images/Jumper_Wires_Female_to_Female.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ຕໍ່ລະຫວ່າງໂມດູນສອງອັນທີ່ມີຫົວ pin ທັງຄູ່.

---

### 7. 9V Battery Connector

**ຄຳອະທິບາຍ:** ຂໍ້ຕໍ່ສໍາລັບແບັດເຕີຣີ 9V ມີສາຍຕໍ່ເຂົ້າກັບ Arduino.

**ການໃຊ້ງານ:** ສະໜອງໄຟຟ້າໃຫ້ Arduino ເມື່ອບໍ່ມີ USB ຕໍ່ກັບຄອມພິວເຕີ.

![9V Battery Connector](./images/9V_Battery_Connector.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ໃຊ້ກັບໂປຣເຈັກທີ່ເຮັດວຽກແບບເຄື່ອນທີ່ໄດ້ເຊັ່ນ: ລົດຫຼີ້ນຄວບຄຸມດ້ວຍ Arduino.

---

## 💡 Basic Components

### 8. LEDs (Red, Yellow, Blue, RGB)

**ຄຳອະທິບາຍ:** Light Emitting Diode - ໄຟທີ່ສ່ອງສະຫວ່າງເມື່ອມີກະແສໄຟຟ້າຜ່ານ. ມີ 5 ສີແດງ, 5 ສີເຫລືອງ, 5 ສີຟ້າ, ແລະ 1 RGB.

**ການໃຊ້ງານ:** ສະແດງສະຖານະ, ສັນຍານ, ຫລືຜົນການປະມວນຜົນ. RGB LED ສາມາດສ້າງສີໄດ້ຫລາຍສີ.

![LED](./images/LEDs.jpg)

**Pinout:**

- **ຂາຍາວ (Anode +):** ຕໍ່ກັບຝັ່ງບວກຜ່ານ resistor
- **ຂາສັ້ນ (Cathode -):** ຕໍ່ກັບ GND

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໄຟສັນຍານຈະລາຈອນດ້ວຍ LED 3 ສີ (ແດງ, ເຫລືອງ, ຂຽວ).

---

### 9. RGB Module

**ຄຳອະທິບາຍ:** ໂມດູນ LED RGB ທີ່ມີ 4 pin ສາມາດສ້າງສີໄດ້ຫລາຍໂດຍການປະສົມສີແດງ, ຂຽວ, ຟ້າ.

**ການໃຊ້ງານ:** ໃຊ້ PWM ຄວບຄຸມຄວາມສະຫວ່າງຂອງແຕ່ລະສີເພື່ອສ້າງສີຕ່າງໆ.

![RGB Module](./images/RGB_Module.jpg)

**Pinout:**

- **R:** Red (ສີແດງ)
- **G:** Green (ສີຂຽວ)
- **B:** Blue (ສີຟ້າ)
- **GND:** ຕໍ່ດິນ

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໄຟມູດທີ່ປ່ຽນສີຕາມອຸນຫະພູມຫລືເວລາ.

---

### 10. Resistors (220Ω, 1kΩ, 10kΩ)

**ຄຳອະທິບາຍ:** ອຸປະກອນທີ່ຈໍາກັດກະແສໄຟຟ້າໃນວົງຈອນ ມີຄວາມຕ້ານທານຕ່າງໆ.

**ການໃຊ້ງານ:**

- 220Ω: ໃຊ້ກັບ LED
- 1kΩ: ໃຊ້ກັບ pull-down/pull-up
- 10kΩ: ໃຊ້ກັບ sensors ແລະປຸ່ມກົດ

![Resistor](./images/Resistors.webp)

**ການອ່ານຄ່າ:** ອ່ານຈາກແຖບສີ (Color Code)

**ຕົວຢ່າງການນໍາໃຊ້:** ຕໍ່ resistor 220Ω ລະຫວ່າງ Arduino pin ແລະ LED ເພື່ອປ້ອງກັນ LED ໄຫມ້.

---

### 11. Push Buttons (x4 with Lids)

**ຄຳອະທິບາຍ:** ປຸ່ມກົດຊົ່ວຄາວ (momentary switch) 4 ອັນພ້ອມຝາປິດສີຕ່າງໆ.

**ການໃຊ້ງານ:** ສົ່ງສັນຍານ input ເຂົ້າ Arduino ເມື່ອກົດ ໃຊ້ກັບ pull-up ຫລື pull-down resistor.

![Push Button](./images/Push_Buttons.jpg)

**Pinout:**

- 4 ຂາ: 2 ຄູ່ເຊື່ອມຕໍ່ພາຍໃນ
- ເມື່ອກົດ: ເຊື່ອມຕໍ່ທັງ 4 ຂາ
- ເມື່ອປ່ອຍ: ຕັດການເຊື່ອມຕໍ່

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງສະວິດກົດເປີດ-ປິດ LED ຫລືນັບຈໍານວນຄັ້ງທີ່ກົດ.

---

### 12. Potentiometer (5kΩ)

**ຄຳອະທິບາຍ:** ຕົວຕ້ານທານປັບໄດ້ (Variable Resistor) 5000 Ohm ໃຊ້ບິດປັບຄ່າ.

**ການໃຊ້ງານ:** ອ່ານຄ່າ analog (0-1023) ຈາກຕໍາແໜ່ງການບິດ ສາມາດປັບຄວາມສະຫວ່າງ, ຄວາມໄວ, ຫລືຄວາມດັງ.

![Potentiometer](./images/Potentiometer.jpg)

**Pinout:**

- ຂາ 1: VCC (5V)
- ຂາກາງ: Signal (ຕໍ່ Analog pin)
- ຂາ 3: GND

**ຕົວຢ່າງການນໍາໃຊ້:** ປັບຄວາມສະຫວ່າງຂອງ LED ດ້ວຍການບິດ potentiometer.

---

### 13. Active Buzzer

**ຄຳອະທິບາຍ:** ຕົວສ້າງສຽງທີ່ມີ oscillator ພາຍໃນ ສົ່ງສຽງຄົງທີ່ເມື່ອມີໄຟຟ້າ.

**ການໃຊ້ງານ:** ເປີດ-ປິດດ້ວຍ digitalWrite() ສຽງຄົງທີ່ປະມານ 2-4kHz.

![Active Buzzer](./images/Active_Buzzer.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງສັນຍານເຕືອນເມື່ອ sensor ກວດພົບອັນຕະລາຍ.

---

### 14. Passive Buzzer

**ຄຳອະທິບາຍ:** ຕົວສ້າງສຽງທີ່ບໍ່ມີ oscillator ຕ້ອງສົ່ງສັນຍານ PWM ເພື່ອສ້າງສຽງ.

**ການໃຊ້ງານ:** ໃຊ້ tone() ເພື່ອສ້າງສຽງຄວາມຖີ່ຕ່າງໆ ສາມາດຫລີ້ນເພງໄດ້.

![Passive Buzzer](./images/Passive_Buzzer.webp)

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງເຄື່ອງຫລີ້ນເພງງ່າຍໆ ຫລືສຽງເຕືອນຫລາຍແບບ.

---

## 📺 Displays & Output

### 15. 16x2 LCD Display

**ຄຳອະທິບາຍ:** ຈໍ LCD ຂະໜາດ 16 ຖັນ x 2 ແຖວ ສະແດງຕົວອັກສອນ.

**ການໃຊ້ງານ:** ສະແດງຂໍ້ຄວາມ, ຕົວເລກ, ແລະສັນຍາລັກພິເສດ. ຕ້ອງໃຊ້ລະຫວ່າງ 6-16 pins ຫລືໃຊ້ກັບ I2C adapter.

![LCD 16x2](./images/16x2_Character_LCD_Display.jpg)

**Pinout:**

- VSS: GND
- VDD: 5V
- V0: Contrast
- RS, RW, E: Control pins
- D0-D7: Data pins (ໃຊ້ D4-D7 ໃນໂໝດ 4-bit)

**ຕົວຢ່າງການນໍາໃຊ້:** ສະແດງອຸນຫະພູມ, ຄວາມຊື່ນ, ຫລືຂໍ້ຄວາມຈາກ sensors.

---

### 16. I2C Serial Adapter Board Module

**ຄຳອະທິບາຍ:** ໂມດູນແປງ LCD ໃຫ້ໃຊ້ I2C protocol ຫລຸດຈໍານວນ pins ຈາກ 16 ເຫລືອພຽງ 4 pins (VCC, GND, SDA, SCL).

**ການໃຊ້ງານ:** ຕໍ່ກັບດ້ານຫລັງຂອງ LCD ເພື່ອຄວບຄຸມດ້ວຍ I2C.

![I2C LCD Adapter](./images/I2C.webp)

**ຕົວຢ່າງການນໍາໃຊ້:** ເຊື່ອມຕໍ່ LCD ກັບ Arduino ດ້ວຍສາຍພຽງ 4 ເສັ້ນ.

---

### 17. 7-Segment Display (Common Cathode)

**ຄຳອະທິບາຍ:** ຈໍສະແດງຕົວເລກ 0-9 ແລະຕົວອັກສອນບາງຕົວ ປະກອບດ້ວຍ LED 7 ແທ່ງ (a-g) ແລະຈຸດທົດສະນິຍົມ.

**ການໃຊ້ງານ:** Common Cathode ໝາຍຄວາມວ່າ cathode ຮ່ວມກັນ ຕ້ອງສົ່ງ HIGH ໄປແຕ່ລະ segment ເພື່ອເປີດໃຊ້.

![7-Segment](./images/7.png)

**Pinout:**

- Segments a-g: ຄວບຄຸມແຕ່ລະແທ່ງ
- DP: Decimal Point
- Common pin: ຕໍ່ GND

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໂມງນັບຖອຍຫລັງ ຫລືສະແດງຄະແນນ.

---

### 18. 4-Digit 7-Segment Display

**ຄຳອະທິບາຍ:** ຈໍ 7-segment 4 ຕົວເລກ ໃຊ້ການສະແກນແບບ multiplexing ສະແດງຕົວເລກ 4 ຫຼັກ.

**ການໃຊ້ງານ:** ປ່ຽນການສະແດງຜົນຂອງແຕ່ລະຕົວເລກຢ່າງໄວເກີນກວ່າຕາຈະຈັບໄດ້ ເຮັດໃຫ້ເບິ່ງຄືສະແດງພ້ອມກັນ.

![4-Digit 7-Segment](./images/4_Digit.webp)

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໂມງດິຈິຕອນ (ຊົ່ວໂມງ:ນາທີ) ຫລືຕົວນັບ 0-9999.

---

### 19. 8x8 Dot Matrix Display

**ຄຳອະທິບາຍ:** ຈໍ LED ຂະໜາດ 8x8 = 64 LED ສາມາດສ້າງຮູບ, ຕົວອັກສອນ, ແລະແອນິເມຊັນ.

**ການໃຊ້ງານ:** ໃຊ້ການສະແກນ rows ແລະ columns ເພື່ອຄວບຄຸມ LED ທັງໝົດ.

![8x8 Matrix](./images/8x8.png)

**ຕົວຢ່າງການນໍາໃຊ້:** ສະແດງຂໍ້ຄວາມແບບເລື່ອນ, ໜ້າຍິ້ມ, ຫລືເກມງ່າຍໆ.

---

## 🔌 Sensors & Input Modules

### 20. Temperature and humidity sensor (DHT11)

**ຄຳອະທິບາຍ:** Sensor ວັດອຸນຫະພູມ (0-50°C) ແລະຄວາມຊື່ນ (20-90% RH).

**ການໃຊ້ງານ:** ສົ່ງຂໍ້ມູນດິຈິຕອນຜ່ານສາຍເສັ້ນດຽວ ຕ້ອງໃຊ້ library DHT.

![DHT11](./images/Temperature.jpg)

**Pinout:**

- VCC: 3-5V
- Data: Digital pin
- GND: Ground

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງສະຖານີອາກາດແບບງ່າຍສະແດງຜົນໃນ LCD.

---

### 21. LM35 Temperature Sensor

**ຄຳອະທິບາຍ:** Sensor ວັດອຸນຫະພູມແບບແອນາລັອກ ສົ່ງແຮງດັນ 10mV ຕໍ່ 1°C.

**ການໃຊ້ງານ:** ອ່ານຄ່າຈາກ analog pin ແລ້ວແປງເປັນອົງສາ (Celsius).

![LM35](./images/LM35.jpg)

**ຄຳນວນ:** Temperature = (analogRead × 5000/1024) / 10

**ຕົວຢ່າງການນໍາໃຊ້:** ຄວບຄຸມພັດລົມອັດຕະໂນມັດເມື່ອອຸນຫະພູມສູງ.

---

### 22. Tilt Sensor (x2)

**ຄຳອະທິບາຍ:** Sensor ກວດຫາການເອຽງ ມີລູກບານ mercury ຫລືໂລຫະພາຍໃນທີ່ເຊື່ອມຕໍ່ວົງຈອນເມື່ອເອຽງ.

**ການໃຊ້ງານ:** ອ່ານເປັນ digital input (HIGH/LOW) ຕາມຕໍາແໜ່ງ.

![Tilt Sensor](./images/Tilt_sensor.jpeg)

**ຕົວຢ່າງການນໍາໃຊ້:** ເຕືອນເມື່ອວັດຖຸລົ້ມ ຫລືສ້າງເກມຄວບຄຸມດ້ວຍການເອຽງ.

---

### 23. Photoresistor (LDR x3)

**ຄຳອະທິບາຍ:** Light Dependent Resistor - ຕົວຕ້ານທານທີ່ປ່ຽນຄ່າຕາມແສງສະຫວ່າງ (ແສງຫລາຍ = ຕ້ານທານຕ່ໍາ).

**ການໃຊ້ງານ:** ອ່ານຄ່າ analog ດ້ວຍ voltage divider circuit.

![LDR](./images/Photoresistor.webp)

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໄຟເປີດອັດຕະໂນມັດເມື່ອມືດ (Street light).

---

### 24. PIR Sensor

**ຄຳອະທິບາຍ:** Passive Infrared Sensor - ກວດຫາການເຄື່ອນໄຫວຂອງຄົນ/ສັດຈາກຄວາມຮ້ອນທີ່ປ່ຽນແປງ.

**ການໃຊ້ງານ:** ສົ່ງສັນຍານ HIGH ເມື່ອກວດພົບການເຄື່ອນໄຫວ.

![PIR Sensor](./images/pir2.jpg)

**Pinout:**

- VCC: 5V
- OUT: Digital signal
- GND: Ground
- ປຸ່ມປັບ: Sensitivity ແລະ Delay time

**ຕົວຢ່າງການນໍາໃຊ້:** ລະບົບຮັກສາຄວາມປອດໄພ ຫລືເປີດໄຟເມື່ອມີຄົນຜ່ານ.

---

### 25. Ultrasonic Module (HC-SR04)

**ຄຳອະທິບາຍ:** Sensor ວັດໄລຍະທາງດ້ວຍຄື່ນສຽງຄວາມຖີ່ສູງ (ultrasonic) 2-400cm.

**ການໃຊ້ງານ:** ສົ່ງຄື່ນສຽງແລະວັດເວລາທີ່ສະທ້ອນກັບມາ.

![Ultrasonic](./images/Ultrasonic_module.webp)

**Pinout:**

- VCC: 5V
- Trig: Trigger pulse
- Echo: Echo pulse
- GND: Ground

**ສູດຄໍານວນ:** Distance (cm) = Duration (μs) / 58

**ຕົວຢ່າງການນໍາໃຊ້:** ລົດຫລີກລ່ຽງອຸປະສັກ, ວັດລະດັບນໍ້າໃນຖັງ.

---

### 26. Sound Sensor

**ຄຳອະທິບາຍ:** Sensor ກວດຫາສຽງດ້ວຍໄມໂຄໂຟນ ສົ່ງທັງແບບ analog (ລະດັບສຽງ) ແລະ digital (ເກີນກໍານົດ).

**ການໃຊ້ງານ:** ອ່ານລະດັບສຽງແວດລ້ອມຫລືກວດພົບສຽງດັງ.

![Sound Sensor](./images/Sound_sensor.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ເປີດໄຟດ້ວຍການກົບມື, ວັດລະດັບສຽງດັງ.

---

### 27. Water Sensor

**ຄຳອະທິບາຍ:** Sensor ກວດຫານໍ້າ ມີຮ່ອງໂລຫະທີ່ວັດຄວາມຕ້ານທານເມື່ອຖືກນໍ້າ.

**ການໃຊ້ງານ:** ສົ່ງຄ່າ analog ຕາມລະດັບນໍ້າ.

![Water Sensor](./images/Water_sensor.webp)

**ຕົວຢ່າງການນໍາໃຊ້:** ເຕືອນນໍ້າຮົ່ວ, ກວດສອບຝົນຕົກ, ຄວບຄຸມລະດັບນໍ້າ.

---

### 28. Flame Sensor

**ຄຳອະທິບາຍ:** Sensor ກວດຫາແສງອິນຟາເຣດຈາກໄຟ ໃຊ້ photodiode ທີ່ສັງເກດເຫັນຄວາມຍາວຄື່ນ 760-1100nm.

**ການໃຊ້ງານ:** ສົ່ງສັນຍານ digital LOW ເມື່ອພົບໄຟ.

![Flame Sensor](./images/Flame_sensor.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ລະບົບເຕືອນໄຟໄໝ້, ຫຸ່ນຍົນດັບໄຟ.

---

### 29. RFID Module (RC522)

**ຄຳອະທິບາຍ:** Radio Frequency Identification - ໂມດູນອ່ານບັດ/ແທັກ RFID ຄວາມຖີ່ 13.56MHz.

**ການໃຊ້ງານ:** ສື່ສານດ້ວຍ SPI protocol ອ່ານ UID ແລະຂໍ້ມູນໃນບັດ.

![RFID RC522](./images/RFID_module.webp)

**Pinout:**

- SDA, SCK, MOSI, MISO: SPI pins
- IRQ: Interrupt (ບໍ່ໃຊ້ສ່ວນຫລາຍ)
- GND, RST, 3.3V

**ຕົວຢ່າງການນໍາໃຊ້:** ລະບົບຄວບຄຸມການເຂົ້າອອກ, ລະບົບລົງທະບຽນເວລາ.

---

### 30. RFID Tag/Card

**ຄຳອະທິບາຍ:** ບັດ RFID ຫລືແທັກທີ່ມີ chip ແລະເສົາອາກາດພາຍໃນ ແຕ່ລະອັນມີ UID ເປັນເອກະລັກ.

**ການໃຊ້ງານ:** ເອົາໃກ້ກັບ RFID reader ເພື່ອອ່ານຂໍ້ມູນ.

![RFID Tag](./images/RFID_tag.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ກຸນແຈເປີດປະຕູ, ບັດສະມາຊິກ, ລະບົບຊໍາລະເງິນ.

---

### 31. Infrared Receiver (IR)

**ຄຳອະທິບາຍ:** ຕົວຮັບສັນຍານອິນຟາເຣດຄວາມຖີ່ 38kHz ຈາກລີໂມດ.

**ການໃຊ້ງານ:** ຮັບສັນຍານແລະແປງເປັນຂໍ້ມູນດິຈິຕອນ ຕ້ອງໃຊ້ library IRremote.

![IR Receiver](./images/Infrared_receiver.png)

**Pinout:**

- OUT: Signal
- GND: Ground
- VCC: 5V

**ຕົວຢ່າງການນໍາໃຊ້:** ຄວບຄຸມໂປຣເຈັກດ້ວຍລີໂມດໂທລະພາບ.

---

## 🎮 Remote & Control

### 32. Infrared Remote Control

**ຄຳອະທິບາຍ:** ລີໂມດຄວບຄຸມທາງໄກດ້ວຍ IR ມີປຸ່ມຕ່າງໆ ແຕ່ລະປຸ່ມສົ່ງລະຫັດເປັນເອກະລັກ.

**ການໃຊ້ງານ:** ກົດປຸ່ມສົ່ງສັນຍານ IR ໄປຫາ receiver.

![IR Remote](./images/infrared_remote_control.jpg)

**ຕົວຢ່າງການນໍາໃຊ້:** ຄວບຄຸມ LED, servo, ຫລືແອັບພລິເຄຊັນຕ່າງໆທາງໄກ.

---

### 33. Joystick Module

**ຄຳອະທິບາຍ:** ໂມດູນຄັນຄວບຄຸມ 2 ແກນ (X, Y) ພ້ອມປຸ່ມກົດ (Z).

**ການໃຊ້ງານ:** ອ່ານຄ່າ analog ຈາກ VRx, VRy (0-1023) ແລະ digital ຈາກ SW.

![Joystick](./images/Joystick_module.webp)

**Pinout:**

- GND, +5V
- VRx: Analog X
- VRy: Analog Y
- SW: Button

**ຕົວຢ່າງການນໍາໃຊ້:** ຄວບຄຸມລົດຫລີ້ນ, ເກມ, ຫລືຫຸ່ນຍົນ.

---

### 34. 4x4 Matrix Keyboard Module

**ຄຳອະທິບາຍ:** ແປ້ນພິມ 16 ປຸ່ມ (4 ແຖວ x 4 ຖັນ) ຕົວເລກ 0-9 ແລະ A-D, \*, #.

**ການໃຊ້ງານ:** ສະແກນ rows ແລະ columns ເພື່ອກວດຫາປຸ່ມທີ່ກົດ ໃຊ້ library Keypad.

![Matrix Keypad](./images/Matrix-Keypad-4x4.webp)

**ຕົວຢ່າງການນໍາໃຊ້:** ລະບົບລະຫັດຜ່ານ, ເຄື່ອງຄິດເລກ, ໂທລະສັບ.

---

### 35. Relay Module

**ຄຳອະທິບາຍ:** ໂມດູນສະວິດໄຟຟ້າກໍາລັງ ຄວບຄຸມອຸປະກອນ AC/DC ແຮງດັນສູງດ້ວຍສັນຍານ 5V.

**ການໃຊ້ງານ:** ສົ່ງ HIGH ເພື່ອເປີດ relay (ເຊື່ອມຕໍ່ NO-COM), LOW ເພື່ອປິດ.

![Relay Module](./images/Relay_module.webp)

**Pinout:**

- VCC, GND: 5V power
- IN: Control signal
- COM, NO, NC: Contact terminals

**ຕົວຢ່າງການນໍາໃຊ້:** ຄວບຄຸມໄຟບ້ານ, ພັດລົມ, ມໍເຕີ 220V.

---

## ⚙ Motors & Drivers

### 36. Servo Motor

**ຄຳອະທິບາຍ:** ມໍເຕີທີ່ຄວບຄຸມມຸມໄດ້ (0-180°) ດ້ວຍສັນຍານ PWM.

**ການໃຊ້ງານ:** ສົ່ງ pulse width ຕ່າງໆ (1-2ms) ເພື່ອຕັ້ງມຸມ.

![Servo Motor](./images/Servo_Motor.jpg)

**Pinout:**

- Brown/Black: GND
- Red: VCC (4.8-6V)
- Orange/Yellow: Signal

**ຕົວຢ່າງການນໍາໃຊ້:** ແຂນຫຸ່ນຍົນ, ປ່ອງປະຕູ, ກ້ອງຖ່າຍຮູບແບບ pan-tilt.

---

### 37. Stepper Motor

**ຄຳອະທິບາຍ:** ມໍເຕີທີ່ໝູນເປັນກ້າວໆ (steps) ຄວບຄຸມຕໍາແໜ່ງແລະຄວາມໄວໄດ້ແມ່ນຍໍາ. ປົກກະຕິແມ່ນ 28BYJ-48 ມີ 2048 steps ຕໍ່ຮອບ (ພ້ອມ gear ratio 64:1).

**ການໃຊ້ງານ:** ໃຊ້ driver board (ULN2003) ຄວບຄຸມ ສາມາດໝູນທັງສອງທິດທາງ ຄວບຄຸມຈໍານວນກ້າວແລະຄວາມໄວໄດ້.

![Stepper Motor](./images/Stepper_motor.webp)

**ຄຸນສົມບັດ:**

- **Voltage:** 5V DC
- **Steps per Revolution:** 2048 (with gear reduction)
- **Step Angle:** 5.625° (64 steps per revolution at motor shaft)
- **5 Wires:** 4 coils + common wire

**Pinout (28BYJ-48):**

- **Pink/Orange:** Coil 1
- **Yellow:** Coil 2
- **Blue:** Coil 3
- **Red:** Common (VCC)
- **Orange/Pink:** Coil 4

**ຕົວຢ່າງການນໍາໃຊ້:**

- ເຄື່ອງພິມ 3D (ຄວບຄຸມແກນ X, Y, Z)
- ເຄື່ອງ CNC
- ຫຸ່ນຍົນທີ່ຕ້ອງການຄວາມແມ່ນຍໍາສູງ
- ກ້ອງຖ່າຍຮູບແບບໝູນອັດຕະໂນມັດ

**ຕົວຢ່າງ Code:**

```cpp
#include <Stepper.h>

// ກໍານົດຈໍານວນ steps ຕໍ່ຮອບ
const int stepsPerRevolution = 2048;

// ສ້າງ object (IN1, IN3, IN2, IN4)
Stepper myStepper(stepsPerRevolution, 8, 10, 9, 11);

void setup() {
  // ຕັ້ງຄວາມໄວ (RPM)
  myStepper.setSpeed(10);
}

void loop() {
  // ໝູນທວນເຂັມໂມງ 1 ຮອບ
  myStepper.step(stepsPerRevolution);
  delay(1000);

  // ໝູນຕາມເຂັມໂມງ 1 ຮອບ
  myStepper.step(-stepsPerRevolution);
  delay(1000);
}
```

---

### 38. Stepper Motor Driver Board (ULN2003)

**ຄຳອະທິບາຍ:** ບອດຂັບມໍເຕີ stepper ແບບ 4 coils ມີ LED ສະແດງສະຖານະການເຮັດວຽກ.

**ການໃຊ້ງານ:** ເຊື່ອມຕໍ່ Arduino 4 pins ກັບ IN1-IN4 ເພື່ອຄວບຄຸມການໝູນ.

![ULN2003 Driver](./images/Stepper_motor_driver_board.webp)

**Pinout:**

- IN1-IN4: Control inputs
- Power: 5-12V
- Motor connector: 5-pin ຕໍ່ກັບ stepper motor

**ຕົວຢ່າງການນໍາໃຊ້:** ຄວບຄຸມ 28BYJ-48 stepper motor ດ້ວຍ Arduino ໃຫ້ໝູນແມ່ນຍໍາ.

---

## 🔴 ICs & Modules

### 39. Real-time Clock Module (DS1302)

**ຄຳອະທິບາຍ:** ໂມດູນໂມງເວລາແທ້ຈິງທີ່ມີແບັດເຕີຣີສໍາຮອງ ເກັບຂໍ້ມູນວັນທີ ແລະເວລາ (ວິນາທີ, ນາທີ, ຊົ່ວໂມງ, ວັນ, ເດືອນ, ປີ).

**ການໃຊ້ງານ:** ສື່ສານຜ່ານ 3-wire serial interface ຕ້ອງໃຊ້ library DS1302.

![DS1302 RTC](./images/Real-time_Clock_Module_DS1302.jpg)

**Pinout:**

- VCC: 5V
- GND: Ground
- CLK: Clock
- DAT: Data
- RST: Reset/CE

**ຕົວຢ່າງການນໍາໃຊ້:** ສ້າງໂມງປຸກ, ລະບົບບັນທຶກເວລາ, ຕາຕະລາງເວລາອັດຕະໂນມັດ.

---

### 40. 74HC595 Shift Register Chip

**ຄຳອະທິບາຍ:** IC ຂະຫຍາຍ output ຈາກ 3 pins ເປັນ 8 outputs ໂດຍໃຊ້ການເລື່ອນບິດ (shift register).

**ການໃຊ້ງານ:** ສົ່ງຂໍ້ມູນແບບ serial ເຂົ້າໄປທີລະບິດ ເພື່ອຄວບຄຸມ 8 outputs ພ້ອມກັນ. ສາມາດຕໍ່ແບບ cascade ເພື່ອເພີ່ມ outputs ຫລາຍຂຶ້ນ.

![74HC595](./images/74HC595_Chip.webp)
**Pinout ສໍາຄັນ:**

- **DS (Pin 14):** Serial Data Input
- **SHCP (Pin 11):** Shift Clock
- **STCP (Pin 12):** Storage/Latch Clock
- **Q0-Q7 (Pins 15,1-7):** 8 Parallel Outputs
- **Q7' (Pin 9):** Serial Data Output (cascade)
- **OE (Pin 13):** Output Enable (ຕໍ່ GND)
- **MR (Pin 10):** Master Reset (ຕໍ່ VCC)

**ວິທີເຮັດວຽກ:**

1. ສົ່ງຂໍ້ມູນເຂົ້າ DS ທີລະບິດ
2. Pulse SHCP ເພື່ອເລື່ອນບິດ
3. Pulse STCP ເພື່ອສົ່ງຂໍ້ມູນອອກ outputs

**ຕົວຢ່າງການນໍາໃຊ້:**

- ຄວບຄຸມ LED ຫລາຍໆດວງດ້ວຍ pins ໜ້ອຍ
- ຄວບຄຸມ 7-segment display ຫລາຍຕົວ
- ຂະຫຍາຍ outputs ຂອງ Arduino

**ຕົວຢ່າງ Code:**

```cpp
// ກໍານົດ pins
int dataPin = 8;   // DS
int latchPin = 9;  // STCP
int clockPin = 10; // SHCP

void setup() {
  pinMode(dataPin, OUTPUT);
  pinMode(latchPin, OUTPUT);
  pinMode(clockPin, OUTPUT);
}

void loop() {
  // ເປີດ LED ທຸກດວງ
  digitalWrite(latchPin, LOW);
  shiftOut(dataPin, clockPin, MSBFIRST, 0xFF);
  digitalWrite(latchPin, HIGH);
  delay(1000);

  // ປິດ LED ທຸກດວງ
  digitalWrite(latchPin, LOW);
  shiftOut(dataPin, clockPin, MSBFIRST, 0x00);
  digitalWrite(latchPin, HIGH);
  delay(1000);
}
```
