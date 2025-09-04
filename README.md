```markdown
# 📝 React ToDo List

---

## 🚀 Features

- ✅ Add new tasks

- ✅ Delete existing tasks

- ✅ Move tasks up and down the list

- ✅ Update tasks in real time using React `useState`

---

## 💻 Technologies used

- React
- JavaScript (ES6+)

- CSS

---

## 📂 Project structure

```

src/
├─ components/
│ └─ TodoList.jsx
├─ css/
│ └─ ToDo.css
├─ App.jsx

````

- `TodoList.js` – The main React component for the ToDo list.
- `ToDo.css` – Styling the ToDo list.

---
## ⚡ Usage

* **Add task**: Enter your task in the input field and press **Add**.
* **Delete Task**: Click the **Delete** button next to the task.
* **Move Task Up**: Click the ☝ button to move the task up.
* **Move Task Down**: Click the 👇 button to move the task down.

---

## 🌟 Example Code Snippet

```jsx
function addTask() {
if (newTask.trim() !== "") {
setTasks((t) => [...t, newTask]);
setNewTask("");
}
}
```

This snippet shows how new tasks are added to the state array.

---

## 📫 Contact

If you have any questions or suggestions, feel free to reach out:

* GitHub: [AlexandruChet](https://github.com/AlexandruChet)

---

<h3 align="center">✨ Thanks for checking out my to-do list project! ✨</h3>
```
