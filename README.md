The key insight is that we must test the number of potential scenarios distinguishable by the remaining tries vs the number of potential states left in the system.

- For example we know for certain that the initial problem from that perspective is possible
- Given that each "trial" can represent 3 states we can distinguish between 3^3 = 27 possible states
- Meanwhile the system itself has 12 * 2 = 24 states.
- From this point of view the system is possible (this is a necessary but not sufficient condition - for example we might be tempted to say that we could solve the analogous problem for 13 marbles however notice that the first weigh is discrete and will put us into a deadend no matter which boundary we break across
- So the most likely candidates for the first weigh is 3 vs 3 or 4 vs 4. We can rule out 3 vs 3 because that MIGHT potentially leave us with 6 remaining unknown marbles with both heavier and lighter states possible, ie 12 possible states with a resolution of only 3^2 = 9 states. So we know we cannot procede down this path
- The rest is simply conjuring a sequence of tries that satisfies 1. all possible scenarios of \ / _ must be possible as much as possible to extract the most possible information from the system as possible
