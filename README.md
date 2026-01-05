# Latex Codespaces Project Template

Create a repository from this template and within this repository start a Github Codespace.
There you can edit and build your latex project (using the *latexmk (latexmkrc)* recipe).

Alternatively you can run this dev container locally following this guide for [Docker Engine installation](https://docs.docker.com/engine/install/) (better would be a less-intrusive container runtime, but unfortunately docker is the official one).
Installing the VS Code *Dev Containers* extension by Microsoft and then opening the project folder in a container.

You can also import the project into your Overleaf Account, if you have Overleaf Pro access and connected your Github account to it.
Though, this will require manual pushing and pulling of changes in Overleaf to sync the Github repository.

TODO: figure out a way to automate syncronization with Overleaf using the Overleaf git (instead of GitHub) integration + Github actions to automatically pull and push changes to and from a (private) dev container enabled Github repository at a specified interval.
