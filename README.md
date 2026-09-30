# Secret Archive

This repository is a collection of Minecraft versions and related web builds archived from the `secret-stuff` repositories.

The collection currently ranges from **Minecraft C0.30 through Minecraft 26.2**, preserving different versions and builds in one place.

## Minecraft Versions

The archive includes versions ranging across Minecraft's history, including:

* Minecraft C0.30
* Minecraft Indev
* Minecraft Alpha 1.2.6
* Minecraft Beta 1.3_01
* Minecraft Beta 1.7.3
* Minecraft 1.8.8 / EaglercraftX
* Minecraft 1.12.2
* Minecraft 1.13.2
* Minecraft 1.14.4
* Minecraft 1.16.5
* Minecraft 26.2

Additional builds and versions may be included as the archive is updated.

## Repository Structure

Each archived repository has its own directory containing its current `index.html`:

```text
secret-archive/
├── secret-stuff/
│   └── index.html
├── secret-stuff-v2/
│   └── index.html
├── secret-stuff-v3/
│   └── index.html
├── ...
└── secret-stuff-v13/
    └── index.html
```

The complete contents of all archived repositories are also packaged into a ZIP archive and published through GitHub Releases.

## Source Repositories

The archive is built from the following repositories:

* `secret-stuff`
* `secret-stuff-v2`
* `secret-stuff-v3`
* `secret-stuff-v4`
* `secret-stuff-v5`
* `secret-stuff-v6`
* `secret-stuff-v7`
* `secret-stuff-v8`
* `secret-stuff-v9`
* `secret-stuff-v10`
* `secret-stuff-v11`
* `secret-stuff-v12`
* `secret-stuff-v13`

The GitHub Actions workflow automatically fetches the repositories, updates their archived `index.html` files, creates a complete ZIP archive, and publishes the archive as a GitHub Release.

## Archive

The ZIP release contains the complete contents of each source repository at the time the archive was created.

Each repository is stored under its own directory inside the archive:

```text
secret-archive-all/
├── secret-stuff/
├── secret-stuff-v2/
├── secret-stuff-v3/
├── secret-stuff-v4/
├── secret-stuff-v5/
├── secret-stuff-v6/
├── secret-stuff-v7/
├── secret-stuff-v8/
├── secret-stuff-v9/
├── secret-stuff-v10/
├── secret-stuff-v11/
├── secret-stuff-v12/
└── secret-stuff-v13/
```

## Updates

The archive can be manually updated through the GitHub Actions workflow. Each run creates a new archive containing the current contents of the source repositories.

## Purpose

The purpose of this repository is to keep the different Minecraft versions and builds together as a historical collection, making it easier to preserve and access the versions represented by the `secret-stuff` repositories.
