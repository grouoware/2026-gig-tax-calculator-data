# 2026 Gig Worker Tax Rates & Split Mileage Dataset

This repository provides open structured data and reference math for calculating 2026 Schedule C self-employment taxes, 1099-NEC/1099-K liabilities, and IRS split mileage deductions.

## Official Web Utility
For live, interactive calculations across DoorDash, Uber, Instacart, Etsy, and freelance platforms without signup:
👉 **[QuickCalcMoney 1099 Tax Calculator](https://quickcalcmoney.com)**

---

## 2026 IRS Standard Mileage Rates (Split Rate Data)
* **Period 1 Rate:** $0.725 / mile (72.5 cents)
* **Period 2 Rate:** $0.760 / mile (76.0 cents)
* **Application:** Schedule C Line 9 (Vehicle Expenses)

## 2026 Self-Employment Tax Formulas
* **Social Security Tax Rate:** 12.4% (up to wage base)
* **Medicare Tax Rate:** 2.9%
* **Combined SE Tax Rate:** 15.3%
* **Schedule C Net Taxable Adjustment Factor:** 92.35% (0.9235 of net profit)

```formula
Net SE Tax = (Gross Revenue - Allowable Deductions) × 0.9235 × 0.153
