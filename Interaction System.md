## Core

- [ ] Interactor
    - The entity performing the interaction
    - Finds and attempts interactions
    - Sends interaction requests

- [ ] Interactable
    - The thing being interacted with
    - A door, item, car, generator, NPC, etc.
    - Defines what happens when interacted with

- [ ] Interactor Capability ??? (Unsure)
    - Defines what the interactor is capable of doing
    - Inventory capability, Damage capability, Tool capability, Access capability
    - Other interaction requirements
- Might just introduce Actor abstraction with "ICapability"


## Feedback
- [ ] Prompt
	- [ ] ActionText
		`Open` / `Close` / `Repair` / `Lock` / `Use` / `Hack` / `Unlock` / `Pick Up`
	- [ ] Title
		`Door` / `Generator` / `Terminal`
	- [ ] Description
		"`Require a key`" / "`Require fuel`" 
	- [ ] Progression
		*Just a float to represent the current normalized progression of the interaction* 