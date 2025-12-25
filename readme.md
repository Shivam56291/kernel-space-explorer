<div align="center">

<img src="https://raw.githubusercontent.com/MariaLetta/free-gophers-pack/master/characters/png/tux.png" width="150" alt="Linux Gopher">

# 🐧 Linux System Programming & Kernel

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=FCC624&center=true&vCenter=true&width=600&lines=Mastering+System+Calls;Exploring+Kernel+Space+vs+User+Space;Process+Lifecycle+%26+Memory+Layout;Multi-threading+%26+IPC+Mechanisms" alt="Typing SVG" />
</a>

<br/>

![Linux](https://img.shields.io/badge/Linux-Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-Language-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![POSIX](https://img.shields.io/badge/Standard-POSIX-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

<br/>

<a href="#-the-philosophy"><strong>The Why</strong></a> · <a href="#-learning-pathway"><strong>Pathway</strong></a> · <a href="#-tech-stack"><strong>Tools</strong></a>

</div>

---

### 🛡️ The Philosophy: Why System Programming?

Every CS student should master Linux System Programming because it is the **bridge between Hardware and Software**. Understanding the kernel isn't just about code—it's about understanding how the digital world _actually_ functions.

> "If you don't understand system calls and memory management, you are just writing code; when you understand the kernel, you are building systems."

---

### 🗺️ Learning Roadmap

I am documenting my progress through the core pillars of the Linux environment, moving from basic File I/O to complex Inter-Process Communication.

<div align="center">

| Module           | Core Concepts                                   | Practice Focus                          |
| :--------------- | :---------------------------------------------- | :-------------------------------------- |
| **📁 File I/O**  | `open()`, `read()`, `write()`, `lseek()`        | Low-level file manipulation & Atomicity |
| **🏗️ Processes** | `fork()`, `exec()`, `wait()`, `Zombie/Orphan`   | Lifecycle management & Memory Layout    |
| **🧠 Memory**    | Virtual Memory, Page Tables, `malloc` internals | Managing Process Address Space          |
| **📡 Signals**   | `SIGKILL`, `SIGUSR`, Signal Handlers            | Asynchronous event communication        |
| **🧵 Threads**   | `Pthreads`, Mutex, Condition Variables          | Concurrency & Race Condition resolution |
| **🔌 IPC**       | `Pipes`, `FIFOs`, `Shared Memory`, `Semaphores` | Cross-process data synchronization      |

</div>

---

### 🔍 Deep Dive: The Big Picture

During this phase, I focus on:

- **Atomicity & Race Conditions:** Learning why execution order matters in multi-tasking environments.
- **File Descriptors:** Mastering the internal tables that Linux uses to track every open resource.
- **The Execution Bridge:** Moving smoothly between **User Mode** (Safety) and **Kernel Mode** (Power).

---

### 🛠️ Tech Stack & Lab Tools

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,c,bash,vim,vscode,git" />
</div>

---

### ⚡ Hands-on Execution

```bash
# 1. Compile System Programs (using GCC)
gcc -o my_process main.c -lpthread

# 2. Trace System Calls
strace ./my_process

# 3. Monitor Process States
htop
```

<div align="center">

Author: Shivam

<p>Diving deep into the stack.</p>

<img src="https://www.google.com/search?q=https://raw.githubusercontent.com/MariaLetta/free-gophers-pack/master/characters/png/2.png" width="60">

</div>
