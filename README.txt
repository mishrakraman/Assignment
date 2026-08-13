For this requirement is a consistent-hashing-based distributed key-value store. Each key maps to exactly one node, while virtual nodes help keep the record distribution reasonably even, hash(key) -> position on ring -> first node clockwise.

Therefore, one record has exactly one owner node, I have also done using multiple virtual nodes per physical node significantly improves distribution.
