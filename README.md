# SaniStar System User Guide

This repository contains the SaniStar system user guide. The guide supports the ERP-lite workflow used for service tickets, sales orders, build orders, inventory, material management, shipping, invoicing, stock replenishment, and production.

## Purpose

The user guide is intended to help team members understand the business workflow, where information is entered, how records move through the system, and what to watch for during daily use.

## Guide Outline

- **Overview** - Introduction to the guide, system purpose, and technology structure.
- **Look Outs** - Important system notifications, refresh behavior, and items that need user attention.
- **Getting Started** - Login, navigation, and basic first-use guidance.
- **Sales Orders** - How sales order information is entered and how it drives downstream activity.
- **Service Tickets** - How service requests are handled, resolved, and documented.
- **Build Order** - How build orders are created and connected to production activity.
- **Inventory** - Inventory tracking, related workflows, and stock movement.
- **Shipping & Invoicing** - Final workflow steps for shipment and invoice processing.
- **Material Management** - SKUs, PAMs, material relationships, and prerequisite data.

## Project Structure

- `index.html` - Main overview page.
- `content/` - Individual guide pages.
- `partials/` - Shared header and sidebar navigation.
- `images/` - Screenshots, diagrams, logos, and visual references.
- `js/` - Shared JavaScript for partial loading and image modal behavior.
- `styles.css` and `css/styles.css` - Styling for the guide.

## Viewing the Guide

Open `index.html` in a browser to view the guide locally.

The intended hosted URL is:

```text
https://userguide.sanistardump.com/
```

## Notes

- Keep customer, order, service, inventory, and production records complete and accurate.
- Once the system is live, transactions within the system scope should be recorded through the workflow.
- If data drifts from actual business activity, corrective steps may be needed to realign the records.

