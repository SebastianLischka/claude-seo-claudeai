# claude-seo für claude.ai (Spiegel)

Spiegel von [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) (MIT), angepasst für den Plugin-Sync von claude.ai.

**Einzige Änderung:** Das verschachtelte Plugin `plugins/seo-cockpit` (Claude-Code-Mods-Begleiter) und sein Eintrag in `.claude-plugin/marketplace.json` sind entfernt. claude.ai lehnt Plugins mit verschachtelter `plugin.json` ab.

**Updates:** `.github/workflows/sync.yml` prüft täglich das Original und öffnet bei Änderungen einen Pull Request. Vor dem Merge den Diff prüfen.

**Rückweg:** Sobald das Original ohne Patch in claude.ai synchronisiert, diesen Spiegel als Marketplace entfernen und `AgriciDaniel/claude-seo` direkt eintragen.
