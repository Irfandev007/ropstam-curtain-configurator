``` Shopify Made-to-Measure Curtain Configurator```

Ropstam Solutions - Senior Shopify Developer Assessment
Project: Made-to-Measure Curtain Configurator

Developer: Irfan Ali

This repository contains the technical implementation for the Senior Shopify Developer assessment at Ropstam Solutions. The project is designed to demonstrate advanced expertise in Shopify data modeling, custom Product Detail Page (PDP) development using Liquid and vanilla ES6+ JavaScript, Ajax Cart API integration, and robust order data integrity.

Technical Overview & Implementation Details
To address the core requirements of dynamic pricing, user-friendly eCommerce experiences, and strict cart validation, this solution implements the following architecture:

Real-Time Dynamic Pricing Engine: Computes custom pricing instantly on the frontend using width tiers and drop multipliers driven dynamically by Shopify Metaobjects.

Premium Product Page Customization: The user interface has been fully customized with a mobile-first CSS grid layout, sticky desktop media anchoring, live fabric swatch preview switching, and intuitive validation handling.

Price-Matched Variant Architecture: Because standard Shopify architecture restricts direct frontend price overrides via the cart API for security reasons, direct pricing cannot be passed straight from Metaobjects. To resolve this, the system implements a price-matched variant resolution pattern where calculated totals are programmatically mapped to pre-configured variants within the Shopify Admin to ensure accurate, single-item checkout totals.

Platform Context & Shopify Plus Capabilities: While standard Shopify plans require a client-side variant-matching approach to bypass these API limitations, native dynamic pricing and custom pricing logic without variants are offered natively exclusively on Shopify Plus via Checkout Extensibility and Shopify Functions.

Modular Block-Based Architecture: Developed using dynamic Liquid blocks, enabling merchants to configure labels, inputs, and fabric swatches directly within the Shopify Theme Editor for both desktop and mobile environments.

Note on Code Documentation: I have included detailed inline comments throughout the product page code to clearly map each logic section to its corresponding block element. It is my standard practice to leave comprehensive comments to streamline the review process and make it easier for future developers to navigate, maintain, or update specific areas of the codebase.
