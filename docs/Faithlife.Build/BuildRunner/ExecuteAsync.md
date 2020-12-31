# BuildRunner.ExecuteAsync method

Executes an automated build. Called from `Main`.

```csharp
public static Task<int> ExecuteAsync(string[] args, Action<BuildApp> initialize)
```

| parameter | description |
| --- | --- |
| args | The command-line arguments from `Main`. |
| initialize | Called to initialize the build. |

## Return Value

The exit code for the build.

## See Also

* class [BuildApp](../BuildApp.md)
* class [BuildRunner](../BuildRunner.md)
* namespace [Faithlife.Build](../../Faithlife.Build.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Build.dll -->