# 🚀 BFHL REST API

This is a **REST API** built with **Node.js + Express** for the BFHL assignment.  
It accepts an array in the request body and returns details such as even/odd numbers, alphabets, special characters, sum, and a formatted string.

---

## 📌 Features
- Splits input array into:
  - Even numbers
  - Odd numbers
  - Alphabets (converted to uppercase)
  - Special characters
- Returns sum of numbers (as string)
- Concatenates alphabets in **reverse order with alternating caps**
- Always returns:
  - `is_success`
  - `user_id` in format: `{fullname_ddmmyyyy}`
  - `email`
  - `roll_number`

---

## 📌 Tech Stack
- **Node.js**
- **Express.js**
- Hosted on **Render**

---

## 📌 Endpoint
Base URL:https://bajajtest-s5wv.onrender.com/bfhl

### POST `/bfhl`
**Request Body:**
```json
{
  "data": ["a","1","334","4","R","$"]
}

