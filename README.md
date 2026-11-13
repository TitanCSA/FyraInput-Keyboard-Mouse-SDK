# FyraInput-Keyboard-Mouse SDK packages

Public Windows x64 user-mode SDK source packages. These folders contain the existing SDK and its licenses; no kernel driver, activation secret or installer is included.

- [Native SDK source and recipes](https://github.com/TitanCSA/sdk-packages/blob/main/projects/FyraInput-Keyboard-Mouse/packaging/native/README.txt)
- [Registry status](SDK-PUBLICATION.md)

Downloadable release artifacts do not imply publication on a central package registry.

<!-- central-sdk-packages:start -->
## Paquets et installation

Les sources, licences, guides API et exemples sont regroupes dans [le depot SDK dedie](https://github.com/TitanCSA/sdk-packages/tree/main/projects/FyraInput-Keyboard-Mouse). Choisis le paquet a installer puis execute sa commande dans son dossier.

| Registre | Paquet | Installation / utilisation |
| --- | --- | --- |
| vcpkg | `fyrainput-keyboard-mouse` | `vcpkg install fyrainput-keyboard-mouse:x64-windows` |
| Conan | `fyrainput-keyboard-mouse` | `conan install --requires=fyrainput-keyboard-mouse/0.1.0 -r titancsa --build=missing -s compiler.cppstd=17` |
| NuGet | `FyraInput-Keyboard-Mouse.Native` | `Install-Package FyraInput-Keyboard-Mouse.Native -Version 0.1.0` |
| NuGet | `FyraInputKeyboardMouse.SDK` | `dotnet add package FyraInputKeyboardMouse.SDK --version 1.0.0` |
| PyPI | `fyrainput_keyboard_mouse` | Commande prevue apres publication : `python -m pip install fyrainput-keyboard-mouse==1.0.0` |
| Conda | `fyrainput-keyboard-mouse` | `conda install --override-channels -c https://raw.githubusercontent.com/TitanCSA/sdk-packages/089bc73095aa8eda89bacbe10d0b9e58394b0207/conda-channel -c conda-forge fyrainput-keyboard-mouse` (canal TitanCSA) |
| crates.io | `fyrainput_keyboard_mouse` | `cargo add fyrainput-keyboard-mouse@1.0.0` |
| npm | `fyrainput_keyboard_mouse` | `npm install fyrainput-keyboard-mouse@1.0.0` |
| Maven Central | `io.github.titancsa:fyrainput-keyboard-mouse` | `io.github.titancsa:fyrainput-keyboard-mouse:1.0.0 (pom.xml / Gradle)` |
| JitPack | `com.github.TitanCSA:FyraInput-Keyboard-Mouse-SDK` | `com.github.TitanCSA:FyraInput-Keyboard-Mouse-SDK:java-sdk-v1.0.0 (avec le depot JitPack)` |
| Go Modules | `github.com/TitanCSA/FyraInput-Keyboard-Mouse-SDK/FyraInput-Keyboard-Mouse-Go-modules` | `go get github.com/TitanCSA/FyraInput-Keyboard-Mouse-SDK/FyraInput-Keyboard-Mouse-Go-modules@v1.0.0` |
| pkg.go.dev | `github.com/TitanCSA/FyraInput-Keyboard-Mouse-SDK/FyraInput-Keyboard-Mouse-Go-modules` | `Documentation : https://pkg.go.dev/github.com/TitanCSA/FyraInput-Keyboard-Mouse-SDK/FyraInput-Keyboard-Mouse-Go-modules@v1.0.0` |
| PowerShell Gallery | `fyrainput_keyboard_mouse` | `Install-Module FyraInputKeyboardMouse -RequiredVersion 1.0.0 -Scope CurrentUser` |
| pub.dev | `fyrainput_keyboard_mouse` | `dart pub add fyrainput_keyboard_mouse:1.0.0` |
| RubyGems | `fyrainput_keyboard_mouse` | `gem install fyrainput-keyboard-mouse -v 1.0.0` |
| Packagist | `fyrainput_keyboard_mouse` | Commande prevue apres publication : `composer require titancsa/fyrainput-keyboard-mouse:1.0.0` |

Pour vcpkg et Conan, configure d abord le registre TitanCSA avec [le guide complet](https://github.com/TitanCSA/sdk-packages/tree/main/projects/FyraInput-Keyboard-Mouse/README.md). Le guide explique aussi Maven/Gradle, les prerequis et le chargement des DLL. Les pilotes/applications du produit sont installes separement. Les commandes marquees prevues ne sont pas encore disponibles.

Les anciens imports Go et versions JitPack gardent leurs tags. Pour les anciennes archives SDK, utilise [les liens de remplacement](https://github.com/TitanCSA/sdk-packages/blob/main/release-assets/URL-MIGRATION.json).
<!-- central-sdk-packages:end -->
