# Miyagi extract of 現存植生図2024: verification and profile

- polygons: 143,044 (143,044 MultiPolygon), CRS EPSG:6668, bbox lon 140.2749 to 141.6773, lat 37.7732 to 39.0028
- source files: {'veg2024bk2a.gpkg': 123328, 'veg2024bk2b.gpkg': 19716}
- cut: 137,994 polygons wholly inside Miyagi kept as they are; 5,050 polygons that cross the boundary were clipped to it (none dropped); the clipped polygons had 2772.2 km2 before the cut and keep 533.8 km2
- area: 7277.973 km2 in EPSG:6678, against 7277.973 km2 for the N03 polygon of Miyagi (99.99999%, difference -0.000 km2)
- area by 地域ブロック: 2 東北 7277.973 km2 (100.00% of N03)
- geometry validity: 0 invalid, 0 empty; fid unique: True
- overlaps: 263 pairs of polygons overlap by a sliver (largest 5.48e-09 square degrees, about 53 m2); not repaired
- NULLs: 0 in all columns

## 作成年度 (polygons)

| year | polygons |
| --- | ---: |
| 2000 | 30,665 |
| 2002 | 34,508 |
| 2013 | 21,068 |
| 2015 | 49,454 |
| 2018 | 7,326 |
| 2020 | 23 |

## Legends whose name contains ブナ, ミズナラ, ナラ or コナラ

19 of the 145 legends present in Miyagi; 23,128 polygons, 2041.1 km2 together (the legends overlap in meaning, do not read this as one class).

| code | name (original) | polygons | area km2 | ブナ | ミズナラ | ナラ | コナラ |
| --- | --- | ---: | ---: | :-: | :-: | :-: | :-: |
| 110100 | チシマザサ－ブナ群団 | 551 | 379.57 | x |  |  |  |
| 110103 | スギ－ブナ群落 | 5 | 0.65 | x |  |  |  |
| 110500 | ミズナラ群落（日本海型） | 16 | 5.39 |  | x | x |  |
| 110501 | ホツツジ－ミズナラ群集 | 5 | 0.13 |  | x | x |  |
| 130100 | スズタケ－ブナ群団 | 1 | 0.04 | x |  |  |  |
| 130105 | スズタケ－ブナ群集 | 2 | 2.24 | x |  |  |  |
| 130200 | イヌブナ群落 | 59 | 5.38 | x |  |  |  |
| 130203 | モミ－イヌブナ群集 | 195 | 6.07 | x |  |  |  |
| 130205 | アブラツツジ－イヌブナ群集 | 20 | 0.48 | x |  |  |  |
| 190100 | ウラジロヨウラク－ミヤマナラ群団 | 75 | 12.72 |  |  | x |  |
| 220100 | ブナ－ミズナラ群落 | 737 | 162.69 | x | x | x |  |
| 220102 | クリ－ミズナラ群集 | 331 | 20.45 |  | x | x |  |
| 220103 | オオバクロモジ－ミズナラ群集 | 1,223 | 152.07 |  | x | x |  |
| 220500 | コナラ群落（V） | 9,307 | 729.37 |  |  | x | x |
| 220501 | オクチョウジザクラ－コナラ群集 | 327 | 31.16 |  |  | x | x |
| 220502 | カスミザクラ－コナラ群落 | 1 | 0.00 |  |  | x | x |
| 221100 | ミズナラ群落（V） | 15 | 3.46 |  | x | x |  |
| 410100 | コナラ群落（VII） | 239 | 8.18 |  |  | x | x |
| 410101 | クリ－コナラ群集 | 10,019 | 521.06 |  |  | x | x |

The match is by substring on the original name. ナラ also matches names that are neither ミズナラ nor コナラ: ウラジロヨウラク－ミヤマナラ群団 (190100). ブナ also matches イヌブナ, another species: イヌブナ群落 (130200), モミ－イヌブナ群集 (130203), アブラツツジ－イヌブナ群集 (130205).
The full list of Miyagi legends is `legend_miyagi.tsv`.

## 作成年度 of the polygons of those legends

| year | polygons |
| --- | ---: |
| 2000 | 3,932 |
| 2002 | 4,678 |
| 2013 | 4,108 |
| 2015 | 8,755 |
| 2018 | 1,651 |
| 2020 | 4 |
