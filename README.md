# lotr_risk_simulation
A simulation of LOTR Risk to determine how often the fellowship can win the game. 

The main addition to this game is the ring mechanic. The ring starts in the shire and, each turn, it moves moves one teritory closer to Mount Doom. If the ring makes it to Mount Doom, then the ring is destroyed and the good guys win the game! However, if at the end of someone's turn, the territory the ring is in is controlled by the forces of evil, then they can search for the ring. The forces of evil roll two dice and if they get a 12, then they find the ring, use it to enslave the continent, and win the game.

One final detail, is that the ring can get held up at certian locations like Moria or Lorien. When the ring is in one of these teritories, then to advance the ring to the next teritory, the forces of good must roll one die and get a 4 of more. Otherwise, the ring remains in that terrirory and they must make another roll next turn to advance it. 

---

After playing a few games, my friends and I found that the forces of evil were able to win by finding the ring every time. This made me think that the ring mechanic was heavily skewed in their favor. I was curious about exactly how much it was skewed in their favor so I wrote a quick program to simulate the ring mechanic and play one round of the game. Then, I just had it play a ton of games and see where/if the ring was found. 

I found that the good guys can get the ring to Mount Doom about 36% of the time. 

This makes it totally reasonable that the bad guys will win frequently but its definately not impossible for the good guys to win. It is just really hard, which is what you kinda want with this game. Good job game devs!!!
