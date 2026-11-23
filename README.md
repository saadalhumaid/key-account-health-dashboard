# Key Account Health Dashboard

A free, private tool for key account managers.

It shows which account needs follow-up, why it needs it, and a suggestion for what to do next. Then it exports your portfolio to Excel (Power BI ready) and PowerPoint in one click, so you can show it to your manager or executive.

**Built by [Saad Alhumaid](https://www.linkedin.com/in/saadalhumaid/), Key Account Manager.**

**Try it:** https://saadalhumaid.github.io/key-account-health-dashboard/ (demo data with fictional companies loads on first visit). Arabic and English.

## Private by design

- No server, no account, no tracking, no external libraries or fonts.
- Your accounts are saved only in your own browser on your own device.
- Conversations you paste are analyzed inside the browser and never sent anywhere.
- Use **Backup** to keep a copy and **Restore** to bring it back.

## How it works

1. **My accounts**: every account as a card, green, yellow or red, with the main reason and the next step. A banner shows which accounts need you today.
2. **Account page**: where it stands, why (in plain words), what to do today, and a ready message you can copy and send. Plus the 90-day view: the score if nobody touches the account.
3. **Add accounts**: one by one (name, value, renewal date, last contact, three yes/no questions, optional conversation), or **import from Excel/CSV** in one go, up to 500 accounts.
   - Columns are matched automatically from their names (Arabic or English), and you confirm the match before importing.
   - Accounts with the same name are updated, not duplicated.
   - Any extra column (city, contract number, owner…) is kept as "More information", shown on the account page and included in exports. It does not change the score.
   - A ready Excel template is available from the home page.
4. **Schedule the follow-up**: the tool suggests a call or meeting, its length and a working day (Sunday to Thursday) based on the account's risk.
   - **Add to my calendar** downloads a calendar file (.ics) for your phone or computer, with your preparation notes (agenda, questions to ask, expert advice, ready message).
   - **Send an invitation** works with any email: Outlook (work), Outlook.com / Hotmail, Gmail, or any other email app. Only the client-facing invitation text is used, never your internal notes.
5. **Export for presentation**: one click downloads
   - an **Excel** workbook with clean tables (`tblAccounts`, `tblPeople`, `tblSignals`) that Power BI can load directly (Get data → Excel), and
   - a **PowerPoint** deck: portfolio summary, the McDonald portfolio map, account health, accounts that need action, deep dives on the riskiest accounts with expert advice, and a 30-day plan.

## Health score (0-100)

| Part | Weight | What it measures |
|---|---|---|
| Contact | 30% | Days since the last real contact (7 days or less = full marks, 60 days = zero) |
| Relationship | 30% | Decision maker engaged, a supporter inside the client, client satisfied |
| Conversation | 20% | Closing and risk signals, reply speed and unanswered follow-ups in the latest conversation |
| Optional | 20% | SLA compliance, days to pay, growth vs last year |

70 and above is healthy, 50-69 needs attention, below 50 is at risk.

## The expert layer

The tool turns well-known sales and relationship frameworks into rules applied to each account:

| Framework | Author | Where it shows up |
|---|---|---|
| Key Account Management | Malcolm McDonald | **Portfolio map**: each account is Strategic, Star, Status or Streamline by attractiveness (value and growth) and your position (health), with how to invest your time |
| SPIN Selling | Neil Rackham | **Questions to ask**: situation, problem, implication and need-payoff questions that change with the account's situation |
| MEDDIC / MEDDPICC | Dick Dunkel & Jack Napoli | **Deal qualification**: optional 8-point check with a readiness score |
| Strategic Selling | Robert Miller & Stephen Heiman | Buying roles of the people at the client; the decision maker and internal supporter feed the score |
| Never Split the Difference | Chris Voss | **Ready messages**: labeling, open "how/what" questions and no-oriented questions |
| The Challenger Sale | Matthew Dixon & Brent Adamson | Messages and advice that open with a new insight and the cost of doing nothing |
| How to Win Friends and Influence People | Dale Carnegie | Relationship advice in the expert council |
| The Psychology of Selling | Brian Tracy | Asking clearly for the next commitment |

Every account page has an **expert council**: three short pieces of advice chosen for that account's situation, each linked to its framework. Principles are summarized in our own words; the tool is not affiliated with the authors.

## Languages

Arabic and English, including WhatsApp exports in both languages. Exports follow the language you are using.

## Limits

- Signals are detected with transparent rules, not AI. That is what keeps your data on your device.
- Clearing your browser data deletes your accounts. Use Backup regularly.

## License

MIT. Free to use, share and adapt. Please keep the credit line.
