# .NET CLI Templates for usage with Visual Studio Code
Custom templates for `dotnet new` command when developing C# projects using Visual Studio Code

## Installing Template
Clone this respository to your local machine
```bash
git clone https://github.com/IvoKara/dotnet-vscode-templates.git
```

Change directory to the cloned git repository, then navigate to the desired template folder and install the template using the `dotnet new -i` command
```bash
cd dotnet-vscode-templates
cd <foldername>
dotnet new -i .
```

Or alternatively install it using the foldername as an argument of the `-i` flag:
```bash
dotnet new -i <foldername>
```
