# Sets

Collection of items/things
**Set** is made up of **elements**
**Cardinality** is the size (number of **elements**) in the **set**
Empty set (or ∅) has no elements and has a cardinality of 0

Examples: 
- A={1, 2, -7, 14, 7}
- E={Apple, monkey, testing}

Notation Examples:
- 2 ϵ A: 2 is an element of set A
- 15 ∉ A: 15 is not an element of set A
- |A| = 5: cardinality of set A is 5

## Intersection & union

Sample Sets
- A = {1, 2, -3, 7}
- B = {2, 8, -3, 10}
- D = {5, 10}

A ∩ B = {2, -3} is the intersection of A & B, the elements sets A & B share in common. 
B ∩ D = {10}
A ∩ D = {} or ∅ (the empty set)

A ∩ B = {x: x ϵ A and x ϵ B} - conditional expression instead of showing actual members

A ∪ B = {1, 2, -3, 7, 8, 10} - is the union of A & B, the elements that are either in A or B
A ∪ B = {x: x ϵ A or X ϵ B}

## Medical Testing Example
Imaginary syndrome: VBS
X = set of people in clinical trial
S = {x ϵ X : x has VBS} - sick set
H = {x ϵ X : x does not have VBS} - healthy set
X = S ∪ H - the union of S & H is everyone, assume each person either has it or does not
S ∩ H = ∅ - no one can be in both sets, you either have it or you do not, so the intersection is the empty set

P = {x ϵ X : x tests positive for VBS}
N = {x ϵ X : x tests negative for VBS}
X = P ∪ N - the union of P & N is everyone, each person either tests positive or negative
P ∩ N = ∅ - no one can be in both sets, you either test positive or negative, so the intersection is the empty set

Sets to consider 
S ∩ P - sick that tests positive - true positives
H ∩ N - healthy that tests negative - true negatives
S ∩ N - sick that tests negative - false negatives
H ∩ P - sick that tests positive - false positives

|S| / |X| - proportion of people in study who have VBS
|H| / |X| - proportion of people in study who do not have VBS

|S ∩ P| / |S| - proportion of true positives to those who are sick or true positive rate
|H ∩ P| / |H| - false positive rate
|S ∩ N| / |S| - false negative rate
|H ∩ N| / |H| - true negative rate

## Venn Diagrams
Method to visualze sets - overlap at intersects

## Inclusion-exclusion formula
|A ∪ B| = |A| + |B| - |A ∩ B|