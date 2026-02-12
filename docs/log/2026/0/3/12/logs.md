# MCBackpack Project Changes Report

## Project Changes Summary (efbf6fd5705b412c32d4b5a7d0a89f7077fffc9a → 65c89bacc548)

### Feature Updates (newest first)

- **Update check via mcutil**: Added mcutil-powered update checking in the PaperMC engine so servers are notified when a new release is available.
- **Plugin version surfaced**: Exposed the plugin version from build metadata for consistent reporting and logging.
- **Version source fix**: MCBackpack now reads the plugin meta version to avoid mismatches in reported versions.

### Build & Versioning

- **Dependency added**: Included mcutil in `platform/papermc/engine/build.gradle` to support update checking.
- **Cleanup**: Removed trailing blank lines in `gradle.properties` during merge housekeeping.

### Impact

- Servers receive automatic update availability signals with accurate version information.
- Version reporting is centralized and aligned with plugin metadata; build files stay tidy.

### Statistics

- **Total commits processed**: 5
- **Files touched**: `platform/papermc/engine/MCBackpack.java`, `platform/papermc/engine/build.gradle`, `gradle.properties`.
- **Branch inspected**: master (mcbackpack).
