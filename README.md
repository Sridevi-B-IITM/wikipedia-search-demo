# Wikipedia Summary Search

## Overview
A minimal single-page web app to fetch and display a topic’s title, summary, and thumbnail image from the Wikipedia REST API.

## Setup
- Option 1: Open index.html directly in your browser.
- Option 2 (recommended for best compatibility): Serve locally
  - Python 3: python -m http.server 8000
  - Then open http://localhost:8000

No build step or dependencies required.

## Usage
- Enter a topic (e.g., “Ada Lovelace”) and click Search or press Enter.
- The page shows the Wikipedia title, a short summary (extract), and a thumbnail image if available.
- If the topic is not found or an error occurs, a helpful message is displayed.

## License
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.