# Minimal setup of typescript library
This directory contains a minimal setup for a basic hello-world library done in typescript.

## Remarks
- `tsconfig.json` defines where the compiled javascript will be put.
    - Here you specify input (source code) and output (compiled files) directories.
    - Notice that in `tsconfig.json` you also need to enable publishing `declarations` to be able to import this library in ts project.
- `package.json` defines the structure of the library:
    - `main` field specifies the entry point,
    - `types` field is used by ts to find types declarations,
    - `files` field is used to whitelist all compiled files.
