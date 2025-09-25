---

# 🏥 Clinica Express – Backend API

In this project I’m building a **clinic backend system** using **Express.js**.
It’s a simple CRUD application for managing **technicians**, each having an **ID**, **CRM (unique)**, **name**, and **specialty**.

---

## 🛠 Tech Stack

* **Node.js** – Runtime environment
* **Express.js** – Web framework
* **PostgreSQL** – Database
* **Prisma** - ORM

---

## 📦 Installation

Clone this repository:

```bash
git clone https://github.com/MatCalixto/clinica-express.git
```

Go into the project folder:

```bash
cd clinica-express
```

Install dependencies:

```bash
npm install
```

Start development server:

```bash
npm run dev
```

---

## ▶️ Usage

Once running, the server will be available at:

```
http://localhost:3000
```

### API Endpoints (Technicians 👨‍⚕️👩‍⚕️)

| Method | Endpoint               | Description                |
| ------ | ---------------------- | -------------------------- |
| GET    | `/api/medicos`         | Get all technicians        |
| GET    | `/api/medicos/:id`     | Get a technician by CRM/ID |
| POST   | `/api/medicos`         | Add a new technician       |
| PUT    | `/api/medicos/:id`     | Update a technician’s data |
| DELETE | `/api/medicos/:id`     | Remove a technician        |

---
