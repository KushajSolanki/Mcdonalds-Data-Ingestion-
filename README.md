# 🍔 McDonald's Real-time Data Ingestion Pipeline with Kafka & MongoDB

<p align="center">
  <img src="/Mcdonalds.png" alt="Pipeline Diagram" width="700"/>
</p>

This project showcases a real-time data ingestion architecture designed for McDonald's order and payment systems.

Using **Apache Kafka**, streaming data from `Orders` and `Payments` topics is ingested and processed via **KSQL** to generate a **Joined Stream** combining transactional details. The enriched data is then written to **MongoDB** using **Kafka Connect MongoDB Sink**, enabling real-time analytics and visualization through a **MongoDB-powered dashboard**. 

Development and stream simulation are handled via **Visual Studio Code** with a custom Python producer application.

---

## ✅ Key Components

- ⚡ **Kafka Streams** for real-time order-payment joins  
- 🧠 **KSQL** for stream processing and real-time data transformation  
- 🔗 **Kafka Connect** for seamless MongoDB integration  
- 📊 **MongoDB Dashboard** for real-time insights  
- 💻 **Python Application** (VS Code) to simulate Orders & Payments data

---

## 📁 Project Structure

