# Sample Common Crawl documents

100 unique-URL documents from Common Crawl's July 2025 crawl (`CC-MAIN-2025-30`), crawled July 20, 2025.

- `documents/document-01.txt` through `documents/document-100.txt`: extracted plain text from WET records.
- `documents/metadata.json`: original URLs, crawl timestamps, text sizes, and archive paths.
- `documents/documents.jsonl`: one document per line, with metadata and full text.

## Sampling

One WET archive was chosen randomly from the crawl's WET path list. Its first 2 MiB of compressed data were fetched, and complete records were parsed. Documents were randomly selected without content filtering, excluding duplicate URLs. The collection includes the earlier samples gathered during the same session.

This is a convenience sample from one archive portion, not a uniform or representative sample of Common Crawl. It includes navigation, placeholders, spam, and multilingual text. The original HTML and HTTP responses are not included. No random seed was recorded.

## Source

[Common Crawl WET archive](https://data.commoncrawl.org/crawl-data/CC-MAIN-2025-30/segments/1751906235433.80/wet/CC-MAIN-20250720021502-20250720051502-00495.warc.wet.gz)

Archived content originated on third-party websites; inclusion does not grant rights to that content.
