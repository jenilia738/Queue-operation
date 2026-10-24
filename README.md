# Queue Playground 🎢

An interactive, single-file web playground designed to visualize and contrast **Linear Queues** and **Circular Queues**. Built with modern vanilla JavaScript, CSS, and SVG.

**🔗 Live demo:** https://jenilia738.github.io/Queue-operation/

## ✨ Features

* **Linear Queue View:** Visualizes front, rear, and the classic "wasted space" problem when elements are dequeued.
* **Circular Queue View:** Features an interactive SVG ring graphic showing how rear wraps around using modulo arithmetic `(rear + 1) % SIZE`.
* **Versus / Comparison Mode:** Type once and watch how both queues handle identical inputs side-by-side. Includes an automated demo script.
* **Full Operations:** Enqueue, Dequeue, Peek, Display and Clear, with overflow and underflow messages.
* **Neo-Brutalist Aesthetic:** Vibrant color palette, chunky borders, and smooth micro-animations.
* **Mobile Friendly:** Works on phones and desktops.

## 📊 Linear vs Circular

| | Linear Queue | Circular Queue |
|---|---|---|
| Space reuse | No, freed slots are wasted | Yes, rear wraps around |
| Move rear | `rear++` | `rear = (rear + 1) % SIZE` |
| Move front | `front++` | `front = (front + 1) % SIZE` |
| Full check | `rear == SIZE - 1` | `(rear + 1) % SIZE == front` |
| Empty check | `front == rear` | `front == -1` |
| Memory use | Poor | Efficient |


## 🛠️ Tech Stack

* **HTML5**
* **CSS3** (Custom properties, Flexbox, Grid)
* **JavaScript** (ES6)
* **SVG** (For circular queue rendering)


## 🎯 Purpose

Created for learning, exploring, and visualising data structures.