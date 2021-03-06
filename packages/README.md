Packages
================

A package allows the creation of modular code that can easily be shared. For example, packages can enable use cases to make network requests, integrate with device APIs, and so on. The minimal components of a package include:

* **`pubspec.yaml`** A metadata file declaring package name, version, author, etc.

* **`lib`** The lib directory containing the package's public code and minimally contains a single `<package-name>.dart` file.

To implement a pure Dart package, you can either add the functionality inside `lib/<package name>.dart` or add the functionality in several files inside the `lib` directory.

This directory contains several examples of packages used with Flutter.
For more information on how to use or develop new packages, see the [Using Packages](https://flutter.dev/docs/development/packages-and-plugins/using-packages/) guide.

Shared Packages
===============================
Flutter supports users sharing their developed packages with the Flutter and Dart community.

Flutter packages are published to the ['pub.dev'](https://pub.dev/) website. Users can find the most downloaded and highly recommended Flutter and Dart packages.

Developing Packages
===============================
The Flutter community is a supportive and creative community that encourages its members to develop new packages if no package exists for their specific use case. Please be sure to review the ['Contributing to Flutter'](https://github.com/flutter/flutter/blob/master/CONTRIBUTING.md) page and the ['Code of Conduct'](https://github.com/flutter/flutter/blob/master/CODE_OF_CONDUCT.md) page for general contribution guidelines.

To write a new package, see the ['Developing Packages'](https://flutter.dev/docs/development/packages-and-plugins/developing-packages) page.

To see how to best organize the package contents see the ['Dart library package'](https://dart.dev/guides/libraries/create-library-packages) documentation page.

To test a package, see the ['Unit Tests'](https://flutter.dev/docs/testing#unit-tests) page for guidance.

To publish your package for others to use, see the [`Publishing Pakcages`](https://pub.dev/help/publishing) page.
