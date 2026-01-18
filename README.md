# Stream-Reels: Instagram Reel Downloader

**Stream-Reels** is a focused web utility for viewing and downloading Instagram Reels. Paste a valid Reel URL to instantly preview the video and access the download link.

## Key Features

* **Reel Focus:** Strictly accepts and processes only Instagram Reel URLs (containing `/reel/`).

* **Video Preview:** Instantly plays the fetched video on the page.

* **Security:** Automatically strips potentially unsafe query parameters (like `igsh`) from the input URL before processing.

* **Stability:** Implements exponential backoff and a 10-second timeout for reliable network requests.

* **Responsiveness:** Optimized for all devices.

## Usage

1. Copy the URL of the desired Instagram Reel.

2. Paste the URL into the input field and click **Fetch Media**.

3. The video will appear for preview, along with **Download File** and **Copy Link** buttons.

## Technical Details

* **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript.

* **API Used:** `https://api.raiden.ovh/insta?url={urlencoded_reel_url}`

## AI-Generated Disclosure

This application, including all its HTML, CSS, and JavaScript logic, was generated entirely by an AI large language model (LLM) based on user specifications.
