
# Data Product Canvas - Berlin Day Care Centers (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data products providing Berlin daycare center data
* updated: 2026-02-01

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-daycare-centers-{{ current_year }}-{{ current_month }}
name: Kitas in Berlin
* owner: Senatsverwaltung für Bildung, Jugend und Familie
* url: https://www.berlin.de/sen/bildung/service/daten/
* license: CC-BY-3.0-Namensnennung
* updated: 2022-08-31

**Files**

* [kitaliste_aktuell.xlsx](https://www.berlin.de/sen/jugend/traegerservice/kitaliste_aktuell.xlsx)


## Transformation Steps

* [Data extractor](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/extract/data_extractor.py) extracts data from inout ports
* [Data copier](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_copier.py) copies and renames extracted data
* [Data CSV converter](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_csv_converter.py) converts Excel files to CSV format
* [Data aggregator](https://github.com/open-data-product/open-data-product-python-lib/blob/main/opendataproduct/transform/data_aggregator.py) aggregates data to be used as output ports

## Output Ports

### berlin-daycare-centers-2025-10-csv
name: Berlin Daycare Centers 2025 10 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-10-csv
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2025-10-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-city.csv)
* [berlin-daycare-centers-2025-10-details.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-details.csv)
* [berlin-daycare-centers-2025-10-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-district-regions.csv)
* [berlin-daycare-centers-2025-10-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-districts.csv)
* [berlin-daycare-centers-2025-10-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-forecast-areas.csv)
* [berlin-daycare-centers-2025-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-planning-areas.csv)


### berlin-daycare-centers-2025-10-parquet
name: Berlin Daycare Centers 2025 10 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-10-parquet
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2025-10-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-city.parquet)
* [berlin-daycare-centers-2025-10-details.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-details.parquet)
* [berlin-daycare-centers-2025-10-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-district-regions.parquet)
* [berlin-daycare-centers-2025-10-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-districts.parquet)
* [berlin-daycare-centers-2025-10-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-forecast-areas.parquet)
* [berlin-daycare-centers-2025-10-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-planning-areas.parquet)


### berlin-daycare-centers-2025-11-csv
name: Berlin Daycare Centers 2025 11 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-11-csv
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2025-11-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-csv/berlin-daycare-centers-2025-11-city.csv)
* [berlin-daycare-centers-2025-11-details.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-csv/berlin-daycare-centers-2025-11-details.csv)
* [berlin-daycare-centers-2025-11-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-csv/berlin-daycare-centers-2025-11-district-regions.csv)
* [berlin-daycare-centers-2025-11-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-csv/berlin-daycare-centers-2025-11-districts.csv)
* [berlin-daycare-centers-2025-11-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-csv/berlin-daycare-centers-2025-11-forecast-areas.csv)
* [berlin-daycare-centers-2025-11-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-csv/berlin-daycare-centers-2025-11-planning-areas.csv)


### berlin-daycare-centers-2025-11-parquet
name: Berlin Daycare Centers 2025 11 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-11-parquet
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2025-11-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-parquet/berlin-daycare-centers-2025-11-city.parquet)
* [berlin-daycare-centers-2025-11-details.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-parquet/berlin-daycare-centers-2025-11-details.parquet)
* [berlin-daycare-centers-2025-11-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-parquet/berlin-daycare-centers-2025-11-district-regions.parquet)
* [berlin-daycare-centers-2025-11-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-parquet/berlin-daycare-centers-2025-11-districts.parquet)
* [berlin-daycare-centers-2025-11-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-parquet/berlin-daycare-centers-2025-11-forecast-areas.parquet)
* [berlin-daycare-centers-2025-11-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-11-parquet/berlin-daycare-centers-2025-11-planning-areas.parquet)


### berlin-daycare-centers-2025-12-csv
name: Berlin Daycare Centers 2025 12 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-12-csv
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2025-12-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-csv/berlin-daycare-centers-2025-12-city.csv)
* [berlin-daycare-centers-2025-12-details.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-csv/berlin-daycare-centers-2025-12-details.csv)
* [berlin-daycare-centers-2025-12-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-csv/berlin-daycare-centers-2025-12-district-regions.csv)
* [berlin-daycare-centers-2025-12-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-csv/berlin-daycare-centers-2025-12-districts.csv)
* [berlin-daycare-centers-2025-12-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-csv/berlin-daycare-centers-2025-12-forecast-areas.csv)
* [berlin-daycare-centers-2025-12-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-csv/berlin-daycare-centers-2025-12-planning-areas.csv)


### berlin-daycare-centers-2025-12-parquet
name: Berlin Daycare Centers 2025 12 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-12-parquet
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2025-12-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-parquet/berlin-daycare-centers-2025-12-city.parquet)
* [berlin-daycare-centers-2025-12-details.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-parquet/berlin-daycare-centers-2025-12-details.parquet)
* [berlin-daycare-centers-2025-12-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-parquet/berlin-daycare-centers-2025-12-district-regions.parquet)
* [berlin-daycare-centers-2025-12-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-parquet/berlin-daycare-centers-2025-12-districts.parquet)
* [berlin-daycare-centers-2025-12-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-parquet/berlin-daycare-centers-2025-12-forecast-areas.parquet)
* [berlin-daycare-centers-2025-12-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-12-parquet/berlin-daycare-centers-2025-12-planning-areas.parquet)


### berlin-daycare-centers-2026-01-csv
name: Berlin Daycare Centers 2026 01 Csv
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2026-01-csv
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2026-01-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-csv/berlin-daycare-centers-2026-01-city.csv)
* [berlin-daycare-centers-2026-01-details.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-csv/berlin-daycare-centers-2026-01-details.csv)
* [berlin-daycare-centers-2026-01-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-csv/berlin-daycare-centers-2026-01-district-regions.csv)
* [berlin-daycare-centers-2026-01-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-csv/berlin-daycare-centers-2026-01-districts.csv)
* [berlin-daycare-centers-2026-01-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-csv/berlin-daycare-centers-2026-01-forecast-areas.csv)
* [berlin-daycare-centers-2026-01-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-csv/berlin-daycare-centers-2026-01-planning-areas.csv)


### berlin-daycare-centers-2026-01-parquet
name: Berlin Daycare Centers 2026 01 Parquet
* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2026-01-parquet
* updated: 2026-02-01

**Files**

* [berlin-daycare-centers-2026-01-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-parquet/berlin-daycare-centers-2026-01-city.parquet)
* [berlin-daycare-centers-2026-01-details.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-parquet/berlin-daycare-centers-2026-01-details.parquet)
* [berlin-daycare-centers-2026-01-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-parquet/berlin-daycare-centers-2026-01-district-regions.parquet)
* [berlin-daycare-centers-2026-01-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-parquet/berlin-daycare-centers-2026-01-districts.parquet)
* [berlin-daycare-centers-2026-01-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-parquet/berlin-daycare-centers-2026-01-forecast-areas.parquet)
* [berlin-daycare-centers-2026-01-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2026-01-parquet/berlin-daycare-centers-2026-01-planning-areas.parquet)


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).