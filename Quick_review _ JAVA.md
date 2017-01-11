Java Programming Cheatsheet

This appendix summarizes the most commonly-used Java language features in the
textbook. Here are
the [APIs](http://introcs.cs.princeton.edu/java/11cheatsheet/api.pdf) of the
most common libraries.

**Hello, World.**

![Hello, World in Java](media/89b802dd0edabe5cf0e991a17d6ab89b.png)

**Editing, compiling, and executing.**

![Compiling Hello, World in Java](media/4c9128a6b2d6b3aa31fa6b48132e4fca.png)

**Built-in data types.**

![Built-in types of data](media/73b3b2c12088d3d86adec19d806a1634.png)

**Declaration and assignment statements.**

![Assignment statements](media/37f3e139fd2662fe0a4461accec0048a.png)

**Integers.**

![int data type](media/3b513a6e820bbcfdaf651f903e04dbcb.png)

![Integer expressions](media/5b23807260b1591f8414cdbe14d8008a.png)

**Floating-point numbers.**

![double data type](media/d2deb3d0d5c77006b5ecac3f2bdbc5f9.png)

![double expressions](media/b0ad80bb9d6265560a87879611428274.png)

**Booleans.**

![boolean data type](media/df0b567b995c99a393ecb0117f389fe6.png)

![Boolean operators](media/1d585bfe25ede701b5493f00325de51c.png)

**Comparison operators.**

![Comparison operators](media/5ef4f919c313f4527573ba3cf984c8fe.png)

![Comparison examples](media/1a2c10502e0557cff4b2ee9257d36114.png)

**Parsing command-line arguments.**

![parsing Command-line arguments](media/410dbf9a8e83149109a6689c68ef0c9c.png)

**Math library.**

![Math library API](media/c6e206e576a68a617d4eee901962bb9a.png)

![Expressions that use Java library methods](media/d98540fda02c36b112c2a051a37ce58f.png)

The full *java.lang.Math API*.

**Type conversion.**

![Type conversion](media/30a41c345f45a76d30fb92fdb751ec51.png)

**If and if-else statements.**

![If-else statements](media/1dae93c47298f9304dfe7fc9bc4f361e.png)

**Nested if-else statement.**

![Nested if-else statements in Java](media/02fbe5bc28c47b0613b30be6dc23d94d.png)

**While and for loops.**

![While loop](media/b7de42c5206eb5eed4485eb7fca2bd60.png)

![For loop](media/1ce1c07cc2242d785706e67fdf5bbf36.png)

![While and for loops in Java](media/044392d37f974f60761f0313da325ff8.png)

**Break statement.**

![Break statement in Java](media/f8453b615002298587eac0a586e87f47.png)

**Do-while loop.**

![Do-while loop in Java](media/af2ff9df09d2c1b72681b1f6c419a512.png)

**Switch statement.**

![Switch statement in Java](media/1c8b63c081b03929da165c4ab59f4d4c.png)

**Arrays.**

![An array](media/2396063ac505f6311c3fc3608469b391.png)

Compile-time initialization.

![Compile-time initialization of arrays](media/689d06136c0d799744124d51c8d5a20e.png)

Typical array-processing code.

![Typical array-processing code](media/90e38afd90b717b13c3eb69bb4928801.png)

**Two-dimensional arrays.**

![2D array](media/ee575e11a281867a471361906c0f8d2f.png)

Compile-time initialization.

![2D array compile-time initialization](media/08119eda2441dd69d7926649cc138261.png)

Ragged arrays.

![Ragged arrays](media/0a9a5508f7455f8edb01a5e4d04b4fbe.png)

**Our standard output library.**

![Standard output API](media/2774cdd23425a75e8d5ba06ebc825b8f.png)

The full *StdOut API*.

![Anatomy of printf](media/66f97d63e05b050b20fecb28f0d3bb47.png)

![Formatting codes for printf](media/34688f23dc619b69224e25bc9b1f5b07.png)

**Our standard input library.**

![Standard input API](media/0cba2e20b258e32ffde7dde19c088e0d.png)

The full *StdIn API*.

**Our standard drawing library.**

![Standard drawing API](media/d29561014ae40de387b982af5fd5eaae.png)

The full *StdDraw API*.

**Our standard audio library.**

![Standard audio API](media/d742f2495359d48ce05ac262b6875097.png)

The full *StdAudio API*.

**Redirection and piping.**

![Redirecting standard output](media/70161aaad5cc30e97735e876efad77bd.png)

![Redirecting standard input](media/61f1f019171830f4ff7bdec3c28e64d0.png)

![Piping](media/419d68837000d669dcad47c4ee8adad7.png)

**Functions.**

![Anatomy of a function](media/317f46999b692b587947a106b56da9e0.png)

![Example functions](media/30ffb53901c744438ef8dd4061761c79.png)

**Libraries of functions.**

![Library abstraction](media/c981b49d99eb38873caf419ef43561d0.png)

**Our standard random library.**

![Standard random](media/713fad3ed804e4317129f3cf145bb756.png)

**Our standard statistics library.**

![Standard statistics](media/19a9b00c3af92449b98172eb5cdf74ab.png)

**Using an object.**

![Using an object](media/98615e231eebd8f2a9d7a0f7b89ae4c2.png)

**Creating an object.**

Instance variables.

![Anatomy of instance variables](media/be329612428a6548b68d3d9beef923a4.png)

Constructors.

![Anatomy of a constructor](media/6d3d2991c309ec95cfb815640fc21652.png)

Instance methods.

![Anatomy of an instance method](media/5bd5b41a299837eaece828e35f476a8d.png)

**Classes.**

![Anatomy of a class](media/e3250dac99ebc37d7c5069596cbc048b.png)

**Object-oriented libraries.**

![Object-oriented library abstraction](media/44506379f80ffe8f1489dc2f8ad2d54a.png)

**Java's String data type.**

![String library API](media/a9e56a4b01d58d7ec8a3e70fad483446.png)

The full *java.lang.String API*.

![String operations](media/c61509423f883dab03454105b3902d22.png)

*Note*: the *java.lang.StringBuilder* API is similar, but StringBuilder supports
some operations more efficiently than String (notably, string concatenation) and
some operations less efficiently (notably, substring extraction).

**Java's Color data type.**

![Color library API](media/bc13b9ca06592d7b392fc35c1ac5e776.png)

The full *java.awt.Color API*.

**Our input library.**

![Input API](media/2cf72961b769c0cc459ebeddb5dcd0f8.png)

The full [In API](http://introcs.cs.princeton.edu/java/stdlib/javadoc/In.html).

**Our output library.**

![Output API](media/373df56bec97c4559f8dd079ebb4c3fd.png)

The full [Out
API](http://introcs.cs.princeton.edu/java/stdlib/javadoc/Out.html).

**Our picture library.**

![Picture API](media/7d5b7fe70d3a5a796c34c3ad5cf87795.png)

The full [Picture
API](http://introcs.cs.princeton.edu/java/stdlib/javadoc/Picture.html).
