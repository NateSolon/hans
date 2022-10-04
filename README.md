Baseline analysis for the chess cheating controversy related to Hans Niemann and Magnus Carlsen.

## Overview
Magnus Carlsen has leveled accusations of cheating against Hans Niemann. Subsequently, many have argued that Niemann's games are impossibly accurate. This analysis compares Niemann's accuracy (compared to engine analysis) against comparable players.

## Data
All over-the-board classical games between 2020-2022 by Hans Niemann, Magnus Carlsen, Ian Nepomniachtchi, Dommaraju Gukesh, and Arjun Erigaisi. The idea behind the selection of players is to provide a comparison to the current best players in the world (Carlsen and Nepomniachtchi) and young players who have made rapid progress in the same period as Niemann (Gukesh and Erigaisi). The game data for all players is included in the pgns directory.

## Analysis
I analyzed every move from every game with Stockfish 15 at depth 18. I then calculated the _centipawn loss_ of each move. The engine evaluation is based on the top line, so by definition, the best move maintains the current evaluation. Centipawn loss is the difference between the evaluation of the best move and the evaluation after the move the player actually played. It's a measure of how much they lost by playing subpar moves.

## Contributing
All the data and code used for this analysis is included in the repo. See the Issues for ideas for further work, or try your own ideas. Contributions are welcome.
