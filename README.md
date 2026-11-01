# vscan-http-header-scanner
Performs lightweight scans of HTTP headers to identify common security vulnerabilities and misconfigurations, such as missing security headers (e.g., Strict-Transport-Security, X-Frame-Options). - Focused on Lightweight web application vulnerability scanning focused on identifying common misconfigurations and publicly known vulnerabilities

## Install
`git clone https://github.com/ShadowStrikeHQ/vscan-http-header-scanner`

## Usage
`./vscan-http-header-scanner [params]`

If the initial URL cannot be fetched, the tool reports that target as failed and exits 1, with no completion claim. A discovered link that cannot be fetched is reported as failed and not scanned, never as a page with no issues. Crawl links are resolved with urljoin against the page URL, and only links on the same scheme and host are followed. The `-r` flag prints the fetched raw headers for each scanned URL; values of credential shaped headers (Set-Cookie, Cookie, Authorization, Proxy-Authorization) are masked.

## Parameters
- `-h`: Show help message and exit
- `-v`: No description provided
- `-o`: No description provided
- `-r`: No description provided

## License
Copyright (c) ShadowStrikeHQ
