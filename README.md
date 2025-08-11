# **Smart Mirror: Personalized Reminders with Face Recognition**

---

## **About This Project**

Ever wished your mirror could do more than just show your reflection? This project turns an ordinary mirror into an **intelligent personal assistant**. Using **real-time facial recognition**, the mirror identifies the person standing in front of it and displays **personalized daily reminders** — no login, no buttons, just you and your mirror.

---

## **The Data**

All reminders are stored in a **MySQL database**, tagged to specific users and dates.

* **Face images** of registered users are stored locally for recognition.
* **Tasks/reminders** include a title, description, and date.
* Data is retrieved in real time whenever a user is recognized.

---

## **What I Did**

* Developed a **face recognition system** using **Python**, **OpenCV**, and **face\_recognition**.
* Created a **Flask web interface** to add and manage reminders.
* Integrated **MySQL** for persistent storage of user tasks.
* Designed a **real-time camera feed system** to identify users instantly.
* Displayed **daily reminders** only for the recognized person.

---

## **Technologies Used**

* **Python**
* **OpenCV**
* **face\_recognition** (dlib)
* **Flask** (web framework)
* **MySQL** (database)

---

## **Why This Project is Cool**

* Fully **personalized** — no two users see the same reminders.
* **Hands-free operation** — perfect for a real smart mirror.
* Uses **open-source tools** so anyone can learn and build on it.
