## Aquarius.FieldDataFramework Release Notes

This page highlights some changes in the field data framework.

Not all changes will be listed, but you can always [compare by version tags](https://github.com/AquaticInformatics/aquarius-field-data-framework/compare/v17.4.1...v17.4.0) to see the full source code difference.

### 17.4.2
- Added `/ExpectedStatus` and `/ExpectedError` options to `PluginTester.exe`, so that failure conditions of a plugin can also be tested. This can be useful to confirm that your plugin quickly returns `CannotParse` when asked to parse `Kitten.jpg`.

### 17.4.1
- Exit the `PluginTester.exe` with an error code if the plugin detects an error. This enables easy integration testing.

### 17.4.0
- For simplicity, changed the package version scheme to match the compatible AQTS version.
- Fixed a bug in the `PluginPackager.exe` so that a plugin can resolve its .NET dependencies correctly during the packaging step.

### 1.0.1
- Initial public release, compatible with AQTS 2017.4+.
