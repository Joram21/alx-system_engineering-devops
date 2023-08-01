Regular Expressions- are simply expresions used regularly in programming. 
Repetition tokens are greedy, they continue to match until the last matching token. This is fixed quickly by using laziness, by adding a '?' after +. Thus matching only the HTML tags,<.+?>
A better altenative is to use negative character class. <|^>|+>. This is much more efficient in terms of backtracking and hence returns results faster.
