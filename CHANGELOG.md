# Changelog

## 2.0.0-a1 02/03/2026
  - [NEW] Initial release as standalone phpBB extension
  - [NEW] Extracted from bbGuild core as part of the game plugin architecture
  - [NEW] Implements `game_provider_interface` — registers EQ2 with bbGuild via tagged services
  - [NEW] `eq2_installer` extends `abstract_game_install` with clean array-based table names
  - [NEW] `eq2_provider` supplies game metadata (factions, ZAM URLs)
  - [CHG] Installer uses `$this->table()` helper instead of direct property access
  - [FIX] Italian race #12 language code corrected from 'ti' to 'it'
  - [NEW] Game images served from plugin directory
