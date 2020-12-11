# [![](../assets/img/logo-readme2.jpg)](https://devmentor.pl) &nbsp; React: Testing #04

> :loudspeaker: Jeśli chciałbyś więcej tego typu zadań to zapraszam do :moneybag: [wsparcia mojego konta](https://github.com/sponsors/devmentor-pl)!

&nbsp;

Komponent `<Auth>` zawiera implementację uwierzytelnienia użytkownika. Wykorzystujemy wewnątrz niego wcześniej już wykorzystywany `<LoginForm>`. Tym razem dane wpisywane do formularza są przekazywane do rodzica i tam sprawdzane.

W pliku `./src/db/users.js` mamy imitację bazy danych. Gdzie przechowujemy dane o użytkownikach. W celu zwiększenia bezpieczeństwa nie przechowujemy haseł jawnie zapisanych, tylko jako skrót MD5 ([nie jest to idealne rozwiazanie](https://www.md5online.org/blog/why-md5-is-not-safe/), ale lepsze takie niż żadne). W ten sposób przejęcie bazy danych nie powoduje od razu przejęcia haseł.

Aby móc sprawdzić czy dane wprowadzone w formularzu są prawidłowe przesyłam je do API, aby uzyskać hash MD5, który nastepnie porównuje z zawartością bazy danych. Pamiętaj, że to tylko "ćwiczenia". Przesyłanie haseł do zewnętrznych usług nie jest dobrym pomysłem. To rozwiązanie można by było wykonać po stronie aplikacji wykorzystując [natywne rozwiązanie](https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/digest) lub [swój algorytm](https://css-tricks.com/snippets/javascript/javascript-md5/).

Twoim zadaniem jest napisanie testów, które pozwolą sprawdzić czy uwierzytelnienie działa prawidłowo. Użyj `.spyOn()`, aby uniezależnić testy od zewnętrznej usługi.

&nbsp;

> :warning: Jeśli nie posiadasz materiałów do tego zadania to znajdziesz je na stronie [devmentor.pl](https://devmentor.pl)

