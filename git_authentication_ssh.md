# GitHub Authentication with SSH

## 🧭 Overview

Password authentication is no longer supported for Git operations over HTTPS.

Instead, you should use **SSH keys** for secure and seamless authentication with GitHub.

---

## 🚀 Step 1: Generate SSH Key

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

* Press Enter to accept defaults
* Optionally add a passphrase

---

## 🚀 Step 2: Start SSH Agent and Add Key

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
```

---

## 🚀 Step 3: Copy Public Key

```bash
pbcopy < ~/.ssh/id_ed25519.pub
```

---

## 🚀 Step 4: Add Key to GitHub

Go to:
https://github.com/settings/keys

* Click **New SSH key**
* Give it a name (e.g. "MacBook")
* Paste your key
* Save

---

## 🚀 Step 5: Configure SSH (Recommended)

Create or edit:

```bash
~/.ssh/config
```

Add:

```text
Host *
  AddKeysToAgent yes
  UseKeychain yes
  IdentityFile ~/.ssh/id_ed25519
```

Set permissions:

```bash
chmod 600 ~/.ssh/config
```

---

## 🚀 Step 6: Switch Repo to SSH

Check current remote:

```bash
git remote -v
```

If it shows HTTPS, update it:

```bash
git remote set-url origin git@github.com:USERNAME/REPO_NAME.git
```

---

## 🚀 Step 7: Test Connection

```bash
ssh -T git@github.com
```

Expected output:

```text
Hi USERNAME! You've successfully authenticated...
```

---

## 🚀 Step 8: Push Code

```bash
git push
```

You should NOT be prompted for a username/password.

---

## ⚠️ Common Issues

* Still using HTTPS remote
* Copied wrong key (must be `.pub`)
* Forgot to add key to GitHub
* SSH key not added to agent

---

## 🧭 Summary

| Step | Action             |
| ---- | ------------------ |
| 1    | Generate SSH key   |
| 2    | Add key to agent   |
| 3    | Copy public key    |
| 4    | Add to GitHub      |
| 5    | Configure SSH      |
| 6    | Switch repo to SSH |
| 7    | Test connection    |
| 8    | Push code          |

---

## 💡 Final Note

Once set up, SSH removes the need to enter credentials and makes Git workflows seamless.

This is the recommended setup for all developers.
