# Latest releases #
  * 0.24Beta: [Windows](http://bit.ly/StockPortfolio_24Beta_windows) or [OSX-Linux](http://bit.ly/StockPortfolio_024Beta_osx-linux)


---

## Release note ##

0.24:
  * [Issue 69](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=69): Add Transaction window would sometime fail to open (with a runtime exception): fixed.
  * [Issue 67](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=67): Symbol list now refreshed every time (no need to restart the application).
  * [Issue 65](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=65): Total cost now includes the commission.
  * [Issue 64](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=64): The filter panel would lose its list of symbols if a symbol was updated/created when filtering on: fixed.
  * Wrapped all UI actions in try-catches for logging.
  * Fixed currency combobox size for OS X.
  * Behind the scene: changed build from ant to maven.
  * Behind the scene: Added unit test for Analysis calculation.
  * new feature to create backup zip archive (with logs for investigation)
  * Bug fix: new database are now created in the installation directory (not "current directory", which could be different depending on how the program was launched);
  * Error opening database exception handling (global handling)
  * Centralized SWING exception handling (with log statements)
  * Title bar displays path to the database location
  * New menu to "delete current portfolio"
  * Bug fix: display logo on "add symbol" and "add transaction" popup
  * Database version in line with Software version (instead of incrementing different numbers...)
  * Fixed bug when renaming a symbol associated to a transaction (was failing with exception)
  * Unit test database upgrade with all previous versions
  * Support multiple databases (selection at launch), scan installation folder AND current folder (may be different for some users)
  * Add Edit Symbol menu
  * Change log folder (forced to installation folder)
  * Change properties folder (forced to installation folder)
  * Fix refresh issues when deleting a label used as a filter
  * Fix broken shortcuts menu
  * [Issue 27](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=27): Remove JFree Year references
  * Prevent toString from being used for business logic
  * Handle date better with Calendar

0.23:
  * Fixed an error when importing transactions from Google. The error was caused by unexpected locale/date format.

0.22:
  * [Issue 10](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=10): Added several graphs: sector and currency pie charts + label and Yearly return Bar charts.
  * Symbols are now also filtered by criteria.
  * Note: This is the First release to trigger the "new version available" notification (added on 0.21).

0.21:
  * Behind the scene: Major code refactoring. No added features with the refactoring, only increased maintainability.
  * [Issue 8](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=8): Company sector added to the symbol properties + filter by sector.
  * [Issue 47](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=47): Update database creation to support future changes more easily.
  * [Issue 44](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=44): Separate build artifact for MAC/Linux users with a tar.gz file (and executable rights: thanks to Olivier).
  * [Issue 33](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=33): Improve Import/Export CSV.
  * Added a notification when a new Version is released. Reads the latest version from https://code.google.com/p/stock-portfolio-manager/source/browse/latestversion.

0.20
  * Included Launch.bat (to be used only when double clicking StockPortfolioLauncher.jar does not launch the application).
  * Fine tuned logging at launch time to make sure in case of error it is caught and logged.
  * Fixed a bug on the total auto-calculation when adding a transaction (emptying the Commission field did not trigger a recalculation).

0.19 (Quick release, few minutes after 0.18):
  * Fix the "Filtering" view layout problem, it was taking too much space.

0.18:
  * Added a nice graphical date picker for the transaction date.
  * [Issue 48](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=48): Allow reinvesting dividend: when creating a "Dividend" transaction, a "Buy" transaction can now be created simultaneously.
  * [Issue 46](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=46): There was a weird behavior when values caused the calculation to return an incalculable value. It this case, the word "Infinite" is displayed in the grids.
  * [Issue 45](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=45): Code update on the Import issue (without more details for the bug). More header support was added (other header names) + logging to traces.log in case of failure.
  * [Issue 32](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=32): Added filtering by transaction type.
  * Behind the scene: Started creating automated tests for the UI (using Sikuli).
  * Added automatic calculation for the fields Quantity/Price/Total when adding a transaction (ex: Type price and total, the quantity is resolved automatically).

0.17
  * Bug Fixed: Decimal numbers for in the Performance view were rounded (and filled with zeros!)

0.16:
  * Add "Edit symbol" icon under the Symbol tab

0.15:
  * Add "Setting" icon in the main toolbar
  * Fix Label/Tags popup display issue in Transaction Panel

0.14:
  * Move the toolbar over the "Tabs" (so that the icons remain displayed regardless of which tab is selected)

0.13:
  * Add a toolbar with icons to Add/Remove transaction and Symbol + update prices
  * For now, only single select is supported, upcoming version will allow multiple row selection (mainly for delete purpose)

0.12:
  * Import supports Google CSV format (ignores the Cash flow field when present)

0.11:
  * [Issue 33](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=33): importing transactions is more safe proof.
  * [Issue 40](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=40): reset focus to the first field after adding a transaction (without closing).
  * [Issue 41](https://code.google.com/p/stock-portfolio-manager/issues/detail?id=41): populate symbol dropdown when opening "add transaction" popup.

0.10
  * Change database location from user home directory to current directory.
  * Logs errors and calculations in "logs" directory.
  * Allows exporting transactions to CSV format.
  * Allows importing transactions from a CSV file (not bullet proof in this version).

> 
---

## Old releases ([view](https://drive.google.com/folderview?id=0B5XbviLoYz2FZktST2hsd3RQaEk#list)) ##
  * 0.23Beta: [Windows](http://bit.ly/StockPortfolio_023Beta_windows) or [OSX-Linux](http://bit.ly/StockPortfolio_023Beta_osx-linux)
  * 0.22Beta: [Windows](https://docs.google.com/uc?export=download&id=0B5XbviLoYz2Fd1RUUVA2Z29nT3M) or [OSX-Linux](https://docs.google.com/uc?export=download&id=0B5XbviLoYz2FbVlmQ1c1VmZFN3c)
  * 0.21Beta: [Windows](https://docs.google.com/uc?export=download&id=0B5XbviLoYz2FVFhKZnRvNXJ0a1E)

## Deprecated (do not go there) releases ##
https://drive.google.com/folderview?id=0B5XbviLoYz2FeWp2NVlITDhrdVU#list