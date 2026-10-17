# MG3
## Devlog
1. float is 0.0, int is 0, bool is false, string gets null.
2. I don't need to call the Update method myself. Unity automatically calls Update one every frame.
3. In the TimerText, the IsFinished method in the Timer is used to determine when the game is over and to set the gameObject's setActive property to false. During this process, the Update method is called once every frame, allowing for a countdown timer to be implemented.
## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)
