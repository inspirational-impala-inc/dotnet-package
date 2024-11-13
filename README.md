# Hello World for Packages

This is a simple .NET Application designed to test publishing packages to the
GitHub NuGet Registry.

# Scopes

The scopes used for the personal access token in the `publish.yml` workflow are:

- `write: packages`
- `read: packages`

# Publishing a new package version

1. Create a new branch.
2. Bump the version in the `dotnet-package.csproj` file.
3. Push the branch to the server.
4. Run the `Publish Package` workflow.
