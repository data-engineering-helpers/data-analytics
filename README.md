Data-lakes, data warehouses and data lake-houses
================================================

# Table of Content (ToC)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

# Overview
[This project](https://github.com/data-engineering-helpers/data-analytics)
intends to collect, analyze and synthetize referential material
about data analytics/analysis.

Even though the members of the GitHub organization may be employed by
some companies, they speak on their personal behalf and do not represent
these companies.

## Other repositories of Data Engineering helpers
* [Data Engineering Helpers - Knowledge Sharing - Cheat sheets](https://github.com/data-engineering-helpers/ks-cheat-sheets)
* [Data Engineering Helpers - Knowledge Sharing - Data products](https://github.com/data-engineering-helpers/data-products)
* [Data Engineering Helpers - Knowledge Sharing - Data contracts](https://github.com/data-engineering-helpers/data-contracts)
* [Data Engineering Helpers - Knowledge Sharing - Data quality](https://github.com/data-engineering-helpers/data-quality)
* [Data Engineering Helpers - Knowledge Sharing - Architecture principles](https://github.com/data-engineering-helpers/architecture-principles)
* [Data Engineering Helpers - Knowledge Sharing - Data life cycle](https://github.com/data-engineering-helpers/data-life-cycle)
* [Data Engineering Helpers - Knowledge Sharing - Data management](https://github.com/data-engineering-helpers/data-management)
* [Data Engineering Helpers - Knowledge Sharing - Metadata](https://github.com/data-engineering-helpers/metadata)
* [Data Engineering Helpers - Knowledge Sharing - Data pipeline deployment](https://github.com/data-engineering-helpers/data-pipeline-deployment)
* [Data Engineering Helpers - Knowledge Sharing - Semantic layer](https://github.com/data-engineering-helpers/semantic-layer)

# References

# Articles

## DuckDB in browser - SQLRooms examples - deck.gl Mosaic
* Author: Ilya Boyandin
  ([Ilya Boyandin on LinkedIn](https://www.linkedin.com/in/ilyabo/))
* Date: Dec. 2025
* LinkedIn post: https://www.linkedin.com/posts/ilyabo_new-sqlroomsorg-example-big-thanks-to-gjore-ugcPost-7410991784463552512-3ZvD/
> New [sqlrooms.org](http://sqlrooms.org/) example, big thanks to
> [Gjore Milevski](https://www.linkedin.com/in/gjore-milevski/), showcasing the integration with
> [deck.gl](http://deck.gl/), [Kyle Barron](https://www.linkedin.com/in/kylebarrongeo/)'s
> geoarrow layers, and UWData Mosaic [idl.uw.edu/mosaic/](http://idl.uw.edu/mosaic/)
> for efficient cross-filtering.


# Frameworks

## Analytics with DuckDB in the browser
* See also
  [Data Engineering Helpers - Knowledge Sharing - DuckDB Cheat sheet](https://github.com/data-engineering-helpers/ks-cheat-sheets/edit/main/db/duckdb/README.md)

### Mosaic
* [Mosaic on UW IDL web site](https://idl.uw.edu/mosaic/)
* Overview:
  * Mosaic is a collaboration of the [UW Interactive Data Lab (IDL)]((https://idl.uw.edu/)
  and the [CMU Data Interaction Group (DIG)](https://dig.cmu.edu/)
> Mosaic is an extensible framework for linking databases and interactive views
  * **Explore massive datasets** - Visualize, select, and filter datasets with millions or billions of records
  * **Flexible deployment** - Build data-driven web apps, or interact with data directly in Jupyter notebooks
  * **Interoperable & extensible** - Create new components that seamlessly integrate across selections and datasets
  * **Powered by DuckDB** - Mosaic pushes computation to DuckDB, both server-side and in your browser via WebAssembly

### SQLRooms
* [SQLRooms](https://sqlrooms.org)
* [SQLRooms - Examples](https://sqlrooms.org/examples.html)
* [GitHub - SQLRooms examples]((https://github.com/sqlrooms/examples)
* Overview:
> An open source React toolkit for human and agent collaborative analytics apps
  * **Local Analytics, No Backend Required** - Leverage DuckDB's powerful SQL capabilities, enabling fast in browser data processing without a backend
  * **Own Your Data** - Data remains on your local device for maximum privacy, sub-second analytics on large datasets, and offline functionality
  * **Privacy-Preserving AI Integration** - Use agents that can write and execute SQL queries, and generate insights without sharing your data with model providers
  * **Modular Architecture** - Pick and choose the functionality you need for composable, extensible applications, with integrations for popular data visualization libraries
  * **Modern UI Components** - Comprehensive set of React components including data tables, layouts, and visualization tools for building beautiful analytics interfaces
  * **Offline Use** - Work with your data, run queries, and analyze results even without an internet connection. SQLRooms supports offline workflows using persistent storage via OPFS

## PostgreSQL extensions

### `pg_lake`

### `pg_incremental`
* Post on LinkedIn: https://www.linkedin.com/posts/marcoslot_why-we-developed-pgincremental-one-of-activity-7392183986577440770-HCZU/
* Date: Nov. 2025
* Author: [Marco Slot](https://www.linkedin.com/in/marcoslot/)

