# Fork Changes

Default wiring parse behaviour `packages.LoadAllSyntax` was changed to `packages.NeedName | packages.NeedFiles` to
reduce execution time for our needs, This **must** be generalized properly.

The module name was updated to have ability to insatll it via `go install`.