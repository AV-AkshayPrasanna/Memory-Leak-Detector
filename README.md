<div align="center">

# 🧠 Memory Leak Detector

### Understand memory management. Track allocations. Spot potential leaks.

A clean, interactive browser-based simulation that brings an Operating Systems concept to life.

[🚀 **Launch Live Demo**](https://av-akshayprasanna.github.io/Memory-Leak-Detector/)

</div>

---

## ✨ What is it?

**Memory Leak Detector** is an educational web project created for the **Operating Systems (21CSC202J) mini-project** at **SRM Institute of Science and Technology (SRMIST)**.

It simulates memory allocation and deallocation so you can explore what happens when memory blocks are allocated, released, or left active. Run the detection step to flag allocations that have not been released.

> [!NOTE]
> This is a **browser-based simulation** for learning purposes. It does not inspect real operating-system processes or detect memory leaks inside running applications.

## 🚀 Try it live

### 👉 [Open the Memory Leak Detector Demo](https://av-akshayprasanna.github.io/Memory-Leak-Detector/)

No installation needed—open the website and start experimenting.

## 🔍 Features

| Feature | What it does |
|---|---|
| 🧱 **Memory Allocation** | Add a named memory block and specify its size in KB. |
| ♻️ **Memory Deallocation** | Release a previously allocated block in the simulation. |
| 🚨 **Leak Detection** | Flag blocks that remain allocated when detection runs. |
| 📊 **Memory Summary** | View allocation counts, deallocation counts, active blocks, and active memory. |
| 🧾 **Allocation Tracker** | Review block sizes, allocation/release times, and current status. |
| 🧪 **Demo Scenario** | Load a sample scenario to explore the workflow quickly. |
| 🎨 **Responsive Dashboard** | Explore the project through a navy and olive-green interface. |

## 🧪 Try it in 60 seconds

1. Open the [live demo](https://av-akshayprasanna.github.io/Memory-Leak-Detector/).
2. Enter a block name, such as `bufferA`, and a size, such as `150` KB.
3. Select **Allocate** and click **Apply Operation**.
4. Add another block. Deallocate one and leave the other active.
5. Click **Detect Memory Leaks** to review unreleased allocations.
6. Click **Reset** to clear the simulation and try again.

**Tip:** You can also click **Load Demo** to populate a sample scenario.

## 🛠️ Built with

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</div>

- **HTML** — page structure
- **CSS** — layout, styling, and responsive presentation
- **JavaScript** — interactive memory-operation simulation

## 💻 Run locally

Want to try it without cloning the repository? **[Open the live demo here](https://av-akshayprasanna.github.io/Memory-Leak-Detector/).**

To run the source locally, clone the repository:

```bash
git clone https://github.com/AV-AkshayPrasanna/Memory-Leak-Detector.git
cd Memory-Leak-Detector
```

Then open `index.html` in a modern web browser. No dependencies or build steps are required.

## 👥 Project team

Built collaboratively by a team of three as part of our Operating Systems coursework.

| Team member | Contribution |
|---|---|
| **M. Dev Aryan** | Frontend & UI Development |
| **S. Kaushik** | Logic & Integration |
| **A.V. AkshayPrasanna** | Testing & Presentation |

## 🎓 Academic context

- **Course:** Operating Systems — **21CSC202J**
- **Institution:** SRM Institute of Science and Technology (SRMIST)
- **Project type:** Educational mini-project

## 🌱 What we learned

- Memory allocation and deallocation concepts
- Tracking active memory blocks and simulated usage
- Identifying unreleased allocations in a controlled simulation
- Building an interactive front end with HTML, CSS, and JavaScript
- Collaborating to turn a core OS concept into a usable prototype

---

<div align="center">

### Thanks for checking out our project! 💚

**[🌐 Try the live demo](https://av-akshayprasanna.github.io/Memory-Leak-Detector/)**

*Built for learning, experimenting, and making Operating Systems concepts easier to explore.*

</div>
