# ⚡ VoidData Engine

> **A lightweight alternative to Firebase based on Cloudflare Workers.**  
> Create online games, messengers, and project showcases without having to worry about databases, complex access rules, and 1 MB limits.

---

## 🚀 Why is VoidData better than Firestore?

| Parameter | Firebase Firestore | VoidData Engine |
| :--- | :--- | :--- |
| **Document/file limit** | Strictly 1 MB | ** Up to 100 MB** |
| **Access Settings** | Dreary Security Rules | **Works out of the box (CORS\*)** |
| **Protection** | Setting up reCAPTCHA | **Built-in Cloudflare Turnstile** |
| **Complexity of implementation** | Heavy SDKs, configs | **One URL and a simple command for AI** |

---

# Quick start (In 10 seconds)

### Option 1. Via any neural network (ChatGPT / Gemini / Claude)
Copy this text, add your HTML/JS code, and send it to the AI chat.:

```text
Connect online to my project via Cloudflare Worker VoidData:
[https://voiddata.portalvrobloks3.workers.dev/](https://voiddata.portalvrobloks3.workers.dev/)

Mood:
1. Getting data via GET /projects
2. Publishing via POST /publish
3. Comments via POST /comment
4. Download files via GET /download?id=...
5. Live auto-update every 3 seconds.
