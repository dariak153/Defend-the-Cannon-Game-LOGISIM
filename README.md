# Defend the Cannon - Game in LOGISIM

<p allign="center">
  <img src="https://user-images.githubusercontent.com/46852756/222492428-e0443d7c-fa29-4721-92e5-f8db1f3ecfa6.gif">
</p>

Defend the Cannon is a simple game made in [Logisim](http://www.cburch.com/logisim/). The main goal of the game is destroying the enemies (for this purpose we're using cannon) so they cannot reach the cannon. For each opponent hit by a projectile user get 1 point. Best score of the session is saved and displayed as a record.

At the start of each game the map is randomly generated (file [generowanie poziomu.circ](https://github.com/dariak153/Defend-the-Cannon-Game-LOGISIM/blob/main/generowanie_poziomu.circ) is responsible for it). There is 50% possibility that next column will have a higher ground level, 25% that it will be the same and 25% that it will decrease.
