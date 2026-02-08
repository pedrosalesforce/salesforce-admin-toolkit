# Salesforce Admin Toolkit

A collection of production-ready Salesforce tools built to solve real admin pain points.  
Open-core, admin-first, and designed for real-world orgs.

Built by admins, for admins.

---

## Overview

This repository contains a set of modular tools aimed at improving productivity, reliability, and maintainability in Salesforce orgs.

The project follows an **open-core model**:
- Core functionality is open source and available to the community
- Advanced features are offered as Pro modules

The goal is to provide **practical, opinionated solutions** to problems admins face every day.

---

## Modules

### Flow Error Logger
Centralized error logging for Salesforce Flows.

**Core features**
- Custom object to store Flow errors  
- Reusable subflow for error logging  
- Manual logging from any Flow  
- Basic LWC to view logged errors  
- Permission Set included  
- Clear documentation and examples  

**Pro features**
- Unlimited logs  
- Alerts (Email / Chatter)  
- Advanced filters and grouping  
- Error retention policies  
- Enhanced dashboard  
- Priority support  

---

### LWC DataTable Pro
Reusable and configurable data table component that extends `lightning-datatable`.

**Core features**
- Dynamic columns  
- Basic sorting  
- Works with standard and custom objects  
- Simple configuration  
- Examples and documentation  

**Pro features**
- Advanced filters (text, picklist, date)  
- Server-side pagination  
- CSV export  
- Secure dynamic SOQL  
- Related list support  
- Custom Metadata configuration  

---

### Admin LWC Pack
A set of reusable UI components for Salesforce admins.

**Core features**
- Configurable modal  
- Confirmation dialog  
- Toast manager  
- Reusable action button  
- Salesforce-aligned UI  

**Pro features**
- Dynamic forms  
- Inline edit components  
- Metadata-driven rendering  
- Advanced validation  
- Component playground  

---

### Org Health Check
Automated analysis of Salesforce org health.

**Core features**
- Basic security and configuration checks  
- Simple dashboard  
- Checklist of findings  
- General recommendations  

**Pro features**
- Global health score  
- Advanced metadata analysis  
- Technical debt detection  
- Prioritized recommendations  
- PDF export  
- Scheduled scans  
- Historical tracking  

---

## Repository Structure

salesforce-admin-toolkit/
├─ docs/
├─ packages/
│  ├─ flow-error-logger/
│  ├─ lwc-datatable-pro/
│  ├─ admin-lwc-pack/
│  └─ org-health-check/
├─ scripts/
├─ README.md
└─ LICENSE

---

## Open Core Model

This project follows an **open-core** approach.

- Core functionality is open source and licensed under MIT  
- Pro features are distributed separately as managed packages or private modules  

The distinction between Core and Pro is clearly documented for each module.

---

## Getting Started

Each module contains its own README with:
- Installation steps  
- Configuration instructions  
- Usage examples  
- Known limitations  

Start with the **Flow Error Logger** if you want the quickest value.

---

## Roadmap

- [x] Flow Error Logger (MVP)  
- [ ] Flow Error Logger alerts  
- [ ] Enhanced LWC dashboard  
- [ ] DataTable advanced filtering  
- [ ] Org Health Check scoring  
- [ ] Bundle release  

The roadmap may evolve based on community feedback.

---

## Contributing

Contributions are welcome.

You can contribute by:
- Reporting bugs  
- Suggesting features  
- Improving documentation  
- Submitting pull requests  

Please keep contributions aligned with the project’s scope and philosophy.

---

## License

This project is licensed under the **MIT License**.

Core features are open source.  
Pro features are distributed separately.

---

## Disclaimer

This project is not affiliated with, endorsed by, or sponsored by Salesforce.  
Salesforce is a registered trademark of Salesforce, Inc.
