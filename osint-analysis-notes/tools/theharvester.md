# theHarvester

## Purpose
theHarvester is used to collect publicly available information such as:
- email addresses
- subdomains
- hostnames
- employee names
- banners / open-source indexed data

## Use Cases
- External reconnaissance
- Attack surface awareness
- Initial domain profiling
- Public exposure mapping

## Example Commands

```bash
theHarvester -d example.com -b bing
theHarvester -d example.com -b duckduckgo
theHarvester -d example.com -b crtsh
```

## Notes
- Results should be validated before reporting
- Different sources may return different quality levels
- Best used as part of a broader workflow, not as a single source of truth
