# Program and Absolute Paths - pwn.college

**Description:**  
In this challenge, the goal was to execute a program named `run` located inside the `/challenge` directory using its absolute path.

The program is located at:  
`/challenge/run`

---

**Solution:**  
Since the program must be executed using its absolute path, I ran:

```bash
/challenge/run
```

---

**Result:**  
The program executed successfully and returned the flag.

---

**What I Learned:**  
- Understanding directory structure in Linux  
- Absolute paths with nested directories  
- Executing programs using full paths like `/challenge/run`