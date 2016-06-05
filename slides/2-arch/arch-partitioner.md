##  Partitioner

- Bepaalt fysieke plaats
  - hash functie

- 3 Soorten
  1. RandomPartitioner
  2. Murmur3Partitioner
  3. ByteOrderedPartitioner

note:
Horizontaal schalen:
- dynamische partitionering van data over de nodes
  - partitioners
    - hashfuncties

3 Soorten
1. RandomPartitioner
  - MD5 hash
2. Murmur3Partitioner
  - Murmur hash
  - Standaard sinds 1.2
3. ByteOrderedPartitioner
  - Volgens bytes primaire sleutel
  - Problemen:
    - "Hot spots"
    - Gebalanceerde cluster
