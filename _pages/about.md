---
permalink: /
title: "Welcome to my Academic Website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;900&display=swap" rel="stylesheet">

<div class="homepage-header">
  <div class="cinematic-box">
    <h1 class="animated-name">Naseer Muhammad</h1>
    <p class="animated-title">
      <span id="typed-subtitle">|</span>
    </p>
  </div>
</div>




Thanks for visiting my website!  
Here you can find information about my background, research, and academic journey.

---

# About Me

I am actively seeking a **PhD position** in the research field of **optimal control of quantum systems, superconducting quantum circuits, and quantum optics**.  

- Passionate researcher in the **Optimal Control of Hybrid Quantum Systems**  
- Strong background in **Quantum Optics** and **Quantum Mechanics**  
- Skilled in **Python (QuTiP, Qiskit)**, **C++**, and quantum computing frameworks  
- Winner of the **Best Presenter Award** at the [International Physics Seminar](https://ips2024.snf-unj.ac.id/), June 2024  

---

# Education

- **M.Sc. Physics (CGPA: 3.68/4.00)** — [Universitas Indonesia](https://www.ui.ac.id/en/)  
- **B.Sc. Applied Physics** — [Federal Urdu University of Arts, Science and Technology, Islamabad](https://fuuastisb.edu.pk/)  
- **Associate Bachelor’s (Physics & Mathematics)** — [University of the Punjab](https://www.pu.edu.pk/)  

---

#  Research Interests

- Nitrogen-Vacancy (NV) centers in diamond  
- Superconducting quantum circuits  
- Quantum optics and hybrid systems  

---

# Current Role

Since **August 2024**, I have been working as a **Physics Lecturer** at  
[F.G Sir Syed College, Mall Road, Saddar, Rawalpindi](https://fgssc.edu.pk/),  
teaching undergraduate courses in:  
- *Quantum Mechanics*  
- *Electromagnetism*  

---
<script>
const subtitles = [
  "Physicist",
  "Quantum Systems",
  "Quantum Optics",
  "Quantum Computing"
];

let i = 0;
let j = 0;
let currentText = "";
let isDeleting = false;
const typingSpeed = 120;
const pauseTime = 1500;

function type() {
  const subtitle = subtitles[i];
  if (isDeleting) {
    currentText = subtitle.substring(0, j--);
  } else {
    currentText = subtitle.substring(0, j++);
  }

  document.getElementById("typed-subtitle").textContent = currentText;

  if (!isDeleting && j === subtitle.length + 1) {
    isDeleting = true;
    setTimeout(type, pauseTime);
  } else if (isDeleting && j === 0) {
    isDeleting = false;
    i = (i + 1) % subtitles.length;
    setTimeout(type, 300);
  } else {
    setTimeout(type, typingSpeed);
  }
}

type();
</script>


