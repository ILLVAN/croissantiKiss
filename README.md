# croissantiKiss

**Experimental Python DAX indicator and strategy research using the Interactive
Brokers Trader Workstation API.**

Created by **ILLVAN / Silvan Weber** in 2021. The project combines market-data
handling, weighted indicator logic, and Plotly-based visualisation. It is
preserved as a personal research prototype with limited ongoing maintenance.

## Implementation

The main entry point is [TWS_CROISSANTI_KISS_SCALE.py](TWS_CROISSANTI_KISS_SCALE.py).
It connects to a locally running TWS or IB Gateway instance and requests market
data for the configured contract. The script uses `ibapi`, NumPy, pandas, and
Plotly alongside the Python standard library.

## Local evaluation

Review the script's settings, API port, contract, and weights before running it.
A configured TWS/IB Gateway session and the appropriate market-data access are
required. Broker login credentials belong in the broker software, not in this
repository.

The original source records unfinished configuration/weight-management work and
known connection/disconnection issues. This README update does not validate the
strategy, market-data compatibility, or suitability for live trading.

## License and reuse

The project code is available under the [BSD 3-Clause license](LICENCE),
including commercial use, subject to its conditions. Preserve the applicable
copyright, license, and disclaimer notices when redistributing it.

If you build something with this project, a short note via a GitHub issue and
credit linking to https://github.com/ILLVAN/croissantiKiss would be appreciated.
This is a voluntary request, not an additional license condition. Third-party
components retain their own licenses and notices.
