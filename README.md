# badminton-score
A peer to peer badminton scoring system written to a blockchain, and signed and verified by all players.

# Use Case
As a badminton player, when I play with someone I don’t know, I want to record our match score so that I can certify our scoring and be ranked along with other badminton players across the nation.

# Principals
- For a singles match, all 2 players must sign and certify the result of the match.
- For a doubles match, at least 3 players out of the 4 must certify the match.
- Identities are anonymous, but still verified or some method of signing
- Scores are not verified, until the players plays with a ranked player and that game is recorded.
   - Simplistic view: Player A plays 5 games against other unranked players.  All 5 games are not verified, until they play against player B, who is ranked at C.  If Player A wins, then they are ranked at C and all 5 games they become verified.

Using blockchain, the 2-4 players must all certify the match without an official judge.

# Scoring and Ranking
## Possible
- https://en.wikipedia.org/wiki/Glicko_rating_system
