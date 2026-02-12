# MCBackpack Project Changes Report

## Project Changes Summary (876252e0ff63 → d7fd73429702)

### Feature Updates (newest first)

- **Model Data Applicator command added**: Introduced a `model data` applicator command with handler, listener, and tab-completion support to apply string-list Custom Model Data to backpacks; registered in `plugin.yml` for PaperMC.
- **Command syntax refinements**: Renamed the model data subcommand to `get` across handlers, tab completer, engine wiring, and `plugin.yml` for clarity.

### Build & Versioning

- **Iteration bumped to 11** in `gradle.properties` to reflect the latest feature set.

### Impact

- Players can now apply custom model data via a dedicated applicator workflow, aligning with 1.21.4 string-list support.
- Command naming is more consistent, and the plugin iteration now signals the new capability.

### Statistics

- **Total commits processed**: 3
- **Files touched**: Command handlers, listener, tab completer, engine entry, `plugin.yml`, `gradle.properties`.
- **Branch inspected**: mcbackpack-website (commit range newest-first ordering above).
