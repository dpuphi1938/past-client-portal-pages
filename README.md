# past-client-portal-pages

Post-close pages for closed *listing* (seller-side) transactions, published
by the `transaction-portal` CLI (`ninja-realtor/transaction-portal`). Once a
listing closes there's no more timeline/milestones/FAQ to show — this is a
standing "thanks for trusting me with your sale" reference page for a past
seller, not an active transaction tracker.

**This repo is public (required for free GitHub Pages), but nothing here is
discoverable.** There is deliberately no root `index.html` and no page lists
the transactions that exist — each one lives at `/<slug>/`, where `<slug>` is
a long random token. The URL itself is the access control, the same trust
model already used for MLS share links. Don't add an index/directory page
here; doing so would defeat that.

Source data (client names, addresses, sale details) lives locally and
privately in `transaction-portal/data/` and is never committed here — only
the rendered HTML output is.
