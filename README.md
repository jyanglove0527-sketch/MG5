# MG5
## Devlog
Put your Devlog here.
## Devlog
**Q1**
I think a NavMesh is better when the character needs to find its own path to a spot the player picks, instead of being controlled directly. For example, League of Legends makes sense with a NavMesh, because the player clicks on the ground and the champion walks there by itself, going around walls and obstacles. A game like Super Mario does not make sense with a NavMesh, because the player controls Mario directly with jumping, running, and bouncing off things, so it needs physics movement instead.

**Q2**
The for loop goes through every bird in the _birds array, from index 0 to the last one. For each bird, Vector3.Distance calculates the distance between that bird's position and the player's (Pudu's) position. If that distance is less than or equal to _interactDistance, the bird calls RunAway and flies away from the player. So only the birds that are close enough to the player run away.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)