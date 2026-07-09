# Player Movement

## Locomotion
- [ ] Walking `WASD`
- [ ] Running `SHIFT`
- [ ] Stance State `C`
    - [ ] Kneeling
    - [ ] Crouching
    - [ ] Crawling
    - [ ] Transitions between stances

## Core Movement
- [ ] Inertia
    - [ ] Transition between states
    - [ ] Acceleration
    - [ ] Deceleration
- [ ] Gravity
- [ ] Ground detection
- [ ] Jumping
    - [ ] OnJump
    - [ ] OnFall
    - [ ] OnLanded
- [ ] Air control
- [ ] Slopes
- [ ] Steps / Stairs
- [ ] Moving platforms

## Traversal
- [ ] Sliding
- [ ] Vaulting
- [ ] Mantling
- [ ] Ladders -> Might be separated
- [ ] Swimming -> Might be separated

## Other Movement
- [ ] Leaning `Q/E`

## Feedback
- [ ] When falling Camera should go slightly higher or making camera shake (head bob but velocity based) ?
- [ ] When hitting the ground camera should shake a little while going lower "kind of like a bump"
- [ ] When running FOV should change slightly, head bob more intense
	- [ ] Maybe headbob based on velocity? which would naturally make falling camera shake occur? 
- [ ] Depending on Stance head bob should be more or less


> Can't seem to decide on whether I should do the movements with a rigidbody, a character controller or completely on my own