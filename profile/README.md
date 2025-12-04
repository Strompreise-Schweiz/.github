![Strompreise Schweiz Logo](../assets/Logo_Strompreise_Schweiz.svg)  
  

# Strompreise Schweiz – Swiss Electricity Tariffs (Open Data)

[![License: terms_by_ask](https://img.shields.io/badge/license-terms__by__ask-purple)](https://www.dcat-ap.ch/vocabulary/licenses/20240716.html#terms_by_ask)
[![Validation with ajv](https://img.shields.io/badge/validation-ajv-orange)](https://github.com/Strompreise-Schweiz/supplier-data-validation)
[![Open Data](https://img.shields.io/badge/open-data-yellow)](https://www.strompreise-schweiz.ch)

This GitHub organization provides an **open and unified way to publish Swiss electricity tariffs** from energy suppliers, either as **static** or **dynamic** data.  

## Purpose and Goal

Switzerland already has [ElCom’s official electricity price comparison platform](https://www.strompreis.elcom.admin.ch/), which provides a **general overview of average annual prices**. Additionally, associations like [Verein SmartGridready](https://smartgridready.ch/loesungen/dynamischetarife) list or link to **dynamic tariffs** published by some utilities.

This initiative complements it by going one step further:  
- Publishing **detailed tariff structures**, not just averages of **static and dynamic tariffs**.  
- Enabling consumers to understand **exactly what they pay for electricity**.  
- Allowing **Energy Management Systems (EMS)** – such as smart home controllers, solar optimizers, or EV charging stations – to automatically shift consumption to times when electricity is both **available and affordable**.  
- Providing an **ecosystem for dynamic tariffs**, where energy suppliers not only publish **daily updated tariff data**, but also rely on a **stable infrastructure, validation tools, and operational support** that ensure long-term **traceability, consistency, and reliability** of their data.

The project’s ultimate goal is to make **Swiss electricity tariffs transparent, comparable, and usable** — both for **consumers** and for **automated energy systems**.   

## Open Data principles

Energy suppliers are encouraged to publish their tariff data under open license terms defined by [www.dcat-ap.ch](https://www.dcat-ap.ch/). Within this organization, the target license is:  

- [`terms_by_ask`](https://www.dcat-ap.ch/vocabulary/licenses/20240716.html#terms_by_ask)  

This means:  
- Free usage is permitted.  
- Attribution is required (author, title, and link to the dataset).  
- Commercial use is only allowed with prior permission from the data provider.  

Please note: Logos, brand names, and other graphical assets included in repositories remain the property of their respective owners and are **not automatically licensed for reuse**.  

Other providers may publish similar datasets outside of this organization, possibly under different license terms. Always check the dataset’s own documentation.  

## About this GitHub Organization

This GitHub organization hosts **two types of repositories**:

1. **Electricity tariff data (Open Data):**  
   Repositories where Swiss energy suppliers or electricity providers can publish their tariffs.  
   - Some datasets are updated **once per year**.  
   - Others are updated **daily** (e.g., dynamic tariffs).  

2. **Validation & Schema repositories (Open Source):**  
   Tools and JSON Schemas for validating published tariff data.   

All repositories in this organization are either **Open Source** or **Open Data**.  

## Ecosystem

- The website [www.strompreise-schweiz.ch](https://www.strompreise-schweiz.ch) indexes and lists available datasets.  
  - It is **not open source**, but serves as a **central aggregator**.  
- Everyone is free to build their own portal or services on top of the open datasets, for example by converting tariffs into **OCPI**, a standard widely used in the e-mobility sector.  

## Contributing

Everyone is welcome to contribute:  

- **Energy suppliers** can create their own repository in this organization and become the maintainer of their tariffs.  
- **Developers and enthusiasts** can improve schemas, validation, or build tools on top of the published data.  

We strongly encourage Swiss energy suppliers to participate — **these datasets enable real innovation**. It is not enough to just *talk* about supporting green technologies and innovation. By publishing transparent electricity tariffs, suppliers actively **shape the future of energy in Switzerland**.  

If you are unsure how to start, feel free to contact us at info@strompreise-schweiz.ch, we are happy to help. The most important step is the **will to co-create the energy future**.  

For questions, ideas, or collaboration proposals, please also use the [Discussions](https://github.com/orgs/Strompreise-Schweiz/discussions) section.  
