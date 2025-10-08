# 🚀 Laravel Auto-Installer

A beautiful, automated installer that makes Laravel project setup as simple as clone-and-click. No more manual configuration!

![Laravel Auto-Installer](https://via.placeholder.com/800x400/3B82F6/FFFFFF?text=Laravel+Auto-Installer+Preview)

## ✨ What This Solves

Ever cloned a Laravel project and spent 30+ minutes on setup? This installer automates everything:

- ✅ **System Requirements Check** - PHP, extensions, Composer, Node.js
- 🗃️ **Database Setup** - Connection testing, database creation
- 📁 **Environment Configuration** - Automatic .env file setup  
- 📦 **Dependency Installation** - Composer & NPM packages
- 🔑 **Security Setup** - App key generation
- 🗃️ **Database Migrations** - Schema setup
- 📊 **Real-time Progress** - Live installation tracking
- 🎨 **Beautiful UI** - Modern TailwindCSS interface

## 🚀 Quick Start

### For Project Owners:
1. **Include** `install-app.php` in your Laravel project's public directory
2. **Update** your `index.php` with the installation check (example below)
3. **Users** can now clone and install with one click

### For Users:
```bash
# Clone any Laravel project with this installer
git clone [project-repo]
cd [project-name]

# Access the installer via browser
# Visit: http://localhost/your-project/public/install-app.php
# Follow the step-by-step wizard
