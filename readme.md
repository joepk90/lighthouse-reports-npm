# Lighthouse Reports
### An npm project for Lighthouse Reports
Run the following command to generate a report
```sh
npm run lighthouse --url="https://youtube.com"
```

## Generating reports use using the terminal:
```sh
npm run env -- 
```

### Examples:

Generate an html report:
```sh
npm run env -- lighthouse https://youtube.com --budget-path=./budget.json --output-path=./reports/report.html --chrome-flags=\"--headless\" --view=true
```

Generate a json report:
```sh
npm run env -- lighthouse https://youtube.com --budget-path=./budget.json --output=json --output-path=./reports/report.json --chrome-flags=\"--headless\" --view=true
```


### Lighthouse Documentation
| Lighthouse NPM | [https://www.npmjs.com/package/lighthouse][PlGh] |
| Budgets | [https://github.com/GoogleChrome/lighthouse/blob/HEAD/docs/performance-budgets.md][PlDb] |
