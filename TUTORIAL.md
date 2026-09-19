# Trace tutorial

A walkthrough of how to use Trace to split a bill with friends.

**[← Back to README](README.md)**

## 1. Welcome screen

When you open Trace, you'll see a short welcome screen explaining what the app does — split any bill evenly, by percentage, by shares, or item by item, entirely on your device. Tap **Start splitting** to begin.

![Welcome screen](docs/screenshots/welcome.png)

## 2. Add the people in your split

You'll land on the **People** tab. Tap the **+** button in the top right to add a member — enter their name (and, optionally, a phone number). Repeat for everyone involved in the split. Tap the **×** next to a name to remove them.

![People tab with members added](docs/screenshots/people-tab.png)

## 3. Add an expense

Switch to the **Expenses** tab, then tap the **+** button. You'll be asked whether this is:

- **Simple expense** — one total amount, split a certain way.
- **Itemized receipt** — a receipt with several items, where different people had different things.

![Choosing between a simple expense and an itemized receipt](docs/screenshots/add-expense-chooser.png)

### 3a. Simple expense

On the **Add expense** screen:

1. Enter what the expense was for and the total amount.
2. Choose **who paid** from the list of members.
3. Choose a **split method**:
   - **Equal** — split evenly among everyone selected.
   - **Exact** — enter the exact amount each person owes.
   - **%** — enter each person's percentage share.
   - **Shares** — enter a relative number of shares per person (e.g. someone with 2 shares owes twice as much as someone with 1).
4. Check off who's included in the split, and — for Exact, %, and Shares — enter each person's value. A banner at the bottom tracks how much has been allocated so far and confirms once it matches the total.
5. Tap **Add expense**.

![Adding a simple expense with an equal split](docs/screenshots/add-expense.png)

### 3b. Itemized receipt

On the **Itemized receipt** screen:

1. Name the receipt (e.g. "Dinner at Nyama Grill") and choose who paid the bill.
2. For each item, enter its name and amount, then check off who had it. Tap **+ Add item** to add more lines.
3. Tap **Add receipt** — Trace folds all the items into a single expense, working out each person's total based only on the items they were checked into.

![Adding items to an itemized receipt](docs/screenshots/itemized-receipt.png)

## 4. Review your expenses

Back on the **Expenses** tab, every expense you've added is listed with who paid, the split method used, and how many people it covers. Tap the **×** on an expense to remove it. Your running **total spent** is shown at the bottom of the screen.

![Expenses tab showing a list of logged expenses](docs/screenshots/expenses-tab.png)

## 5. Split the bill

Once you've added at least one person and one expense, tap **Split the bill**. Trace calculates the fewest possible payments needed to settle everyone up.

## 6. Settle up

The **Settle up** screen shows the total spent and a list of settlements, split across two tabs:

- **Who pays** — each person and who they owe money to.
- **Who receives** — each person and who owes them money.

If everyone's already even, you'll see a message confirming no payments are needed.

![Settle up screen showing who owes whom](docs/screenshots/settle-up.png)

When you're ready to start over, tap **Start a new split** to clear everyone and begin a fresh session.

---
