# WP Phlox-Pro XSS Vulnerability Checker

This Python tool checks for potential Cross-Site Scripting (XSS) vulnerabilities in WordPress websites using the Phlox Pro theme. It assesses accessibility to the Phlox Pro theme's `style.css` file, identifies version information, and highlights potential 'searchform' XSS vulnerabilities based on the detected version.

![demo](https://raw.githubusercontent.com/D4rkLyc4n/phlox-pro-XSS-/main/demo.jpg)

## Features
- Validates accessibility to the Phlox Pro theme's `style.css` file.
- Retrieves version information and assesses potential vulnerabilities.
- Identifies XSS vulnerability likelihood in the 'searchform'.
- Provides an example payload for potentially exploited sites.

## Usage
1. Prepare a `website.txt` file containing WordPress website URLs.
2. Run the Python script to check each URL for potential vulnerabilities.
3. Receive version details and vulnerability assessments for each site.

**Usage Example:**
```bash
./Phlox-Pro_XSS.bin 
