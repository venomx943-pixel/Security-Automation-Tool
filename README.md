# Web Security Automation Tool

A professional, stealthy, and efficient automation tool designed for security researchers to streamline the reconnaissance phase. This script performs static analysis on client-side assets to uncover hidden endpoints and validates their availability while simulating human-like browsing patterns.

## Features
* **Static Analysis:** Extracts hidden API paths and endpoints from JavaScript files.
* **Stealthy Scanning:** Implements randomized User-Agent rotation and request jitter to bypass basic rate-limiting.
* **Intelligent Filtering:** Automatically ignores non-relevant assets (images, fonts, css) to reduce noise.
* **Vulnerability Insight:** Highlights paths with potential sensitive keywords (admin, config, etc.) and searches for potential secret leaks.
* **Multi-threaded:** Uses `ThreadPoolExecutor` for high-performance scanning.
