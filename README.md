# 💕 BillBae — Valentine's Love Receipt Generator

**Bill your bae today. They owe you.**

BillBae is a fun Valentine's Day web app that lets you generate a love receipt, itemizing everything your partner owes you for your patience, love, and emotional support.

🔗 **Live App:** [billbae-1.web.app](https://billbae-1.web.app)

---

## ✨ Features

- 🧾 **Love Receipt Generator** — Select from preset line items (Unlimited Patience, Forgiveness, Late Night Talks, etc.) or add your own custom items
- 💰 **Automatic Total** — Calculates the grand total of everything your bae owes you
- 📸 **Download as Image** — Save the receipt as a high-quality PNG to share on social media
- ➕ **Multiple Custom Items** — Add unlimited custom charges with your own names and prices
- 🔄 **New Receipt** — Clear everything and start fresh with one click
- 📱 **Mobile Friendly** — Fully responsive, works beautifully on phones and tablets
- 🎨 **Animated Background** — Floating Valentine's Day emojis for a festive vibe

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML | Structure |
| [Tailwind CSS](https://tailwindcss.com/) (CDN) | Styling |
| [Alpine.js](https://alpinejs.dev/) (CDN) | Interactivity & State |
| [html2canvas](https://html2canvas.hertzen.com/) | Receipt image download |
| [Font Awesome](https://fontawesome.com/) | Icons |
| Google Fonts (Inter + VT323) | UI + Receipt typography |

---

## 🚀 Getting Started

### Run Locally

No build step required — it's a single HTML file!

```bash
# Clone the repo
git clone https://github.com/oseifelix/BillBae.git
cd BillBae

# Serve locally (any static server works)
npx serve .
```

Then open [http://localhost:3000](http://localhost:3000) in your browser.

### Deploy to Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase init hosting    # Select public directory: .
firebase deploy
```

---

## 📸 How It Works

1. Click **"Create a Love Receipt"**
2. Fill in your name, your partner's name, and the date
3. Check off the line items your bae owes you
4. Add any custom charges
5. Hit **"Download Receipt"** to save as a PNG
6. Share it on social media and tag your bae 💅

---

## 👤 Author

**Felix Osei Marfo**
- X/Twitter: [@oseimarfofelix](https://x.com/oseimarfofelix)
- GitHub: [@oseifelix](https://github.com/oseifelix)

---

## 📄 License

MIT — use it, share it, bill your bae with it. Happy Valentine's Day! 💖
