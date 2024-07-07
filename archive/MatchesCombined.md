Source: https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017

MatchesCombined is a contains 2023 and 2024 extracts from
    qualifying matches - all officially part of the UEFA 2024 Euros
    friendlies - some of these include matches with non-European teams
    UEFA Nations League - competion involving the UEFA European teams held in 2022-23.

Total matches - 570.

Suggest that this could be our primary source of data for ML.  

Additional features to improve the models outcomes:

- added in the xGD for each team that we could get (else 0)
    RECONSIDER THE VALUE FOR NULLS.  CUZ 0 IS A PRETTY GOOD SCORE.  MAYBE USE ONE LESS THAN WORST SCORE?
- clarified the target (for now): model will find teams that end in top 4
- add other rankings data, such as the ELO calculated, and betting odds (added!)

Next up:

- put this into a model.  does the outcome make sense?  should put spain, england, portugal, germany in the top group, or other teams near the top.

- does it work to have data where each team has MULTIPLE ROWS?  <<-- Hmmm


