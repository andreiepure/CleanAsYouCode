Sample copied from https://github.com/SonarSource/sonar-dotnet (commit id 6b9097bbcb)

Modifications:
- copied only "sonar-dotnet\analyzers\its\Projects\ManuallyAddedNoncompliantIssues.CS" 
- removed folders "AspNet4x", "NetFramework*" (except NetFramework48), "Net5"
- renamed files under "IntentionalFindings" to "Foo*"
- added Directory.Build.props, .editorconfig, NuGet.config