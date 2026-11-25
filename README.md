# Public Renewable Energy Finance and Electricity Access: A Global Comparison by Income Group

[Download the replication package](Reviewer_Replication_Public_Finance.zip?raw=true)

The country-level analysis compares public renewable energy commitments with population and electricity exclusion during 2000–2024. The World Bank approval analysis covers 2014–2024. The solar and wind transaction analysis covers 2000–2024.

## Reproducing the results

Extract the archive and run the following commands from its root with Python 3.10 or later:

```sh
python verify.py
python -m pip install -r requirements.txt
python analyse.py
python figures.py
```

The archive includes public inputs, analysis code, aggregate results, and a table-by-table guide in `README.txt`. The supplied market aggregates support figure reproduction. Rebuilding those aggregates from individual transactions requires licensed LSEG data. Instructions for that step are in the archive.

Archive SHA-256: `fb26043e6964fb12317295f3a429fa57247f8f5b9e8f242e111de18a8ae58fd5`
