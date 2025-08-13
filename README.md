# Phoenix In-Warranty Flow – Postman Collection

This repository contains the **Postman collection** and **environment files** for automating the *Phoenix In-Warranty Flow* API testing.

---

## 📂 Project Contents
- `Inwarranty-flow Collection.postman_collection.json` → Postman collection with all API requests & test scripts.
- `QA.postman_environment.json` → Environment file with variables for base URL, tokens, and dynamic data.
- `testData.csv` → Data file for **data-driven testing** in Postman Collection Runner / Newman.

---

## 🛠 Prerequisites
- [Postman](https://www.postman.com/downloads/) (v10+ recommended)
- [Node.js](https://nodejs.org/) (for Newman CLI)
- [Newman](https://github.com/postmanlabs/newman) installed globally:
```bash
npm install -g newman
