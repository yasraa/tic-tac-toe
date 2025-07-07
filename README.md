
### 🧠 Game Logic

* The game uses a **3x3 grid** represented by 9 boxes.
* Players take turns placing either **"O"** or **"X"** in an empty box.
* The game tracks turns using a boolean flag `turn0` to alternate between "O" and "X".
* After every move, the game checks for a winning combination using predefined **winning patterns** (horizontal, vertical, diagonal).
* If a player wins, further input is disabled using the `disableboxes()` function.
* Game outcome is logged in the console (can be extended to display visually).

---

### 🔧 Core JavaScript Features Used

* `querySelectorAll()` to select all grid boxes
* `forEach()` loop to add click event listeners to each box
* Conditional logic to alternate turns
* Array iteration to check winning patterns
* DOM manipulation to update text and disable boxes

---


### 📚 Learning Objectives

* Understand basic game development logic in JavaScript
* Practice conditional statements, functions, and event listeners
* Learn how to dynamically update and interact with the DOM

---

### 🚀 Future Improvements (Optional)

* Display winning message on the screen
* Add a restart button
* Track player scores
* Improve UI/UX with animations

---

Let me know if you want the matching `HTML` and `CSS` files for this to complete your GitHub repo setup!
