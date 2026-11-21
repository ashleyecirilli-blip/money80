# Money 80

Your Money. Your Practice. Your Progress.

This folder is the Money 80 preview website:

- `index.html` is the landing page with the waitlist sign-up.
- `prototype/index.html` is the clickable member prototype, using sample data.

## Publish it with GitHub Pages

1. Create a new repository on GitHub, for example `money80`.
2. Click **Add file → Upload files**, drag in everything from this folder (keep the `prototype` folder), and commit.
3. Go to **Settings → Pages**. Under "Build and deployment," choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two, the site is live at `https://YOUR-USERNAME.github.io/money80/`. The prototype is at `.../money80/prototype/`.

Both pages carry a "noindex" tag, so search engines won't list them while they're in review. Remove that line from each page before a public launch.

## Connect the waitlist

The sign-up runs in preview mode until an email service is connected. Near the bottom of `index.html`, find the CONFIG block and paste your form's address into `formEndpoint`. Then make these custom fields in your email service so the answers land on each subscriber:

- `text_interest`
- `offer_interest`
- `feel_better_about`
- `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`, `utm_term`

Submit a test sign-up and confirm it reaches your list before running any ads.
