# GoPackagesModules
Training for Modules/Packages in Go

"go install" - after changes

"export PATH=$PATH:$(dirname $(go list -f '{{.Target}}' .))" - to export the path