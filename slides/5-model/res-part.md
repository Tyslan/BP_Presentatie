##  Restricties - Partitiekolommen

- Enkel rechtstreeks '=' en 'IN' mogelijk
- '<', '<=', '>', '>='
  - Via token
  - Rechtstreeks met ByteOrderedPartitioner

note:
- Gebruik token performant
- niet altijd gewenste uitkomst
- ByteOrderedPartitioner heeft veel meer problemen dan dat het er oplost
