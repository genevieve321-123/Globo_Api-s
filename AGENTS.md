# AGENTS.md

## Repository Overview
This repository tracks a collection of proxy IP addresses and API endpoints.

---

## Recent Changes

### October 2025

#### Proxy IP Database Update
**Commit:** `22249fc` (2025-10-10)  
**Author:** genevieve321-123

- **Action:** Restored previous proxy list ("Undo last action")
- **Impact:** Re-added 327 proxy IP addresses to the `IP's` file
- **Details:** The file now contains a comprehensive list of HTTP and SOCKS proxies with various ports (primarily port 80, 8080, and 3128)

**Proxy Collection Stats:**
- Total entries: 327 IP addresses
- Primary ports used: 80, 8080, 3128, and various custom ports
- Geographic distribution: Global proxy servers from various regions

---

## Repository Structure

```
Globo_Api-s/
└── IP's          # Main proxy list file containing IP:PORT entries
```

---

## File Details

### `IP's`
A plain text file containing proxy server addresses in the format `IP:PORT`. This file serves as a database of available proxy endpoints that can be used for API requests or web scraping operations.

**Format:**
```
<IP_ADDRESS>:<PORT>
```

**Example entries:**
```
104.16.130.82:80
104.21.19.154:80
160.153.1.156:80
```

---

## Notes

- The repository currently has minimal commit history (1 commit)
- The main focus is maintaining a curated list of proxy servers
- No additional documentation or code files present at this time

---

*Last Updated: 2025-11-18*  
*This file was automatically generated based on git commit history*
