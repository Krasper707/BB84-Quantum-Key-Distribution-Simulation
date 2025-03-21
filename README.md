# **BB84 Quantum Key Distribution Simulation** 🔑💡  

This project implements the **BB84 quantum key distribution (QKD) protocol** using **Qiskit**.  
It simulates Alice and Bob securely sharing a secret key over a quantum channel.  

---

## **🚀 Features**  
✅ **Quantum Bit (Qubit) Encoding** – Alice encodes bits using **Z & X bases**  
✅ **Quantum Measurement** – Bob randomly selects bases to measure the qubits  
✅ **Key Sifting** – Only matching basis measurements are kept  
✅ **Error Checking** – Bob and Alice publicly compare a subset of bits to detect eavesdropping  
✅ **Final Secret Key Extraction**  

---

## **📌 Prerequisites**  
Make sure you have **Python 3.7+** and **Qiskit installed**.  

### **🔹 Install Qiskit**  
```bash
pip install qiskit qiskit-aer numpy
```

## 📜 How It Works

1️⃣ Alice generates random bits (0s and 1s) and random measurement bases (Z or X).

2️⃣ Alice encodes qubits based on the chosen bases.

3️⃣ Bob selects random bases and measures the qubits.

4️⃣ Alice & Bob compare their bases and keep only matching results.

5️⃣ They perform an optional eavesdropper check by publicly revealing a subset of bits.

6️⃣ Final shared secret key is established and used for secure communication.

## 📜 License
This project is licensed under the MIT License.


