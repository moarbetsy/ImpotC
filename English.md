
# Crypto Tax in Québec — Quick Guide for Beginners

## 1️⃣ Introduction

Crypto taxes may seem complex, but in reality, a few simple rules go a long way. **TurboCrypto** automates conversions to Canadian dollars, calculates your gains/losses, and prepares your data for filing.
You stay in control of your data — we handle the rest.

---

## 2️⃣ Key Concepts

### a) What is a Capital Gain?

Quick analogy: you buy a bike for $300, sell it for $500 → your profit is **$200**.
Crypto works the same way:

```
Gain = Proceeds of disposition (in CAD) – Cost of acquisition (in CAD, including fees)
```

**50% rule:** For the 2024 tax year, **50% of your capital gain** is added to your taxable income.
TurboCrypto automatically applies the correct rate for each declared year.

---

### b) When Does Tax Apply?

No tax as long as you **HODL** (hold your crypto).
Tax arises only when you **dispose** of it:

* Selling crypto for dollars
* Paying for a purchase with crypto (barter transaction)
* Exchanging one crypto for another (e.g., ETH → SOL)

> **Note:** Transfers between your own wallets **are not dispositions**.

---

### c) Everything Is Calculated in CAD

Each transaction is valued at its **fair market value in Canadian dollars** at the exact time it occurs (sale, payment, trade).
This ensures accurate calculation of your gains, losses, and income.

---

### d) Rewards, Mining, and Staking

Cryptos received (through mining, staking, or activity-based airdrops) generally count as **income upon receipt**, based on their CAD value on that date.
That value becomes their **cost basis** for future gain/loss calculations.

---

## 3️⃣ Using TurboCrypto in 3 Steps

### 1. Connect or Import

Connect your accounts (e.g., **Shakepay, Coinbase, Binance**) and/or import CSV files and wallet addresses.
TurboCrypto centralizes your full transaction history.

### 2. Let It Calculate

TurboCrypto automatically:

* Converts every transaction into CAD (exact date/time)
* Calculates the **average cost per asset** and detects dispositions (sales, payments, trades)
* Separates income (staking/mining) and expenses (fees, gas)
* Keeps a complete **audit trail** (rates, fees, transaction IDs)

### 3. Export Reports

Generate:

* A **gains/losses report** ready for your **Schedule G (Capital Gains)**
* A **business income summary**, if applicable (**Schedule L**)
* All details needed for **line 24 of the TP-1** (crypto acquisition/holding/use) and the **crypto information return (TP-21.4.39)**

> **Québec 2024 Compliance:**
> If you acquired, held, or used cryptoassets during the year, you must answer line 24, and TP-21.4.39 may be required.
> TurboCrypto detects this automatically and prepares the necessary data.

---

## 4️⃣ FAQ — Quick Answers

### I only bought and held crypto. Do I owe taxes?

No, as long as you haven’t disposed of it (sold, paid, or exchanged).
However, you must still answer line 24 and possibly attach TP-21.4.39.
TurboCrypto reminds you automatically.

### Paying with BTC/ETH — is it taxable?

Yes. It’s considered a **disposition (barter)**.
A gain or loss may occur depending on CAD value at payment time.
TurboCrypto handles the calculation automatically.

### Is trading one crypto for another taxable?

Yes. It’s treated as selling the first and buying the second.
TurboCrypto manages conversion and updates your cost bases.

### How is my gain calculated?

```
Gain = Proceeds (CAD) – Average cost (CAD, including fees)
```

TurboCrypto applies the **average cost method** and maintains a full audit trail.

### Mining/staking — how do I declare it?

The CAD value of received coins at the time of receipt is generally **income**.
TurboCrypto records this and adjusts your cost basis for future calculations.

### Do I need to keep proof?

Yes — transaction history, conversion rates, fees, transaction IDs (txid).
TurboCrypto helps you **store and archive** all this information.

---

## 5️⃣ Key Takeaways

* Tax applies **only upon disposition**, not on mere holding.
* Calculations are in **CAD**, based on the **date/time** of each operation.
* **50% of capital gains** are taxable for 2024 (TurboCrypto applies the current rate).
* TurboCrypto automates imports, conversions, calculations, and reporting for accurate, compliant filing.

> ⚠️ **Disclaimer:**
> This guide is for information purposes only and **does not replace professional tax advice**.
> For complex cases (advanced DeFi, large volumes, businesses), consult a qualified tax professional.

---
# Comprehensive Guide to Crypto Asset Taxation in Quebec & Canada (2024 Tax Year)

**Version:** 1.1  
**Author:** Professional Team (based on user-provided documentation)  
**Jurisdictions:** Quebec (QC), Canada (CA-federal)  
**Last Reviewed:** 2025-10-26  
**Description:** This document provides practical rules for the taxation of crypto assets for individuals in Quebec and at the federal level for the 2024 tax year. It integrates new compliance obligations and provides guidance on common scenarios, including rewards programs.

---

## Table of Contents
1.  [Executive Summary](#1-executive-summary)
2.  [Key Compliance Obligations for 2024](#2-key-compliance-obligations-for-2024)
    -   [Mandatory Reporting: Form TP-21.4.39](#mandatory-reporting-form-tp-21439)
    -   [Penalties for Non-Compliance](#penalties-for-non-compliance)
    -   [Record Retention Requirements](#record-retention-requirements)
3.  [Tax Reporting Paths](#3-tax-reporting-paths)
4.  [Core Tax Principles & Calculations](#4-core-tax-principles--calculations)
    -   [Crypto as Property (Barter Transactions)](#crypto-as-property-barter-transactions)
    -   [Adjusted Cost Base (ACB) Method](#adjusted-cost-base-acb-method)
    -   [Capital Gains Inclusion Rate (2024)](#capital-gains-inclusion-rate-2024)
    -   [Mandatory Gain/Loss Ventilation for 2024](#mandatory-gainloss-ventilation-for-2024)
5.  [Decision Tree for Tax Events](#5-decision-tree-for-tax-events)
6.  [Classification of Activities & Special Rules](#6-classification-of-activities--special-rules)
    -   [Capital Gains vs. Business Income](#capital-gains-vs-business-income)
    -   [Non-Fungible Tokens (NFTs)](#non-fungible-tokens-nfts)
    -   [Superficial Loss Rule](#superficial-loss-rule)
    -   [Cross-Border Reporting (T1135)](#cross-border-reporting-t1135)
    -   [Sales Taxes (GST/QST)](#sales-taxes-gstqst)
7.  [Treatment of Rewards, Staking, and Mining](#7-treatment-of-rewards-staking-and-mining)
    -   [Reward Rules Summary Table](#reward-rules-summary-table)
    -   [Mining, Staking & "Earn" Programs](#mining-staking--earn-programs)
8.  [Data & Record-Keeping Requirements](#8-data--record-keeping-requirements)
    -   [Required Transaction Data Schema](#required-transaction-data-schema)
    -   [Data Integrity Controls](#data-integrity-controls)
9.  [Practical Examples](#9-practical-examples)
10.  [Escalation Policy](#10-escalation-policy)
11.  [Official Sources & References](#11-official-sources--references)
12.  [Appendix: AI Integration Playbook](#12-appendix-ai-integration-playbook)

---

## 1. Executive Summary

For the 2024 tax year, crypto assets are treated as **property**, not currency, by Canadian and Quebec tax authorities. This core principle means that any disposition—including selling for cash, swapping for another crypto, or using it to buy goods and services—is a taxable event.

**Key principles to remember:**
*   **New Mandatory Reporting (Quebec):** Starting in 2024, any individual who acquired, held, or used crypto assets must check a box on **line 24 of their TP-1 return** and file the new **Form TP-21.4.39**, even if no transactions occurred (i.e., "HODLing").
*   **Calculation Method:** Gains and losses must be calculated using the **average cost method** (Adjusted Cost Base - ACB). FIFO/LIFO methods are not permitted for identical properties like Bitcoin or Ethereum.
*   **Valuation:** All transactions must be valued at their Fair Market Value (FMV) in Canadian dollars ($CAD) at the time of the transaction.
*   **2024 Inclusion Rate:** The capital gains inclusion rate for 2024 remains at **50%**. The proposed increase to 66.67% has been deferred and does not affect the 2024 tax year.
*   **Record Keeping:** Taxpayers must maintain detailed records for a minimum of **six years** following the end of the relevant tax year.

This guide consolidates official rules to ensure accurate and compliant reporting for crypto asset activities.

## 2. Key Compliance Obligations for 2024

### Mandatory Reporting: Form TP-21.4.39

For 2024, Revenu Québec introduced a mandatory reporting requirement for all taxpayers involved with crypto assets.

*   **Who Must File:** Any individual who **acquired, held, or used** crypto assets at any point during 2024. This obligation applies even if you only held assets without making any transactions.
*   **How to File:**
    1.  Check "Yes" on **Line 24** of your provincial TP-1 tax return.
    2.  Complete and attach **Form TP-21.4.39, *Déclaration relative aux cryptoactifs***. This form consolidates all crypto-related activities, including capital gains (Parts 4.1/4.2), business income (Part 5), and other income like interest or rewards (Parts 6.1/6.2).

### Penalties for Non-Compliance

Failure to meet these new obligations can result in significant penalties.
*   **Failure to File Form TP-21.4.39:** A penalty of **$10 per day**, up to a maximum of **$2,500**.
*   **Inaccurate or Missing Information:** A penalty of **$100** for each piece of missing or incorrect information on the form.

These penalties are in addition to any interest or penalties on unpaid taxes resulting from unreported income.

### Record Retention Requirements

Tax authorities require taxpayers to keep comprehensive records to support their tax filings for a period of **at least six years**. For crypto assets, this includes:

*   Date and time of each transaction.
*   Type of transaction (buy, sell, swap, spend, reward, etc.).
*   Quantity and symbol of the asset.
*   Fair Market Value in Canadian dollars ($CAD) at the time of the transaction.
*   Transaction fees (gas, exchange commissions) in $CAD.
*   Counterparty details (exchange, other individual's wallet address).
*   Transaction IDs (TxID) and blockchain records.
*   Records of your wallet addresses.
*   Supporting documents like exchange CSV exports, screenshots, and receipts.

## 3. Tax Reporting Paths

Income and gains from crypto activities must be reported on specific lines of your tax returns. The final destination depends on the nature of the income.

| Income Type                 | Quebec (TP-1)                                      | Federal (T1)                      |
| --------------------------- | -------------------------------------------------- | --------------------------------- |
| **Capital Gains/Losses**    | **Line 139** (via Annexe G)                        | **Line 12700** (via Schedule 3)   |
| **Business/Property Income**| **Line 164** (via Annexe L, lines 16.1 & 26.1)     | **Lines 13499–14300** (via T2125) |
| **Other Income** (e.g., non-spend rewards) | **Line 154**                                       | **Line 13000**                    |
| **Interest Income** (e.g., staking, "Earn") | **Line 130**                                       | **Line 12100**                    |

## 4. Core Tax Principles & Calculations

### Crypto as Property (Barter Transactions)

The Canada Revenue Agency (CRA) and Revenu Québec (RQ) do not consider cryptocurrencies to be legal tender. Instead, they are treated as a commodity or property. This means any transaction where crypto is exchanged for something else is a **barter transaction**, which is a taxable disposition.

Common dispositions include:
*   Selling crypto for fiat currency (e.g., CAD, USD).
*   Trading one crypto for another (e.g., BTC for ETH).
*   Using crypto to purchase goods or services.
*   Gifting crypto to someone (you are deemed to have sold it at its fair market value).

### Adjusted Cost Base (ACB) Method

For identical properties like cryptocurrencies, you cannot choose which specific unit you are selling (e.g., "first-in, first-out"). Instead, you must calculate the average cost of all your holdings of that specific asset. This is the ACB.

**Formula Outline:**
1.  **New Total ACB** = Old Total ACB + Cost of new units (in $CAD) + Purchase Fees  
2.  **New Total Quantity** = Old Total Quantity + Quantity of new units  
3.  **ACB per Unit** = New Total ACB / New Total Quantity

**Calculating Gain or Loss on Disposition:**
1.  **Proceeds of Disposition** = Fair Market Value (in $CAD) of what you received - Sale Fees  
2.  **Cost of Disposed Units** = ACB per Unit (before the sale) × Quantity of units sold  
3.  **Gain (or Loss)** = Proceeds of Disposition - Cost of Disposed Units

### Capital Gains Inclusion Rate (2024)

For the 2024 tax year, **50%** of your net capital gains are taxable. This means if you have a net capital gain of $1,000, only $500 is added to your taxable income.

### Mandatory Gain/Loss Ventilation for 2024

Although the inclusion rate remained at 50% for all of 2024, the tax forms (specifically Annexe G in Quebec) were updated to prepare for a potential rate change. As a result, taxpayers **must** separate and report their capital gains and losses based on whether they occurred:
1.  **On or before June 24, 2024**  
2.  **On or after June 25, 2024**

Your transaction records must have precise timestamps to comply with this requirement.

## 5. Decision Tree for Tax Events

To determine your reporting obligations, follow this simplified logic:

**Q1: Did you acquire, hold, or use crypto assets in 2024?**  
*   **Yes:** You must check the box on line 24 of the TP-1 and file Form TP-21.4.39. Proceed to Q2.  
*   **No:** No specific crypto reporting is required.

**Q2: What was the nature of the event?**  
*   **Disposition (Sale, Swap, Spend):** This is a taxable event. Calculate the gain or loss. Determine if it is on capital or business account (see section 6.1).  
*   **Received a Reward:** This may be taxable upon receipt. Proceed to Q3.  
*   **Mining/Staking/"Earn":** Generally treated as income (interest or business) upon receipt, valued at its FMV. This FMV then becomes the ACB of the received asset.  
*   **Internal Transfer (between your own wallets):** Not a taxable event, but keep records to prove continuous ownership.

**Q3: Was the reward directly linked to a specific purchase (like credit card cashback)?**  
*   **Yes (Cashback-like):** Recommended (medium confidence) as a non-taxable rebate upon receipt. The crypto received has an ACB of $0, or reduces the cost base of the purchased item. Gain is realized only upon future disposition. *Escalate if material.*  
*   **No (Sign-up bonus, referral bonus, ShakingSats):** **Other Income**, taxable at FMV upon receipt (high confidence). The FMV becomes the asset's ACB.

## 6. Classification of Activities & Special Rules

### Capital Gains vs. Business Income

The default treatment for a casual investor is capital gains. However, if your crypto activities are frequent, organized, and conducted in a commercial manner, the tax authorities may classify them as a business activity.

| Factor                    | Capital Account Indication       | Business Account Indication                          |
| ------------------------- | -------------------------------- | ---------------------------------------------------- |
| **Frequency/Volume**      | Low, infrequent trades           | High, frequent, systematic trading                   |
| **Holding Period**        | Long-term (months/years)         | Short-term (days/hours), "day trading"               |
| **Intent**                | Long-term investment growth      | Short-term profit from market fluctuations           |
| **Knowledge/Time**        | Casual, hobbyist level           | Significant research, time, and expertise invested   |
| **Commercial Nature**     | No business plan, personal funds | Business plan, advertising, seeking financing        |

**Effect:** Business income is **100% taxable**, whereas capital gains are **50%** taxable.

### Non-Fungible Tokens (NFTs)

NFTs are treated as unique crypto assets.  
*   **Purchasing an NFT with crypto (e.g., ETH):** Two-part transaction. First, you **dispose** of the ETH (capital gain/loss). Second, you **acquire** the NFT. The ACB of the NFT is the FMV of the ETH at that moment.  
*   **Selling or Exchanging an NFT:** Disposition of the NFT. Gain/loss based on its specific ACB.

### Superficial Loss Rule

A superficial loss occurs if you sell a crypto asset at a loss and you (or an affiliated person) buy back the **same or identical property** within a 61-day window (30 days before the sale to 30 days after) and still own it at the end of that period.  
If the rule applies, your capital loss is denied and added to the ACB of the repurchased asset.

### Cross-Border Reporting (T1135)

If at any point during the year the total cost amount of your **specified foreign property** exceeds **$100,000 CAD**, you must file Form T1135.  
Crypto assets are considered specified foreign property if their "situs" (location) is outside Canada—often the location of the exchange or custodian (e.g., non-Canadian exchange). Self-custody situs is less clear and may require analysis.

### Sales Taxes (GST/QST)

*   **Trading Crypto:** Generally an exempt financial service (no GST/QST).  
*   **Paying with Crypto:** If you are a GST/QST registrant and accept crypto for taxable goods/services, you must collect/remit tax based on the crypto’s FMV in CAD at the time of the transaction.

## 7. Treatment of Rewards, Staking, and Mining

### Reward Rules Summary Table

| Rule ID | Reward Type                                             | Treatment on Receipt                                                                                                 | Reporting on Receipt (QC/Fed)                         | Disposition Route | Confidence |
| ------- | ------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- | ----------------- | ---------- |
| **RW1** | Cashback linked to a purchase                           | Non-taxable rebate. ACB of crypto is $0 (or reduces cost of goods). Gain realized only on future sale. *Escalate if material.* | None / None                                           | Capital           | Medium     |
| **RW2** | Not linked to a purchase (signup/referral, "ShakingSats") | Taxable as "Other Income" at FMV. FMV becomes the ACB.                                                               | TP-1 L154 / T1 L13000                                 | Capital           | High       |
| **RW3** | Interest / "Earn" / Staking                             | Taxable as interest or business income at FMV. FMV becomes the ACB.                                                 | TP-1 L130 (or L164) / T1 L12100 (or business lines)   | Capital           | High       |

### Mining, Staking & "Earn" Programs

Income from these activities is generally taxable when received.  
*   **Hobby:** Report FMV as interest/other income.  
*   **Business:** Report FMV as business revenue; related expenses may be deductible.  
In both cases, the reported FMV becomes the **ACB** of the new coins for future disposition calculations.

## 8. Data & Record-Keeping Requirements

Accurate reporting requires meticulous records. Minimum information per transaction:

### Required Transaction Data Schema

| Field                  | Type             | Description                                                                 | Required? |
| ---------------------- | ---------------- | --------------------------------------------------------------------------- | --------- |
| `timestamp_utc`        | String (ISO 8601) | Date and time of the transaction in UTC.                                    | **Yes**   |
| `asset_symbol`         | String           | Ticker symbol (e.g., BTC, ETH, NFT-ID).                                     | **Yes**   |
| `quantity`             | Number           | Amount transacted (positive or negative).                                   | **Yes**   |
| `side`                 | Enum             | Type (buy, sell, swap_in, mining, fee).                                     | **Yes**   |
| `jvm_cad`              | Number           | Fair Market Value in CAD.                                                   | **Yes**   |
| `fees_cad`             | Number / Null    | Fees (gas, commissions) in CAD.                                             | No        |
| `counterparty`         | String / Null    | Exchange name or wallet address.                                            | No        |
| `txid`                 | String / Null    | Blockchain transaction identifier.                                          | No        |
| `wallet_from`          | String / Null    | Source wallet address.                                                      | No        |
| `wallet_to`            | String / Null    | Destination wallet address.                                                 | No        |
| `exchange`             | String / Null    | Name of the exchange.                                                       | No        |
| `classification`       | Enum / Null      | Tax classification (CAP, BUS, INV).                                         | No        |
| `batch_id`             | String / Null    | ID for grouping imported transactions.                                      | No        |
| `evidence_link`        | String / Null    | URI to supporting document (screenshot, receipt).                           | No        |
| `comment_optional`     | String / Null    | Free-text notes.                                                            | No        |
| `taxable_flag_optional`| Boolean / Null   | Whether the transaction is a taxable event.                                 | No        |

### Data Integrity Controls

1.  **ACB Reconciliation:** Ending ACB = Opening ACB + acquisitions − cost base of disposed units.  
2.  **Temporal Ventilation:** Dispositions flagged correctly before/after the June 25, 2024 cut-off.  
3.  **Form Reconciliation:** Transaction totals match TP-21.4.39 and flow to Annexe G/L and TP-1/T1 lines.

## 9. Practical Examples

**Example 1: Cashback on Purchase**  
*   **Facts:** Receive $4 BTC as cashback.  
*   **Treatment:** Not taxable on receipt. ACB $0. Later sell for $9 → capital gain $9; taxable amount $4.50.

**Example 2: Referral Bonus**  
*   **Facts:** Receive $20 BTC referral bonus.  
*   **Treatment:** Include $20 as "Other Income" in year received. ACB becomes $20. Later sell for $26 → capital gain $6; taxable amount $3.

**Example 3: Interest from an "Earn" Program**  
*   **Facts:** Receive $10 stablecoin interest.  
*   **Treatment:** Include $10 as "Interest Income". ACB becomes $10.

## 10. Escalation Policy

Escalate for professional advice when facing:  
*   **Material amounts** in uncertain areas (e.g., large cashback).  
*   **Complex DeFi** (LP tokens, yield farming).  
*   **Business vs. capital** classification doubts.

**Routes:**  
*   **Revenu Québec:** *Demande de décision anticipée* (binding).  
*   **CRA:** Technical Interpretation (non-binding) or Advance Income Tax Ruling (binding).

## 11. Official Sources & References

*(Links provided by the user; verify directly on the official sites when filing.)*

| Label                                         | URL                                                                                                               |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| **RQ — Virtual Currency**                     | `https://www.revenuquebec.ca/fr/une-mission-des-actions/vous-aider-a-vous-conformer/.../monnaie-virtuelle/`      |
| **RQ — Line 24 (Crypto-assets) / TP-21.4.39** | `https://www.revenuquebec.ca/fr/citoyens/declaration-de-revenus/.../ligne-24/`                                   |
| **CRA — Cryptoassets Guide**                  | `https://www.canada.ca/en/revenue-agency/programs/about-canada-revenue-agency-cra/compliance/cryptocurrency-guide.html` |
| **CRA — Tax Lines (12700, 13000, etc.)**      | `https://www.canada.ca/en/revenue-agency/services/tax/individuals.html`                                          |

---

## 12. Appendix: AI Integration Playbook

Technical components and processes for building a Crypto Tax AI assistant based on this guide.

### A) Quickstart Integration

*   **PDF Indexing:**
    *   Index `crypto_tax_qc_2024_guide.pdf` with chunk size ~700 tokens, overlap ~80, respecting H1/H2.
*   **Tabular Data Ingestion:**
    *   `forms_mapping.csv`, `knowledge_map.json`, `rules_crypto_tax_qc_2024.json`, `schema_transactions_crypto.csv`.
*   **QA & Controls:**
    *   Reconciliations (TP-21.4.39 ↔ G/L ↔ TP-1), temporal ventilation (21/121), ACB checks.
*   **Testing:**
    *   Run `test_cases_fr.csv` for Annex G (21/121), Annex L (16.1/26.1), TP-1 (139/164).
*   **Deep Research:**
    *   Use `deep_research_plan.csv` (R01 → R20) to anchor official excerpts.

#### Example Ingestion Pipeline (Pseudo-code)

```python
# 1) PDF Indexing
doc = load_pdf("crypto_tax_qc_2024_guide.pdf")
chunks = chunk(doc, target_tokens=700, overlap=80, respect_headings=True)

# 2) Tabular Ingestion
forms_map = load_csv("forms_mapping.csv")
rules = load_json("rules_crypto_tax_qc_2024.json")
knowledge = load_json("knowledge_map.json")
schema = load_csv("schema_transactions_crypto.csv")

# 3) Post-processing & Routing
for disp in dispositions:
  route = route_from_rules(disp, rules, forms_map)
  apply_to_forms(route)

# 4) QA
assert reconcil_tp21_annexe_tp1()
assert split_annexe_g_21_121_ok()
assert acb_average_ok()

# 5) RAG (optional)
index_jsonl("rag_crypto_tax_qc_2024.jsonl")
```

### B) "Deep Research" Table (R01 → R20)

Refers to `deep_research_plan.csv`, used to validate key rules against primary sources. *(File content not included.)*

### C) Included Assets - Summaries & Inline Content

*   `README_assets.md` — Overview and usage for assets.  
*   `forms_mapping.csv` — Mapping for TP-21.4.39 → Annexe G/L → TP-1.  
*   `knowledge_map.json` and `rules_crypto_tax_qc_2024.json` — Rules engine & knowledge graph.  
*   `schema_transactions_crypto.csv` — ACB import schema and examples.  
*   `ingestion_config.yaml` — Chunking/normalization/QA settings.  
*   `faq_pairs_fr.csv` — FAQ on TP-21.4.39, barter, ACB, GST/QST.  
*   `test_cases_fr.csv` — Personas & scenarios.  
*   `prompts_kb.md` — Prompt snippets for classification/calculation/routing/QA.  
*   `glossary_fr.json` — NER glossary.

### D) Sample JSONL for RAG Ingestion

```json
{"id": "sec_synthese", "section": "Synthèse exécutive", "text": "Obligation 2024: TP-21.4.39 pour..."}
{"id": "sec_obligations", "section": "Obligations 2024", "text": "TP-1 ligne 24 (cryptoactifs) do..."}
{"id": "sec_traitements", "section": "Traitements fiscaux", "text": "Revenu d'entreprise: 100% im..."}
{"id": "sec_calcul", "section": "Calculs & PBR", "text": "Gain/perte = Produit (JVM $CA) - PBR..."}
{"id": "sec_scenarios", "section": "Scénarios", "text": "Échange BTC-ETH: aliénation BTC; PBR de..."}
{"id": "sec_nft", "section": "NFTs", "text": "Achat avec $CA: PBR NFT = prix + gas. Achat avec cr..."}
{"id": "sec_staking", "section": "Staking/Minage", "text": "Récompenses: revenu à la JVM à la réc..."}
{"id": "sec_taxes_vente", "section": "Taxes de vente", "text": "Si fourniture taxable et paiement..."}
{"id": "sec_procedure", "section": "Procédure conformité", "text": "Registre complet (6 ans) → T..."}
{"id": "sec_etude_julie", "section": "Étude de cas Julie 2024", "text": "PBR ETH moyen: 14 000/5=..."}
{"id": "sec_penalites", "section": "Pénalités", "text": "Non-production d'un formulaire prescrit:..."}
```

### E) Tests & Quality Controls

1.  Load `test_cases_fr.csv` and simulate classification (business/capital), superficial loss detection, etc.  
2.  Verify calculations & form logic (Annexe G lines 21/121; Annexe L lines 16.1/26.1 → TP-1 line 164).  
3.  Ensure ACB recalculates after each acquisition; reconcile totals across forms.

### F) Useful Downloads (placeholders)

*   **Main PDF Guide:** `/mnt/data/crypto_tax_qc_2024_guide.pdf`  
*   **Integration Playbook (this document):** `/mnt/data/crypto_tax_qc_all_in_one_playbook.pdf`  
*   **Assets Bundle (ZIP):** `/mnt/data/crypto_tax_qc_2024_assets.zip`  
*   **RAG JSONL:** `/mnt/data/rag_crypto_tax_qc_2024.jsonl`

