# Awesome CampaignTech

## Contents

## About this list

At the same time that getting good people into office has never been more important, running an effective political campaign has never been more complex. 

Effective campaigning in 2022 means bringing together a wide array of tools to bridge the physical reality of running a field program and digital demands of brand awareness, fundraising, and mass communication, often wrangling data that is both overwhelming and quickly-outdated. Political campaigns are almost always understaffed, underfunded, and out of time.

There are some monolithic platforms that have grown to fill these needs (and some are undeniably amazing) but they are often out of reach of first-time or grassroots candidates and, even then, only as good as the data your finance and field teams provide them. 

This is a (growing) curated collection of tools and resources that I use, or have at some point found helpful, to solve the "mechanical", nitty-gritty problems of running a political campaign.

## Advertising

- [Facebook Ad Library](https://www.facebook.com/ads/library/) - Facebook's repository of all ads. Great to use as a resource for inspiration and to monitor opposition messaging/spend.

- [Facebook Political Ads Collector](https://github.com/CybersecurityForDemocracy/FacebookApiPolAdsCollector) - Python collector for the FB Ad Library API

- [Google Advertising Transparency Report](https://adstransparency.google.com/) - Google's repository of all political advertising published through the Google Ad Network, including YouTube ads.

- 

## CRM/DRM

- [CiviCRM](https://civicrm.org/) - Self-hosted, open-source CRM for donor and volunteer management. Alternative (with a bunch of elbow grease) to NGP. Large ecosystem of extensions and mature, well-documented REST api. Native integration with Wordpress, Drupal, and Joomla.



## Email

- [MJML](https://mjml.io/) - Responsive email framework that takes the pain out of building good-looking, cross-platform emails. Can be used with a native editor, as a nodejs module, or free-to-use API. Very easy to build the classic 1-col fundraising email layout.

- [Stripo.email](https://stripo.email/) - Hybrid WISYWIG/code editor for email production. Lots of quality-of-life features, like device preview, asset hosting, and export to many different ESPs. The editor itself feels kind of clunky/limited but code can be edited simultaneously.

- [Can I Email...?](https://www.caniemail.com/) - HTML/CSS feature reference for compatability and client support. Important to know that 60% of your recipients won't see your slick linear-gradient header, so be sure to set a fallback. 

## Security

- [Defending Digital Campaigns](https://defendcampaigns.org/) - Non-profit that offers cybersecurity training, resources, and products at low-to-no cost to Federal campaigns.

- [1Password For Democracy](https://1password.com/for-democracy/) - Cross-platform password manager for teams, free for political organizations.

## Data Management

- [move-coop/Parsons](https://github.com/move-coop/parsons) - Fantastic python utility library that makes it easy to interact with the APIs of many common campaign tools, like NGPVAN, Mobilize, and Hustle. Connectors abstract Requests and Parsons Table wraps petl with a bunch of quality-of-life methods for getting data in and out of various formats.

- [ActBlue Connector for AirByte](https://github.com/community-tech-alliance/airbyte-source-actblue)

- [dedupeio](https://github.com/dedupeio/dedupe) - Python library that uses machine learning to perform fuzzy matching, deduplication, and record-linking.

## Datasets

- [Open States Bulk Data](https://openstates.org/data/) - State legislature data for upper and lower chambers in each state. Has data on legislators, bills, and votes. Bulk data and API available.
- [FEC Bulk Data](https://www.fec.gov/data/browse-data/?tab=bulk-data) - Bulk data downloads for Federal committees.
- 

## Geospatial

- [New York State Legislative Task Force on Demographic Research and Reapportionment](https://latfor.state.ny.us/data/) - NYS legislative boundaries for CD/SD/AD, available in shapefiles.

- [NYS Street Address Mapping (SAM)](http://gis.ny.gov/streets/) - NYS GIS geocoding service. Typically an exact match for the state voter file.