# GoPackagesModules
Training for Modules/Packages in Go

"go install" - after changes

"export PATH=$PATH:$(dirname $(go list -f '{{.Target}}' .))" - to export the path

in package ReverseRunes not reverseRunes - Because ReverseRunes function begins with an upper-case letter, it is exported, and can be used in other packages that import our morestrings package.

Remote modules need a tidy - "go mod tidy"