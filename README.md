# MongoDB Data Modeling – Cul d'Ampolla Optical Store

## 📌 Project Description

This project focuses on designing a **MongoDB NoSQL database** for managing the data of an optical store called **Cul d'Ampolla**.

The goal is to practice **data modeling in MongoDB**, using concepts such as **embedded documents and references between collections**.

The project contains **two exercises**, each modeling the data from a different perspective of the application interface.

---

## 📌 Exercise 1 – Customer Perspective

In this exercise the database is modeled from the **customer point of view**.

The main collection is **`customers`**, where each customer document contains their personal information and an embedded array of their **last purchases**.

This design allows easy retrieval of a customer's purchase history.

Main collections:

* `customers`
* `providers`

---

## 📌 Exercise 2 – Glasses Perspective

In this exercise the database is modeled from the **glasses point of view**.

The main collection is **`glasses`**, which contains the glasses information and an embedded array `bought_by` with the customers who purchased them.

This structure allows the system to easily display **which customers bought a specific pair of glasses**.

Main collections:

* `glasses`
* `customers`
* `providers`

---

## 🛠 Technologies

* MongoDB
* Mongosh (MongoDB Shell)
* MongoDB Database Tools
* Draw.io / Diagrams.net

---

## 📂 Repository Structure

```
mongoDB-estructura
│
├── Task1
│   ├── customers.json
│   ├── providers.json
│   └── customers_optica.png
│
└── Task2
    ├── glasses.json
    ├── customers.json
    ├── providers.json
    └── glasses_optica.png
