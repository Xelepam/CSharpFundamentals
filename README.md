# CSharpFundamentals
Repo for quick crash course on c# fundamentals. <br/>
<br/>
# Introduction to C# & .NET Framework
- C# vs .NET <br/>
C# : Programming language <br/>
.NET : Framework for building applications <br/>
    - CLR <br/>
    - Class Library <br/>

- Common Language Run-time (CLR) <br/>
Before C#, we had C & C++ when we would compile our app the compiler would translate it to the native code for the machine it was running on. In other words, if you compiled on a windows machine it would not run on a linux machine.
When we compile in C# we get "IL" Code, or Intermediate Language Code, it is independent of the machine its running on. We need something to translate IL code to native code and that is what CLR does. It sits in the memory and compiles just in time, or JIT. <br/>

- Architecture of .NET Applications <br/>
At the high level your Application will consist of building blocks called Classes, containers that hold Data and contains Methods. <br/>
As Classes grow we have containers for these classes called Namespaces. <br/>
As Namespaces grow we have containers for them called Assemblys or (DLL's / EXE's) <br/>
Applications are composed of these Assemblys. <br/>
<br/>

# Primitive Types & Expressions
"""
C# Type - .NET Type - Bytes - Range <br/>
byte - Byte - 1 - 0 to 255 <br/>
short - Int16 - 2 - -32,768 to 32,767 <br/>
int - Int32 - 4 - -2.1B to 2.1B <br/>
long - Int64 - 8 - ... <br/>
float - Single - 4 - -3.4x10^38 to 3.4x10^38 <br/>
double - Double - 8 - ... <br/>
decimal - Decimal - 16 - -7.9x10^28 to 7.9x10^28 <br/>
char - Char - 2 - Unicode Characters <br/>
bool - Boolean - 1 - True or False <br/>
"""
<br/>
- Variables & Constants <br/>
    - Variable : A name given to a storage location in memory. <br/>
    - Constants : An immutable value. <br/>
<br/>
- Overflowing <br/>
- Scope <br/>
- Type Conversion <br/>
- Operators <br/>
- Logical Operators <br/>
- Comments <br/>


