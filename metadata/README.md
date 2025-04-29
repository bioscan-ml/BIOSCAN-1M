# BIOSCAN-1M

BIOSCAN-1M metadata file.

###### <h3> Metadata file
The metadata files of the BIOSCAN-1M dataset are available in the [GoogleDrive](https://drive.google.com/drive/u/1/folders/1kD9cXuQ1FdL30etp7sjy_Gs_NAAJ3EXI),
within [BIOSCAN_1M_metadata](https://drive.google.com/drive/u/1/folders/14-j4B2eeWNokjdHiVT2sEMwLWojzcvXf) folder.
There are two metadata file format `TSV` and  `JSON-LD`.

```plaintext
BIOSCAN_1M_Insect_Dataset_metadata.[type_extension]
```

- `[type_extension]`:
  - `tsv`
  - `jsonld`

###### <h3> Metadata fields
The table below lists the metadata fields of the BIOSCAN-1M dataset. To facilitate the use of BIOSCAN datasets, corresponding fields from the BIOSCAN-5M metadata are also included for reference.

> **Note**: All specimens of the BIOSCAN-1M dataset are available in the BIOSCAN-5M dataset.  
> `NA` denotes Not Applicable, which shows that the field is not available in the corresponding metadata file.

|    | **BIOSCAN-1M Field**    | **BIOSCAN-5M Field**      | **Description**                                                              | **Type** |
|----|-------------------------|---------------------------|------------------------------------------------------------------------------|----------|
| 1  | `processid`             | `processid`               | A unique number assigned by BOLD (International Barcode of Life Consortium). | String   |
| 2  | `sampleid`              | `sampleid`                | A unique identifier given by the collector.                                  | String   |
| 3  | `name`                  | `taxon`                   | Bio.info: Most specific taxonomy rank.                                       | String   |
| 4  | `phylum`                | `phylum`                  | Bio.info: Taxonomic classification label at phylum rank.                     | String   |
| 5  | `class`                 | `class`                   | Bio.info: Taxonomic classification label at class rank.                      | String   |
| 6  | `order`                 | `order`                   | Bio.info: Taxonomic classification label at order rank.                      | String   |
| 7  | `family`                | `family`                  | Bio.info: Taxonomic classification label at family rank.                     | String   |
| 8  | `subfamily`             | `subfamily`               | Bio.info: Taxonomic classification label at subfamily rank.                  | String   |
| 9  | `tribe`                 | `NA`                      | Bio.info: Taxonomic classification label at genus rank.                      | String   |
| 10 | `genus`                 | `genus`                   | Bio.info: Taxonomic classification label at genus rank.                      | String   |
| 11 | `species`               | `species`                 | Bio.info: Taxonomic classification label at species rank.                    | String   |
| 12 | `subspecies`            | `NA`                      | Bio.info: Taxonomic classification label at species rank.                    | String   |
| 13 | `uri`                   | `dna_bin`                 | Bio.info: Barcode Index Number (BIN).                                        | String   |
| 14 | `nucraw`                | `dna_barcode`             | Bio.info: Nucleotide barcode sequence.                                       | String   |
| 15 | `NA`                    | `country`                 | Geo.info: Country associated with the site of collection.                    | String   |
| 16 | `NA`                    | `province_state`          | Geo.info: Province/state associated with the site of collection.             | String   |
| 17 | `NA`                    | `coord-lat`               | Geo.info: Latitude (WGS 84; decimal degrees) of the collection site.         | Float    |
| 18 | `NA`                    | `coord-lon`               | Geo.info: Longitude (WGS 84; decimal degrees) of the collection site.        | Float    |
| 19 | `NA`                    | `image_measurement_value` | Size.info: Number of pixels occupied by the organism.                        | Integer  |
| 20 | `NA`                    | `area_fraction`           | Size.info: Fraction of the original image the cropped image comprises.       | Float    |
| 21 | `NA`                    | `scale_factor`            | Size.info: Ratio of the cropped image to the cropped_256 image.              | Float    |
| 22 | `NA`                    | `inferred_ranks`          | Integer indicating inferred taxonomic ranks.                                 | Integer  |
| 23 | `NA`                    | `split`                   | Split set (partition) the sample belongs to.                                 | String   |
| 24 | `NA`                    | `chunk`                   | Subdirectory name (or empty string) for this image.                          | String   |
| 25 | `chunk_number`          | `NA`                      | Subdirectory number for this image.                                          | Integer  |
| 26 | `large_diptera_family`  | `NA`                      | Split set for experiments with Large Diptera Family dataset.                 | String   |
| 27 | `medium_diptera_family` | `NA`                      | Split set for experiments with Medium Diptera Family dataset.                | String   |
| 28 | `small_diptera_family`  | `NA`                      | Split set for experiments with Small Diptera Family dataset.                 | String   |
| 29 | `large_insect_order`    | `NA`                      | Split set for experiments with Large Insect Order dataset.                   | String   |
| 30 | `medium_insect_order`   | `NA`                      | Split set for experiments with Medium Insect Order dataset.                  | String   |
| 31 | `small_insect_order`    | `NA`                      | Split set for experiments with Small Insect Order dataset.                   | String   |

