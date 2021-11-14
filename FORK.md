# Fork Changes

Default wiring parse behaviour `packages.LoadAllSyntax` was changed to `packages.NeedName | packages.NeedFiles` to
reduce execution time for our needs, This **must** be generalized properly.