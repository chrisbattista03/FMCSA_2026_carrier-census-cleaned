# FMCSA_2026_carrier-census-cleaned
Cleaned, CRM Ready 2026 FMCSA Motor Carrier Census filtered for active fleets with 5+ power units. De-duplicated and formatted.
# 2026 FMCSA Motor Carrier Census (Cleaned & CRM-Ready)

A standardized, pre-filtered export of the FMCSA Company Census designed specifically for direct import into CRMs (Salesforce, HubSpot, Zoho) and outbound dialers.

This repository hosts a **50-row unmasked validation sample** (`premium_sample.csv`) so RevOps and engineering teams can inspect the schema and data quality prior to production licensing.

---

## The Master Dataset Overview

The raw FMCSA registry contains millions of inactive records, malformed phone strings, screaming all-caps text, and single-truck owner-operators that choke outbound pipelines. This dataset resolves those operational hurdles:

* **Active Fleets Only:** Filtered exclusively for active motor carriers operating **5 or more power units** (219,628 total records).
* **CRM Formatting:** All legal entities and DBA names converted to proper title case.
* **Dialer Normalization:** Phone numbers standardized to 10-digit formats `(XXX) XXX-XXXX`.
* **Cleaned Schema:** Includes USDOT, Legal Name, DBA, Phone, Email, Physical Address, Power Units, Total Drivers, and Add Date.

---

## Download the 50-Row Sample

You can inspect the sample file directly in this repository by opening [`premium_sample.csv`](./premium_sample.csv). Use this to test field mapping against your CRM import templates.

---

## Commercial Licensing & Full Database Access

The complete 219,628-record master file is packaged as a ready-to-import `.csv` asset for outbound sales teams, insurance brokers, freight factoring firms, and fleet tech vendors.

👉 **[Download the Full 219k Master Database on Gumroad](https://battista56.gumroad.com/l/qlctxn)**

---

## Technical Specifications
* **Record Count:** 219,628
* **File Type:** `.csv` (UTF-8 encoded)
* **Target Platforms:** Salesforce, HubSpot, Close, Outreach, Apollo, Salesloft
* **Data Origin:** Federal Motor Carrier Safety Administration (FMCSA) Company Census

For custom geographic splits, carrier size segmentations, or API integration inquiries, open an issue in this repository or contact:
`Chris Battista` | [servicesoftwarepro.com](https://servicesoftwarepro.com)
