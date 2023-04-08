# GodotGameTemplate

[![Chickensoft Badge][chickensoft-badge]][chickensoft-website] [![Discord][discord-badge]][discord] [![Read the docs][read-the-docs-badge]][docs]

C# game template for Godot 4 with automatic releases, dependency updates, debug launch configurations, testing (locally and on CI/CD), code coverage, and spell check working out-of-the-box!

```sh
# Install this template
dotnet new --install Chickensoft.GodotGame

# Generate a new game based on this template
dotnet new chickenpackage --name "MyPackageName" --param:author "My Name"
```

**NOTE:** This repository contains only the `dotnet new` template information and package description. The actual template contents are included as a git submodule from the [GodotGame] repository.

The [GodotGame] template contents are included as a submodule, since it is easier to verify changes to the template if it compiles and bundles into a package of its own.

Microsoft has an article on [creating template packages][create-template-package].

<!-- Links -->

<!-- Header -->
[chickensoft-badge]: https://raw.githubusercontent.com/chickensoft-games/chickensoft_site/main/static/img/badges/chickensoft_badge.svg
[chickensoft-website]: https://chickensoft.games
[discord-badge]: https://raw.githubusercontent.com/chickensoft-games/chickensoft_site/main/static/img/badges/discord_badge.svg
[discord]: https://discord.gg/gSjaPgMmYW
[read-the-docs-badge]: https://raw.githubusercontent.com/chickensoft-games/chickensoft_site/main/static/img/badges/read_the_docs_badge.svg
[docs]: https://chickensoft.games/docs/

<!-- Article -->
[GodotGame]: https://github.com/chickensoft-games/GodotGame
[create-template-package]: https://learn.microsoft.com/en-us/dotnet/core/tutorials/cli-templates-create-template-package
