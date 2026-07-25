# web_server

This project is part of the System Engineering / DevOps curriculum. It covers the basics of web servers, DNS, HTTP, and how to publish files to a remote server.

## Requirements

- Ubuntu 16.04 LTS
- Allowed editors: `vi`, `vim`, `emacs`
- All Bash scripts must pass `Shellcheck` (version 0.3.7) without errors
- All Bash scripts must start with `#!/usr/bin/env bash`
- The second line of every script must be a comment explaining what it does
- All Bash scripts must be executable
- `systemctl` is not allowed for restarting processes

## Files

| File | Description |
| --- | --- |
| `0-transfer_file` | Transfers a file from the client to a server's home directory using `scp`, with strict host key checking disabled|
| `1-install_nginx_web_server` | Installs and configures nginx, serving a page containing "Holberton School" on port 80 |
| `2-setup_a_domain_name` | Contains the registered .tech domain name pointing to web-01 |
| `3-redirection` | Configures nginx so that `/redirect_me` returns a 301 redirect |
| `4-not_found_page_404` | Configures nginx with a custom 404 page containing "Ceci n'est pas une page" |
| `5-design_a_beautiful_404_page.html` | A creative, Magritte-inspired 404 page design containing "Ceci n'est pas une page" |
