# 🧹 Riddance

> Batch script to **remove non-current local user accounts** — parses `whoami` and `net user`, deletes users whose RID does not match current user. Enables UAC (EnableLUA=1).

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 👤 **User Cleanup** | Deletes local users except current user |
| 🔒 **UAC** | Sets EnableLUA=1 |
| 📋 **RID Compare** | Compares user RIDs to avoid deleting self |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **Privileges** | Administrator |

---

## 🚀 Usage

```cmd
:: Run as Administrator
Riddance.cmd
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Tooling</sub>
</p>
