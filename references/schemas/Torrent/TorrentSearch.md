# TorrentSearch

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `pageNumber` | integer (int32) | No |  |
| `pageSize` | integer (int32) | No |  |
| `lastId` | integer (int64) | No |  |
| `keyword` | string | No |  |
| `authorId` | integer (int64) | No |  |
| `categories` | integer[] | No |  |
| `imdb` | string | No |  |
| `douban` | string | No |  |
| `dmmCode` | string | No |  |
| `author` | integer (int64) | No |  |
| `sources` | integer[] | No |  |
| `mediums` | integer[] | No |  |
| `standards` | integer[] | No |  |
| `videoCodecs` | integer[] | No |  |
| `audioCodecs` | integer[] | No |  |
| `teams` | integer[] | No |  |
| `processings` | integer[] | No |  |
| `countries` | integer[] | No |  |
| `labels` | integer (int32) | No |  |
| `uploadDateStart` | string (date-time) | No |  |
| `uploadDateEnd` | string (date-time) | No |  |
| `visible` | integer (int32) | No |  |
| `onlyFav` | boolean | No |  |
| `offer` | boolean | No |  |
| `hot` | boolean | No |  |
| `mode` | enum: normal, adult, movie... | No |  |
| `dmmField` | [TorrentDmmSearchField](TorrentDmmSearchField.md) | No |  |
| `discount` | enum: NORMAL, PERCENT_70, PERCENT_50... | No |  |
| `labelsNew` | string[] | No |  |
| `sortField` | enum: CREATED_DATE, SIZE, SEEDERS... | No |  |
| `sortDirection` | enum: ASC, DESC | No |  |
| `formSystem` | boolean | No |  |
| `withCache` | boolean | No |  |

