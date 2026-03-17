# LoioLog — Advanced Kodi Log Manager

Kodi addon for viewing, filtering, searching, analyzing and exporting Kodi logs.

## Installation

### Option 1: From Kodi File Manager (Recommended)

1. Go to **Settings → File Manager → Add Source**
2. Enter the URL: `https://loioloio.github.io/loiolog/`
3. Name it `LoioLog Repo` and click OK
4. Go to **Settings → Addons → Install from ZIP**
5. Select `LoioLog Repo` → `repository.loiolog` → `repository.loiolog-1.0.0.zip`
6. Go to **Install from Repository → LoioLog Repository → Programs → LoioLog → Install**

### Option 2: Manual ZIP Install

1. Download `plugin.program.loiolog-1.0.0.zip` from [Releases](https://github.com/loioloio/loiolog/releases)
2. In Kodi: **Settings → Addons → Install from ZIP** → select the downloaded file

## Features

| Tool | Description |
|---|---|
| **Filtered log** | Show recent entries mentioning a specific addon (configurable) |
| **Visual viewer** | Each line as a severity-colored list item |
| **Full log** | Complete unfiltered Kodi log |
| **Errors only** | Filter by error, warning, exception, traceback |
| **Previous log** | View kodi.old.log from the previous session |
| **Free search** | Search any text across the full log |
| **Regex search** | Search with regular expressions |
| **Event log** | Recent Kodi events (notifications, callbacks, signals) |
| **Statistics** | Severity counts + most mentioned addons |
| **Compare logs** | New errors in current vs previous log |
| **Export TXT** | Save filtered, full or errors-only to TXT |
| **Export JSON** | Structured JSON export with severity and timestamps |
| **Upload to paste** | Upload to termbin.com, copy URL to clipboard |
| **View on network** | Serve the log on a local web server for mobile viewing |
| **Log info** | File size, line count and path of current and old logs |
| **System info** | Kodi version, OS, CPU, RAM, Python, installed addons |
| **Toggle debug** | Enable/disable Kodi debug logging from the addon |
| **Reverse order** | Toggle between newest-first and oldest-first display |
| **Copy log path** | Copy the log file path to the system clipboard |
| **Filter by addon** | Pick an installed addon and show its log entries immediately |
| **Kodi paths** | Show main Kodi paths and copy any to clipboard |
| **RunScript API** | Documentation of available commands for other addons |
| **Delete logs** | Remove kodi.log and/or kodi.old.log with confirmation |

## Settings

- **Filter log by addon**: term to filter log entries
- **Enable sensitive data cleanup**: masks tokens, passwords and API keys in log output
- **Show newest entries first**: reverse display order

## Requirements

- Kodi 19 (Matrix) or newer
- Python 3

Available in English and Spanish.

## Support

[Open an issue](https://github.com/loioloio/loiolog/issues) on GitHub.
