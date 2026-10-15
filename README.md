> ## ⚠️ Commercial Project / All Rights Reserved
>
> This repository is for portfolio and evaluation purposes by potential employers. You may view and review the source code. The only other permitted use is running the unmodified app for your own personal, non-commercial budgeting, as described in [Use it in Claude](#use-it-in-claude). You do not have permission to modify, distribute, resell, share publicly, or use this code in any other personal or commercial project.
>
> © 2026 Alex Martin. All rights reserved.

# Budget App

A private, browser-based personal finance dashboard built for people whose money lives in more than one currency. Track spending and budgets, import bank exports, and see net worth, investments, debt payoff and savings goals in one place. Your data never leaves your device.

**[▶ Open the live demo](https://tayloramartin220.github.io/budget-app/)** (loads with sample data for an American living in Lisbon)

![Dashboard](dashboard.png)

## 🌍 Built for life across currencies

Most budgeting tools assume all your money is in one currency. This one doesn't. If you live abroad, get paid in one currency and owe money in another, or invest back home, everything still adds up.

- **Every amount keeps its own currency.** Transactions, bank accounts, investment accounts, debts, assets and savings goals can each be in a different currency. Enter a euro grocery bill, a dollar student loan and a pound train ticket exactly as they happened.
- **One total, any currency.** Pick a currency in **Show in** and every total, chart and net worth figure converts instantly. Switch from USD to EUR to GBP and back with one click.
- **Add any currency you need.** USD, EUR and GBP are set up in the demo, and you can add others (CAD, AUD, NZD, CHF, JPY, NOK and more) with your own exchange rates.
- **You control the rates.** The app works offline and never fetches live rates. You set them yourself, so your numbers don't shift unless you update them.
- **Transfers between accounts.** Move money between a home-country account and a local one without it counting as spending.

**Great for:** expats and digital nomads, international students, people paying off loans in their home country, anyone investing abroad, and couples or families managing money in two countries.

![Currencies and accounts](currencies.png)

## Features

- **Dashboard**: net worth at a glance across cash, savings, retirement, investments, other assets and debt, plus savings goal and debt payoff rings
- **Spending & transactions**: money in vs. out each month, spending by group and category, a six-month trend, and itemized entries in any currency
- **Bank import**: drop in an Excel (.xlsx) or CSV export from your bank and review categories before anything is added. Payees you've categorized before fill in automatically
- **Accounts & investments**: balances in each account's own currency, holdings by asset class, and target allocations that show when you're off balance
- **Debts**: payoff timeline with and without extra payments, and the interest you'd save
- **Savings goals**: progress and pacing toward each target date, in each goal's own currency
- **Light & dark themes**

![Spending](spending.png)

## How your data is stored

Everything saves automatically in your browser's local storage on the device you're using. Nothing is uploaded, and there's no account to create.

- **Export backup** downloads your data as a file. Use it to back up or move to another device, then open it there with **Load data**.
- **Start over** lets you clear everything and begin with a blank budget, or reload the sample data.

Clearing your browser's site data erases saved data, so export a backup now and then.

## Use it in Claude

If you use [Claude](https://claude.ai), you can publish the app as your own private artifact and keep it in your artifacts list:

1. Download [`index.html`](index.html). Open the file on GitHub and click the **Download raw file** button.
2. Start a new chat in Claude and attach the file.
3. Send this message:

   ```
   Publish this HTML file as an artifact exactly as it is, without changing any code.
   ```

Your artifact is private to you until you choose to share it. Data you enter is saved in your browser, the same way it works on the live demo. Use **Start over** to clear the sample data and begin with your own.

This permission covers personal use of the unmodified app only. Please don't share your artifact link publicly, modify the app, or redistribute it.

## Run it locally

It's a single HTML file. Download `index.html` and open it in any modern browser.

## License

No license is granted. © 2026 Alex Martin. All rights reserved. You're welcome to try the live demo, review the code, and run the unmodified app for your own personal budgeting, either locally or as a private Claude artifact. Modifying, distributing, reselling or using it in any other project requires written permission. For inquiries, contact me through my GitHub profile.
