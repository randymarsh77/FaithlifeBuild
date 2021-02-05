# DotNetBuild.RunTests method

Runs tests on the specified path.

```csharp
public static void RunTests(this DotNetBuildSettings settings, string? path)
```

## Remarks

If null, runs all tests in the current solution. If an assembly, runs all tests in that assembly. Otherwise, runs all tests in the specified project or solution.

## See Also

* class [DotNetBuildSettings](../DotNetBuildSettings.md)
* class [DotNetBuild](../DotNetBuild.md)
* namespace [Faithlife.Build](../../Faithlife.Build.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Build.dll -->