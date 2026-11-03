# Blackjack 21

[Play Blackjack 21](https://yumiut.github.io/blackjack/)

Play against the dealer with 5,000 virtual chips and a single 52-card deck. The deck is shuffled before every round, and your chip balance is saved in your browser.

## How to play

1. Choose chips to build your bet, or select **All in** to wager your remaining balance. Use **Clear bet** to take your chips back before the deal.
2. Select **Deal**. Try to finish closer to 21 than the dealer without going over. Face cards count as 10, and an ace counts as 1 or 11.
3. Choose **Hit** to draw another card or **Stand** to keep your total. The dealer reveals the hidden card and draws until reaching at least 17. The dealer stands on soft 17.
4. The result panel shows your net gain or loss. After two seconds, the table is ready for your next bet.

## Double down and split

- **Double down** matches your current hand’s bet, deals one final card, and ends that hand. It is available on a two-card hand when you have enough chips.
- **Split** a pair of the same rank by matching your original bet. Each hand gets another card. Play the left hand first, then the right. You can split once per round, and each hand is scored separately.

## Payouts

A regular win pays 1:1. An opening two-card blackjack pays 3:2 unless the dealer also has blackjack, in which case your bet is returned. A 21 after a split pays 1:1. All other ties also return the bet.

## Run locally

Download `index.html` from this repository and open it in a browser. The game includes its HTML, CSS, and JavaScript in one file and needs no installation or build step.
