<div align="center">

# 🧹 Free Up RAM on Windows with RAMMap

**Clear cached memory in under a minute, using a free official Microsoft tool.**

![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Tool](https://img.shields.io/badge/Tool-RAMMap-blueviolet?style=for-the-badge)
![Price](https://img.shields.io/badge/Price-Free-brightgreen?style=for-the-badge)

</div>

---

## 📖 What is this?

Windows keeps a lot of data in RAM as **cache** so apps open faster. Sometimes that cache piles up and leaves less memory for the things you actually want to run.

**RAMMap** is a free tool from Microsoft's Sysinternals suite. It lets you manually clear that cached memory in just a few clicks.

---

## 🚀 Step-by-Step Guide

### 1️⃣ Download RAMMap

Go to the official Microsoft page and download the tool:

👉 **[Download RAMMap (Microsoft Sysinternals)](https://learn.microsoft.com/en-us/sysinternals/downloads/rammap)**

<div align="center">
  <img src="https://i.imgur.com/EjblAdy.png" alt="Download RAMMap" width="700">
</div>

### 2️⃣ Extract the ZIP

Once the download finishes, **right-click the ZIP file → Extract All**.

You will get a few files inside the folder:

<div align="center">
  <img src="https://i.imgur.com/qunjIFU.png" alt="Extracted RAMMap files" width="700">
</div>

### 3️⃣ Open RAMMap

Open the extracted folder and run:

```
RAMMap.exe
```

> 💡 If Windows asks for permission, click **Yes**. RAMMap needs admin rights to clear memory.

### 4️⃣ Empty the memory

At the top of the RAMMap window, click the **Empty** menu, then click these two options:

| Order | Option to click |
|:-----:|-----------------|
| 1️⃣ | **Empty Working Sets** |
| 2️⃣ | **Empty Standby List** |

That's it. Done! ✅

---

## 👀 How to Check That It Worked

Want to see the changes? Here's how:

1. Press **`Ctrl + Shift + Esc`** to open **Task Manager**
2. Go to the **Performance** tab
3. Click **Memory**
4. Look at the **In use** and **Cached** values

If **In use** and **Cached** went down compared to before, **you did it!** 🎉

### 📊 Before vs After

| ❌ Before | ✅ After |
|:---------:|:--------:|
| <img src="https://i.imgur.com/wvec2gi.png" alt="Task Manager before" width="400"> | <img src="https://i.imgur.com/fyeGPsb.png" alt="Task Manager after" width="400"> |

> 📸 **Tip:** Check these numbers *before* and *after* using RAMMap so you can see the difference clearly.

---

## ⚠️ Good to Know

- ✔️ RAMMap is made by **Microsoft**, so it's safe to use.
- 🔄 The effect is **temporary**. Windows will slowly fill the cache again as you use your PC.
- 🐢 Apps may open a little slower right after clearing, because the cache needs to rebuild.

---

<div align="center">

⭐ **Found this helpful? Give the repo a star!** ⭐

</div>
