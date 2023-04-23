# Task 1

## Subtask 1

9 punktów


## Subtask 3

Cześć, 
Jestem Wiola. Zdecydowałam się na udział w projekcie, ponieważ potrzebuję określić kierunek, w którym chcę się rozwijać. Doskwiera mi stagnacja związana z brakiem nowych możliwości na obecnym stanowisku, nie chcę jednak skoczyć na głębię bez uprzedniego przygotowania. Oczekuję, że kurs w praktyczny sposób przygotuje mnie do nowej pracy i wyzwań, które na mnie czekają, oraz że moja kreatywność znajdzie w nich pole do popisu. Wiem, że jak każdy zawód, ten też ma swoje plusy i minusy, ale jak to się mówi, kto nie ryzykuje szampana nie pije. 

*Wiola*


## Subtask 4

Aplikacja Scouts Test ma za zadanie tworzenie profilu zawodnika piłki nożnej, a następnie na podstawie rozegranych przez niego meczy, tworzone są raporty. Każdy mecz można w raporcie można ocenić, co potem przedkłada się na średnią ocenę zawodnika. Każdego dodanego do aplikacji zawodnika można porównywnać z innymi graczami. Istnieje możliwość wyszukania graczy na podstawie konkternych cech - imię/nazwisko, wiek, pozycja, wiek ocena.  

Funkcjonalności:
* Logowanie do systemu - służy do uzyskania dostępu do funkcji aplikacji - bardzo prosty wygląd, oprócz nazwy brak jest jakichkolwiek informacji dotyczących aplikacji, u której bram się znajdujemy czy ekran powitania, domyślam się, gdzie zaprowadzi mnie podanie loginu oraz hasła i w zasadzie to wszystko,

* Dodanie nowego gracza - zakłada profil dla danego zawodnkika, uwzględnia jego dane osobowe, cechy i umiejętności, umożliwia zapisanie jego danych kontaktowych oraz wstawienia linków do profilu na fb, filmów yt i innych stron - intuicyjna, ale niezabezpieczona przed złą wolą osoby zakładającej profil - szczegółowe informacje znajdują się przy akapicie z błędami, uważam że uwzględnienie informacji o przebytych kontuzjach czy możliwość dodania zdjęcia zawodnika wzbogaciłoby profil, jak również uatrakcyjniło surowy widok aplikacji,

* Przeglądanie meczy - opcja pojawia się po wybraniu zawodnika, zawiera listę meczy, w których brał udział zawodnik, z tego panelu można stworzyć raport prezentujący zachowanie gracza na boisku - intuicyjne jeśli chodzi o samo dodanie meczu, jednak panel z boiskiem jest mniej zrozumiały, jak również funkcja nie jest zabezpieczona przez złą wolą użytkownika, szczegółowe informacje znajdują się w akapicie z błędami,

* Przeglądanie raportów - opcja pojawia się po wybraniu zawodnika, zawiera listę raportów zapisanych dla gracza oraz możliwość edycji każdego - dodanie raportu jest intuicyjne, jednak poruszanie się po arkuszu już nie jest, zwłaszcza gdy chodzi o mapę z działaniami zawodnika,

* Przeglądanie zawodników - wyświetla listę zawodników zapisanych w aplikacji, pozwala na wygenerowanie i zapis pliku oraz wydruk - nie wszystkie jej elementy są intuicyjne - w nagłówku pojawia się panel umożliwiający wyszukiwanie zawodnika, klawisz enter służy do aktywacji polecenia jednak lupa przy panelu nie działa - ta funkcja jest łatwiej dostrzeglana mimo iż filtrowanie działa na podobnej zasadzie i jest lepszą wersją tej funkcji, nie jest jednak dostatecznie wyróżniona - znajduje się na końcu łańcuszka poleceń oznaczonych szarym kolorem; dodałanym możliwość wybrania strony, na którą chcę przejść ręcznie i możliwość zmiany liczby zawodników wyświetlanych na stronie, przydatną opcją byłoby również ręczne wybranie graczy do porównania,

* Zmiana języka - służy do przetłumaczenia strony, oferuje języki Polski oraz Angielski - intuicyjna, jednak nie wszystkie elementy strony podlegają translacji, co należy poprawić,

* Wylogowanie - służy do opuszczenia aplikacji - intuicyjna, nie ma potrzeby wprowadzania zmian, ewentualnie można dodać komunikat na zasadzie popup box na wypadek gdyby został kliknięty nieumyślnie 'Czy na pewno chcesz opuścić stronę?',

* Aktywność, linki pomocnicze, Scouts Panel - panel, na którym widać informację o ostatnio dodanych zawodnikach, meczach i raportach, możliwość skontaktowania się z dev team - intuicyjnu, ułatwia przemieszczanie się w obrębie ostatnio dodanych elementów, bez konieczności ich ręcznego wyszukiwania,



Interfejs jest prosty, mało porywający, surowy. Przemieszczanie się pomiędzy głównymi opcjami nie stanowi problemu, aplikacja wygląda poprawnie zarówno na ekranie komputera jak i smartfona z pewnymi zastrzeżeniami, nie budzi jednak mojej sympatii. Aplikacja nie dostosowuje się do domyślnego koloru mojego systemu czy przeglądarki, razi i męczy oczy przy dłuższym korzystaniu. Nie widzę opcji, które pomogły by korzystać z niej osobom słabowidzącym/niedowidzącym, np. zmiany wielkości liter czy ich kontrastu w stosunku do pozostałych elementów na stronie. Dodanie gracza możliwe jest tylko ze strony głównej, w panelu linki pomocnicze - dodaj gracza, nie znalazłam jednak tej opcji nigdzie indziej. Chciałabym mieć możliwość skorzystania z panelu, w którym znajdować się będą jedynie gracze, mecze i raporty dodane przeze mnie - brak tej opcji dziwi mnie, zwłaszcza, że gdy dodaje się lub modyfikuje wielu zawodników łatwo stracić z oczu wszystkie dokonane przez siebie zmiany. Obawiam się, że gdyby aplikacja w takim stanie została przedstawiona klientowi jako efekt końcowy prac, mogłaby spotkać się z negatywną oceną, a nawet jego złością.

Aplikacja jest intuicyjna do momentu tworzenia raportów. Opcie dostepne przy rozgrywaniu meczu nie są podpisane i mimo prostego przekazu potrzebowałam chwili aby zrozumieć, konieczne jest uruchomienie zegara, jak również przeskakiwanie do konkretnych minut w trakcie gry. 


Błędy:
* Dodawanie nowego gracza - wykrywa zły adres e-mail, ale za krótki nr telefonu już nie,
* Dodawanie nowego gracza - umożliwia dodanie ujemnego lub zbyt wysokiego wzrostu (np. 600cm), ujemnej wagi, kolor koszulki, który jest cyfrą lub ujemny, gracz może mieć ponad sto lat lub być nieletni,
* Dodawanie meczu - ograniczenie czasu trwania meczu - możliwość dodania meczy o bardzo długim czasie trwania, ujemnym czasie trwania,
* Rozgrywanie meczu - rzut rożny możliwy ze środka boiska, można dodać kilka odległych akcji w bardzo krótkim odstępie czasu, można określić inny wynik meczu w formularzu i dodać inną ilość goli na mapie, gol możliwy na środku boiska,
* Dodawanie nowego gracza - przy zakładaniu profilu zawodnika możliwe jest dodanie imienia składającego się ze znaków, które nie występują w imionach,
* Dodawanie nowego gracza - możliwe jest dodanie 2 graczy o dokładnie takich samych danych, aplikacja nie wykrywa, że dla zawodnika został już zapisany profil,
* Dodawanie nowego gracza - dodano kilku graczy, jednak nie przypisano im meczy ani nie wygenerowano raportów - gracze nie zostali zapisani mimo pozytywnej informacji zwrotnej z systemu, z można jednak stworzyć pusty raport bez oceny zawodnika i komentarzy, który figuruje na liście,
* Raporty - przy generowaniu raportu z meczu czasem tworzy się duplikat - nie ma możliwości jego usunięcia, można także umyślnie stworzyć kilka raportów do meczu,
* Dodawanie nowego gracza - pole 'województwo' jest wymagane do stworzenia raportu jednak możliwe jest dodanie zawodnika, dla którego ten atrybut jest pusty,
* Dodawanie nowego gracza - data urodzenia zawodnika i data meczu może być taka sama, dodaje mecze z przyszłości i bardzo dalekiej przeszłości, zawodnik może nie być pełnoletni (może urodzić się w dniu meczu, w którym gra), może także brać udział w meczu, przed swoim narodzeniem,
* Dodawanie nowego gracza - dla gracza może być przypisana pozycja, której nie ma na boisku - np. Jedi,
* Rozgrywanie meczu - przy najechaniu kursorem na ikonę nie zawsze otrzymujemy informację, co ona robi, dotyczy to głównie mapy boiska, brak limitu czasowego dla meczu, synchronizacji z informacją o tym, która połowa jest aktualnie rozgrywana, mogę ustawić nawet wartość  mniejszą od 0,
* Zmiana języka - niektóre polecenia nie ulegają translacji - save, submit, clear, print - konieczne zachowanie pewnej konsekwencji,
* Raporty - w przypadku meczu 2:1 istnieje możliwość przypisania wszystkich goli dla naszego zawodnika - czy aplikacja rozróżnia bramkę samobójczą od zwykłej? mimo wszystko skuteczność 100%...
* Raporty - drużyna zawodnika i przeciwna mogą być takie same,
* odpowiedzi z serwera HTTP informują o użyciu przestażałych parametrów,
* w przypadku generowania widoku dla smartfona pasek poleceń ładnie się chowa, jednak po obróceniu ekranu ta funkcja znika i nie można jej przywołać, to samo dotyczy zmiany rozmiaru okna przeglądarki,
* generowany plik csv jest mało czytelny,
* Przeglądanie zawodników - wydruku informacji dla wybranych graczy wygląda inaczej niż niż w aplikacji - przypomina to widok z ekranu smartfona, zajmuje więcej miejsca niż tabelka na ekranie monitora,




**poszukać więcej, sprawdzić widok na smartfonie,  nasz profil, 




