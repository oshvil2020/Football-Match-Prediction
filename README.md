# Football-Match-Prediction

##Descriptive columns

target - The variable you have to predict the probabilities only available in the train set.

home_team_name - The name of the Home the team.

away_team_name - The name of the Away the team.

match_date - The match date (UTC).

league_name - The league name.

league_id - The league id. Note that league names can be identical for two differents id.

is_cup - If the value is 1 the match is played for a cup compettion.

home_team_coach_id - The id of the Home team coach.

away_team_coach_id - The id of the Away team coach.


##Historical home team features

home_team_history_matchdate{i} - The date of the last i-th match played by Home team.

home_team_history_is_playhome{i} - If 1, the Home team played home.

home_team_history_iscup{i} - If 1, the match was a cup competition.

home_team_historygoal{i} - The number of goals scored by the Home team on its last i-th match.

home_team_history_opponentgoal{i} - The number of goals conceded by the Home team on its last i-th match.

home_team_historyrating{i} - The rating of the Home team on its last i-th match (pre match rating). 

home_team_history_opponentrating{i} - The rating of the opponent team on Home team last i-th match (pre match rating). 

home_team_historycoach{i} - The coach id of the Home team on its last i-th match. 

home_team_history_leagueid{i} - The league name id by the Home team on its last i-th match.


##Historical away team features

away_team_history_matchdate{i} - The date of the last i-th match played by Away team.

away_team_history_is_playhome{i} - If 1, the Away team played home.

away_team_history_iscup{i} - If 1, the match was a cup competition.

away_team_historygoal{i} - The number of goals scored by the Away team on its last i-th match.

away_team_history_opponentgoal{i} - The number of goals conceded by the Away team on its last i-th match.

away_team_historyrating{i} - The rating of the Away team on its last i-th match (pre match rating).

away_team_history_opponentrating{i} - The rating of the opponent team on Away team last i-th match (pre match rating).

away_team_historycoach{i} - The coach id of the Away team on its last i-th match.

away_team_history_leagueid{i} - The league name id played by the Away on its last i-th match.
