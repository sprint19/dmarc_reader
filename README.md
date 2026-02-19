## DMARC XML Reader

A lightweight, browser-based DMARC aggregate report parser that converts raw XML files into a clean, human-readable summary.

The tool runs entirely on GitHub Pages using static HTML and JavaScript. Users upload a DMARC XML file, and the report is parsed locally in their browser. No data is stored. No files are uploaded to any server. No backend or infrastructure is required.

The output presents:

* Report metadata
* Domain policy details
* Total message count
* SPF and DKIM pass rates
* Clear risk indicator
* Simple source IP breakdown

The purpose is to reduce unnecessary technical escalations by giving stakeholders a clear, calm interpretation of DMARC reports without involving the engineering team.

Scope is intentionally minimal: upload, parse, render, done.