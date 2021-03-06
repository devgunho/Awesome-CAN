# Awesome CAN(Controller Area Network) (DevGun) π°π·

<p align="center">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"/>
</p>
<br/>

## Table of Contents

- OBD (On Board Diagnostics)
- ECU (Electronic Control Unit)
- Reference Paper
  - (2021) WINDS_A Wavelet-Based Intrusion Detection System for Controller Area Network (CAN)
- (2020) CANBus Traffic Anomaly Detection with LSTM and Autoencoders (`can-anomaly-detection`)

<br/>

<br/>

<br/>

## # OBD (On Board Diagnostics)

>https://m.blog.naver.com/suresofttech/221282372396

OBD(On Board Diagnostics)λ μλμ°¨μ μ κΈ°/μ μμ μΈ μλ μνλ₯Ό νμΈνκ³  μ μ΄νκΈ° μν μ§λ¨ κ·κ²©μΌλ‘ λ°°μΆκ°μ€μ κ΄λ ¨λ μμ€νμ κ°μνκ³ , ECUμ μ λ³΄λ₯Ό μ μ₯νμ¬ λ°°μΆκ°μ€μ μν₯μ μ£Όλ κ³ μ₯μ΄ λ°μνμ κ²½μ°, κ³ μ₯μ½λλ₯Ό κΈ°λ‘νκ³  ν΄λ¬μ€ν°μ κ²½κ³ λ±μ μ λ±νμ¬ μ°¨λ μ΄μ μ λ° μ λΉμκ° λ¬Έμ λ₯Ό μΈμνκ³  μ§λ¨μ ν  μ μλλ‘ λ§λ  μμ€νμ΄λ€.

OBDκ° λ°°κΈ°μ κ΄λ ¨λ μμ€νκ³Ό λΆνλ€μ λν μ€μν μ λ³΄λ₯Ό μ κ³΅νμ§λ§, OBD λμ λΉμ(1988)μ κΈ°μ μ  νκ³λ‘ ν¬ν¨λμ§ λͺ»ν ν­λͺ©λ€μ΄ μλ€.

κ·Έ ν κΈ°μ  λ°μ μ μνμ¬ μ§λ¨ ν  μ μλ λ²μκ° λμ΄μ§λ©΄μ CARB(California Air Resource Board) μ£Όλνμ λ ν¬κ΄μ μΈ OBD λ²κ·κ° μ μ λμλ€.

OBD νμ€μ κ·Έ ν λ³΄μμ κ±°μ³ OBD-β‘λΌλ μ΄λ¦μ κ°μ§ νμ¬μ νμ€μΌλ‘ λ°μ νκ² λμλ€.

OBD-β‘ κ·μ μμλ DLC(Data Link Cable) μ»€λ₯ν°μ ν΅μ μ¬μ, μ μμ μ΄ λΆνμ μ©μ΄μ κ³ μ₯μ½λλ₯Ό νμ€νμν΄μΌλ‘μ¨ λ³΄λ€ νΈνμ±μ λμκ³ , κ³ μ₯λ°μμ λ°°μΆκ°μ€κ° μ¦κ°λλ ν­λͺ©μ λν κ³ μ₯ νμ κΈ°μ€κ³Ό μ§λ¨ μλ Ήμ΄ μΆκ°λμ΄ κ°μ λμλ€.

νμ¬μ OBD-β‘ μμ€νμ μλμ°¨μ λ°°μΆκ°μ€ κ·μ λ λ¬Όλ‘  κ³ μ₯ μ§λ¨ μμ€νμΌλ‘ μ¬μ©λκ³  μμΌλ©°, λλ΅μ μΈ OBD-β‘μ μ κ² ν­λͺ© λ° κ³Όμ μ λ€μ κ·Έλ¦Όκ³Ό κ°λ€.

<p align="center">
    <img src="README.assets/obd1.png"/>
    <div align="center">OBD-β‘ μ μ κ² ν­λͺ© λ° κ³Όμ </div>
</p>

<br/>

<br/>

<br/>

## # ECU (Electronic Control Unit)

> https://www.mk.co.kr/news/business/view/2017/12/817633/

μμ§μ μ΄μ λ(engine control unit, ECU) λλ μμ§μ μ΄λͺ¨λ(engine control module, ECM)μ μμ§μ λ΄λΆμ μΈ λμμ λ€μνκ² μ μ΄νλ μλ² λλ μ₯μΉμ΄λ€.

κ°μ₯ λ¨μν ECUλ SI μμ§(Spark Ignition)μ ν­λ°μμ μ€λ¦°λμ μ°λ£λΆμ¬λμ μ μ΄νλλ° μ¬μ©λλ©°, νλμ λλΆλΆ μλμ°¨μ νμ¬λ μ’ λ λ³΅μ‘ν ννμ ECUλ μ ν μκΈ°, κ°λ³ λ²¨λΈ νμ΄λ°, ν°λ³΄μ°¨μ μμ μ‘°μ νλ λΆμ€ν° λ λ²¨, κΈ°ν μ£Όλ³μ₯μΉ λ±μ μ μ΄νλλ° μ¬μ©λλ€.

μλμ°¨ μ μμ μ΄κΈ°λ₯Ό λ»νλ ECU(Electronic Control Unit)λ μ¬λμΌλ‘ μΉλ©΄ λ¨Έλ¦¬μ ν΄λΉλλ λΆνμ΄λ€.

μλμ°¨ ECUλ μ»΄ν¨ν°μ μ€μμ²λ¦¬μ₯μΉ(CPU)λ₯Ό ν¬ν¨νλ©΄μ λ¬Όλ¦¬μ  μ μ΄ μμ­μΌλ‘ νμ₯λ κ°λμ΄λ€.

'μΈμ§(μΌμ)βμ°μ Β·λͺλ Ή(ECU)βμ€ν(μ‘μΆμμ΄ν°)'μ νλ¦μΌλ‘ λͺ¨ν°μ μ μμ₯μΉ, μ νμ₯μΉ, νμμ₯μΉ λ± μλμ°¨λ₯Ό μλνλ κΈ°λ₯μ νΉνλ κ²μ΄λ€.

ECUλ μλ ₯μ₯μΉμ μ μ₯μ₯μΉ, μ λ³΄μ²λ¦¬μ₯μΉμ μΆλ ₯μ₯μΉλ‘ κ΅¬μ±λλ€.

μ£Όν μ€μ μμ΄λ λ°μ΄ν° λ±μ μ£Όλ‘ νλ°μ± λ©λͺ¨λ¦¬(RAM)μ μ μ₯νκ³  λ°μ΄ν° μ²λ¦¬λ₯Ό μν μ΄μμ²΄μ  λ±μ λΉνλ°μ± λ©λͺ¨λ¦¬(ROM)μ μ μ₯νλ€.

μκ³ λ¦¬μ¦μ λ°λ₯Έ μ°μ°μ²λ¦¬λ₯Ό μν΄ κ³ μ±λ₯ μ λ³΄μ²λ¦¬μ₯μΉκ° μ μ©λκ³  μ€μλ λ±μ μν©μ κ°μ ν΄ λ°±μ μ₯μΉκ° μΆκ°λκΈ°λ νλ€.

μ°¨λ ν λλ μ½ 60κ°μμ 100μ¬ κ°μ ECUκ° μ¬μ©λλ€.

μ΄λ¬ν ECUλ€μ μκ³ κ΅¬μ‘°λ₯Ό κ°μΆκ³  κ³ μ  κΈ°λ₯λ μννλ©΄μ λ€λ₯Έ ECUλ€κ³Ό 'νμ‘°-μ μ΄'νκΈ°λ νλ€.

ACU(Air bag Control Unit)κ° μμ΄λ°±μ μ κ°νλ©΄ κΈ΄κΈκ΅¬λν΅μ μ₯μΉ(e-CALL)κ° μ¬κ³  μ λ³΄λ₯Ό κ΄μ μΌν°μ μλ μ μ‘νλ μμ΄λ€.

νμ΄λΈλ¦¬λμ°¨μ μ μ΄μ₯μΉμΈ HCU(Hybrid Control Unit)λ μμ§μ μ΄μ₯μΉ, λͺ¨ν°μ μ΄μ₯μΉ, μ°¨μ²΄μμΈμ μ΄μ₯μΉμ λ°°ν°λ¦¬μ μ΄μ₯μΉ λ± μ°¨λ κ°λΆμ μ£Όμ μ μ΄μ₯μΉμ κ°κ°μκ³Ό λ°°ν°λ¦¬ μΆ©μ  λ±μ μλ λͺλ Ήμ λ΄λ¦¬λ κ΅¬μ‘°λ₯Ό κ°μΆκ³  μλ€.

μ΅κ·Όμλ μλ‘ μ°κ΄μ± λμ μ¬λ¬ κ° ECUκ° ν΅ν©λλ μΆμΈλ€.

μ±κΈμ½μ΄ 8κ°κ° μ κ°κ° μννλ μμμ μ₯ν(OctaΒ·μ¬λ) μ½μ΄ νλκ° μ²λ¦¬νλ λ±μ λ°©μμΌλ‘ λ°μ΄ν° μ²λ¦¬μ κ³΅κ° νμ© ν¨μ¨μ±μ λμ΄λ κ²μ΄λ€.

νΉν μΈκ³΅μ§λ₯κ³Ό λ₯λ¬λ λ±μ΄ μ μ©λλ λ―Έλμ μμ μμ¨μ£Όν, μ»€λ₯ν°λμΉ΄λ νμΈ΅ κ³ μ°¨μμ μΈ μ μ΄ μ±λ₯μ΄ μκ΅¬λλ€. λ°λΌμ λΆμ°λ ECUλ₯Ό ν©μΉκ³  ν΅μ  κΈ°λ₯μ μ€μνν΄μΌ νλ€.

ECU ν΅ν© κ³Όμ μμ μ΄μμ²΄μ μ ν΅μ  λ°©μ, μ½λ©μΈμ΄ λ±μ΄ μΌκ΄μ± μκ² μ μ©λΌμΌ νλ€.

μ΄κ²μ΄ μ΄λ€μ ΈμΌ λ€μμ μμ²΄λ€μ΄ νλ ₯ κ°λ°νλ μλμ°¨ μ°μμμ μ€κ³ κΈ°κ°μ λ¨μΆμν€κ³  μ±λ₯κ³Ό νμ§κΉμ§ νλ³΄ν  μ μλ€.

μ΄λ₯Ό μν΄ κΈλ‘λ² μμ±μ°¨ μ μ‘°μ¬λ€μ μλμ°¨ μννΈμ¨μ΄ κ΅­μ νμ€ νλ«νΌ(AUTOSAR)μ κΈ°λ°μΌλ‘ μλμ°¨ μννΈμ¨μ΄λ₯Ό μ€κ³νκ³  μλ€.

<br/>

<br/>

<br/>

## # (2021) WINDS_A Wavelet-Based Intrusion Detection System for Controller Area Network (CAN)

### ABSTRACT

μ°¨λμλ μ λ°μ μΈ μμ€ν κΈ°λ₯ λ° μ°κ²°μ±μ λμ΄κΈ° μν΄ ECU(μ μ μ μ΄ μ₯μΉ)κ° μ₯μ°©λμ΄ μλ€. κ·Έλ¬λ, μ¦κ°νλ μ°κ²°μ μ¬μ΄λ² κ³΅κ²©μ λ¬΄λ°©λΉ μνμ λ΄λΆ CAN(Controller Area Network)μ λΈμΆμν¨λ€. IDS(Intrusion Detection System)λ κΈ°μ‘΄ ECUλ₯Ό μμ νμ§ μκ³  λμ νΈλν½ μ€λ²ν€λλ₯Ό μ λ°νμ§ μμΌλ©° CAN λ€νΈμν¬ μμ± λ©μμ§λ₯Ό μλ³νκΈ° μν΄ μ μλ κ°λ λͺ¨λμ΄λ€. κΈ°μ‘΄μ IDS μ κ·Ό λ°©μμ μκ°κ³Ό μ£Όνμ μκ³κ°μ μμ‘΄νμ¬ λμ νμ κ²½λ³΄μ¨λ‘ μ΄μ΄μ§λ λ°λ©΄, μ΅μ²¨λ¨ μλ£¨μμ μ°¨λ μμ‘΄μ±μΌλ‘ μΈν΄ μ΄λ €μμ κ²ͺμ μ μλ€. λ³Έ λΌλ¬Έμ CAN λ€νΈμν¬μ μ μ‘ ν¨ν΄μ λΆμνμ¬ CAN νΈλν½μμ λμ λ³νλ₯Ό μ°ΎκΈ° μν Wavelet κΈ°λ° μ κ·Ό λ°©μμ μ μνλ€. μ μλ WOLD(Wavelet-based Intrusion Detection System)λ λ κ°μ λλ¦½μ μΈ μ°κ΅¬ μΌν°μ μ€μ  μ°¨λ νΈλν½μ μ¬μ©νμ¬ λ€μν κ³΅κ²© μλλ¦¬μ€μμ νμ€νΈλλ λμμ ν©μ± κ³΅κ²©μ μ¬μ©νμ¬ λ³΄λ€ ν¬κ΄μ μΈ κ³΅κ²© μλλ¦¬μ€λ‘ νμ₯μν¨λ€. μ΄ κΈ°μ μ μ΅μ²¨λ¨ μλ£¨μ λ° κΈ°μ€ μ£Όνμ λ°©λ²κ³Ό λΉκ΅νμ¬ νκ° λ° λΉκ΅λλ€. μ€ν κ²°κ³Όμ λ°λ₯΄λ©΄ WINDλ λ?μ νμ κ²½λ³΄λ₯Ό μμ±νλ λμμ κ³ μ ν μ κ·Ό λ°©μμ ν΅ν΄ λ€μν μ°¨λμ μ μ©ν  μ μλ μ°¨λ λλ¦½μ μΈ μλ£¨μμ μ κ³΅νλ€.

<br/>

<br/>

<br/>

## # (2020) LSTM-Based Intrusion Detection System for In-Vehicle Can Bus Communications

**Publisher: IEEE**

### ABSTRACT

The modern automobile is a complex piece of technology that uses the Controller Area Network (CAN) bus system as a central system for managing the communication between the electronic control units (ECUs). Despite its central importance, the CAN bus system does not support authentication and authorization mechanisms, i.e., CAN messages are broadcast without basic security features. As a result, it is easy for attackers to launch attacks at the CAN bus network system. Attackers can compromise the CAN bus system in several ways including Denial of Service (DoS), Fuzzing and Spoofing attacks. It is imperative to devise methodologies to protect modern cars against the aforementioned attacks. In this paper, we propose a Long Short-Term Memory (LSTM)-based Intrusion Detection System (IDS) to detect and mitigate the CAN bus network attacks. We generate our own dataset by first extracting attack-free data from our experimental car and by injecting attacks into the latter and collecting the dataset. We use the dataset for testing and training our model. With our selected hyper-parameter values, our results demonstrate that our classifier is efficient in detecting the CAN bus network attacks, we achieved an overall detection accuracy of 99.995%. We also compare the proposed LSTM method with the Survival Analysis for automobile IDS dataset which is developed by the Hacking and Countermeasure Research Lab, Korea. Our proposed LSTM model achieves a higher detection rate than the Survival Analysis method.

---

νλ μλμ°¨λ μ μ μ μ΄ μ₯μΉ(ECU) κ°μ ν΅μ μ κ΄λ¦¬νκΈ° μν μ€μ μμ€νμΌλ‘ CAN(Controller Area Network) λ²μ€ μμ€νμ μ¬μ©νλ λ³΅μ‘ν κΈ°μ μλλ€. ν΅μ¬μ μΈ μ€μμ±μλ λΆκ΅¬νκ³  CAN λ²μ€ μμ€νμ μΈμ¦ λ° κΆν λΆμ¬ λ©μ»€λμ¦μ μ§μνμ§ μμ΅λλ€. μ¦, CAN λ©μμ§λ κΈ°λ³Έ λ³΄μ κΈ°λ₯ μμ΄ λΈλ‘λμΊμ€νΈλ©λλ€. κ²°κ³Όμ μΌλ‘ κ³΅κ²©μκ° CAN λ²μ€ λ€νΈμν¬ μμ€νμμ κ³΅κ²©μ μμνκΈ° μ½μ΅λλ€. κ³΅κ²©μλ μλΉμ€ κ±°λΆ(DoS), νΌμ§ λ° μ€νΈν κ³΅κ²©μ λΉλ‘―ν μ¬λ¬ κ°μ§ λ°©λ²μΌλ‘ CAN λ²μ€ μμ€νμ μμμν¬ μ μμ΅λλ€. μ μ ν κ³΅κ²©μΌλ‘λΆν° νλ μλμ°¨λ₯Ό λ³΄νΈνκΈ° μν λ°©λ²λ‘ μ κ³ μνλ κ²μ΄ νμμ μλλ€. λ³Έ λΌλ¬Έμμλ CAN λ²μ€ λ€νΈμν¬ κ³΅κ²©μ νμ§νκ³  μννκΈ° μν΄ LSTM(Long Short-Term Memory) κΈ°λ° IDS(Intrusion Detection System)λ₯Ό μ μν©λλ€. λ¨Όμ  μ€ν μ°¨λμμ κ³΅κ²©μ΄ μλ λ°μ΄ν°λ₯Ό μΆμΆνκ³  νμμ κ³΅κ²©μ μ£Όμνκ³  λ°μ΄ν° μΈνΈλ₯Ό μμ§νμ¬ μμ²΄ λ°μ΄ν° μΈνΈλ₯Ό μμ±ν©λλ€. μ°λ¦¬λ λͺ¨λΈμ νμ€νΈνκ³  νλ ¨νκΈ° μν΄ λ°μ΄ν° μΈνΈλ₯Ό μ¬μ©ν©λλ€. μ°λ¦¬κ° μ νν νμ΄νΌνλΌλ―Έν° κ°μ μ¬μ©νμ¬ κ²°κ³Όλ λΆλ₯κΈ°κ° CAN λ²μ€ λ€νΈμν¬ κ³΅κ²©μ κ°μ§νλ λ° ν¨μ¨μ μ΄λ©° 99.995%μ μ μ²΄ κ°μ§ μ νλλ₯Ό λ¬μ±νμμ λ³΄μ¬μ€λλ€. λν μ μλ LSTM λ°©λ²μ νκ΅­μ ν΄νΉ λ° λμ± μ°κ΅¬μμμ κ°λ°ν μλμ°¨ IDS λ°μ΄ν° μΈνΈμ λν μμ‘΄ λΆμκ³Ό λΉκ΅ν©λλ€. μ μν LSTM λͺ¨λΈμ μμ‘΄ λΆμ λ°©λ²λ³΄λ€ λ λμ νμ§μ¨μ λ¬μ±ν©λλ€.

<br/>

### LSTM-Based Network Intrusion Detection System

For our investigation, we use python PyCharm IDE 2019.2.2 and Keras [21] with TensorFlow as backend. We conduct our experiment with Intel Core i7 CPU 2.20 GHz, 16 GB RAM, Windows 10 (64-bit), and NVIDIA GeForce GTX 1050. We use the *categorical_cross entropy* as loss function. The *Nadam* optimizer is applied with a learning rate of 0.0001, the rest of the parameters conserve their default values and *softmax* is used as an activation function output. Tables 3 and 4 provide the experimental settings regarding attacks detection based on LSTM binary and multiclass classification models. We preprocessed raw CAN dataset before inputting the model, we train the model by providing 80% of the elements and we test the classifier with 20% of the elements. After training, the classifier can classify the attack and benign class elements. Fig. 10 schematizes the deep neural network model wherein we can input the CAN bus data into the input layer and, after preprocessing, the classifier will provide the output as a benign or attack class.

---

μ‘°μ¬λ₯Ό μν΄ λ°±μλλ‘ TensorFlowμ ν¨κ» Python PyCharm IDE 2019.2.2 λ° Keras [21]λ₯Ό μ¬μ©ν©λλ€. Intel Core i7 CPU 2.20GHz, 16GB RAM, Windows 10(64λΉνΈ) λ° NVIDIA GeForce GTX 1050μΌλ‘ μ€νμ μνν©λλ€. categorical_cross μνΈλ‘νΌλ₯Ό μμ€ ν¨μλ‘ μ¬μ©ν©λλ€. *Nadam* μ΅ν°λ§μ΄μ λ 0.0001μ νμ΅λ₯ λ‘ μ μ©λκ³  λλ¨Έμ§ λ§€κ°λ³μλ κΈ°λ³Έκ°μ μ μ§νλ©° *softmax*λ νμ±ν ν¨μ μΆλ ₯μΌλ‘ μ¬μ©λ©λλ€. ν 3κ³Ό 4λ LSTM λ°μ΄λλ¦¬ λ° λ€μ€ ν΄λμ€ λΆλ₯ λͺ¨λΈμ κΈ°λ°μΌλ‘ ν κ³΅κ²© νμ§μ λν μ€ν μ€μ μ μ κ³΅ν©λλ€. λͺ¨λΈμ μλ ₯νκΈ° μ μ μμ CAN λ°μ΄ν° μΈνΈλ₯Ό μ¬μ  μ²λ¦¬νκ³  μμμ 80%λ₯Ό μ κ³΅νμ¬ λͺ¨λΈμ νμ΅νκ³  μμμ 20%λ‘ λΆλ₯κΈ°λ₯Ό νμ€νΈν©λλ€. νλ ¨ ν λΆλ₯κΈ°λ κ³΅κ²© λ° μμ± ν΄λμ€ μμλ₯Ό λΆλ₯ν  μ μμ΅λλ€. κ·Έλ¦Ό 10μ CAN λ²μ€ λ°μ΄ν°λ₯Ό μλ ₯ κ³μΈ΅μ μλ ₯ν  μ μλ μ¬μΈ΅ μ κ²½λ§ λͺ¨λΈμ λμννκ³  μ μ²λ¦¬ ν λΆλ₯κΈ°λ μμ± λλ κ³΅κ²© ν΄λμ€λ‘ μΆλ ₯μ μ κ³΅ν©λλ€.