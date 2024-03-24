# "Avoid the Monsters" in Godot 3.5
This video game is my very first full-fledged project on GitHub, derived from the section "Your First 2D Game" in
the Godot 3.5.3 documentation. _I usually engage in game development as a hobby for myself, to be honest._

Many an element in this project is slightly adjusted, and all of the game code is rewritten in Visual Basic .NET by
means of a class library, which is currently my favorite programming language, even though I also enjoy writing C#
scripts in Godot. ___Getting started with VB.NET in Godot requires ".NET Core 3.1 SDK", with GodotSharp.dll added as
a reference to the .vbproj file.___ In addition, the corresponding .csproj file must include Microsoft.VisualBasic.Core.dll,
just before the VB.NET class library can be added to the Godot C# project.

All the classes defined in the VB.NET library are bound to be inherited by empty C# stripts, so that they can be
brought to use in the game. _Nevertheless, as for my game development in Godot in the future, I will be writing
C# scripts for real, with a VB.NET class library still used as a module._

__Last but not least, I have added touch controls in the project. The whole game can be either played on computers
or exported to the Android devices.__
