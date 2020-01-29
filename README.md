# NewspaperMetadata

Metadata, automatically and manually generated, about historical newspapers.

Currently, the JSON and CSV files contain the following fields:

Field | Description
---- | -----
`series` | unique identifier for a newspaper series, usually derived from existing identifiers such as LCCN numbers
`title` | title of series
`lang` | common languages in the series, according to catalogue data; in JSON, an array; in CSV, a semicolon-delimited list
`publisher` | series publisher
`placeOfPublication` | listed place of publication
`coverage` | link to a https://dbpedia.org/ entry for the place of publication
`lon` | DBpedia decimal longitude
`lat` | DBpedia decimal latitude
`subcollection` | series type

