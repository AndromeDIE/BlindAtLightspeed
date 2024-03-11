# Technical Design Document
### “Blind at Lightspeed”

### <ins>Game Concept:
The game “Blind at Lightspeed” is a fast-paced, endless resource-management simulator, in which the player is locked in a small room with three consoles. These consoles are used to manage the level of resources, which keep the space-shuttle, in which the player character finds themselves in, running. Depletion of a resource results in the end of the game or the appearance of a hazard, which if not handled, too, will end the game. The longer a round is running, the higher the score of the player will grow.

### <ins>Technical Details:
The game is being developed in Unreal Engine 5, mainly using Blueprints. C++ is not excluded from being used in the future.

### <ins>Version Control Policy
The project repo can be found at 
https://github.com/AndromeDIE/BlindAtLightspeed

Commits are to be fitted with a descriptive commit message, describing the purpose of edited or newly added files as clearly as possible
working on files that are checked out by another contributor should never be done without communicating the process with the affected individuals and serves only as a last resort

### <ins>Naming Convention
All newly added Files are to be named with a fitting prefix which can be viewed at <br>
https://docs.unrealengine.com/5.3/en-US/recommended-asset-naming-conventions-in-unreal-engine-projects/ <br>
The exceptions are:
- Blueprint Interfaces: “I_” instead of “BI_”
- Blueprint Libraries: “LIB_” (no recommended prefix)
- Structures: “S_” instead of “F_”
