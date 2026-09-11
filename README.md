# GrafPack

An interactive 2D vector graphics editor built in C# with WinForms and GDI+, developed as a university coursework project.

## Features

- Draw squares, triangles and circles interactively using rubber-band selection.
- Select, move and delete shapes on the canvas.
- Rotate the selected shape by 90 or 180 degrees, implemented with matrix-based point rotation around the shape's centre.
- Change outline colour, fill colour and border thickness per shape via a custom menu system.

## Structure

- `GrafPack/GrafPack.cs` - main form: shape creation, selection, rotation (matrix transforms), colour/thickness menus, mouse and rubber-band handling.
- `GrafPack/Program.cs` - application entry point.
- `GrafPack/GrafPack.Designer.cs` - WinForms designer-generated layout.
- `GrafPack/GrafPack.csproj` - project file (targets .NET Framework 4.7.2, WinForms).

## Tech stack

C#, WinForms, GDI+.
