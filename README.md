# This is a demo of Coverlet nuget package

Commands:
1. ~\Demo.UnitTest.CodeCoverage.UnitTest$ dotnet test --collect:"XPlat Code Coverage"
2. ~\Demo.UnitTest.CodeCoverage.UnitTest$ reportgenerator "-reports:Path\To\TestProject\TestResults\{guid}\coverage.cobertura.xml" "-targetdir:coveragereport" -reporttypes:Html
