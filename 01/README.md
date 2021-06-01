> :star: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s2e09-react-testing` (dotyczy [mentee](https://devmentor.pl/mentoring-javascript/)). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#01` React: Testowanie


W lokalizacji `./src/components/Task01.js` znajdziesz komponent, który renderuje formulrz.

Formularz ten jest renderowany przez komponent `<LoginForm>`.

W jego wnętrzu znajdziesz rzucanie wyjatkami (błędami), gdy dane wpisywane do formalarza są zbyt krótkie tj. ilość znaków jest mniejsza, bądź równa 3.

Twoim zadaniem jest obsługa tych błędów:
1. Gdy użytkownik wpisuje dane do formularza (`onChange`) to ma się pojawić stosowana informacja jeśli ilość wprowadzonych znaków będzie równa, bądź mniejsza jak 3 znaki. (użyj `try ... catch`)
2. Jeśli użytkownik wyśle nieprawidłowe dane (`onSubmit`) to ma się pojawić zamiast formularza element `<h1>` ze stosownym komunikatem. (użyj `.getDerivedStateFromError()`)

> **Uwaga** Pamiętaj, aby zainstalować wszystkie paczki zapisane w `package.json` przy pomocy `npm i`. Uruchomienie serwera jak zwykle odbywa się przez `npm start`.

&nbsp;

> :arrow_left: ~~*poprzednie zadanie*~~ | [*następne zadanie*](./../02) :arrow_right:
