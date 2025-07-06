# AzureResume
# 📄 Personal Resume Website – Guillaume Boisseau-Allaire

> ⚠️ **Disclaimer:** I am not a front-end developer by trade. This website was created in part using ChatGPT to assist with the design and structure.  
> Although I do understand HTML/CSS and the frontend stack enough to edit the provided HTML/CSS/Javascript, The primary purpose of this project is to showcase my **Azure**, **CI/CD**, and **cloud infrastructure** skills through a real-world implementation.

---

## 🎯 Project Overview

This is a simple, personal website built to present my resume and professional experience. The goal of this project is not visual perfection, but to demonstrate my ability and give me a reason to deepen my understanding of the whole Website hosting process by:

- Deploying a website using **Azure Static Web Apps**
- Working with **GitHub** and **Git** to implement version control  
- Integrating **GitHub Actions** for CI/CD
- Managing **custom domains**, **SSL certificates**, and **Azure CDN**
- Preparing for advanced features like **visitor tracking** and **data storage in Azure**

---

## 🧰 Technologies Used

- **HTML/CSS/JavaScript**
- **Azure Static Web Apps** for hosting
- **GitHub Actions** for CI/CD
- (Planned) **Azure Functions** + **Azure Table Storage** for stats tracking

---

## 🚀 Deployment

The site is deployed via [Azure Static Web Apps](https://learn.microsoft.com/en-us/azure/static-web-apps/overview).  
Every commit to the `main` branch automatically triggers a deployment using GitHub Actions.
I also went ahead and manually implemented CI/CD on a Storage Account Hosted static website

You can view the Static Web App version at:  
👉 [guillaumeba.ca](https://guillaumeba.ca)

You can view the Storage Account version at:  
👉 [cv.guillaumeba.ca](https://cv.guillaumeba.ca)

---

## 🔬 Preview Environment (CI/CD)

Pull requests automatically trigger **preview deployments** through Azure Static Web Apps.  
This allows me to test changes in an isolated environment before merging into production.

---

## 📊 Visitor Analytics (Planned Feature)

I am currently working on a `statistics.html` page that will:
- Store visitor IPs and geolocation data
- Use an Azure Function to log data into a database (likely Azure Table Storage)
- Respect privacy and minimize data retention

---

## 📁 File Structure
- /index.html # Main resume page, in French
- /anglais.html # Main resume page, in English
- /statistics.html # Visitor stats page
- /styles.css # Styling
 - /.github/workflows/ # GitHub Actions pipeline

---

## 🧪 Local Development

Just clone the repo and open `index.html` or `statistics.html` in your browser.  
No build steps or dependencies needed.

---

## 🙏 Acknowledgements

- [ChatGPT](https://openai.com/chatgpt) for help with HTML structure and design ideas
- [Lucide](https://lucide.dev) for open-source icons
- Microsoft Azure for providing world-class cloud tools and services

---

**© Guillaume Boisseau – 2025**

