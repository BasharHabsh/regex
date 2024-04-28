# URL Extractor

A simple JavaScript utility to extract URLs from a given text.

# Overview

URL Extractor is a lightweight JavaScript library that allows you to extract URLs from any text input. It's particularly useful for parsing text content and retrieving links for further processing or analysis.

# Features

Extract URLs from text content.
Support for both HTTP and HTTPS links.
Simple and easy-to-use API.

# Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, feel free to open an issue or submit a pull request.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

# Installation

To install the URL Extractor library, simply download the latest version from the [releases page](https://github.com/BasharHabsh/regex) and include it in your project.

# Usage

Once the library is included in your project, you can start using it to extract URLs from text. Here's an example:

```js
const URLExtractor = require("url-extractor");

const text = "This is a sample text with some URLs: https://www.example.com and http://www.example.org";
const extractor = new URLExtractor();

const urls = extractor.extract(text);
console.log(urls);
// Output: [ 'https://www.example.com', 'http://www.example.org' ]
```

# API

The URLExtractor class provides the following methods:

- `extract(text)`: Extracts URLs from the given text.
- `getUrls()`: Returns an array of extracted URLs.
- `addUrl(url)`: Adds a new URL to the list of extracted URLs.
- `removeUrl(url)`: Removes a URL from the list of extracted URLs.
- `clearUrls()`: Removes all extracted URLs.
