---
ns: PATHFIND
aliases: ["0xA0F8A7517A273C05"]
---
## _GET_ROAD_SIDE_POINT_WITH_HEADING

```c
// 0xA0F8A7517A273C05
BOOL _GET_ROAD_SIDE_POINT_WITH_HEADING(float x, float y, float z, float heading, Vector3* outPosition);
```

## Parameters
* **x**: Game.PlayerPed.Position.X;
* **y**: Game.PlayerPed.Position.Y;
* **z**: Game.PlayerPed.Position.Z;
* **heading**: Game.PlayerPed.Heading;
* **outPosition**: ref new Vector3();

## Return value

**outPosition** shows the closest sidepoint (paving) to the player
