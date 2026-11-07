# My_AI_Robot
# 🤖 My AI Robotics Roadmap (Microduck-like Project)

Այս ֆայլը իմ անձնական ուղեցույցն է AI Ռոբոտաշինության, Embedded Systems-ի և PCB դիզայնի աշխարհում:

## 📅 Ընթացիկ Ստուգաթերթ (Checklist)
- [ ] ՓՈՒԼ 1. Embedded Systems & Embedded Rust
- [ ] ՓՈՒԼ 2. Data Science & AI Math Foundations
- [ ] ՓՈՒԼ 3. Machine Learning & Reinforcement Learning
- [ ] ՓՈՒԼ 4. Full-Stack AI Robot Integration (Sim-to-Real)

---
## 🦀 ՓՈՒԼ 1. Embedded Systems & Embedded Rust
**Նպատակը:** Տիրապետել Rust-ին և կառավարել ESP32-ը `no_std` ռեժիմով:
- [ ] Սովորել Rust-ի հիմունքները (Ownership, Borrowing, Traits):
- [ ] Կարգավորել `esp-hal` միջավայրը ESP32-C3/S3-ի համար:
- [ ] Գրել կոդ՝ IMU MPU6050 սենսորից տվյալներ կարդալու համար:
- [ ] Կառավարել սերվոմատորները (PWM/UART):

## 📊 ՓՈՒԼ 2. Data Science & AI Math Foundations
**Նպատակը:** Մաթեմատիկական հիմքի ստեղծում և տվյալների ֆիլտրում:
- [ ] Սովորել Գծային հանրահաշիվ (Մատրիցներ, Վեկտորներ):
- [ ] Սովորել Մաթեմատիկական անալիզ (Ածանցյալներ, Gradient Descent):
- [ ] Ուսումնասիրել Կալմանի Ֆիլտրը (Kalman Filter):
- [ ] Մշակել սենսորների CSV տվյալները Rust `Polars` գրադարանով:

## 🤖 ՓՈՒԼ 3. Machine Learning & Reinforcement Learning
**Նպատակը:** Վիրտուալ ռոբոտի մարզում սիմուլյատորում:
- [ ] Սովորել Ուղիղ և Հակադարձ կինեմատիկա (Kinematics):
- [ ] Մոդելավորել ռոբոտի 3D կորպուսը (URDF ֆորմատ):
- [ ] MuJoCo / Isaac Lab սիմուլյատորում PyTorch-ով մարզել քայլքի մոդելը (RL):
- [ ] Արտահանել պատրաստի ԱԲ ուղեղը `.onnx` ֆորմատով:

## 🚀 ՓՈՒԼ 4. Full-Stack AI Robot Integration
**Նպատակը:** Բոլոր համակարգերի միավորում իրական ռոբոտի մեջ:
- [ ] Կարգավորել Orange Pi 3B-ն (Linux, NPU դրայվերներ):
- [ ] Գրել հիմնական ռոբոտի կառավարման ծրագիրը Rust-ով (`Candle` / `tract`):
- [ ] Օպտիմալացնել `.sh` սկրիպտները ավտոմատ մեկնարկի համար:
- [ ] Կատարել առաջին Sim-to-Real քայլքի փորձարկումը:
