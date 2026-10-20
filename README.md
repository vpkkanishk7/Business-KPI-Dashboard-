# Business KPI Dashboard — Task 2

Interactive dashboard based on the supplied synthetic customer churn CSV.

## Run locally
Open `index.html` in a browser with an internet connection (Chart.js is loaded from jsDelivr).

## Publish one public link (GitHub Pages)
1. Sign in to GitHub and create a **public** repository named `business-kpi-dashboard`.
2. Upload `index.html`, `customer_churn_sample.csv`, and this README to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for deployment and open the published URL shown on the Pages screen. Test filters and charts in an incognito/private window.
6. Submit that published URL.

## KPI definitions
- Churn rate = churned customers / customers in current filtered view.
- Retention rate = retained customers / customers in current filtered view.
- Monthly revenue at risk = sum of monthly charges for customers marked Churn = Yes.
- Average tenure = mean TenureMonths in current filtered view.

## Quality and limitations
The supplied file has 15 rows, 11 columns, no missing cells, and no exact duplicate rows. This is a very small synthetic sample; all segment observations are descriptive, not predictive or causal. The dashboard uses filters for contract type, tenure segment, and payment method. Currency is displayed as INR per the task brief.
