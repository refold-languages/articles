---
title: "Jak skonfigurować Anki"
roadmapTitle: "Jak skonfigurować Anki"
sort: 3
---

Jak wytłumaczyliśmy w [Etapie 0: Aktywna Nauka][stage-0-active-study], będziemy korzystali z programu używającego metody wielokrotnych powtórzeń (MWP), aby nauczyć się słownictwa naszego języka docelowego.

Istnieje wiele programów MWP, ale my polecamy Anki. Jest to program darmowy, wieloplatformowy, bogaty w różne funkcje i darmowy dla większości platform. Jedyną jego wadą jest to, że trudno jest nauczyć się z niego korzystać. Jeśli nie jesteś pewien, jak działa Anki, nie martw się, po tygodniu lub dwóch mniej więcej zrozumiesz, o co chodzi. Większość tego artykułu będzie się koncentrować na wyjaśnieniu podstaw Anki. Aby ci pomóc szybkiej konfiguracji nie będziemy dokładnie tłumaczyć tego, co robią dane ustawienia lub czemu się na takie zdecydowaliśmy.

Pod koniec artykułu zapewnimy również pewne materiały zaawansowanym użytkownikom, którzy chcą głębiej zrozumieć Anki z innego punktu widzenia.

### Instalacja

Najnowsza stabilna wersja Anki może zostać pobrana ze [strony Anki][ankidownload]. Wersja na komputery jest w 100% darmowa i kompatybilna z systemem Windows, Mac i Linux.

Istnieje też oficjalna aplikacja na iOS, [AnkiMobile][ankimobile], którą można kupić w sklepie App Store za ~100zł (cena różni się w zależności od kraju). Dostępna też jest zewnętrzna aplikacja na Androida, [AnkiDroid][ankidroid], która jest darmowa w Google Play. Jest też wersja online: [AnkiWeb][ankiweb].

AnkiMobile, AnkiDroid i AnkiWeb są świetne do robienia powtórek, ale interfejs do tworzenia kart jest ograniczony. Na razie skoncentrujemy się na tym, jak dodać nowe karty do wersji na komputery.

Pozostała część tego artykułu skoncentruje się na skonfigurowaniu wersji Anki na komputery.

### Podstawy Anki

#### Talie

![](images/anki-decks.png)

Kiedy otwierasz Anki, pierwszą rzeczą, którą widzisz, jest lista talii. Początkowo będziesz mieć tylko jedną talię: "Domyślna".

Talie to po prostu grupy fiszek. Podczas nauki, możesz uczyć się jednocześnie tylko z jednej talii.

Możesz utworzyć nową talię naciskając przycisk "Utwórz talię" na dole. Możesz mieć tyle talii, ile chcesz, i nie ma ograniczenia ile kart może być w jednej talii.

Ogólnie rzecz biorąc, zalecamy stworzyć nie więcej niż dwie talie. Podział kart na wiele talii sprawia, że udzielanie prawidłowej odpowiedzi jest sztucznie łatwiejsze. Na przykład, jeśli posiadasz talię o nazwie „nazwy zwierząt”, podczas robienia powtórek w tej talii, twój mózg automatycznie wie, że odpowiedź musi być nazwą zwierzęcia. Ta „wskazówka” ułatwia ci przypominanie sobie odpowiedzi. Ponieważ nie będziesz mieć tego rodzaju wskazówek, na których można polegać w prawdziwym życiu, najlepiej jest uczyć się bez nich.

#### Notatki i karty

Różnica między notatkami i kartami jest najbardziej zagmatwaną częścią Anki. Nie martw się, jeżeli na początku wszystko wydaje ci się skomplikowane. Najważniejsze jest to, że już wiesz o istnieniu tego programu. Z czasem zaczniesz go lepiej rozumieć.

Najbardziej podstawową jednostką Anki jest „notatka”, która jest abstrakcyjnym pomysłem. Nie możesz ani dotykać ani trzymać notatki, co sprawia, że jest ona bardzo zagmatwanym pojęciem.

![](images/anki-note-data-entry.png)

Notatka jest zbiorem danych stanowiących wspólną całość. Możesz mieć na przykład pięć następujących typów danych:

* Pisana forma słowa w języku docelowym
* Zdanie, które używa tego słowa w kontekście
* Uproszczone tłumaczenie tego słowa na polski
* Audio native speakera wypowiadającego to słowo
* Zdjęcie znalezione w Google podczas wyszukiwania słowa

Tak więc notatka to te 5 typów danych połączonych ze sobą (niewidocznie).

Wartości te przekształcają się w fiszki (lub „karty” według Anki). Są to karty, które codziennie przeglądasz.

![](images/anki-cards-in-browser.png)

Podsumowując: notatka jest zbiorem danych, a dane są wykorzystywane do generowania jednej lub większej liczby kart.

Być może zastanawiasz się, jak te karty są tworzone, co prowadzi nas do kolejnego abstrakcyjnego pojęcia: typy notatek.

#### Typy Notatek

![](images/anki-note-types.png)

Typ notatki jest jeszcze bardziej abstrakcyjny niż notatka, a więc masz teraz pełne prawo czuć się skołowany tym pojęciem.

Typ notatki jest schematem dla notatek. Składa się on z:

* Nazwy
* Listy pól
* Zbioru typów kart

Aby przywołać powyższy przykład, nazwą notatki może być "Słownictwo", bo jest używana do tworzenia kart ze słownictwem.

![](images/anki-vocabulary-note-type.png)

Listą pól może być:

* Słowo
* Przykładowe zdanie
* Znaczenie
* Plik audio
* Zdjęcie

Każde pole jest symbolem zastępczym dla danych, które będą przechowywane w notatce.

#### Typy kart

Typy kart są szablonami wizualnymi, które Anki wypełnia danymi, aby wygenerować karty. Tutaj to ty decydujesz, jak będzie wyglądała karta i jakie dane będą wyświetlane na przedniej i tylnej stronie twoich kart. Anki umożliwia tworzenie wielu typów kart dla typu dla jednej notatki, ale nie zalecamy tego robić.

![](images/anki-vocabulary-card-type.png)

#### Podsumowując

* Notatka zawiera dane.
* Karta jest tym, co przeglądasz.
* Typ notatki opisuje, jakie dane notatka może przechowywać.
* Typ karty konfiguruje co jest wyświetlane na karcie.

Jeśli dokonasz zmiany typu notatki, wszystkie karty powiązane z tym typem notatki również natychmiast się zmienią. Jeśli następuje zmiana typu karty, wszystkie powiązane z nią karty również się zmienią.

Anki ma pięć typów notatek. Możesz modyfikować te typy notatek i tworzyć nowe typy. Aby zmodyfikować lub utworzyć nowy typ, przejdź do „Narzędzia > Zarządzaj typami notatek” z okna głównego Anki.

### Dodawanie kart

![](images/anki-add-note.png)

Anki, samo w sobie nie posiada żadnych materiałów do nauki. Zamiast tego tworzysz własne karty lub ściągasz talię z już wcześniej zrobionych kart.

Aby utworzyć nowe karty, otwórz okno dodawania klikając "Dodaj" w górnej części głównego okna Anki.

Na górze okna dodawania możesz wybrać typ notatki, który chcesz użyć, i w której talii chcesz żeby była. Następnie wypełnij odpowiednie pola i naciśnij „Dodaj”.

#### Wcześniej zrobione talie

Oprócz tworzenia własnych kart możesz pobierać talie wykonane przez innych ze [strony Anki][ankipremade].

Ponieważ każda karta jest zawsze powiązana z typem notatki, kiedy dodasz czyjąś talię do kolekcji, to zwykle będzie ona dostępna z nowym typem notatki. Ten typ notatki zostanie dodany do twojej kolekcji i będziesz mógł go używać podczas tworzenia nowych kart samodzielnie.

### Przeglądarka

![](images/anki-browser.png)

Przeglądarka jest miejscem, w którym możesz przeglądać wszystkie karty w swojej kolekcji i wprowadzać niezbędne zmiany.

Aby otworzyć przeglądarkę, kliknij przycisk "Przeglądarka" w górnej części głównego okna Anki.

Szukając kart w przeglądarce, możesz filtrować według talii, typu notatki lub tagów (oznaczeń). Możesz również użyć okna wyszukiwania.

Możesz zmodyfikować zawartość pola karty po prostu wybierając ją w oknie przeglądarki. Aby usunąć kartę lub przenieść ją do innej talii, kliknij prawym przyciskiem myszki na kartę i wybierz odpowiednią opcję.

### Preferencje

![](images/anki-preferences.png)

Preferencje są ustawieniami globalnymi, które wpływają na cały program Anki. Możesz uzyskać dostęp do preferencji, przechodząc do "Narzędzia > Preferencje…" w głównym oknie Anki.

Istnieje jedno ustawienie w Preferencjach, które zalecamy zmienić: "Pokaż następną porę przeglądu nad przyciskami odpowiedzi" w zakładce Planowanie. Gdy ta opcja jest włączona, podczas przeglądania kart, nad każdym przyciskiem będzie wyświetlać się informacja o tym, kiedy znowu zobaczysz daną kartę. Może to sprawić, że będziesz kwestionować swoją pamięć i oceniać się zbyt ostrożnie. Lepiej zaufać algorytmowi i nie martwić się o konkretne liczby.

Jeśli chcesz zsynchronizować swoją kolekcję Anki z kontem AnkiWeb, możesz to zrobić w zakładce "Sieć". Pozwoli to na synchronizację Anki z innych urządzeń.

### Opcje

Opcje to miejsce, w którym dostosowujesz specyfikację sposobu działania algorytmu Anki. Opcje są ustawione na poziomie poszczególnych talii.

Na górze okna opcji możesz zobaczyć, z której grupy obecnie korzystasz w danej talii. Grupa opcji to zestaw opcji. Możesz utworzyć grupę opcji dla każdej talii lub mieć wiele talii, które współdzielą jedną grupę opcji.

Jeśli używasz wielu talii, zalecamy utworzenie oddzielnej grupy opcji dla każdej talii. Możesz utworzyć nową grupę opcji, naciskając przycisk "Zarządzaj..." w prawym górnym rogu i wybierając przycisk "Dodaj".

### Zalecane Ustawienia

Domyślne ustawienia opcji, z którymi wiąże się Anki, są bardzo problematyczne. Ważne jest, aby dostosować je do nauki języka.

Oto ustawienia opcji, które zalecamy:

![](images/anki-decks.png)

![](images/anki-decks.png)

![](images/anki-decks.png) ![](images/anki-decks.png)

Jedyną opcją, którą zalecamy spersonalizować, jest ustawienie "Nowe karty/dzień" w zakładce "Nowe karty". Ta opcja kontroluje ile nowych kart Anki pokaże cię każdego dnia. Wyjaśnimy, jak określić, jaką wartość należy ustawić w jednym z kolejnych artykułów.

#### Naprawianie starych ustawień
Jeśli już jakiś czas korzystałeś z Anki, to musisz zaktualizować starsze karty i usunąć starsze dodatki.

Aby zaktualizować starsze karty, użyj dodatku [Refold Ease][refold-ease]. Domyślne ustawienia Refold Ease są wystarczająco dobre (chociaż jesteśmy świadomi 1% rozbieżności w modyfikacji odstępu między kolejnym zobaczeniem karty).

Jeśli masz zainstalowany którykolwiek z następujących dodatków, należy je usunąć:

1. No Penalties or Boosting
1. ResetEZ

### Nauka

![](images/anki-studying.png)

Aby uczyć się kart z talii, wybierz talię z głównego okna Anki i naciśnij „Ucz się Teraz”.

Podczas nauki Anki pokaże ci przednią stronę karty i pozwoli ci zobaczyć tył po naciśnięciu przycisku "Pokaż odpowiedź". Gdy tylna strona karty zostanie pokazana, zostaniesz poproszony o jej ocenę.

Przy ocenianiu karty w Anki jesteś proszony o wybranie do czterech różnych opcji: "Powtórz", "Trudne", "Dobrze" i "Łatwe".

(W przypadku powtórek zostaną wyświetlone wszystkie te opcje. W przypadku nowych kart wyświetlone zostaną tylko „Powtórz”, „Dobrze” i „Łatwe”. W przypadku zamkniętych kart pokazane będą tylko „Powtórz” i „Dobrze”

**Zalecamy używać WYŁĄCZNIE przycisków "Powtórz" i "Dobrze" oraz unikać przycisków "Trudne" i "Łatwe".**

![](images/anki-buttons-xd.png)

Przyciski „Trudne” i „Łatwe” mają zły wpływ na algorytm Anki, co powoduje długotrwałe problemy. Aby uzyskać więcej informacji na ten temat, prosimy zapoznać się z sekcją „Low-key Anki” na końcu tego artykułu.

### Statystyki

![](images/anki-stats.png)

Możesz zobaczyć różne statystyki dotyczące swojej nauki, klikając na "Statystyki" na stronie głównej Anki.

Najważniejszą statystyką jest twój „wskaźnik pamiętania”, czyli procent kart ocenianych przez ciebie jako „Dobre” lub „Łatwe”. Wskaźnik retencji jest pokazany w sekcji "Przycisk odpowiedzi" na stronie statystyk.

Wskaźnik ten jest podzielony na trzy kategorie: Uczone, Młode i Dojrzałe. „Uczone” oznacza karty będące w trakcie nauki. „Młode” to karty, których w pełni się nauczyłeś, ale nadal przeglądasz co najmniej raz na 20 dni. „Dojrzałe” karty przeglądasz tylko co 21 dni lub więcej.

Wskaźnik retencji ma znaczenie tylko dla kart Dojrzałych. Karty „uczone” są kartami, których jeszcze nie nauczyłeś, więc naturalne jest to, że ich nie pamiętasz. „Młode ” karty są kartami, których się niedawno nauczyłeś, a więc ich również nie osadziłeś jeszcze w pełni w swojej pamięci.

W kontekście nauki języków idealny wskaźnik pamiętania kart dojrzałych wynosi od 80 % do 90 %. Na etapie 1C: Najlepsze praktyki przedstawiamy zalecenia dotyczące sposobu postępowania ze wskaźnikiem retencji poza tym zakresem.


### Początkujący zatrzymajcie się tutaj

Pozostała część tego artykułu zawiera szczegółowe informacje na temat algorytmu Anki. Jeśli jesteś nowy w Anki, pomiń tę sekcję i przejdź do [następnego artykułu][stage-1b-phonetics].

### Zaawansowane użycie

Możesz otrzymać 90% optymalizacji Anki postępując zgodnie z powyższymi instrukcjami. Jeśli jednak chcesz w pełni zoptymalizować Anki, musisz dowiedzieć się, jak działa ich algorytm. Jeśli jesteś nowy w Anki, wróć do tej sekcji w ciągu miesiąca lub dwóch po osiągnięciu komfortu z tym programem.

#### Algorytm w pełni wyjaśniony

W poniższym filmiku w pełni wyjaśniamy algorytm Anki i skutki wszystkich różnych ustawień opcji.

* [Anki: Poradnik | Opcje talii i algorytm Anki][explanation-anki-algorithm]

### Podstawowy Opis Low-key Anki

Low-key Anki to popularna modyfikacja algorytmu Anki w społeczności Refold. W kontekście nauki języka Low-key Anki znacznie poprawia skuteczność algorytmu poprzez unikanie wielu pułapek, które możemy napotkać bez tego dodatku.

Low-key Anki zostało już uwzględnione w powyższych częściach artykułu. Pilnując się tych zalecanych ustawień i postępując zgodnie z instrukcjami robienia powtórek, uzyskasz pełne korzyści z Low-key Anki.

Jeśli chcesz zrozumieć logikę leżącą u podstaw Low-key Anki, przeczytaj [tę serię artykułów][explanation-lowkey-anki].

### Szczegółowy Opis Low-key Anki

Low-key Anki składa się z dwóch elementów: używanie jedynie przycisków „Powtórz” i „Dobrze” oraz na usunięciu wszystkich ułatwień. Jak wyjaśniliśmy w serii powyższych artykułów, początkowo, zostało to wdrożone przy użyciu dodatku, który uniemożliwił Anki zmianę współczynnika łatwości kart niezależnie od tego, jak oceniono karty. Jednakże można też wdrożyć Low-key Anki bez użycia żadnych dodatków.

W Anki minimalny współczynnik łatwości, jaki może mieć karta, wynosi 130%. Gdy współczynnik łatwości karty osiągnie 130%, nigdy się on nie zmniejsza, nawet jeśli karta jest oceniona jako „Powtórz” lub „Trudna”. Zatem dzięki ustawieniu czynnika łatwości kart na 130%, zakładając, że użytkownik nigdy nie używa przycisku „Łatwe”, współczynnik łatwości kart nigdy się nie zmieni. Ponieważ współczynnik łatwości zaczyna się na minimalnej wartości, przyciski „Powtórz” i „Trudne” nie zmniejszą czynnika łatwości, a przycisk "Dobrze" nigdy nie zmienia czynnika łatwości.

Niska łatwość startowa może być przesunięta przez wydłużenie modyfikatora odstępu do 192%. Zapewni to taki sam przedział czasowy jak łatwość początkowa 250% i modyfikator odstępów 100%.

Niestety, istnieje błąd w Anki 2.1.35, który powoduje, że wszystkie karty ze współczynnikiem łatwości 130% są resetowane na 250% owego współczynnika. Zmieniliśmy minimalną łatwość na 131% i modyfikator odstępu 191%, aby uniknąć tego błędu.

Ta bezpłatna wersja Low-key Anki jest tym, co zostało uwzględnione w ustawieniach zalecanych powyżej opcji.

[ankidownload]: https://apps.ankiweb.net/
[ankidroid]: https://play.google.com/store/apps/details?id=com.ichi2.anki&hl=en_US
[ankimobile]: https://apps.apple.com/us/app/ankimobile-flashcards/id373493387
[ankiweb]: https://ankiweb.net/
[ankipremade]: https://ankiweb.net/shared/decks/
[explanation-anki-algorithm]: https://www.youtube.com/watch?v=lz60qTP2Gx0
[explanation-lowkey-anki]: https://web.archive.org/web/20210203165239if_/https://massimmersionapproach.com/table-of-contents/anki/low-key-anki/intro/
[refold-ease]: https://ankiweb.net/shared/info/819023663
[stage-0-active-study]: /roadmap/stage-0/c/active-study
[stage-1b-phonetics]: /roadmap/stage-1/b/phonetics
