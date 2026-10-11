# minigame 2
## Devlog
1.When I worked on Step 2 of the Spell script, I forgot to remove all the comment slashes // for the if statement. The code did not run the logic to disable the spell object when _timeLeft hit zero. I checked line by line, deleted the comment marks, and then the if statement worked correctly. The spell would turn invisible and disable its collider once its lifetime ran out.
2. For the code line _spriteRenderer.color = new Color(r, 0.2f, 0.2f);:<br/>. The period . connects the object _spriteRenderer to its property color, meaning I am accessing the color setting of the sprite renderer component. The keyword new creates a brand-new Color object with custom red, green, blue values. The variable r controls how much red appears, while green and blue stay fixed at 0.2f. When health decreases, r gets smaller and the sprite turns darker red.
## Open-Source Assets
- Pixel art environment & character sprites: https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605
