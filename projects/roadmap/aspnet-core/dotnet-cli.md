source #source/dotnet-documentation
area #area/programming/aspnet
subject #subject/cli
type #raw 
related-notes

# Overview
The .NET command-line interface (CLI) is a cross-platform toolchain for developing, building, running, and publishing .NET applications.

CLI command structure consists of [the driver ("dotnet")](https://learn.microsoft.com/en-us/dotnet/core/tools/#driver), [the command](https://learn.microsoft.com/en-us/dotnet/core/tools/#command), and possibly command [arguments](https://learn.microsoft.com/en-us/dotnet/core/tools/#arguments) and [options](https://learn.microsoft.com/en-us/dotnet/core/tools/#options).

```copy
dotnet new console
dotnet build --output ./build_output
dotnet ./build_output/my_app.dll
```
---
## Driver
The driver is named [dotnet](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet) and has two responsibilities, either running a [framework-dependent app](https://learn.microsoft.com/en-us/dotnet/core/deploying/) or executing a command.

If you want to run an app that depends on the dotnet framework, just do:
``` copy
dotnet ./build_output/my_app.dll
```

If you want to run a command using dotnet cli, just do:
``` copy
dotnet build
```
---
## Command

The command performs an action. For example, `dotnet build` builds code. `dotnet publish` publishes code. See the [CLI commands](https://learn.microsoft.com/en-us/dotnet/core/tools/#cli-commands) section for a list of commands.

---
## Arguments

The arguments you pass on the command line are the arguments to the command invoked or to options specified with the command. For example, when you execute `dotnet publish my_app.csproj`, the `my_app.csproj` argument indicates the project to publish and is passed to the `publish` command.

---
## Options

The options you pass on the command line are the options to the command invoked. For example, when you execute `dotnet publish --output /build_output`, the `--output` option and its value provided by the `/build_output` argument are passed to the `publish` command.

---
## Basic commands
- [`new`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-new)- [`restore`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-restore)- [`build`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-build)- [`publish`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-publish)- [`run`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-run)- [`test`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-test)- [`vstest`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-vstest)- [`pack`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-pack)- [`clean`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-clean)- [`sln`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-sln)- [`help`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-help)- [`store`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-store)- [`watch`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-watch)- [`format`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-format)
## Project modification commands
- [`package add`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-package-add)- [`package download`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-package-download)- [`package list`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-package-list)- [`package remove`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-package-remove)- [`package search`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-package-search)- [`package update`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-package-update)- [`project convert`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-project-convert) - [`reference add`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-reference-add)- [`reference list`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-reference-list)- [`reference remove`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-reference-remove)
## NuGet commands
- [`nuget delete`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-delete)- [`nuget locals`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-locals)- [`nuget push`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-push)- [`nuget add source`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-add-source) - [`nuget disable source`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-disable-source) - [`nuget enable source`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-enable-source) - [`nuget list source`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-list-source) - [`nuget remove source`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-remove-source) - [`nuget update source`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-update-source) - [`nuget verify`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-verify) - [`nuget trust`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-trust) - [`nuget sign`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-sign) - [`nuget why`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-nuget-why) 
## Workload management commands
- [`workload`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload) - [`workload clean`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-clean) - [`workload config`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-config) - [`workload install`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-install) - [`workload history`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-history) - [`workload list`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-list) - [`workload update`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-update) - [`workload restore`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-restore) - [`workload repair`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-repair) - [`workload uninstall`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-uninstall) - [`workload search`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-workload-search) 
## Advanced commands
- [`sdk check`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-sdk-check)
- [`msbuild`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-msbuild)
- [`build-server`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-build-server)
- [`dev-certs`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-dev-certs)
- [`dotnet install script`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-install-script)

## Tool management commands
Tools are console applications that are installed from NuGet packages and are invoked from the command prompt. You can write tools yourself or install tools written by third parties. Tools are also known as global tools, tool-path tools, and local tools. For more information, see [.NET tools overview](https://learn.microsoft.com/en-us/dotnet/core/tools/global-tools).

- [`tool install`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-install)- [`tool list`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-list)- [`tool update`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-update)- [`tool restore`](https://learn.microsoft.com/en-us/dotnet/core/tools/global-tools#install-a-local-tool)- [`tool run`](https://learn.microsoft.com/en-us/dotnet/core/tools/global-tools#invoke-a-local-tool)- [`tool uninstall`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-uninstall)- [`tool search`](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-search)


# Most used commands

