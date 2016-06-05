##  Replicatie - Voorbeeld

<img src="./img/2-arch/SimpleStrategy.png" alt="SimpleStrategy"/>

note:
SimpleStrategy
- Replicatiefactor 3
- kloksgewijs replica's plaatsen
- Zwart = origineel, grijs=replica

NetworkTopologyStrategy
- Aangeraden voor productieclusters
- Meerdere datacenters
  - Ieder datacenter kan andere replicatie factor hebben
- Rack-awareness
  - Replica's op verschillende racks
