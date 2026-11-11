# WoW Forever Economy Toolkit

A community-focused economy analysis toolkit for **World of Warcraft Forever**, built around NPC vendor inventories, TradeSkillMaster auction house data, and crafting profitability.

## Project Goals

The goal is to help players make informed economic decisions with limited starting capital by identifying potentially profitable opportunities.

The toolkit is intended to:

- Discover items available from NPC vendors.
- Compare NPC purchase prices against current auction house market prices.
- Account for auction house fees, vendor reputation discounts, and limited-stock items.
- Identify profitable crafting recipes and material costs.
- Generate simple, readable reports for players.

## Technology

- PowerShell 7 for data collection and analysis
- TradeSkillMaster (TSM) public auction house data
- CSV-based historical price archives
- WoW Forever item and vendor information

## Planned Features

- NPC vendor inventory database
- Vendor-to-auction-house profit calculator
- Crafting profitability reports
- Price history and trend analysis
- Risk indicators based on available market data

## Data Sources and Attribution

This project uses publicly available auction house data and aims to integrate additional game information through authorized APIs.

**ForeverDB:** https://foreverdb.net

ForeverDB is credited as a potential source of item, vendor, and game-world data. Any future use of its API will follow its access requirements and attribution rules.

TradeSkillMaster: https://www.tradeskillmaster.com

## Project Status

**Early development / proof of concept**

The initial focus is on building a reliable NPC vendor price database and comparing vendor purchase prices with auction house prices.

No automated in-game purchasing, auction posting, or gameplay automation is planned.

## License

MIT License for the original project code. Third-party game data remains subject to the respective providers' terms and licenses.
