# etl.sh
A catalog of command line ETL tools

**Note:** this repository is a stub, a proposal, an idea. Perhaps someday the idea will be implemented.

I've been fed with various ETL stuff up my nose. There is a lot of ETL to do in any automation system; and ETL is tedious, boring, stupid stuff.

One of the solutions I can see is to use an ensemble of command line tools to clean up the raw data for loading to database or analysis.

[etl.sh](https://etl.sh) should be a catalog of such tools.

## Features

This is going to be a static **but interactive** website (a SPA).

- Choose input format, destination format, and find which tools can convert from one to the other, what language they're written in, what licenses they have and see snippets of how to do the conversion.
- Choose input format and operation to do (sort, filter, validate, group, ...) — to see the tools which can do such an operation.

## Sources

- [structured-text-tools](https://github.com/dbohdan/structured-text-tools)
- [eBay tsv utilities / Other open-source tools](http://ebay.github.io/tsv-utils/docs/OtherToolkits.html)
- [Data Science in the Command Line](https://www.datascienceatthecommandline.com/)
- My own [ysv](https://github.com/ysv-rs/)


## Competitors in the visual data preparation world

- Talend Data Studio
- AWS Glue DataBrew
- Google Cloud DataPrep

