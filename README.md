# Project Calzone Documentation
This project is using MKDocs as it's documentation site generator.

# Contribution
You don't need to ask permision to contribute, though if you are unsure of something, something's wrong, is confusing, or needs more clarification. Please [file an issue on GitHub](https://github.com/TailTwistStudios/Project-Calzone-Docs/issues) so we can address it.

# Using MKDocs To contribute
Because the documentation consists almost entirely out of markdown files, you don't need any other tools other than git and a text editor to contribute. Though if you'd like to export the static site or have a live usable version while you contribute; you'll need to use MKDocs.

Make sure you have Python installed and use `pip install mkdocs-material` to install the required packages, updating pip if needed.

Once installed, use `mkdocs serve` to genearte a live preview. View the preview by going to `localhost:8000` in your web browser. To export a hostable version use `mkdocs build`. This will make a ready-to-host version available in the `site/` directory.