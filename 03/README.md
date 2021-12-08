> :star: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s2e09-react-testing` (dotyczy [mentee](https://devmentor.pl/mentoring-javascript/)). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#03` React: Testowanie


Twoim zadaniem jest napisanie testów dla komponentu `<Md5Form>` z wykorzystaniem `.spyOn()`.

Sprawdź przynajmniej kilka rzeczy:
- czy tekst wprowadzony do pola formularza pojawia się w elemencie o klasie `.data-text`
- czy wysłanie formularza (event `submit`) powoduje wczytanie pobranych danych do elementu o klasie `.data-md5`
- czy zmiana danych w `<input>` powoduje wyczyszczenie zawartości elementu `.data-md5`

> *Możesz użyć [container + .querySelector()](https://testing-library.com/docs/queries/about/#manual-queries) – pamiętaj tylko, aby nie nadużywać w swoich testach tego rozwiązania!*

&nbsp;

> :arrow_left: [*poprzednie zadanie*](./../02) | [*następne zadanie*](./../04) :arrow_right:
