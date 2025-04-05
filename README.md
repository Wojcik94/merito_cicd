# MeritoWebApp CI/CD

## Opis projektu
To repozytorium zawiera aplikację internetową napisaną w technologii .NET oraz zestaw testów jednostkowych z wykorzystaniem frameworka xUnit. Projekt służy do nauki automatyzacji procesów CI/CD z wykorzystaniem GitHub Actions oraz wdrażania aplikacji w środowisku chmurowym Microsoft Azure.

## Struktura projektu
- **MeritoWebApp**: Główna aplikacja internetowa.
- **MeritoWebApp.Tests**: Projekt testowy zawierający testy jednostkowe aplikacji.

## Wymagania
- .NET SDK w wersji 9.0 lub nowszej.
- Zainstalowane pakiety NuGet:
  - `xunit` (2.4.2)
  - `xunit.runner.visualstudio` (2.4.5)
  - `Microsoft.NET.Test.Sdk` (17.13.0)
  - `Newtonsoft.Json` (13.0.1)
  - `coverlet.collector` (6.0.2)

## Jak skonfigurować projekt
1. **Klonowanie repozytorium**  
   Sklonuj repozytorium na swój lokalny komputer:
   ```bash
   git clone <URL_REPOZYTORIUM>
   cd merito_cicd