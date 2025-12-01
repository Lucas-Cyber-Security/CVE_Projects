# CVE Projects & Security Notes

This repo is where I document short projects around recent CVEs.  
My goal is to take vulnerabilities that are actively being patched or talked about, break down what’s actually going on, reproduce the behavior when possible, and show how to fix or mitigate it.  

This is mainly a learning space for me, but also a portfolio of hands-on security work that shows my process, how I think through problems, and how I approach real-world vulnerabilities.

---

## 📌 What You'll Find Here

- Summaries of each CVE  
- How the vulnerability works in simple terms  
- My reproduction steps or PoC tests (only in safe, isolated environments)  
- Notes on how the issue can be detected, patched, or mitigated  
- Short reflections about what I learned or found interesting  


---

## 🔍 Current Projects

### **CVE-2025-64459 — Django ORM SQL Injection via `_connector`**
A recent SQL injection issue affecting multiple Django versions.  
I cover what causes it, how the injection happens, how to safely reproduce it, and what the patched versions fix.

More CVEs will be added as I work through them.


---

## ⚠️ Disclaimer

All testing is done on isolated environments with no production data.  
Nothing here is intended for misuse.  
This repo is strictly for learning and professional development.

---

## 📝 Structure

Each CVE will have its own folder with:

- A short writeup  
- Any PoC code or testing scripts  
- Notes, screenshots, or findings  

The main README will link to everything so it’s easy to browse.

---

Thanks for checking out the repo — more entries coming soon.
