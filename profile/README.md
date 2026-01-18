#Select Language **[EN](#-table-of-contents)** **[RU](#-содержание)** 





# z3nFarm — Руководство по началу работы

Добро пожаловать в приватную организацию **z3nFarm**. Это руководство поможет вам настроить окружение и начать использовать наши шаблоны автоматизации.

---

## 📋 Содержание

- [Оплата и лицензирование](#-оплата-и-лицензирование)
- [Начало работы](#-начало-работы)
- [Внешние зависимости](#-внешние-зависимости)
- [Безопасность данных](#-безопасность-данных)
- [Импорт данных](#-импорт-данных)
- [Запуск шаблонов](#-запуск-шаблонов)
- [Обновления и список репозиториев](#-обновления-и-список-репозиториев)

---

## 💳 Оплата и лицензирование

### Как приобрести доступ

1. **Оплата**: Произведите оплату по ссылке [Unlock Protocol](https://app.unlock-protocol.com/checkout?id=0e4d7137-89c7-4eab-8b22-5da6be6c9fd5)
2. **Регистрация**: При оплате укажите:
   - Email вашей лицензии ZennoPoster
   - Ваш GitHub username
3. **Приглашение**: После оплаты вы будете приглашены в организацию z3nFarm и получите доступ ко всем репозиториям с шаблонами

### Защита лицензии

- Все шаблоны защищены лицензией ZennoPoster и запускаются с привязанным к лицензии Email
- Если у вас есть вторая лицензия, сообщите email [@w3bgr3p](https://t.me/w3bgr3p)

---

## 🚀 Начало работы

### 1. Выбор базы данных

Вам необходимо определиться, какой БД вы хотите пользоваться:

- **SQLite** — Простая настройка, файловая база
- **PostgreSQL** — Рекомендуется для продакшена

> 📖 **Подробное сравнение**: [Руководство SQLite vs PostgreSQL](https://teletype.in/@w3bgr3p/xvrSAdMn10R)
>
> 💡 **Коротко**: Берите PostgreSQL. Настройка займет ~1 час, но сэкономит вам время в будущем.

### 2. Настройка базы данных

Следуйте подробной инструкции: [Настройка базы данных](https://z3n-1.gitbook.io/z3n/getting-started/database-setup)

---

## 📦 Внешние зависимости

Скачайте актуальные внешние библиотеки и поместите их в директорию ZennoPoster:

1. **Скачать**: [ExternalAssemblies](https://github.com/z3nFarm/z3nCore-full/tree/master/ExternalAssemblies)
2. **Путь установки**:
- [ ] Run _dbTools to initialize database
- [ ] Download required .crx extensions
- [ ] Start using templates

---


# z3nFarm — Getting Started Guide

Welcome to **z3nFarm** private organization. This guide will help you set up your environment and start using our automation templates.

---

## 📋 Table of Contents

- [Payment & Licensing](#-payment--licensing)
- [Getting Started](#-getting-started)
- [External Dependencies](#-external-dependencies)
- [Data Security](#-data-security)
- [Data Import](#-data-import)
- [Running Templates](#-running-templates)
- [Updates & Repository List](#-updates--repository-list)

---

## 💳 Payment & Licensing

### How to Purchase Access

1. **Payment**: Complete your purchase via [Unlock Protocol checkout](https://app.unlock-protocol.com/checkout?id=0e4d7137-89c7-4eab-8b22-5da6be6c9fd5)
2. **Registration**: During checkout, provide:
   - Your ZennoPoster license email
   - Your GitHub username
3. **Invitation**: After payment, you'll be invited to the z3nFarm organization and gain access to all template repositories

### License Protection

- All templates are protected by ZennoPoster license and run with the email bound to your license
- If you have a second license, contact [@w3bgr3p](https://t.me/w3bgr3p) with the additional email

---

## 🚀 Getting Started

### 1. Choose Your Database

You need to decide which database system to use:

- **SQLite** — Simpler setup, file-based
- **PostgreSQL** — Recommended for production use

> 📖 **Detailed comparison**: [SQLite vs PostgreSQL guide](https://teletype.in/@w3bgr3p/xvrSAdMn10R)
>
> 💡 **TL;DR**: Use PostgreSQL. It takes ~1 hour to set up but will save you time in the long run.

### 2. Database Setup

Follow the comprehensive setup guide: [Database Setup Instructions](https://z3n-1.gitbook.io/z3n/getting-started/database-setup)

---

## 📦 External Dependencies

Download the latest external assemblies and place them in your ZennoPoster directory:

1. **Download**: [ExternalAssemblies](https://github.com/z3nFarm/z3nCore-full/tree/master/ExternalAssemblies)
2. **Installation path**:
```
   {drive}:\Program Files\ZennoLab\RU\ZennoPoster Pro V7\7.{version}\Progs\ExternalAssemblies\
```

---

## 🔐 Data Security

Protect your sensitive data (passwords, private keys, API keys) using our encryption system:

### Setup Steps

1. **Download**: [_SAFU.zp and _vars.zp](https://github.com/z3nFarm/_SAFU)
2. **Location**: Place both files inside the `.internal` folder in your templates directory
3. **Configuration**:
   - Open `_vars.zp` in ProjectMaker
   - Enter your passwords in the corresponding fields
   - Change access permissions
4. **Documentation**: [Detailed SAFU guide](https://z3n-1.gitbook.io/z3n/getting-started/safu)

> ⚠️ **Important**: Never commit `_vars.zp` with real credentials to any repository.

---

## 📊 Data Import

Use the `_dbTools` template to initialize your database structure and import necessary data:

1. **Download**: [_dbTools template](https://github.com/z3nFarm/_dbTools/tree/master)
2. **Run** the template in **build mode** with your chosen database
3. **Follow** the popup instructions
4. The tool will:
   - Create the database structure used by the current z3nCore version
   - Import necessary data (selected via checkboxes)
   - Encrypt sensitive information

---

## ▶️ Running Templates

### Browser Extensions

Download the required `.crx` extensions: [Extension Pack](https://github.com/z3nFarm/_crx)

### Execution

- Open templates in **ZennoPoster** or **ProjectMaker**
- Ensure all dependencies are installed
- Check that database connection is configured
- Run templates according to their specific documentation

---

## 🔄 Updates & Repository List

Stay up to date with the latest templates and improvements:

- **Active templates list**: [Repository Index](https://t.me/c/2164296309/867/6746)
- **Announcements**: Follow [@z3nLabs](https://t.me/z3nLabs) on Telegram
- **Support**: Contact [@w3bgr3p](https://t.me/w3bgr3p) for technical assistance

---

## 🌐 Links & Resources

| Resource | Link |
|----------|------|
| **Private Telegram** | [@w3bgr3p](https://t.me/w3bgr3p) |
| **Public Channel** | [@z3nLabs](https://t.me/z3nLabs) |
| **Documentation** | [z3n GitBook](https://z3n-1.gitbook.io/z3n/) |
| **Main GitHub** | [@w3bgr3p](https://github.com/w3bgr3p) |
| **z3nCore Library** | [z3nCore Repo](https://github.com/w3bgr3p/z3nCore) |

---

## ⚡ Quick Start Checklist

- [ ] Complete payment and receive GitHub invitation
- [ ] Choose database (SQLite or PostgreSQL)
- [ ] Install external dependencies
- [ ] Configure SAFU encryption system







> **NO SPAM. NO CORPORATE. JUST AUTOMATION.**

