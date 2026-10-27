# CityBike Service Dashboard

A minimal static website used to practice Git, GitHub and automated quality checks.

## Open the site

Open `index.html` in a browser. No server is required.

> Python 3 and Git are the only tools needed for the offline lab.

## Classroom rules

- Work on a branch for each feature.
- Read your changes before committing.
- Never commit personal passwords, access tokens or `.env` files.

## Release policy

Before constructing a release, it is paramount and part of our functional policy to run the tests for the projects.

```sh
python -m unittest discover -s tests -v

```
Peer review: checked README clarity.

## How we verify releases

The test, `test_site`, composes of checking for structural integrity, existence of the CSS file as well as the nonexistence of merge conflict signatures or sensitive data.
