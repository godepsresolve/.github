# Godepsresolve

It's an educational group of projects to show how Go dependencies are resolved in practice.

# Regular dependency resolving

Go uses [Minimal version selection](https://go.dev/ref/mod#minimal-version-selection) algorithm. In practice you can find it in [mainservice](https://github.com/godepsresolve/mainservice).

# Replaced dependency resolving

Go describes alghorithm [here](https://go.dev/ref/mod#mvs-replace). Repository that shows it in practice is [mainservice_replace_fork](https://github.com/godepsresolve/mainservice_replace_fork).
