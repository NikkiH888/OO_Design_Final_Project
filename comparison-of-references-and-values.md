# Java
#### Comparisons of references and values:
#### How are values compared?
- Reference Type: a == b or a != b
- Value Type: a.equals(b), a.compareTo(b), compare(a,b)

# C#
#### Comparisons of references and values:
#### How are values compared?
- string.Equals() and '==' operator
#### There are two differences:
- Equals() is polymorphic
- The implementation of '=='

#### Example Code:
Object x = new StringBuilder("Nikki").ToString();
Object y = new StringBuilder("Nikki").ToString();
if (x.Equals(y)) // 1

string xs = (string) x;
string ys = (string) y;

- Comparing values appropriately
if (xs == ys) // 1
