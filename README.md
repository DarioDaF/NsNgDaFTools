# NsNgDaFTools

This extension adds 3 CLI programs useful
for NativeScript Angular projects.

## How to launch them

Using relatively new versions of `npm`
the package `npx` is installed by default,
so to execute the CLI utility `x` (even if
only local) `npx x arguments...` is
sufficient.

## Utilities list

- _**NgLocalCM** [app]_: creates `_daf_comps`
and `_daf_mods` TypeScript glue code with
local components and submodules imports.
- _**NsNgComponentTemplate** component [module] [app]_:
creates a component with template and style
in the directory of _<module>_ or its own if not
speficied.
- _**NsNgModuleTemplate** module [app]_:
creates a module with relative router and local
component inclusion based uppon `_daf_comps`.
