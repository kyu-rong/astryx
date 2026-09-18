---
'@astryxdesign/core': patch
---

[fix] ChatComposerInput: the trigger menu's default empty-state text and loading-state text now come from the i18n catalog (`@astryx.chatTriggerMenu.emptySearchResults`, `@astryx.chatTriggerMenu.loading`) instead of literals in the hook, so a localized app translates them. A trigger's own `emptySearchResultsText` and `loadingText` still take precedence. English output is unchanged.

@Kyujenius
