# 💸 Budget Calculator

> *"I'm on a budget. It's called 'see food, check bank account, cry, buy groceries anyway.'"* 🥲

A budget tracker that runs right in your browser. It's the web version of the Finance Hub I use in Notion. Log what comes in 💰 and what goes out 💸, compare it with your monthly plan 🎯, and watch your loans and trip budgets update by themselves ✨.

🌐 **Live site:** https://toomkris.github.io/budgetcalulator/
👋 **Portfolio:** https://toomkris.github.io/work/

---

## 🧰 What it does

- 🔢 **Left to spend**: one big number for the month, plus a colorful bar showing where your money went: 🏠 Needs, 🎈 Wants, 🏦 Debt, 🌱 Savings, and whatever's left (hopefully something 🙏).
- 🧾 **Transactions**: add, edit, search and filter your income and spending. Each one gets a type, category, status (✅ Paid or 🗓️ Planned), account, payment method and notes.
- 🎯 **Monthly budgets**: set a plan per category. The overview compares it with what you actually spent, turns 🟡 when you're getting close and 🔴 when you've gone over.
- 🗓️ **Planned spending**: costs marked Planned get their own list, so next month's hotel doesn't sneak up on you.
- 🏦 **Loans**: track the amount, monthly payment, interest and due day. Link your payments and the payoff bar, remaining amount and months left update automatically. Every payment counts 💪.
- ✈️ **Trips & events**: give a trip, event or birthday 🎂 its own budget, link the spending to it, and see what's spent, planned and left.
- 📥 **Revolut CSV import**: drop in your statement. Duplicates and declined payments get skipped, common shops get sorted into categories automatically 🛒🍔🚇, and anything it can't figure out goes to "Needs a category".
- 💾 **Backup and restore**: download everything as a JSON file and bring it back later or on another device.

> 🤔 *Why did the budget break up with the credit card?*
> *It felt like it was always being taken for granted… and then charged interest for it.* 💔

---

## 🔒 Your data

Everything stays in **your browser** 🖥️. Nothing is sent to a server, nobody's peeking at your snack budget 🍫.

⚠️ Clearing your browser data also clears your budget, so hit **Download backup** every now and then.

🎬 Your first visit loads example data so you can see how it all works. Hit **Clear everything** to start fresh 🧹, or **Load example data** to bring the example back.

---

## 🛠️ Built with

- 📄 Plain **HTML**, **CSS** and **JavaScript**, all in a single `index.html`
- 🚫 No frameworks, no build step, no drama
- 🚀 Hosted on **GitHub Pages**

> 🧮 *My budget and my code have one thing in common: they both work perfectly until I actually run them.* 😅

---

## 💻 Run it locally

Clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/ToomKris/budgetcalulator.git
cd budgetcalulator
open index.html   # or just double-click the file 🖱️
```

## 🌍 Publish on GitHub Pages

1. Go to **Settings → Pages** in the repo ⚙️
2. Choose **Deploy from a branch**
3. Pick `main` and `/ (root)` and save 💾
4. Wait a minute or two ☕ and the site appears at `https://toomkris.github.io/budgetcalulator/` 🎉

---

Made with ☕, 💚 and a slightly worrying number of 🍕 transactions by **Kris Toom**.
