# SCOTUS Nominations
This webpage is an attempt to visualize the time needed to confirm/deny a US Supreme Court nomination based on the majority party in the US Senate at the time.
The data was collected and cleaned from [this table on Wikipedia](https://en.wikipedia.org/wiki/List_of_nominations_to_the_Supreme_Court_of_the_United_States#Nominations) then stored as `nominations.csv`.
The radius of each circle is proportional to the number of days between the date the nomination was submitted and the date of the outcome.
The only exception to this is when the nomination lapses, in this case the circle defaults to the size of the largest.
Since some judges were nominated multiple times, due to their previous nomination lapsing or for a promotion, their nominations are uniquely identified by both their name and the number of days to determine an outcome.
The color of the circle determines the outcome:
- Confirmed - green
- Declined - gray
- Withdrawn - orange
- Rejected - red
- Postponed - yellow
- Lapsed - black
- Other - blue