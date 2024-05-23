# nba_stat

## Data cleaning & transformation

#### Data Cleaning

1. **Missing Values**

   - Are there missing values in the points, assists, or rebounds columns?
      - there are missing values in player dataset. wrote a function to remove all rows with empty player id.

2. **Data Types**

   - Are the date columns in datetime format?
      - Not really
   - Are numerical columns like points and rebounds stored as integers or floats?

3. **Outliers and Anomalies**

   - Are there any players with unusually high or low statistics?
   - How will you handle a player with 0 minutes played but non-zero statistics?

4. **Duplicates**

   - Are there duplicate entries for players in the same game?

5. **Consistency**

   - Are team names and player names consistently formatted?

6. **Accuracy**

   - Are there any players with impossible statistics (e.g., negative points)?

7. **Range and Limits**
   - Are points, assists, and rebounds within reasonable ranges?

#### Data Transformation

1. **Feature Engineering**

   - Can you create a “Points Per Game” (PPG) feature?
   - Can you calculate the player efficiency rating (PER)?

2. **Normalization and Scaling**

   - Should player statistics be normalized to account for different game lengths?

3. **Encoding Categorical Variables**

   - How will you encode player positions (e.g., PG, SG, SF, PF, C)?

4. **Aggregating Data**

   - Should you aggregate player statistics by team or by season?

5. **Date and Time Transformations**

   - Can you extract the season from the game date?

6. **Filtering Data**

   - Will you exclude data from exhibition games?

7. **Merging and Joining**
   - Do you need to join player statistics with salary data?

By systematically addressing these guiding questions, you can ensure that your data is clean, well-structured, and ready for analysis, leading to more accurate and meaningful insights.
