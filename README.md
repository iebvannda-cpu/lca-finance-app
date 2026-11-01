# LCA Church Finance

Church finance app for LCA: income and expenses in USD and KHR, funds, budgets and reports.

- **Launch page:** https://iebvannda-cpu.github.io/lca-finance-app/
- **App:** https://iebvannda-cpu.github.io/lca-finance-app/app/

The app runs entirely on GitHub Pages and talks directly to Supabase. Members sign in with Google; Supabase Row Level Security decides what each person can see and change.

- `index.html`: launch page
- `app/index.html`: the finance app (single file, no build step)

The key in `app/index.html` is Supabase's **publishable** key, which is designed to be public. Never put the `service_role` or secret key in this repository.

Database migrations and project history are kept in the private `lca-finance` repository.
