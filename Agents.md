# Event Ticket Price Arbitrage Scraper

This scraper monitors ticket price differences between **primary sellers** (like Ticketmaster) and **resale platforms** (like StubHub) to uncover arbitrage opportunities.

## Features:
- Compares ticket prices for the same event across primary and resale platforms.
- Filters opportunities based on price gaps.
- Outputs structured data, including URLs to the primary and resale listings.

## Inputs:
- `primarySellerUrls`: List of URLs from the primary seller.
- `resaleSiteUrls`: List of URLs from resale platforms.
- `maxTickets`: Maximum number of ticket listings to scrape per site.

## Outputs:
- Event Name
- Primary Seller Price
- Resale Price
- Price Difference
- URLs to primary and resale listings

## Use Cases:
- **Arbitrage:** Find events where resale prices exceed primary ticket prices.
- **Price Monitoring:** Track ticket price fluctuations across platforms.
