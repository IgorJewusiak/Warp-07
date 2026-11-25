[![Build](https://github.com/IgorJewusiak/Warp-07/actions/workflows/build.yml/badge.svg)](https://github.com/IgorJewusiak/Warp-07/actions/workflows/build.yml)

## Continuous Integration

Workflow uruchamia się automatycznie przy `push` i `pull_request`.
Sprawdza projekt `Warp07.Demo` w środowisku `.NET 10.0.x`.

Kroki:
- sprawdzenie struktury repozytorium (`check-repository.sh`)
- przywrócenie zależności (`dotnet restore`)
- zbudowanie projektu (`dotnet build`)
- publikacja aplikacji (`dotnet publish`)
