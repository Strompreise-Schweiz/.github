![Strompreise Schweiz Logo](../assets/Logo_Strompreise_Schweiz.svg)  
  

# Strompreise Schweiz – Swiss Electricity Tariffs (Open Data)

[![License: terms_open](https://img.shields.io/badge/license-terms__open-green)](https://www.dcat-ap.ch/vocabulary/licenses/20240716.html#terms_open)
[![License: terms_by](https://img.shields.io/badge/license-terms__by-blue)](https://www.dcat-ap.ch/vocabulary/licenses/20240716.html#terms_by)
[![Validation with ajv](https://img.shields.io/badge/validation-ajv-orange)](https://github.com/Strompreise-Schweiz/supplier-data-validation)
[![Open Data](https://img.shields.io/badge/open-data-yellow)](https://www.strompreise-schweiz.ch)

This GitHub organization provides an **open and unified way to publish Swiss electricity tariffs** from energy suppliers, either as **static** or **dynamic** data.  

## Why this project exists

Switzerland already has [ElCom’s official electricity price comparison platform](https://www.strompreis.elcom.admin.ch/), which is excellent for obtaining a **general overview of average prices**.  

This initiative complements it by going one step further:  
- We aim to publish **detailed electricity tariffs** with full price structures, not just averages.  
- With this level of detail, consumers know **exactly what they pay for electricity**.  
- And **Energy Management Systems (EMS)** – such as smart home controllers, solar optimizers, or EV charging stations – can automatically shift consumption to times when electricity is both **available and affordable**.  

## Open Data principles

Energy suppliers are encouraged to publish their tariff data under one of the following open licenses, defined by [www.dcat-ap.ch](https://www.dcat-ap.ch/):  
- [`terms_open`](https://www.dcat-ap.ch/vocabulary/licenses/20240716.html#terms_open)  
- [`terms_by`](https://www.dcat-ap.ch/vocabulary/licenses/20240716.html#terms_by)  

They can publish directly within this GitHub organization, or host their data elsewhere.  
The key is to make tariff data **accessible, machine-readable, and transparent**.  

## About this GitHub Organization

This GitHub organization hosts **two types of repositories**:

1. **Electricity tariff data (Open Data):**  
   Repositories where Swiss energy suppliers or electricity providers can publish their tariffs.  
   - Some datasets are updated **once per year**.  
   - Others are updated **daily** (e.g., dynamic tariffs).  

2. **Validation & Schema repositories (Open Source):**  
   Tools and JSON Schemas for validating published tariff data.  
   Example: [supplier-data-validation](https://github.com/Strompreise-Schweiz/supplier-data-validation).  

All repositories in this organization are either **Open Source** or **Open Data**.  

## Ecosystem

- The website [www.strompreise-schweiz.ch](https://www.strompreise-schweiz.ch) indexes and lists available datasets.  
  - It is **not open source**, but serves as a **central aggregator**.  
- Everyone is free to build their own portal or services on top of the open datasets – for example by converting tariffs into **OCPI**, a standard widely used in the e-mobility sector.  

## Validation with ajv

We use [ajv](https://ajv.js.org/) for JSON Schema validation. Please see the dedicated repository: [supplier-data-validation](https://github.com/Strompreise-Schweiz/supplier-data-validation).  

## Contributing

Everyone is welcome to contribute:  

- **Energy suppliers** can create their own repository in this organization and become the maintainer of their tariffs.  
- **Developers and enthusiasts** can improve schemas, validation, or build tools on top of the published data.  

We strongly encourage Swiss energy suppliers to participate — **these datasets enable real innovation**.  

It is not enough to just *talk* about supporting green technologies and innovation. By publishing transparent electricity tariffs, suppliers actively **shape the future of energy in Switzerland**.  

If you are unsure how to start, feel free to contact us at **info@strompreise-schweiz.ch**, we are happy to help. The most important step is the **will to co-create the energy future**.  

## Goal

The project’s goal is to make **Swiss electricity tariffs transparent, comparable, and usable** — both for **consumers** and for **automated energy systems**. 
It complements [strompreis.elcom.admin.ch](https://www.strompreis.elcom.admin.ch/) by adding **detailed tariff structures** that unlock new possibilities for smart energy usage.  
