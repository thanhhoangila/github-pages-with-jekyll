# EDA - PUBG kill Dataset

**Description**
>This data set is data about 13 milions kill within 128k match in PUBG, 2 map Erangel and Mirama. Each row is an event when a player died.

**Field include**
- killed_by: The reason of the death (weapons, vehicles, bluezones,...)
- killer_name: Name of killer (NaN when killed_by is bluezones or drown)
- killer_placement: The rank of killer in the match (NaN when killed_by is bluezones or drown)
- killer_position_x: x-coordinate of the killer when he killed the victim (NaN when killed_by is bluezones or drown)
- killer_position_y: y-coordinate of the killer when he killed the victim (NaN when killed_by is bluezones or drown)
- map: Map where the match happen (in this dataset we have 2 map Mirama and Erangel)
- time: time in second when the victim was killed
- match_id: id of the match 
- victim_name: Name of victim
- victim_placement: The rank of victim in the match
- victim_position_x: x-coordinate of the victim when he was killed
- victim_position_y: y-coordinate of the victim when he was killed
