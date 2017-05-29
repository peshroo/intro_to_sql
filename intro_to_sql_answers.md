ANSWERS

1. SELECT * FROM robots WHERE source = 'The Hitchhiker"s Guide to the Galaxy';

2. SELECT * FROM robots WHERE personality = 'anxious';

3. SELECT * FROM recipes WHERE nut_free=TRUE;

4. SELECT COUNT(name) FROM recipes WHERE gluten_free=TRUE AND vegetarian=FALSE;

5. SELECT name FROM animals WHERE number_of_legs in(SELECT MAX(number_of_legs) from animals);

6. SELECT name FROM board_games WHERE mins_to_play in(SELECT MIN(mins_to_play) from board_games);

7. SELECT name FROM recipes WHERE minutes_required in(SELECT MAX(minutes_required) from recipes);

8. SELECT name FROM robots WHERE name lIKE 'M%';

9. SELECT COUNT(name) FROM board_games WHERE max_players >= 8 AND min_players <= 8;

10.

11.

12.
