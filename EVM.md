# 📌 Electronic Voting Machine using ESP8266 (ESP-NOW)

## 👤 Project By
**Name:** Muhammed Afkar M A  ,Ahban Ahmed , Albert Shibu 
**Course:** Diploma in Electronics Engineering  
**Institution:** Government Polytechnic College, Kasaragod  

---

## 📖 Introduction

This project is an **Electronic Voting Machine (EVM)** designed using two NodeMCU ESP8266 boards.  
It uses **ESP-NOW wireless communication** to securely send votes from the voter unit to the ballot unit.

The system includes voter authentication through confirmation and time lock, making it reliable and secure for small-scale elections and demonstrations.

---

## 🎯 Objective

- To design a wireless electronic voting system.
- To prevent multiple voting.
- To ensure vote confirmation before counting.
- To display results clearly.
- To provide a secure and simple voting process.

---

## 🧩 Components Used

| Sl. No | Component | Quantity |
|--------|-----------|----------|
| 1 | NodeMCU ESP8266 | 2 |
| 2 | OLED Display | 1 |
| 3 | Buzzer | 1 |
| 4 | Tactile Push Buttons | 8 |
| 5 | LED | 1 |
| 6 | Resistors | As required |
| 7 | Jumper Wires | As required |
| 8 | Power Supply | 2 |

---

## ⚙️ System Architecture

The system consists of two units:

### 1️⃣ Voter Unit
- 5 voting buttons
- Status LED
- ESP8266 transmitter

### 2️⃣ Ballot Unit
- ESP8266 receiver
- OLED display
- Buzzer
- Approve button
- Result button

Communication is done using **ESP-NOW protocol**.

---

## 🔄 Working Principle

### Step 1: Voting
- The voter presses one of the 5 buttons.
- The vote is sent wirelessly to the ballot unit.
- LED indicates vote sent.

### Step 2: Reception
- Ballot unit receives the vote.
- Buzzer beeps to indicate arrival.
- OLED shows pending status.

### Step 3: Approval
- Operator presses the approve button.
- Vote is confirmed and stored.

### Step 4: Voter Lock System
- Next voter cannot vote until previous vote is approved.
- Same voter cannot vote again within 3 seconds.
- Prevents multiple voting.

### Step 5: Result Display
- Result button shows current vote count on OLED.
- Long press clears all votes.

---

## 🔐 Security Features

✔ Voter Confirmation System  
✔ Time Lock (3 seconds)  
✔ One Vote at a Time  
✔ Manual Approval  
✔ Wireless Secure Communication  

These features help prevent fake and repeated voting.

---

## 💻 Communication Technology

### ESP-NOW
ESP-NOW is a low-power wireless communication protocol provided by Espressif.

Advantages:
- No WiFi connection required
- Low latency
- Secure data transmission
- Fast response

---

## 📊 Features

- Wireless voting
- Real-time confirmation
- OLED result display
- Buzzer alert
- Voter lock system
- Easy reset
- Low power consumption
- Portable design

---

## 🚀 Applications

- School elections
- College elections
- Club voting
- Society voting
- Demonstration models
- Educational projects

---

## 🌱 Future Improvements

- Add RFID/Fingerprint authentication
- Mobile/Web result display
- Cloud data storage
- Battery backup
- Encrypted voting
- Multi-station support

---

## ✅ Advantages

- Simple operation
- Low cost
- Secure system
- Portable
- Easy maintenance
- Scalable design

---

## ⚠️ Limitations

- Manual approval needed
- Limited range of ESP-NOW
- No permanent database
- Suitable for small-scale use only

---

## 📝 Conclusion

This project demonstrates a secure and reliable electronic voting system using ESP8266 and ESP-NOW.

It prevents multiple voting, ensures proper confirmation, and provides accurate result display.  
This system is suitable for educational and demonstration purposes.

---

## 🙏 Acknowledgement

I sincerely thank my teachers, institution, and friends for their guidance and support in completing this project successfully.

---

## 📚 References

- Espressif ESP8266 Documentation  
- Arduino IDE  
- ESP-NOW Official Guide  
- Online Technical Forums

---

