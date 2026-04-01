# 💬 Realtime Chat App

This project is a **one-to-one realtime chat application** built using **JavaScript and Supabase**. It demonstrates how modern messaging systems work using a **database-driven and event-based architecture**.

---

## 🚀 Overview

The application allows users to:

* Log in with a username
* Start a conversation with another user
* Send and receive messages instantly in realtime

All messages are synchronized across multiple clients, ensuring a consistent chat experience.

---

## ⚙️ How It Works

The system follows a simple and reliable flow:

* A user sends a message
* The message is stored in the database
* A realtime event is triggered
* All connected clients fetch updated data
* Messages are displayed in the correct order

The database acts as the **single source of truth**, which ensures:

* No duplication of messages
* No ordering issues
* Consistent chat view across tabs/devices

---

## 🧠 Key Concepts

* **Realtime Communication:** Uses event-driven updates instead of manual refresh
* **Client-Server Sync:** All clients stay in sync via database events
* **Deterministic Ordering:** Messages are always shown in correct sequence
* **Scalable Design:** Simple architecture that can be extended to production systems

---

## 💡 Purpose of the Project

This project was built to understand:

* How messaging systems work internally
* How realtime data synchronization is handled
* How to design a stable and consistent chat system

---

## 🚀 Future Improvements

* Seen/Delivered indicators
* Typing status
* Online/offline presence
* Enhanced UI and user experience
