# Log Aggregator

This is a non-production ready script that helps aggregate multiple sources of structured/non-structured logs, and lets you dump it all into one place and filter/transform it much easier.

My use case was JSON logs from apps A and B, and plaintext logging from apps C. By merging it all into one JSON feed, it can be split up in different ways and views.

Example:

- show server messages in log region A
- show server requests in log region B
- show background messages in log region C

You can use a tool like `jq` to stream/query/transform the final result.
