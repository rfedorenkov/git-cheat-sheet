#Git Cheat Sheet

# Headers:
---
# H1
## H2
### H3
#### H4
##### H5
###### H6
---

# Highlighting
---
Cursive text *stars* or _underline_

Bolt text **double stars** or __double underline__

Combined **stars and _underline_**

Two tildes for ~~strike text~~
---

# Lists
---
1. First menu
2. Second menu


* Not numbered menu
* Second point
---

# Links
---
[Google](https://google.com "Google")
---


# Code
---
```bash
touch file.txt
echo "Hello!" > file.txt
cat file.txt
```

```c
int main(void) {
    printf("Hello, World!");
    return 0;
}
```
---

# HEAD
---
File **HEAD** - one of .git service files folders. It points to the commit that was made last (which is what the newest one is). Inside HEAD is a link to the service file: _refs/heads/main_. If you look at this file, you can see the hash of the last commit. _e007f5035f113f9abca78fe2149c593959da5eb7_
---
