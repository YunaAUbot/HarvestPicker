# HarvestPicker

This fork reads Lifeforce prices from Ninja Price's local cache instead of
requesting them directly from poe.ninja. The selected league comes from
`config/global/Ninja_Price.Main_settings.json`; prices are loaded from the
matching `Plugins/Temp/Get-Chaos-Value/NinjaData/<league>/Currency2.json`.

Ninja Price must therefore be installed and must have completed at least one
cache update for the selected league. HarvestPicker automatically reloads the
prices when Ninja Price replaces the currency cache. The **Reload Prices**
button can be used to reload it manually.

If you like it, you can donate via:

BTC: bc1qke67907s6d5k3cm7lx7m020chyjp9e8ysfwtuz

ETH: 0x3A37B3f57453555C2ceabb1a2A4f55E0eB969105
