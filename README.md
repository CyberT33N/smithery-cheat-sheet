# Smithery Cheat Sheet

<br><br>
<br><br>

# Smithery CLI
- https://github.com/smithery-ai/cli
- **Will start the MCP cloud bases at Smithery**

<details><summary>Click to expand..</summary>

```bash
# Smithery CLI Befehl ausführen (ohne Installation)
npx -y @smithery/cli@latest [befehl] [parameter]
```

## Installieren eines Pakets
```bash
npx -y @smithery/cli@latest install <server> --client <name> --yes
```
- `--client <name>`: Gibt den AI-Client an
- `--config <json>`: Konfigurationsdaten als JSON bereitstellen (überspringt Eingabeaufforderungen)
- `--key <apikey>`: API-Schlüssel bereitstellen

## Deinstallieren eines Pakets
```bash
npx -y @smithery/cli@latest uninstall <server>
```

## Inspektion eines Servers aus dem Registry
```bash
npx -y @smithery/cli@latest inspect <server>
```

## Starten eines Servers
```bash
npx -y @smithery/cli@latest run <server>
```
- `--config <json>`: Konfigurationsdaten als JSON bereitstellen
- `--key <apikey>`: API-Schlüssel bereitstellen

## Verfügbare Clients auflisten
```bash
npx -y @smithery/cli@latest list clients
```

### Globale Optionen
- `--help`: Zeigt diese Hilfemeldung an
- `--verbose`: Zeigt detaillierte Logs an

</details>

