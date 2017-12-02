## Boolean Identities
##### Commutative Laws
* (x AND y) = (y AND x)
* (x OR y) = (y OR x)

##### Associative Laws
* (x AND (y AND z)) = ((x AND y) AND z)
* (x OR (y OR z)) = ((x OR y) OR z)

##### Distributive Laws
* (x AND (y OR z)) = (x AND y) OR (x AND z)
* (x OR (y AND z)) = (x OR y) AND (x OR z)

##### De Morgan Laws
* NOT(x AND y) = NOT(x) OR NOT(y)
* NOT(x OR y) = NOT(x) AND NOT(y)

* * *
* Example
NOT(NOT(x) AND NOT(x OR y)) = 
NOT(NOT(x) AND (NOT(x) AND NOT(y))) = 
NOT((NOT(x) AND NOT(x)) AND NOT(y)) = 
NOT(NOT(x) AND NOT(y)) = 
NOT(NOT(x)) OR NOT(NOT(y)) =
x OR y
