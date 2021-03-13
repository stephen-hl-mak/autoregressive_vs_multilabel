This repo contains a toy experiment I performed to test ``autoregressive`` action spaces vs. ``multi-label`` action spaces.

Conclusion:
- Autoregressive action spaces are better as they can learn the dependency between individual actions better.
- Autoregressive action spaces take longer to do inference (by ~40\%), but make up for it by much much improved sample efficiency. In fact, the multi-label approach isn't able to solve this problem at least with the settings I tried (still probably do-able though).

Note: this work was completed within 4 hours, without unit testing or extensive repeated trials. Take this recommendation with a pinch of salt.