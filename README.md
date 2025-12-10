In this project we aim to analyze users movie ratings based off the MovieLense dataset in order to determine whether users who make reviews tend to rate films at extremes. Our scale went from 0.5-5 and we categorized ratings into categories: low (≤1), middle (1-4.5), and high (≥4.5) and examined the distribution of scores to conduct hypothesis tests in order to compare observed extreme ratings to the expected values. In the end, our findings show that even though extreme ratings occurred more often than a neutral systems predict, the extremity is mainly shown on the high ratings side (≥4.5) which tells us there is more biases than true polarization.

| Variable      | Type                | Description                                                                                    |
| ------------- | ------------------- | ---------------------------------------------------------------------------------------------- |
|   userId      | Integer             | Unique identifier for each user. Does *not* reveal personal information; users are anonymized. |
|   movieId     | Integer             | Unique identifier for each movie. Links to the `movies.csv` table.                             |
|   rating      | Numeric (0.5–5.0)   | The rating a user assigned to the movie. Uses half‑star increments.                            |
|   timestamp   | Integer (UNIX time) | The time the rating was recorded, expressed as seconds since Jan 1, 1970.                      |

in terms of /gitignore, we didny have any files that are in the local RStudio project but not the GitHub repo therefore we did not think it was viable to create a /gitignore file.
