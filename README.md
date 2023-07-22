# Welcome to LucidCLI made in C#!

This is my password manager program to store passwords in the terminal.

This software can be either run as a dotnet project or packed as a global tool.


# Global Tool Installation For Dotnet version

1. cd into the directory of the project.
2. In the terminal run: 
  > dotnet pack
  
  > dotnet tool install --global --add-source ./nupkg Lucid

Or run...

  > dotnet publish -p:PublishSingleFile=true -r your-os -c Release --self-contained true

And add the executable file to your PATH.
