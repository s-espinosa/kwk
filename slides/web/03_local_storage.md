# Local Storage

---

# Learning Goals

* Set and get data from localStorage
* Get data from localStorage on page load; if there is none, have a default value
* Convert data to and from JSON

---

# Technical Vocabulary

* localStorage
* database
* client-side storage
* JSON
* persist
* domain

---

# Storing User Data

* What happens when you restart your todo list app?
* What would you like to happen?
* How do you usually save information that you'd like to review later?

---

# Two Ways to Store Data

* Client-side storage
* Server-side storage

---

# Turn & Talk: Favorite App

* What is your favorite or most go-to app? Why?
* Does it store any of your information?
* Do you think it's stored client-side or server-side?
* What would your experience with the app be like if it couldn't store any of your information?

---

# Advantages & Limitations

* Allows you to store information about a user that can persist when a page refreshes.
* Can't share information between different machines (e.g. your partner can't add a to-do to your list)
* Can only store strings in key-value pairs

---

# Methods

* *setItem():* Add an item to local storage.
* *getItem():* Get an item from local storage.
* *removeItem():* Remove an item from local storage.
* *clear():* Clear all items from local storage.

---

# Try It: Get, Set, Remove and Clear

Try running the following methods in your dev tools.

* localStorage.clear();
* localStorage.setItem('Karlie Kloss', 'Supermodel, Entrepreneur, Philanthropist');
* localStorage.getItem('Karlie Kloss');
* Refresh the page and try to get the item again: localStorage.getItem('Karlie Kloss');
* localStorage.removeItem('Karlie Kloss');
* localStorage.getItem('Karlie Kloss');
* localStorage.setItem('Kode With Klossy', 'inspires!');
* localStorage.getItem('Kode With Klossy');

---

# Try It: Color Picker

How do we use this in our JS files?

---

# Share

---

# JSON

* Standard format for data types in different languages converted to strings.
* Methods in JS:
    * JSON.stringify()
    * JSON.parse()

---

# Practice

See lesson plan.

