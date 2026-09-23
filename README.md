# ICF-AI publication source

Canonical source for the ICF-AI landing page, delivery guidance, public research, publication manifest and checkout. All existing research and recorded customer-package hashes are preserved.

Build with `python3 scripts/publish.py build`, validate with `python3 scripts/publish.py validate`, and run `python3 scripts/test-publication.py`.

The public address remains `https://reasoning-library.vercel.app/icf-ai`. A dedicated publication project serves the pages, and the bookstore forwards the recorded routes. Its root redirects to `/icf-ai`; publication metadata is under `/icf-ai/` to avoid collisions with bookstore metadata.

The actual Vercel project ID and project origin still need to be recorded in `publication.json`. Source validation can run before project creation. The release gate remains blocked until project mapping and independent deployment evidence are supplied.

Set the bookstore environment variable `ICF_AI_ORIGIN` to the verified dedicated project origin after deployment. Follow the bookstore's `VERCEL_HANDOFF.md` for the deployment sequence. Do not invent a new public hostname or put paid files in this repository.

The owner-supplied ICF-AI payment link, `https://www.paypal.com/ncp/payment/AYFVNCSR6MYRG`, is recorded in `checkout.hosted_url`. The checkout route redirects only to that link. The manifest price remains USD 4.99. Hosted product settings, payment acceptance and buyer receipt remain unverified.

The customer archive has three recorded files: PDF, purchaser licence and README. Its previous SHA256 and CRC verification is retained; this repair does not claim a new package audit.
