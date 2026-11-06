# KhataBot

Private household budget, bills, IOU and income tax tracker for India (tax year 2026-27, GST 2.0 slabs of 0%, 5%, 18% and 40%).
Made by The Computer Services. Your data is encrypted in the browser (AES-256-GCM) and never leaves the device.

## Put it online with GitHub Pages
1. On github.com click **New repository**. Name it, for example, `KhataBot`. Choose **Public** and create it.
2. Click **uploading an existing file**. Unzip this download first, then drag in everything inside the folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md`, `.nojekyll` and the `icons` folder. Click **Commit changes**.
3. Open **Settings > Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute the app is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Installing
- Android, Windows and Mac (Chrome or Edge): tap **Install app** in the bar at the top.
- iPhone and iPad: tap **Install app** to see the Add to Home Screen steps. Install before you enter data.
- Mac Safari: File > Add to Dock.

## What is built in (as of 2026)
- Income tax: new regime slabs for tax year 2026-27 (nil to ₹4 lakh, then 5%, 10%, 15%, 20%, 25%, 30%), ₹75,000 standard deduction, rebate so there is no tax up to ₹12 lakh taxable, 4% cess. Old regime slabs with 80C (₹1.5 lakh), NPS extra (₹50,000) and other deductions, with a side-by-side comparison.
- GST: choose 0%, 5%, 18% or 40% on each expense to see the GST you paid.
- Key dates: advance tax (15 Jun, 15 Sep, 15 Dec, 15 Mar), end of the tax year (31 Mar) and ITR-1/ITR-2 filing (31 Jul).
- Also: budgets with spending caps, bills in two accounts, festival funds, IOU ledger, other income, reminders, shopping list, tips, reports, accessibility options, privacy and feedback footer.

## Notes
- Data stays on each device and is stored in the browser on each device and is never uploaded.
- Tax rules change every year. After each Union Budget, update the slab and date values in `index.html` and change the version in `sw.js` (`ledger-in-v1` to `ledger-in-v2`) so installed copies refresh.
- This is a planning aid, not tax advice. Check incometax.gov.in or ask a Chartered Accountant.
- Feedback: baglajakh@gmail.com
