<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Tux.png" width="120" alt="Linux Tux">

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=FCC624&center=true&vCenter=true&width=600&lines=sudo+apt-get+install+knowledge;Mastering+System+Calls;Navigating+Kernel+Mode;Inter-Process+Communication;POSIX+Threads+Synchronization" alt="Typing SVG" />
</a>

<br/>

![Linux](https://img.shields.io/badge/Linux-Kernel_v5.x+-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![C](https://img.shields.io/badge/C-System_Programming-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![Glibc](https://img.shields.io/badge/Glibc-Library-004482?style=for-the-badge&logo=gnu&logoColor=white)
![Bash](https://img.shields.io/badge/Shell-Automation-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

</div>

---

### 🛡️ The Mission

> **"Operating Systems are the baseline of reality for software."**
> This repository documents a deep-dive into the Linux Kernel and System Programming. From the raw efficiency of C to the complex orchestration of the Kernel, I am exploring how hardware is tamed by code.

---

### 🗺️ System Engineering Roadmap

I am building my understanding of the OS layer by layer.

| Layer           | Core Pillars                                 | Implementation                    |
| :-------------- | :------------------------------------------- | :-------------------------------- |
| **📁 File I/O** | File Descriptors, Atomicity, Race Conditions | `open()`, `read()`, `write()`     |
| **🏗️ Process**  | Lifecycle, Memory Layout, Virtual Memory     | `fork()`, `exec()`, `wait()`      |
| **📡 Signals**  | Asynchronous Events, Signal Handlers         | `SIGKILL`, `SIGUSR`, `trap`       |
| **🧵 Threads**  | Pthreads, Mutex, Condition Variables         | `pthread_create()`, `sync`        |
| **🔌 IPC**      | Pipes, FIFOs, Shared Memory, Semaphores      | `msgget()`, `shmget()`, `semop()` |

---

### 🔍 Deep Dive Visualization

Understanding the boundary **Kernel Space**.

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Simplified_Structure_of_the_Linux_Kernel.svg/2560px-Simplified_Structure_of_the_Linux_Kernel.svg.png" width="80%" alt="Kernel Architecture">
</div>

---

### 🛠️ Lab Environment

<div align="center">
  <img src="https://skillicons.dev/icons?i=linux,c,vim,bash,git" />
</div>

---

### ⚡ Execution Commands

```bash
# Compile with system libraries
gcc -Wall -o lab_output main.c -lpthread

# Trace every system call made by the program
strace ./lab_output

# Check for memory leaks in Kernel allocations
valgrind ./lab_output
```

<div align="center">

Author: Shivam | Kernel Enthusiast & Systems Engineer

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Tux_Linux_mascotte_with_beak_upward_-_Milano_2022.jpg/640px-Tux_Linux_mascotte_with_beak_upward_-_Milano_2022.jpg" width="200"  alt="Linux Foundation">

"Talk is cheap. Show me the code." — Linus Torvalds 🐧

</div>
