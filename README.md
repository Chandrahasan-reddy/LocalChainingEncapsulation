# LocalChainingEncapsulation

🔹 Local Chaining in Java (Encapsulation Practice)
This Java project demonstrates local variable initialization in multiple constructors rather than using constructor chaining. The class uses encapsulation to manage private data and provides default values and custom values through overloaded constructors.

✅ What This Code Covers
Default constructor – sets default values

Parameterized constructors – allow custom initialization

Local chaining – values are initialized individually in each constructor, no this() chaining used

Encapsulation – private fields with public getter methods

🔧 Code Behavior & Flow
The class MyCustomer includes:

Private fields:

cID (Customer ID)

cName (Customer Name)

cNum (Customer Number)

Constructors:

Default Constructor
Initializes all fields with default values:

cID = 1;
cName = "Chandu";
cNum = 9876543;
One-parameter Constructor


Uses local initialization without calling other constructors:


cID = 1;
cName = name;     // Uses the passed name
cNum = 9876543;
Three-parameter Constructor
Sets all values directly:


this.cID = cID;
this.cName = cName;
this.cNum = cNum;
Getter methods for all fields.




MyCustomer c1 = new MyCustomer(2, "Alex", 456789);
//output Prininting
System.out.println(c1.getcID());
System.out.println(c1.getcName());
System.out.println(c1.getcNum());


You get://output....
2
Chandu
456789

📌 Key Concepts
Local Chaining – Each constructor sets values explicitly

Encapsulation – Data is secure and accessible via getters

Overloading – Multiple constructors provide flexibility
