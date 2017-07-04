# Chiron

[![Chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/xyncro/chiron?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build](https://ci.appveyor.com/api/projects/status/qrben1pugaxklsp3?svg=true)](https://ci.appveyor.com/project/xyncro/chiron)

## What is Chiron?

[Chiron][chiron] is a library for working with JSON for F#, similar to the Haskell Aeson package. See the dedicated [Chiron Site][chiron] for more information.

## Differences in this Branch

This branch removes the dependency on FParsec, using instead a short hand-rolled parser.

## Installation

Chiron can be installed from [NuGet](https://www.nuget.org/packages/chiron "Chiron on NuGet"). Using the Package Manager Console:

```batch
PM> Install-Package Chiron
```

## License

Chiron is under the MIT license.

[chiron]: https://xyncro.tech/chiron
