# Arduino Nano Servo Tester

A simple servo tester using an Arduino Nano.  
This project moves a servo motor smoothly from **0° to 180°** and back again, changing by **1 degree each step**.

Perfect for testing:
- Servo movement
- Servo direction
- Wiring
- Power stability

---

## Tools & Parts

### Hardware
- Arduino Nano
- Servo motor
- Breadboard (optional)
- Jumper wires
- USB cable for Arduino

### Software
- Arduino IDE

---

## Wiring

### Connect the servo:

**Servo wire colors may vary**

- **Brown / Black** → GND on Arduino Nano
- **Red** → 5V on Arduino Nano
- **Orange / Yellow / White (signal)** → D9 on Arduino Nano

---

## Step-by-Step

### 1. Place the Arduino Nano
Connect the Arduino Nano to your breadboard or keep it ready beside your workspace.

### 2. Connect Ground
Connect the servo **GND wire** to **GND** on the Nano.

### 3. Connect Power
Connect the servo **5V wire** to **5V** on the Nano.

### 4. Connect Signal
Connect the servo **signal wire** to **D9**.

### 5. Plug in USB
Connect the Nano to your computer with USB.

### 6. Open Arduino IDE
Start Arduino IDE.

### 7. Select Board
Choose:

**Tools → Board → Arduino Nano**

### 8. Select Port
Choose your Nano COM port:

**Tools → Port**

### 9. Upload
Upload the servo tester sketch.

### 10. Test
The servo should:

- Start at **0°**
- Move smoothly to **180°**
- Move smoothly back to **0°**
- Repeat forever

---

## Notes

### Servo shaking?
Possible causes:
- Loose wire
- Not enough power
- Servo arm blocked

### Servo not moving?
Check:
- Signal wire on **D9**
- Correct board selected
- USB connected

### Moving wrong direction?
Rotate the servo horn or adjust mounting.

---

## Result

Your servo should sweep smoothly back and forth and repeat continuously.
