# PKGREP

Backend for Skitter's package manager (WIP)

# What is this
`rats` (Rats Acquire Tools n' Stuff) is the package manager for Skitter.
It's WIP and is planned to be fairly simple:
- `rats find (name)` - searches for package (name) in the package repo
- `rats get (name)` - installs package (name)
- `rats update (name/all)` updates package (name) or all installed packages
- `rats upgraderats` - updates `rats`

Further future:
- `rats publish (name)` - publishes folder (name) as a package
- `rats genpkg` - generates a package template