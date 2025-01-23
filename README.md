# BiedaProjektSpringTomaszDural

**BiedaProjektSpringTomaszDural** to prosty projekt webowy stworzony w technologii **Spring Boot** z użyciem **Thymeleaf** jako silnika szablonów. Celem tego projektu jest zaprezentowanie podstawowej aplikacji webowej, która dynamicznie renderuje stronę HTML, korzystając z technologii Spring oraz Thymeleaf.

## Spis treści

- [Opis projektu](#opis-projektu)
- [Wymagania](#wymagania)
- [Instalacja](#instalacja)
- [Uruchamianie aplikacji](#uruchamianie-aplikacji)



## Opis projektu

Projekt **BiedaProjektSpringTomaszDural** jest aplikacją opartą na Spring Boot, która:

- Używa Thymeleaf do renderowania dynamicznych stron HTML.
- Zawiera przykład wykorzystania zmiennych w szablonach Thymeleaf.
- Obsługuje zasoby statyczne takie jak obrazy i pliki CSS.

## Wymagania

Aby uruchomić ten projekt, upewnij się, że masz zainstalowane następujące technologie:

- **JDK 21** lub wyższy.
- **Maven**.
- **IDE**: IntelliJ IDEA lub inne IDE wspierające Java i Spring Boot.

## Instalacja

1. **Sklonuj repozytorium**:

   ```bash
   git clone https://github.com/DuralTxStudent/BiedaProjektSpringTomaszDural.git

2. Przejdź do katalogu projektu:
```
   cd BiedaProjektSpringTomaszDural
```
3. Zbuduj projekt:
```
   mvn clean install
```
## Uruchamianie aplikacji

Aby uruchomić aplikację, masz kilka opcji:
1. Za pomocą IntelliJ IDEA:

    Otwórz projekt w IntelliJ IDEA.
    Kliknij prawym przyciskiem myszy na klasę główną z adnotacją @SpringBootApplication.
    Wybierz Run.

2. Za pomocą terminala:
```
   mvn spring-boot:run
```
Po uruchomieniu aplikacji, będzie ona dostępna pod adresem: http://localhost:8080.
