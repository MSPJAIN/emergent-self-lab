# Taiwan payment setup: PayPal.Me

This is the active first payment route for Emergent Self Lab. It is designed for **international, one-time support** from people who want to help the open research work.

**Current URL:** <https://paypal.me/MSPJIAN>

It is not an investment product, a promise of profit, or a charitable-donation receipt system.

## Why start here

PayPal Taiwan's help documentation says that personal account holders in Taiwan can withdraw PayPal funds to an E.SUN Bank account or, subject to conditions, another local bank account. PayPal also provides PayPal.Me links that can be shared as a simple payment page.

This route is intentionally small and reversible at the project level. The PayPal account and Taiwan bank withdrawal path are set up; a small international payment should still be recorded as an operational test.

## Account decision

Choose the account type based on who is actually receiving the money:

- **Personal project:** start by checking a PayPal personal account and your own Taiwan bank withdrawal path.
- **Company or registered organization:** use the appropriate business account and keep the project records separate from personal funds.

Do not describe the payment as a charitable donation unless a legally qualified organization and receipt process actually exist.

## Setup checklist

1. Open or sign in to PayPal Taiwan: <https://www.paypal.com/tw/>.
2. Use your real legal name and contact details. The PayPal name and bank-account name must match exactly, including the language and characters used.
3. Complete email, phone, identity, and any requested account verification.
4. Link a Taiwan bank account. If using E.SUN Global Pass, follow E.SUN's current PayPal withdrawal instructions. PayPal currently states that E.SUN processing may take 3–7 business days.
5. Create a PayPal.Me name carefully. PayPal states that the link cannot simply be renamed or deleted later; choose a project-safe name before publishing it.
6. Ask one trusted person outside Taiwan to make a small test payment.
7. Confirm that the payment appears in the correct PayPal balance and that the withdrawal route works.
8. Record the payment date, gross amount, currency, fees, exchange rate, withdrawn amount, and any withholding or transfer delay.
9. After the test succeeds, keep the real URL in `.github/FUNDING.yml` and record the test outcome privately.

## If your only bank is Cathay United

Do not use the American-bank form shown in the PayPal wallet. PayPal's Taiwan help page describes a separate route through E.SUN Global Pass for withdrawing to another local bank.

According to PayPal's current conditions, this other-local-bank route requires:

- a PayPal personal account;
- age 18 or older;
- no previous E.SUN Bank account;
- a Republic of China identity card;
- a valid Republic of China passport if withdrawing foreign currency to a non-E.SUN foreign-currency account.

If you meet those conditions, enter the PayPal withdrawal flow through E.SUN Global Pass and select your own Cathay United account as the destination. Use an NTD account for the simplest first test. If you intend to withdraw USD to a Cathay USD account, confirm the passport and foreign-currency requirements before submitting.

If the E.SUN Global Pass flow does not offer Cathay United or rejects the account, stop there and contact PayPal or E.SUN support. Do not work around the restriction by entering a made-up US routing number or somebody else's bank account.

## Public wording after verification

Use wording like this:

> Support Emergent Self Lab through PayPal.Me. This is voluntary support for experimental research and documentation, not an investment and not a promise of financial return or a particular research result.

For the first phase, say **one-time international support**. Do not promise monthly benefits until recurring payments have been separately tested.

## Records and boundaries

- Keep PayPal statements and bank withdrawal records in a private, access-controlled location.
- Do not publish supporter names, email addresses, transaction IDs, or screenshots containing personal data.
- Keep project expenses and personal expenses distinguishable.
- Check Taiwan tax, accounting, and foreign-exchange obligations with a qualified professional if the amounts become material or recurring.
- Do not use this route to sell ownership, investment rights, or guaranteed access to undisclosed core IP.

## Go-live and verification record

The payment link is already configured for one-time support. Use this checklist to complete the verification record:

- [ ] account ownership and identity verification complete;
- [ ] Taiwan bank withdrawal path linked;
- [ ] small international test payment received;
- [ ] small withdrawal completed or confirmed as available;
- [ ] fee and currency-conversion behavior recorded;
- [ ] public wording reviewed;
- [ ] PayPal.Me URL tested in a private browser window;
- [x] `.github/FUNDING.yml` updated with the real URL.
