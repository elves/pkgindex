# Elvish Package Index

This is the Elvish package index, a catalog of packages installable by the
Elvish package manager `epm`.

Each package is described by a file under the `pkg` directory of this
repository. Package names may contain slashes. For instance, the package
`elves/acme` is described by the file `pkg/elves/acme`.

One package corresponds to a Git URL.

The package description file should contain a JSON object containing the
following fields:

*   `url`: A Git URL that can be used to clone the package.

*   `description`: A description of the package.
