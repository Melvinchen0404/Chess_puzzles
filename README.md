# Chess_puzzles
Lichess database for chess puzzles: https://database.lichess.org/#puzzles

Database fields: "PuzzleId", "FEN", "Moves", "Rating", "RatingDeviation", "Popularity", "NbPlays", "Themes", "GameUrl", "OpeningTags" <br>
Range of values for "Rating": 399.0 - 3153.0 <br>
Range of values for "Popularity": -100.0 - 100.0 <br>
Restricted range of values for "Themes": "advancedPawn", "discoveredAttack", "enPassant", "doubleBishopMate", "fork", "mateIn1", "mateIn2", "mateIn3", "mateIn4", "mateIn5", "skewer", "sacrifice", "underPromotion", "zugzwang"<br>
<br>
Moves are in UCI format <br>
<br>
All player moves of the solution are "only moves". Playing any other move would considerably worsen the player position. An exception is made for mates in one: there can be several. Any move that checkmates should win the puzzle. FEN is the position before the opponent makes their move.
