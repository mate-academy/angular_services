# Moonbase Control: Serwisy

Zadanie z modułu Angular. Repozytorium zawiera kod startowy aplikacji Moonbase Control dla tej lekcji.

## Zadanie

Przenieś dane misji z komponentu do serwisu.

Student powinien:

- wygenerować `MissionsService` przy pomocy Angular CLI,
- utworzyć model `Mission` oraz wymagane typy,
- przenieść statyczną listę misji do prywatnego sygnału w serwisie,
- udostępnić dane jako sygnał tylko do odczytu przy pomocy `asReadonly()`,
- wstrzyknąć serwis do komponentu `Missions` przy pomocy `inject()`,
- wyświetlić listę misji w szablonie wykorzystując `@for`.
💡 Komponent powinien odpowiadać wyłącznie za wyświetlanie danych. Lista misji nie powinna być przechowywana bezpośrednio w komponencie, lecz udostępniana przez serwis.

## Jak zacząć

1. Zrób fork tego repozytorium na swoje konto GitHub.
2. Sklonuj swój fork na komputer.
3. Zainstaluj zależności: `npm install`.
4. Uruchom aplikację: `npm start`.
5. Jeśli zadanie korzysta z danych z API, uruchom w drugim terminalu mock API: `npm run api`.

## Jak oddać zadanie

1. Zapisz zmiany w commicie i wypchnij je do swojego forka.
2. Otwórz Pull Request z forka do repozytorium `mate-academy/angular_services`, do brancha `main`.
3. Platforma uruchomi review Twojego Pull Requesta.
