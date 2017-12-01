# Pingy Scaffolds

> This is an index of Scaffolds for Pingy.

Please feel free to add your own by creating a PR.

Once a scaffold has been added to this repo then you can use it by running the
command:

```
pingy scaffold [alias]
```

Use your scaffold's `alias` as the key for each entry in `scaffold.json`. Use
the dash (`-`) character to separate multiple words in the alias (e.g..
`bootstrap-jumbotron`). Here's an example of a scaffold entry:

```json
"bootstrap-jumbotron": {
    "title": "Bootstrap Jumbotron",
    "type": "static",
    "description": "Super simple scaffold for Bootstrap 4 beta jumbotron and SCSS",
    "url": "pingyhq/pingy-scaffold-bootstrap-jumbotron"
}
```

Each scaffold should have the following properties:

* **title**: Short title
* **type**: (can be `"web"` or `"static"`). Pingy supports dynamic scaffolding
  using a _web_ browser or _static_ scaffolding using just the CLI.
* **description**: Longer description
* **url**: Git URL. For Github URLs you can use `user/repo`.
