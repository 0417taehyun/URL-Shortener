# URL Shortener

> A server application similar to [Bitly](https://bitly.com/) that shorten URLs.

## Table of Contents

- [TL;DR](#tldr)
- [Background](#background)
    - [How many URLs are shortend per a day?](#how-many-urls-are-shortend-per-a-day)
    - [How many URLs are clicked per a day?](#how-many-urls-are-clicked-per-a-day)
- [Requirements](#requirements)
    1. [Shorten URL](#1-shorten-url)
    2. [Get shortened URL](#2-get-shortened-url)
    3. [Delete URL](#3-delete-url)
    4. [Analyze Statistics](#4-analyze-statistics)
- [LICENSE](#license)

## TL;DR

- The aim is to create a URL shortener like [Bitly](https://bitly.com/), assuming a large-scale service.
- The key is not just the operation of a simple server application, but also considering the business aspects.

## Background

> The following information is based on [Bitly's Daily Usage](https://bitly.com/pages/resources/infographics/a-day-with-bitly).

### How many URLs are shortend per a day?

- Over 31 million URLs are generated per day.

### How many URLs are clicked per a day?

- Over 286 million URLs are accessed per day.

## Requirements

> The following requirements are abstract; feel free to set your own.

### 1. Shorten URL

- The shortened URL should be a unique 7-character ID composed of upper and lower case letters and numbers.

### 2. Get shortened URL

- When accessing the shortened URL, you should be able to retrieve the original URL that was shortened.

### 3. Delete URL

- URLs that are not frequently used should be deleted.

### 4. Analyze Statistics

- You should be able to generate meaningful business-oriented statistics, just like Bitly was able to produce.
