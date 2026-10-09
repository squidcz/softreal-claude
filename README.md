# Softreal – plugin pro Claude

Připojí Clauda k MCP serveru Softrealu (`https://mcp.softreal.cz/`). Claude pak může
číst nabídky nemovitostí, poptávky a klienty, ke kterým má přihlášený uživatel přístup.
Konektor pouze čte, nic nevytváří, nemění ani nemaže.

## Instalace (Claude Code)

Z marketplace v tomto repozitáři (GitHub `squidcz/softreal-claude`):

```
/plugin marketplace add squidcz/softreal-claude
/plugin install softreal@softreal
```

Lokálně pro vývoj:

```
claude --plugin-dir .
```

Po instalaci spusť `/mcp`, vyber server `softreal` a přihlas se do Softrealu (OAuth).

## Příklady dotazů

- Najdi moje nabídky v Softrealu.
- Shrň moje poptávky v Softrealu.
- Najdi klienta v Softrealu.

## Odkazy

- Web: https://www.softreal.cz/
- Podpora: https://www.softreal.cz/kontakt
- Ochrana soukromí: https://mcp.softreal.cz/privacy#soukromi
- Podmínky: https://mcp.softreal.cz/privacy#podminky
