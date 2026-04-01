# Windows XP VM on GitHub Actions

Run Windows XP in GitHub Actions with remote access via ngrok.

## 🚀 Quick Start

1. Fork this repository
2. Go to **Actions** tab
3. Click **Windows XP VM with Ngrok**
4. Click **Run workflow**
5. Set runtime (2 hours recommended)
6. Click **Run workflow**

## 📱 Accessing Your VM

After 3-5 minutes, check the workflow logs:

1. Click on the running workflow
2. Expand **"📡 Display Access Information"** step
3. Copy the Web URL or RDP address
4. Access Windows XP!

### Web Browser (Easiest)
- Click the HTTPS URL from logs
- Use directly in browser

### RDP Client (Better Performance)
- Use the TCP address
- Username: `Administrator`
- Password: `password123`

## ⚙️ Configuration

Edit `.github/workflows/windows-xp-vm.yml`:
```yaml
