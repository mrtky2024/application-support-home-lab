# SSH

## 1. Generate SSH Key(private and public)
ssh-keygen -t ed25519 -C "your-email@example.com"
---
## 2. Copy Public Key
cat ~/.ssh/id_ed25519.pub
---
## 3. Add Public Key to GitHub
GitHub → Settings → SSH and GPG keys → New SSH Key
---
## 4. Test Connection
ssh -T git@github.com

