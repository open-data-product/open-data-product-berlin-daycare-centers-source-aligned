
# Data Product Canvas - Berlin Day Care Centers (source-aligned)

## Metadata

* owner: Open Data Product
* description: Source-aligned data products providing Berlin daycare center data
* updated: 2025-10-31

## Input Ports

### Berlin Lor City

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-city
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-city.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-city/berlin-lor-city.geojson)

### Berlin Lor District Regions From 2021

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-district-regions-from-2021
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-district-regions-from-2021.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-district-regions-from-2021/berlin-lor-district-regions-from-2021.geojson)

### Berlin Lor District Regions Until 2020

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-district-regions-until-2020
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-district-regions-until-2020.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-district-regions-until-2020/berlin-lor-district-regions-until-2020.geojson)

### Berlin Lor Districts

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-districts
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-districts.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-districts/berlin-lor-districts.geojson)

### Berlin Lor Forecast Areas From 2021

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-forecast-areas-from-2021
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-forecast-areas-from-2021.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-forecast-areas-from-2021/berlin-lor-forecast-areas-from-2021.geojson)

### Berlin Lor Forecast Areas Until 2020

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-forecast-areas-until-2020
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-forecast-areas-until-2020.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-forecast-areas-until-2020/berlin-lor-forecast-areas-until-2020.geojson)

### Berlin Lor Planning Areas From 2021

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-planning-areas-from-2021
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-planning-areas-from-2021.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-planning-areas-from-2021/berlin-lor-planning-areas-from-2021.geojson)

### Berlin Lor Planning Areas Until 2020

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-lor-geodata/tree/main/data/02-silver/berlin-lor-planning-areas-until-2020
* license: CC-BY 4.0
* updated: 2025-10-28

**Files**

* [berlin-lor-planning-areas-until-2020.geojson](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/main/data/02-silver/berlin-lor-planning-areas-until-2020/berlin-lor-planning-areas-until-2020.geojson)

### Kitas in Berlin

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

### Berlin Daycare Centers 2025 10 Csv

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-10-csv
* updated: 2025-10-31

**Files**

* [berlin-daycare-centers-2025-10-city.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-city.csv)
* [berlin-daycare-centers-2025-10-details.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-details.csv)
* [berlin-daycare-centers-2025-10-district-regions.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-district-regions.csv)
* [berlin-daycare-centers-2025-10-districts.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-districts.csv)
* [berlin-daycare-centers-2025-10-forecast-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-forecast-areas.csv)
* [berlin-daycare-centers-2025-10-planning-areas.csv](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-csv/berlin-daycare-centers-2025-10-planning-areas.csv)

### Berlin Daycare Centers 2025 10 Parquet

* owner: Open Data Product
* url: https://github.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/tree/main/data/03-gold/berlin-daycare-centers-2025-10-parquet
* updated: 2025-10-31

**Files**

* [berlin-daycare-centers-2025-10-city.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-city.parquet)
* [berlin-daycare-centers-2025-10-details.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-details.parquet)
* [berlin-daycare-centers-2025-10-district-regions.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-district-regions.parquet)
* [berlin-daycare-centers-2025-10-districts.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-districts.parquet)
* [berlin-daycare-centers-2025-10-forecast-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-forecast-areas.parquet)
* [berlin-daycare-centers-2025-10-planning-areas.parquet](https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/main/data/03-gold/berlin-daycare-centers-2025-10-parquet/berlin-daycare-centers-2025-10-planning-areas.parquet)

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

source-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).