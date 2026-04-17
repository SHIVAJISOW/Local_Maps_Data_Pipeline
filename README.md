# 🚀 Enterprise B2B Lead Generation Engine

## Overview
A custom Python-based data extraction pipeline designed for high-volume B2B lead generation via Google Maps. This engine bypasses standard scraping limitations (like the Virtual DOM trap) to deliver 100% unique, cleaned data directly into CSV format for immediate use in cold outreach or custom ad audiences.

## ⚙️ Core Engineering Features
* **Virtual DOM Bypass (URL Sniping):** Instead of relying on flawed visible UI clicking, the bot rapidly scrolls and extracts backend URLs before they vanish from the DOM, ensuring zero duplicate data.
* **Deep Profile Extraction:** Enters individual business profiles to pull hidden data (exact open hours, specific store tags) rather than relying on surface-level sidebars.
* **Data Cleansing Engine:** Automatically scrubs messy HTML tags, Unicode errors (`\xa0`), and poor formatting before writing to the database.
* **Massive Scale Appending:** Built-in command flags allow for "Micro-Targeting" (searching specific neighborhoods) and stacking thousands of leads into a single Master CSV without overwriting previous work.

## 🛠️ Tech Stack
* **Language:** Python 3.8+
* **Automation:** Playwright (Chromium)
* **Data Structuring:** Pandas, Dataclasses

## 📈 Use Case for Performance Marketing
This tool replaces expensive B2B data subscriptions by creating an unlimited, free, in-house pipeline for local business data. 

## 🤝 Credits & Architecture
Initial project scaffolding based on the open-source work by zohaibbashir. The core extraction engine has been completely rewritten and upgraded in this repository to include Playwright URL-sniping, Virtual DOM bypassing, and automated CSV appending for large-scale enterprise extraction.