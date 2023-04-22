# Task 1

## Subtask 1

9 punktów


## Subtask 3

Cześć, 
Jestem Wiola. Zdecydowałam się na udział w projekcie, ponieważ potrzebuję określić kierunek, w którym chcę się rozwijać. Doskwiera mi stagnacja związana z brakiem nowych możliwości na obecnym stanowisku, nie chcę jednak skoczyć na głębię bez uprzedniego przygotowania. Oczekuję, że kurs w praktyczny sposób przygotuje mnie do nowej pracy i wyzwań, które na mnie czekają, oraz że moja kreatywność znajdzie w nich pole do popisu. Wiem, że jak każdy zawód, ten też ma swoje plusy i minusy, ale jak to się mówi, kto nie ryzykuje szampana nie pije. 

*Wiola*


## Subtask 4

Aplikacja Scouts Test ma za zadanie tworzenie profilu zawodnika piłki nożnej, a następnie na podstawie meczy, w których bierze udział tworzone są raporty dotyczące jego zachowania, atrybutów i skuteczności. Każdy raport można ocenić, co potem przedkłada się na średnią ocenę zawodnika. Każdego dodanego do aplikacji zawodnika można porównywnać z innymi graczami. Można wyszukać graczy na podstawie konkternych cech - imię/nazwisko.....

Funkcjonalności:
* Logowanie do systemu - służy do uzyskania dostępu do funkcji aplikacji - intuicyjne, bardzo prosty wygląd, 

* Dodanie nowego gracza - zakłada profil dla danego zawodnkika, uwzględnia jego dane osobowe, cechy i umiejętności, umożliwia zapisanie jego danych kontaktowych oraz wstawienia linków do profilu na fb, filmów yt i innych stron - intuicyjna, ale niezabezpieczona przed złą wolą osoby zakładającej profil - szczegółowe informacje znajdują się przy akapicie z błędami,

* Przeglądanie meczy - opcja pojawia się po wybraniu zawodnika, zawiera listę meczy, w których brał udział zawodnik, z tego panelu można stworzyć raport prezentujący zachowanie gracza na boisku - intuicyjne jeśli chodzi o samo dodanie meczu, jednak panel z boiskiem jest mniej zrozumiały, jak również funkcja nie jest zabezpieczona przez złą wolą użytkownika, szczegółowe informacje znajdują się w akapicie z błędami,

* Przeglądanie raportów - opcja pojawia się po wybraniu zawodnika, zawiera listę raportów zapisanych dla gracza oraz możliwość edycji każdego - dodanie raportu jest intuicyjne, jednak poruszanie się po arkuszu już nie jest, zwłaszcza gdy chodzi o mapę z działaniami zawodnika,

* Przeglądanie zawodników - wyświetla listę zawodników zapisanych w aplikacji, pozwala na wygenerowanie i zapis pliku oraz wydruk - nie wszystkie jej elementy są intuicyjne - w nagłówku pojawia się panel umożliwiający wyszukiwanie zawodnika, klawisz enter służy do aktywacji polecenia jednak lupa przy panelu nie działa **jak to się sprawdza w aplikacji mobilnej?** - ta funkcja jest łatwiej dostrzeglana mimo iż filtrowanie działa na podobnej zasadzie i jest lepszą wersją tej funkcji, nie jest jednak dostatecznie wyróżniona - znajduje się na końcu łańcuszka poleceń oznaczonych szarym kolorem; dodałanym możliwość wybrania strony, na którą chcę przejść ręcznie i możliwość zmiany liczby zawodników wyświetlanych na stronie.

* Zmiana języka - służy do przetłumaczenia strony, oferuje języki Polski oraz Angielski - intuicyjna, jednak nie wszystkie elementy strony podlegają translacji, co należy poprawić,

* Wylogowanie - służy do opuszczenia aplikacji - intuicyjna, nie ma potrzeby wprowadzania zmian, ewentualnie można dodać komunikat na zasadzie popup box na wypadek gdyby został kliknięty nieumyślnie 'Czy na pewno chcesz opuścić stronę?',

* Ostatnie zmiany - panel, na którym widać informację o ostatnio dodanych zawodnikach, meczach i raportach - intuicyjnu, ułatwia przemieszczanie się w obrębie ostatnio dodanych elementów, bez konieczności ich ręcznego wyszukiwania,



Interfejs jest prosty, mało porywający. Przemieszczanie się pomiędzy głównymi opcjami jest sprawne, aplikacja wygląda poprawnie zarówno na ekranie komputera jak i smartfona z pewnymi zastrzeżeniami

Aplikacja jest intuicyjna do momentu tworzenia raportów. 


Błędy:
* wykrywa zły adres e-mail, ale za krótki nr telefonu już nie,
* umożliwia dodanie ujemnego lub zbyt wysokiego wzrostu (np. 600cm), ujemnej wagi, kolor koszulki, który jest cyfrą lub ujemny, gracz może mieć ponad sto lat lub być nieletni,
* ograniczenie czasu trwania meczu - możliwość dodania meczy o bardzo długim czasie trwania,
* mapa - rzut rożny możliwy ze środka boiska, można dodać kilka odległych akcji w bardzo krótkim odstępie czasu,
* przy zakładaniu profilu zawodnika możliwe jest dodanie imienia składającego się ze znaków, które nie występują w imionach oraz długich informacji, które podczas wyszukiwania nie są zwijane/skaracane,
* dodano kilku graczy, jednak nie przypisano im meczy ani nie wygenerowano raportów - gracze nie zostali zapisani mimo pozytywnej informacji zwrotnej z systemu, z można jednak stworzyć pusty raport bez oceny zawodnika i komentarzy, który figuruje na liście,
* przy generowaniu raportu z meczu czasem tworzy się duplikat - nie ma możliwości jego usunięcia,
* pole 'województwo' jest wymagane do stworzenia raportu jednak możliwe jest dodanie zawodnika, dla którego ten atrybut jest pusty,
* data urodzenia zawodnika i data meczu może być taka sama, dodaje mecze z przyszłości i bardzo dalekiej przeszłości, zawodnik może nie być pełnoletni (może urodzić się w dniu meczu, w którym gra), może także brać udział w meczu, przed swoim narodzeniem,
* dla gracza może być przypisana pozycja, której nie ma na boisku - np. Jedi,
* przy najechaniu kursorem na ikonę nie zawsze otrzymujemy informację, co ona robi,
* niektóre polecenia nie ulegają translacji przy zmianie języka - save, submit, clear, print - konieczne zachowanie pewnej konsekwencji,
* w przypadku meczu 2:1 istnieje możliwość przypisania wszystkich goli dla naszego zawodnika - czy aplikacja rozróżnia bramkę samobójczą od zwykłej? mimo wszystko skuteczność 100%...
* drużyna zawodnika i przeciwna mogą być takie same,
* odpowiedzi z serwera HTTP informują o użyciu przestażałych parametrów,
* w przypadku generowania widoku dla smartfona pasek poleceń ładnie się chowa, jednak po obróceniu ekranu ta funkcja znika i nie można jej przywołać,


**poszukać więcej, sprawdzić widok na smartfonie, dodawanie/usówanie raportów, czy ingerencja w mecz po stworzeniu raportu generuje w nim zmianę, czy można dodać raport bez meczu, czy można założyć 2 profile dla 1 zawodnika - czy jest opcja usunięcia duplikatu, print jak działa, generowanie pliku jak działa, może by tak podać informacje o kontuzjach, zdjęcie zawodnika, dodać wybór graczy do porównania, bo w tej chwili ta opcja kuleje, nasz profil**




