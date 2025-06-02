

```markdown
![Banner QR Card](https://business-card-generator.vercel.app/vcard.svg?firstname=Swati&lastname=Chaudhari&picture=https%3A%2F%2Fexample.com%2Ficon.png&company=Freelancer&job=Frontend+Developer&email=yourname%40example.com)

# 🔧 Business Card Generator – Personalized Version

This is a **customized version** of an open-source business card generator that creates QR-based digital cards in multiple formats like **vCard**, **MeCard**, **SVG**, and **PNG**.

I modified and deployed this project to:
- Learn about full-stack deployment
- Explore QR-based data encoding
- Customize UI, themes, and features

🌐 **[Live Demo](https://your-deployment-link.vercel.app)**  
🧑‍💻 **[My GitHub Fork](https://github.com/your-username/business-card-generator)**

---

## ✨ Features

- Generate **vCard** / **MeCard** format QR codes
- Export in **SVG**, **PNG**, or **VCF**
- Live preview and customization options
- Responsive and deployable with one click
- Powered by Flask + Python backend and modern frontend stack

---

## 🚀 Usage

You can generate a business card directly using the deployed version or construct custom URLs like:

```

[https://your-deployment-link.vercel.app/vcard.svg?firstname=Swati\&lastname=Chaudhari\&email=hello@example.com](https://your-deployment-link.vercel.app/vcard.svg?firstname=Swati&lastname=Chaudhari&email=hello@example.com)

````

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Python (Flask)
- **Deployment**: Vercel
- **Extras**: GitHub Actions (CI/CD), QR generation libraries

---

## 🧠 What I Learned

- Working with URL-based parameter passing
- Handling image and card rendering via query strings
- Deploying Flask + static frontend on platforms like **Vercel**
- How QR standards like `vCard` and `MeCard` work

---

## 📦 Setup for Development

```bash
cp .example.env .env
uv sync
uv run flask run
````

VSCode debugging:

```json
{
  "FLASK_APP": "business_card_generator.app:create_app",
  "FLASK_ENV": "development"
}
```

---

## 🙏 Original Author Credit

This project is originally created by [**Romain Clement**](https://github.com/rclement).
My version is a fork with UI and usage-level customizations for portfolio purposes.
Original repo: [rclement/business-card-generator](https://github.com/rclement/business-card-generator)

---

## 📜 License

This project is distributed under the **GNU AGPLv3 License**.




