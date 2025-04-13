# 📝 TrelloBoardApi

This repository contains a Postman collection to demonstrate how to interact with the **Trello API**. It includes examples of:

- Creating a board
- Managing lists
- Handling cards

Useful for learning or automating Trello workflows using Postman and API tokens.

---

## 📦 Prerequisites

Before using the collection:

- **Trello account**  
  Sign up at [trello.com](https://trello.com)

- **Trello API Key and Token**  
  - Get your API key from: [Trello Developer Keys](https://trello.com/app-key)  
  - Follow the same page instructions to generate a token

- **Postman installed**  
  Download: [Postman](https://www.postman.com/downloads/)

---

## 🚀 Getting Started

### 1. Clone this Repository

```bash
git clone https://github.com/suba-learning/TrelloBoradApi.git
```

### 2. Import the Postman Collection

1. Open Postman
2. Click **Import**
3. Select the `.json` file from the `Postman Collections` folder
4. Done!

### 3. Set Up Environment Variables in Postman

Create a Postman environment and add the following:

| Variable   | Value                          |
|------------|--------------------------------|
| `api_key`  | Your Trello API Key            |
| `token`    | Your Trello API Token          |
| `base_url` | `https://api.trello.com/1`     |

---

## 🔧 Available API Requests

The Postman collection includes examples for:

### 📋 Boards
- Create a new board
- Get board details
- Delete a board

### 📂 Lists
- Create a list
- Get all lists on a board

### 🗂 Cards
- Create a card
- Get card details
- Update a card
- Delete a card

---

## 📚 Resources

- [Trello API Docs](https://developer.atlassian.com/cloud/trello/rest/)
- [Postman Docs](https://learning.postman.com/docs/)

---

## 🤝 Contributions

Feel free to fork, explore, and improve this repo. Pull requests are welcome!

---

## 📄 License

This project is intended for educational/demo purposes. No license attached.

---
