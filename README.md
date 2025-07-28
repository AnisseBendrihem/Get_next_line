# 📄 get_next_line

> A function to read a line from a file descriptor, implemented as part of the 42 School curriculum.

---

## 🧠 Objective

The goal of `get_next_line` is to:

- Efficiently read files **line by line**, regardless of file size.
- Handle **multiple file descriptors** simultaneously.
- Manage **buffers**, memory allocation, and newlines correctly.
- Avoid memory leaks and segmentation faults at all costs.

---

## 🔧 Function Prototype

```c
char *get_next_line(int fd);
