This is our read-me, it was done on google docs over the semesester as we thought that was an easier place to communicate thoughts.

| Variable      | Type                | Description                                                                                    |
| ------------- | ------------------- | ---------------------------------------------------------------------------------------------- |
|   userId      | Integer             | Unique identifier for each user. Does *not* reveal personal information; users are anonymized. |
|   movieId     | Integer             | Unique identifier for each movie. Links to the `movies.csv` table.                             |
|   rating      | Numeric (0.5–5.0)   | The rating a user assigned to the movie. Uses half‑star increments.                            |
|   timestamp   | Integer (UNIX time) | The time the rating was recorded, expressed as seconds since Jan 1, 1970.                      |
