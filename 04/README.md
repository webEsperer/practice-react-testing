> :star: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s2e09-react-testing` (dotyczy [mentee](https://devmentor.pl/mentoring-javascript/)). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#04` React: Testowanie

Komponent `<Auth>` zawiera implementację uwierzytelnienia użytkownika. Wykorzystujemy wewnątrz niego wcześniej już używany `<LoginForm>`. Tym razem dane wpisywane do formularza są przekazywane do rodzica i tam sprawdzane.

W pliku `./src/db/users.js` mamy imitację bazy danych, w której przechowujemy dane o użytkownikach. W celu zwiększenia bezpieczeństwa nie przechowujemy haseł jawnie zapisanych, tylko jako skrót MD5 ([nie jest to idealne rozwiazanie](https://www.md5online.org/blog/why-md5-is-not-safe/), ale lepsze takie niż żadne). W ten sposób przejęcie bazy danych nie spowoduje od razu przejęcia haseł.

Aby sprawdzić, czy dane wprowadzone w formularzu są prawidłowe, przesyłamy je do API. W ten sposób uzyskujemy hash MD5, który następnie porównujemy z zawartością bazy danych.

Pamiętaj, że to tylko ćwiczenia. Przesyłanie haseł do zewnętrznych usług nie jest dobrym pomysłem. To rozwiązanie można by było wykonać po stronie aplikacji, wykorzystując [natywne rozwiązanie](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/digest) lub [własny algorytm](https://css-tricks.com/snippets/javascript/javascript-md5/).

Twoim zadaniem jest napisanie testów sprawdzających, czy uwierzytelnienie działa prawidłowo. Użyj `.spyOn()`, aby uniezależnić testy od zewnętrznej usługi.

&nbsp;

> :arrow_left: [*poprzednie zadanie*](./../03) | [*następne zadanie*](./../05) :arrow_right:
