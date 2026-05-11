# Kicktipp World Cup 2026

## Code to retrieve the admiral.at odds for all the World Cup games

This repo shall facilitate the odds extraction for each of the 2026 FIFA World Cup matches. We use the `admiral.at` odds.[^1] Next, we translate odds into implied probabilities and determine the argmax tips for a standard prediction game at `kicktipp.ch`.

To get started, follow these three steps.

1. Create a `kicktipp.ch` account and join a World Cup prediction tipround

2. Create the `login.txt` file in your directory with your credentials:

```
USERNAME: your-kicktipp-username
PASSWORD: your-kicktipp-password
TIPROUND: your-kicktipp-tipround
```

3. Run the `introduction.ipynb` notebook to retrieve the odds from `admiral.at` and translate them into the argmax tip for each of the matches

Currently, this is still written for the 2025/26 Bundesliga season. As soon as the World Cup prediciton games come online, we will update this repo accordingly.

### Primary maintainer
[Moritz Miller](https://mrtzmllr.github.io)

[^1]: Note that `admiral.at` is not available in all countries, but can be accessed from Austria, Italy, and Switzerland, among others.