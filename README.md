# Decode-Gaming-Behavior-Mentorness-DA-Internship-Project-1

**Project Name: Decode Gaming Behavior**

**Description:**
The "Decode Gaming Behavior" project involves analyzing and understanding gaming behavior using two main datasets: Player Details and Level Details. The Player Details table contains information such as Player ID (`P_ID`), Player Name (`PName`), Level 1 and Level 2 status, and system-generated codes for both levels. On the other hand, the Level Details table includes data like Player ID (`P_ID`), Device ID (`Dev_ID`), start time, stages crossed, game level, difficulty level, kill count, headshots count, player score, and extra lives earned.

**Tasks Performed:**
1. Extracting player and device information for players at Level 0.
2. Finding the average kill count for players with two earned lives and at least three stages crossed at Level 1.
3. Analyzing the total stages crossed at each difficulty level for Level 2 players using specific devices, sorted in descending order.
4. Identifying players who played games on multiple days and extracting their unique dates of play.
5. Calculating the sum of kill counts for players above the average kill count for Medium difficulty at each level.
6. Summing up the lives earned for each level, excluding Level 0, and arranging them in ascending order.
7. Ranking the top three scores for each device ID in increasing order, along with the corresponding difficulty.
8. Finding the first login datetime for each device ID.
9. Ranking the top five scores for each difficulty level in increasing order, including the device ID.
10. Identical to Task 9; a repetition in the project description.
11. Determining the cumulative kill counts for each player and date, using both window functions and without.
12. Calculating the cumulative sum of stages crossed over time for each player, excluding the most recent start time.
13. Extracting the top three highest total scores for each device ID along with the corresponding player ID.
14. Identifying players who scored more than 50% of the average score for their total scores.
15. Creating a stored procedure to find the top 'n' headshots count based on each device ID and ranking them.

These tasks cover a wide range of analyses, from basic data extraction to more complex statistical calculations, providing valuable insights into player behavior and game performance.
