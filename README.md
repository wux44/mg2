# minigame 2
## Devlog
### Question 1:
One issue I encountered was for the Spell script where I accidentally updated the time variable instead of _timeLeft when subtracting the elapsed time. This caused the spell's remaining lifetime to never decrease, so the spell would not disappear after one second as intended. So I was confused when playtesting it. Later I realized it by relooking at the code and I fixed it by changing the code from time = _timeLeft - time; to _timeLeft = _timeLeft - time.

### Question 2:
Since I have some experience in coding, I think the line is about setting the color property of _spriteRenderer to a new color with RBG value of r value, 0.2, and 0.2. The period is used to access the color property of _spriteRenderer and new is used for creating a new Color object.  
## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
