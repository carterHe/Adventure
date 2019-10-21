# Adventure

A sample of Orleans, which run as .NET Core 2.2 successed.

# Run 

1. `dotnet build`

2. Open a command line to run `dotnet AdventureSetup.dll` as a server.

3. Open a command line to run `dotnet AdventureClient.dll` as a client, you shoud open more clients.

# Commands

> look : look around of you.

> take : take something in current environment.

> drop : drop something which in your hands.

> go : go four directions, you shoud found the directions in map description.

> kill : kill someone.


# Bug fixed

1. Use `Microsoft.Orleans.CodeGenerator.MSBuild` instead.

REF : https://github.com/dotnet/orleans/issues/5245

2. Convert to .NET Core 2.2 sdk.