# shOk Privacy Policy, Terms and Account Deletion

Public legal and account pages for the shOk delivery app, served by GitHub Pages.

## Pages

- **Privacy Policy** - [live](https://aryanmir15.github.io/shOk-PrivacyPolicy/) | [index.html](index.html)
- **Terms of Service** - [live](https://aryanmir15.github.io/shOk-PrivacyPolicy/terms.html) | [terms.html](terms.html)
- **Delete Account** - [live](https://aryanmir15.github.io/shOk-PrivacyPolicy/delete-account.html) | [delete-account.html](delete-account.html)

## Why the Delete Account page exists

Google Play requires apps that let users create an account to also let them delete it, both from inside the app and from a publicly reachable web page. The page also has to state what is deleted, what is retained, and how long a request takes. Do not remove it, and keep the URL available in Play Console under **App content > Data safety > Account deletion**.

The page must stay in sync with what the backend actually does. The behaviour lives in `utils/accountDeletion.js` in the main repository; if that file changes, update section 7 of the Privacy Policy and the table on the Delete Account page in the same change.

## Contact address

`shok.app.official@gmail.com` is used on every page. It has to be a mailbox someone actually reads, because Play reviewers check that contact details are real.

## Style rules

- No em dashes or en dashes anywhere in the copy. Hyphens only inside numeric ranges or identifier formats.
- Keep the plain light styling. These pages are read, not browsed, and should load fast on a phone.
