# go_workspace_tutorial

Things I learned:
* Go workspaces can be used to declare dependency directives across multiple modules
* `go work init {DIRECTORY}` creates a Go workspace that is connected to the modules in `{DIRECTORY}`
* Executing `go work use {DIRECTORY}` from a workspace directory adds the files in `{DIRECTORY}` to the workspace file
* Executing `go run {DIRECTORY}` from a workspace directory runs the target module with workspace dependencies
* Executing `go build {DIRECTORY}` from a workspace directory builds the target module with workspace dependencies