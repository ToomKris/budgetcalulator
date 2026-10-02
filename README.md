# Budget Calculator

An interactive budget tracker that runs entirely in the browser. It's a web version of the Finance Hub I use in Notion: log what comes in and goes out, compare it with a monthly plan, and watch loans and trip budgets update by themselves.

**Live site:** https://toomkris.github.io/budgetcalulator/
**Portfolio:** https://toomkris.github.io/work/

## What it does

- **Left to spend**: a big number at the top for the chosen month, with a bar that splits your income into Needs, Wants, Debt, Savings and what's left.
- **Transactions**: add, edit, search and filter income and spending. Each one has a type, category, status (Paid or Planned), account, payment method and notes.
- **Monthly budgets**: set a plan per category and group (Needs, Wants, Debt, Savings, Income). The overview compares the plan with what you actually spent and warns you when a category gets close to its limit or goes over.
- **Planned spending**: transactions marked Planned show up separately, so you can see upcoming costs before they happen.
- **Loans**: track original amount, monthly payment, interest and due day. Link loan payments to a loan and the payoff bar, remaining amount and months left update automatically.
- **Trips & events**: give a trip, event or birthday its own budget, link transactions to it, and see what's spent, planned and left.
- **Revolut CSV import**: drop in a Revolut statement. Duplicates and declined payments are skipped, common shops are sorted into categories automatically, and anything it can't sort lands in "Needs a category" on the overview.
- **Backup and restore**: download all your data as a JSON file and load it back later or on another device.

## Your data

Everything is saved in your browser's local storage. Nothing is sent to a server. Clearing your browser data removes it, so use **Download backup** now and then.

The first visit loads example data so you can see how it works. Use **Clear everything** to start fresh, or **Load example data** to bring the example back.

## Built with

Plain HTML, CSS and JavaScript in a single `index.html`. No frameworks, no build step. Hosted on GitHub Pages.

## Run it locally

Download or clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/ToomKris/budgetcalulator.git
cd budgetcalulator
open index.html   # or double-click the file
```

## Publish on GitHub Pages

In the repo, go to **Settings → Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save. The site appears at `https://toomkris.github.io/<repo-name>/` after a minute or two.
