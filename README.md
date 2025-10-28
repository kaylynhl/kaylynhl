# hey, i'm kaylyn 👋

i’m a computer science student at cornell engineering (class of 2026) with a business minor. i like building systems that *actually work at scale*; whether that’s a neural net that tracks bees, a tiny microcontroller that guards a door, or low-level code that keeps threads from fighting.

---

### 🐝 automated bee tracking pipeline
built for the napp robotics lab at cornell.  
i trained YOLOv8 models to detect tagged bees, estimate their direction, and flag pollen carriers.  
i also wrote python tools to sort and preprocess 20k+ images so labeling didn’t take forever; it cut annotation time by ~70%.  
now the data feeds into SQL tables for analysis on swarm behavior.

---

### 🔐 glowguard (embedded door alarm)
a door-mounted security prototype using the frdm-kl46z board.  
when the accelerometer detects motion, rgb leds flash red/orange; idle states glow green/blue.  
uses pwm, gpio interrupts, and some creative soldering.  
coded entirely in c with a custom event loop and timing routines.

---

### ⚙️ os process + locking simulator
implemented spinlocks, blocking locks, and process scheduling from scratch in c to understand concurrency at the kernel level.  
compared performance and starvation behaviors under different lock implementations.

---

### 💬 otome narrative engine
a little ocaml game engine that powers branching dialogue and choice-based stories.  
uses recursive data types and pure functions for scene handling.  
functional programming, but also fun.

---

### 🛠 tech i work with
**languages:** python, c, c++, java, sql, javascript, ocaml, bash  
**ml / vision:** pytorch, yolo, opencv, numpy  
**systems / infra:** docker, linux, ssh/vpn, ci/cd, postgres  
**security:** wireshark, metasploit, bettercap, virtualbox  
**frontend:** html, css, react (basics), accessibility-focused ui

---

### 🌱 learning next
- shipping pytorch models as real apps  
- moderation + trust & safety ml  
- scaling real-time systems

---

### 📫 find me
[linkedin](https://www.linkedin.com/in/kaylynlee/) • [email](mailto:khl62@cornell.edu) • [github](https://github.com/kaylynhl)

> looking for early-career or new-grad roles in ml, platform, systems, or cybersecurity.  
> us citizen • based in ny • open to relocate
