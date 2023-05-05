<h1 align="center"> :black_nib: Wiola's challenge portfolio </h1>


### :point_right: Table of contents
1. [Task 1](#task-1)
2. [Task 2](#task-2)
<br>
<br>

Translation in progress... almost there - please be patient

___


# Task 1

## Subtask 1

My test score = 9/10 points :+1:


## Subtask 3

Hello, <br>
My name is Wiola. I decided to participate in this project because I need to determine the direction in my personal advancement. Bothered by stagnation related mostly to lack of new opportunities in my current workplace, I wish to prepare myself for a deep dive into the unknown. I crave for new possibilities, and my creativity awaits the moment it can spread its wings. I expect that the course will prepare me for any upcoming challenges, but don't get me wrong... I know perfectly well that everything, every job, has it's very own bright and dark sides. Like they say, no risk no gain...


*Wiola*


## Subtask 4

[Scouts Test](https://scouts-test.futbolkolektyw.pl/) is an app designed to create a profile of a soccer player, then, based on matches played by the player, reports are created. Each match can be evaluated in the report, which then translates into the player's average rating. Each player added to the app's database can be compared with other players. What's more, we are able to search for players based on specific characteristics - name, surname, age, main position, raiting, etc.

  

Funcionalities:
* Login to the app - it is used to access the features of the app - the apperance looks extremely simple, poor I should even say; apart from the name, there is no information about the app at which gates we are located, nor the welcome screen. Entering a valid login and password might lead me somewhere, but that's only my guess. Because they are required by the app, their absence results in denied access.

* Adding a new player - creates a profile for a new player, which includes his personal data, features and skilss, enabling us to save his contact details and adding links to his social media profiles, YouTube films and other significant sites. Intuitive, although not protected against the user's ill will - more details on this topic avaliable in the error section. Personally, I believe that including information about past injuries or even adding a photo of the player would enrich the profile, as well as make the app's raw view a little more attractive.

* Matches - this option is avaliable after selecting a player, and contains a list of matches in which a player has participated. By using this panel we are able to create a report presenting the player's behaviour on the pitch. Intuitive, when it comes to adding a match. However, the pitch panel is a different story - not visible enough, less clear and enigmatic, also not protected against the user's ill will. For further details, see the error section.

* Reports - this option is avaliable after selecting a player, and contains a list of reports saved for each player, which we can later modify depending on his actions on the pitch. Adding a report is intuitive, however the sheet is not, probably requires more knowledge on the subject. 

* Players - contains a list of players saved in the app. Not all of the elements are intuitive - a panel appears in the header allowing us to search for information, the command is activated by pressing the Enter key, yet you cannot use the mouse button to proceed, because the magnifying glass icon does not respond. In response to the query, we recieve a list of records containing the searched word. I believe that the browser panel would work better with the option to manually select a page and  the number of records presented on it. Also, it would be useful for us to manually select the players we want to compare,

* Download CSV - generates a file with selected players. Intuitive. Although the file can be opened via Excel, it is hardly readable,

* Print - option to print selected players. Intuitive, however I'm not satisfied with the way the data is arranged on the printout - the page is overstuffed and yet there is little to no information, waste of paper,

![image](https://user-images.githubusercontent.com/128975245/234106629-f811c9d6-335d-4c92-aa6f-edada4eed640.png)

* View columns - enables the user to choose which attributes are displayed. Intuitive,

* Filter Table - works in a simillar way to the search panel, but is a better version of this function and not highlited enough. It additionally helps us to clarify which particular attribute are we interested in finding,

* Change language - used to translate the app into Polish or English. Intuitive, however not all elements are translated to Polish, which should be improved,

* Sign out - used to exit the app - intuitive. Still, there are ways we can improve it, for example adding a popup message in case it was clicked unintentionally -  'Are you sure you want to leave us so soon?', happened to me not once, not twice...

* Activity, Scouts Panel - panel, where you can see information about recently added players, matches, reports, modifications, where you have the ability to contact the dev team - intuitive, makes it easier to navigate within the recently added elements, without having to search for them manually.



Interfejs jest prosty, mało porywający, surowy. Przemieszczanie się pomiędzy głównymi opcjami nie stanowi problemu, aplikacja wygląda poprawnie zarówno na ekranie komputera jak i smartfona z pewnymi zastrzeżeniami, nie budzi jednak mojej sympatii. Aplikacja nie dostosowuje się do domyślnego koloru mojego systemu czy przeglądarki, razi i męczy oczy przy dłuższym korzystaniu. Nie widzę opcji, które pomogły by korzystać z niej osobom słabowidzącym/niedowidzącym, np. zmiany wielkości liter czy ich kontrastu w stosunku do pozostałych elementów na stronie. Dodanie gracza możliwe jest tylko ze strony głównej, w panelu linki pomocnicze - dodaj gracza, nie znalazłam jednak tej opcji nigdzie indziej. Chciałabym mieć możliwość skorzystania z panelu, w którym znajdować się będą jedynie gracze, mecze i raporty dodane przeze mnie - brak tej opcji dziwi mnie, zwłaszcza, że gdy dodaje się lub modyfikuje wielu zawodników łatwo stracić z oczu wszystkie dokonane przez siebie zmiany.

Aplikacja jest intuicyjna do momentu tworzenia raportów. Opcje dostępne przy rozgrywaniu meczu nie są podpisane i mimo prostego przekazu potrzebowałam chwili aby zrozumieć, że konieczne jest uruchomienie zegara, jak również istnieje opcja przeskakiwania do konkretnych minut w trakcie gry. Krótki samouczek lub FAQ były by jak najbardziej na miejscu. Opcje wyszukiwania, które pojawiają się w nagłówku przy panelu przeglądania zawodników, na początku wydawały mi się bardzo ubogie, do momentu gdy zauważyłam przycisk filtrowania - uważam, że wymaga on większego wyróżnienia na stronie.

Errors / irregularities, that caught my attention:
* Adding a new player:
    * wykrywa zły adres e-mail, ale za krótki nr telefonu już nie,
    * umożliwia dodanie ujemnego lub zbyt wysokiego wzrostu (np. 600cm), ujemnej wagi, kolor koszulki, który jest cyfrą lub ujemny, gracz może mieć ponad sto lat lub być nieletni,
    * przy zakładaniu profilu zawodnika możliwe jest dodanie imienia składającego się ze znaków, które nie występują w imionach,
    * możliwe jest dodanie 2 graczy o dokładnie takich samych danych, aplikacja nie wykrywa, że dla zawodnika został już zapisany profil,
    * dodano kilku graczy, jednak nie przypisano im meczy ani nie wygenerowano raportów - gracze nie zostali zapisani mimo pozytywnej informacji zwrotnej z systemu, z można jednak stworzyć pusty raport bez oceny zawodnika i komentarzy, który figuruje na liście,
    * pole 'województwo' jest wymagane do stworzenia raportu jednak możliwe jest dodanie zawodnika, dla którego ten atrybut jest pusty,
    * data urodzenia zawodnika i data meczu może być taka sama, dodaje mecze z przyszłości i bardzo dalekiej przeszłości, zawodnik może nie być pełnoletni (może urodzić się w dniu meczu, w którym gra), może także brać udział w meczu, przed swoim narodzeniem,
    * dla gracza może być przypisana pozycja, której nie ma na boisku - np. Jedi,
* Adding a match - ograniczenie czasu trwania meczu - możliwość dodania meczy o bardzo długim czasie trwania, ujemnym czasie trwania,
* Rozgrywanie meczu:
    * przy najechaniu kursorem na ikonę nie zawsze otrzymujemy informację, co ona robi, dotyczy to głównie mapy boiska, brak limitu czasowego dla meczu, synchronizacji z informacją o tym, która połowa jest aktualnie rozgrywana, mogę ustawić nawet wartość  mniejszą od 0,
    * rzut rożny możliwy ze środka boiska, można dodać kilka odległych akcji w bardzo krótkim odstępie czasu, można określić inny wynik meczu w formularzu i dodać inną ilość goli na mapie, gol możliwy na środku boiska,
* Zmiana języka - niektóre polecenia nie ulegają translacji - save, submit, clear, print - konieczne zachowanie pewnej konsekwencji,
* Raporty:
    * w przypadku meczu 2:1 istnieje możliwość przypisania wszystkich goli dla naszego zawodnika - czy aplikacja rozróżnia bramkę samobójczą od zwykłej? mimo wszystko skuteczność 100%...
    * przy generowaniu raportu z meczu czasem tworzy się duplikat - nie ma możliwości jego usunięcia, można także umyślnie stworzyć kilka raportów do meczu,
    * drużyna zawodnika i przeciwna mogą być takie same,
* Odpowiedzi z serwera HTTP informują o użyciu przestażałych parametrów,
* W przypadku generowania widoku dla smartfona pasek poleceń ładnie się chowa, jednak po obróceniu ekranu ta funkcja znika i nie można jej przywołać, to samo dotyczy zmiany rozmiaru okna przeglądarki,
* Przeglądanie zawodników - wydruku informacji dla wybranych graczy wygląda inaczej niż niż w aplikacji - przypomina to widok z ekranu smartfona, zajmuje więcej miejsca niż tabelka na ekranie monitora.




# Task 2

[Link to my Google Drive](https://drive.google.com/drive/u/1/folders/1VWhxpWYF_y2U7KB0aApo47CPk2D4PEhT), where I store documentation for this task.

## Subtask 1

The task file is avaliable on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1qcSn0Cj1NldS_lztPdzc3xv2Kka49Fbw/edit?usp=sharing&ouid=100493076818843703891&rtpof=true&sd=true) Each Test Case is a separate sheet: for US_01 there are 3, and for US_02 I prepared 4. The ID consists of the User Story number and Test Case number, np. US_01_01.

## Subtask 2

The task file is avaliable on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1rF0C0XI9mb8PAw-67_fDALD1EyknA0Jl/edit?usp=sharing&ouid=100493076818843703891&rtpof=true&sd=true) Each Test Case is a separate sheet, and for this task I prepared 22. The ID consists of the TC shortcut and a sequential number, np. TC_001.


## Subtask 3

Przypadki testowe pomagają uporządkować pracę przy tworzeniu aplikacji/oprogramowania. Po pierwsze, przekazują nam informację o tym jak ma być zaprojektowany dany element systemu oraz czy produkt w obecnym stadium rozwoju spełnia postawione przed nim wymagania. Po drugie, ich obecność pozwala wychwycić błędy, które mogły się wedrzeć do projektu, a każdy napisany przypadek testowy pokrywa kolejne obszary aplikacji pomagając tym samym odszukać je w odpowiednim czasie. 

Moja pierwsza styczność z testowaniem to w zasadzie anegdota, którą usłyszałam na studiach. Dotyczyła przeprowadzanego przypadku testowego dla pewnej gry - __*'przez 8 godzin wsiadam i zsiadam z konia, za każdym razem postać trzyma w dłoni inną broń.'*__ Brzmi jak nudny banał... A jednak powtarzanie tej czynności pozwoli zewryfikować wiele elementów, między innymi znaleźć i naprawić ewentualne bugi, które mogłyby zepsuć nie tylko rozgrywkę, ale i reputację studia.

## Subtask 4

The task file is avaliable on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1ZhTASmDQJxGgv75x1_zy7pYDufsen0Ik/edit?usp=sharing&ouid=100493076818843703891&rtpof=true&sd=true) Each Test Case is a separate sheet, and for this task I prepared 5. The ID consists of the TC shortcut and a sequential number, np. TC_001. 

```diff
! Attention !
```

Do tego zadania został również zamieszczony plik - nagranie z pracy aplikacji pick.eat.up związane z TC_003. [Nagranie](https://drive.google.com/file/d/1bhCO6x7zo3i2B4BKfMmzD174OBfgGIft/view?usp=sharing) dokumentuje błąd, który zaobserwowałam (*właściwie, to 2 błędy, jak się później przypatrzyłam*) , oraz kroki, które wykonałam aby je odtworzyć:
* Po kliknięciu 'Sign out' aplikacja przenosi nas na ekran logowania by po sekundzie samoczynnie zalogować się ponownie - nie było tu mojej ingerencji,
* Dolny panel rozpoczyna pracę po Polsku, po chwili natomiast, po interakcji z ekranem, zmienia język na ustawiony w aplikacji Angielski.










