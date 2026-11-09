# MG5
## Devlog
1. NavMesh is good when you want to define what players can walk on and define obstacles. For example, when walking into a classroom, a student may already know the classroom's layout. But also take into account obstacles in the way to their desks, making those obstacles unwalkable, such as a pillar. While something such as the video game Rocket League focuses more on scripting character movement since it's heavily reliant on the characters' movements and physics.

2. Inside the loop, since it begins with the first bird (index 0) and loops through each bird until the max is reached, which is determined by how many birds we have (length). If the distance of the bird is less than or equal to the interactive distance to the player's position, then the bird triggers the RunAway method. Vector3 is used to determine the distance between the bird and the player, and any bird that meets the if condition will run away. 

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)
