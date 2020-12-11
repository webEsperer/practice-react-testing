# [![](../assets/img/logo-readme2.jpg)](https://devmentor.pl) &nbsp; React: Testing #01

> :loudspeaker: Jeśli chciałbyś więcej tego typu zadań to zapraszam do :moneybag: [wsparcia mojego konta](https://github.com/sponsors/devmentor-pl)!

&nbsp;

W lokalizacji `./src/components/Task01.js` znajdziesz komponent, który renderuje formulrz.

Formularz ten jest renderowany przez komponent `<LoginForm>`.

W jego wnętrzu znajdziesz rzucanie wyjatkami (błędami), gdy dane wpisywane do formalarza są zbyt krótkie tj. ilość znaków jest mniejsza, bądź równa 3.

Twoim zadaniem jest obsługa tych błędów:
1. Gdy użytkownik wpisuje dane do formularza (`onChange`) to ma się pojawić stosowana informacja jeśli ilość wprowadzonych znaków będzie równa, bądź mniejsza jak 3 znaki. (użyj `try ... catch`)
2. Jeśli użytkownik wyśle nieprawidłowe dane (`onSubmit`) to ma się pojawić zamiast formularza element `<h1>` ze stosownym komunikatem. (użyj `.getDerivedStateFromError()`)

> **Uwaga** Pamiętaj, aby zainstalować wszystkie paczki zapisane w `package.json` przy pomocy `npm i`. Uruchomienie serwera jak zwykle odbywa się przez `npm start`.


> :warning: Jeśli nie posiadasz materiałów do tego zadania to znajdziesz je na stronie [devmentor.pl](https://devmentor.pl)