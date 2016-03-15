# Finding The Strongest Pokémon Using Battle Simualtion and Capital Asset Pricing Model

2016 is a great year to be a Pokémon fan. Pokémon Sun and Moon are expected to be release during [the holiday season](http://www.pokemon.com/us/pokemon-video-games/pokemon-sun-and-pokemon-moon/) and Niantic's [Pokémon Go](http://www.pokemon.com/us/pokemon-video-games/pokemon-go/) due some time later this year. The time has come for us to answer one of the most important questions in life, the one that has brought about most heated discussions for elementary schoolers and grown-ups alike: *What is the strongest Pokémon of all time?*

We set out to answer this question by simulating battles for all Pokémon from Generation I to VI, then calculate their ```variance-adjusted average win rate```, in the tradition of the [Sharpe ratio](http://www.investopedia.com/terms/s/sharperatio.asp) often employed in portfolio analysis. The data is obtained from the [Pokémon Database](http://pokemondb.net) including type advatages, Pokédex and moves database. All 800 Pokémons underwent 100 with one another resulting in 800 x 800 x 100 battles simulated in total. We then computed the average variance-adjusted win rates and rank all Pokémons accordingly.

Report is [here](http://cstorm125.github.io/pokemon).

GitHub repository is [here](https://github.com/cstorm125/pokemon).
