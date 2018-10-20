# LibreContent.de Web

Quellcode-Dateien für die Webseite librecontent.de

Lizenz für ./web/*.md - https://github.com/redcctshirt/librecontent.de/blob/master/LICENSE

### mdbook

#### Vorbereitung 

* Rust installieren
* mdbook installieren: `cargo install mdbook`

#### Anwendung

```
# Vorschau http://localhost:3000
cd web
mdbook build
mdbook serve

# mdbook erstellen (statische Webseite)
cd web
mdbook build
```

#### Software

* [mdbook](https://github.com/rust-lang-nursery/mdBook), Lizenz: [Mozilla Public License v2.0](https://github.com/rust-lang-nursery/mdBook/blob/master/LICENSE), [contributors](https://github.com/rust-lang-nursery/mdBook/graphs/contributors)
* http://fontawesome.io created by [Dave Gandy](https://twitter.com/davegandy), licensed under [SIL OFL 1.1](http://scripts.sil.org/OFL), Code licensed under [MIT License](http://opensource.org/licenses/mit-license.html)

