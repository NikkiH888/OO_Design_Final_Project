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

#### Example Codes:
Object x = new StringBuilder("Nikki").ToString();
Object y = new StringBuilder("Nikki").ToString();
- Comparing references
if (x.Equals(y)) { 

} 

string string_x = (string) x;
string string_y = (string) y;

- Comparing values
if (string_x == string_y) {

}
