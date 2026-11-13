# SDK publication status

Current source layout and registry coverage. A GitHub download is distinct from publication on a central registry.

| Target | Status | Package / documentation |
| --- | --- | --- |
| CPP/vcpkg | published_custom_registry | fyrainput-keyboard-mouse |
| CPP/conan | published_custom_source_index | [fyrainput-keyboard-mouse](https://github.com/TitanCSA/sdk-packages/tree/089bc73095aa8eda89bacbe10d0b9e58394b0207/conan-index) [Source](packaging/native/) |
| CPP/nuget | account_email_confirmed_requires_matching_trusted_publishing_policy | FyraInput-Keyboard-Mouse.Native |
| NET/nuget | built_verified_requires_trusted_publishing_policy | FyraInputKeyboardMouse.SDK [Source](FyraInput-Keyboard-Mouse-NET-nuget/) |
| Python/pypi | built_fixture_and_production_verified | fyrainput-keyboard-mouse [Source](FyraInput-Keyboard-Mouse-Python-pypi/) |
| Python/conda-forge | custom_channel_install_verified_requires_conda_forge_review | [fyrainput-keyboard-mouse](https://raw.githubusercontent.com/TitanCSA/sdk-packages/089bc73095aa8eda89bacbe10d0b9e58394b0207/conda-channel) [Source](packaging/conda/) |
| Rust/cargo | published_install_verified | [fyrainput-keyboard-mouse](https://crates.io/crates/fyrainput-keyboard-mouse) [Source](FyraInput-Keyboard-Mouse-Rust-cargo/) |
| JavaScript/npm | registry_publication_requires_action | [fyrainput-keyboard-mouse](https://www.npmjs.com/package/fyrainput-keyboard-mouse) [Source](FyraInput-Keyboard-Mouse-JavaScript-npm/) |
| Java/maven | published_install_verified | [fyrainput-keyboard-mouse](https://central.sonatype.com/artifact/io.github.titancsa/fyrainput-keyboard-mouse/1.0.0) [Source](FyraInput-Keyboard-Mouse-Java-maven/) |
| Java/jitpack | published_install_verified | [fyrainput-keyboard-mouse](https://jitpack.io/#TitanCSA/FyraInput-Keyboard-Mouse-SDK/java-sdk-v1.0.0) [Source](FyraInput-Keyboard-Mouse-Java-maven/) |
| Go/modules | published_install_verified | [fyrainput-keyboard-mouse](https://pkg.go.dev/github.com/TitanCSA/FyraInput-Keyboard-Mouse-SDK/FyraInput-Keyboard-Mouse-Go-modules@v1.0.0) [Source](FyraInput-Keyboard-Mouse-Go-modules/) |
| Go/pkg-go-dev | indexed_verified | [Documentation](https://pkg.go.dev/github.com/TitanCSA/FyraInput-Keyboard-Mouse-SDK/FyraInput-Keyboard-Mouse-Go-modules@v1.0.0) |
| PowerShell/gallery | published_install_verified | [FyraInputKeyboardMouse](https://www.powershellgallery.com/packages/FyraInputKeyboardMouse/1.0.0) [Source](FyraInput-Keyboard-Mouse-PowerShell-gallery/) |
| Dart/pub-dev | published_install_verified | [fyrainput_keyboard_mouse](https://pub.dev/packages/fyrainput_keyboard_mouse) [Source](FyraInput-Keyboard-Mouse-Dart-pub-dev/) |
| Ruby/rubygems | published_install_verified | [fyrainput-keyboard-mouse](https://rubygems.org/gems/fyrainput-keyboard-mouse) [Source](FyraInput-Keyboard-Mouse-Ruby-rubygems/) |
| PHP/packagist | composer_source_and_tag_published | [titancsa/fyrainput-keyboard-mouse](https://packagist.org/packages/titancsa/fyrainput-keyboard-mouse) |

Native SDK source and CMake/Conan/vcpkg/NuGet recipes share [`packaging/native`](packaging/native/LAYOUT.md). Previous release archives and tags remain unchanged.

Application and driver prerequisites and original licensing remain those documented by each SDK. No driver installer is bundled with these source packages.
