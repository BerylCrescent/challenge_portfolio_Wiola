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

* Language - used to translate the app into Polish or English. Intuitive, however not all elements are translated to Polish, which should be improved,

* Sign out - used to exit the app - intuitive. Still, there are ways we can improve it, for example adding a popup message in case it was clicked unintentionally -  'Are you sure you want to leave us so soon?', happened to me not once, not twice...

* Activity, Scouts Panel - panel, where you can see information about recently added players, matches, reports, modifications, where you have the ability to contact the dev team - intuitive, makes it easier to navigate within the recently added elements, without having to search for them manually.



The interface is simple, not very thrilling, raw I should say. Navigating between the main options is not a problem, the app looks correct both on the computer screen and smartphone with some exeptions, but it does not elicit my sympathy. The app does not adapt to the default colour of my system or browser, it hurts my eyes when I use it for too long. I do not see options that would help visually impared people to use it, e.g. changing the size of letters or their contrast in relation to other elements on the page. Adding a player is possible only from the main page - this option is nowhere else to be found (although, by looking at the URL address I see where it should be). I would like to be able to use a panel, which will contain only those players, matches and reports added by me. Lack of this option suprises me, especially because it is easy to loose sight of all the changes that were made when many players are added or modified.  

The app is intuitive untill we reach the report creating menu. The avaliable options are not signed, and despite a seemingly simple message, it took me a moment or two to understand that it is necessary to start the timer, also, that we can change the time manually and jump to specific minutes in game. A short tutorial or FAQ would be most welcome. Search options in the player browsing panel appeared to me as poorly designed until I noticed the filter button - I believe it needs a coming out. 


Errors / irregularities, that caught my attention:
* Adding a new player:
    * detects that the e-mail address is odd, but not that the phone number is too short,
    * allows you to add a negative or too big number for height (e.g. 600cm), negative weight, a shirt colour that is a number, the player may be over a hundred years old, or be underage (even born right before the match),
    * when adding a player's profile it is possible to add a name consisting of characters that are not allowed in names,
    * it is possible to add 2 players with exactly the same data, the app does not detect that a profile already exists,
    * several players have been added, but no matches have been assigned to them and no reports have been generated - players have not been saved despite positive feedback from the system,
    * 'województwo' field is required to create a report, however it is not required in order to create a player,
    * the date of birth and the date of match can be the same, we can add a match from the future or very distant past (e.g. 1920), the player may not be of legal age, he may also participate in the match before he was born, 
    * a player may be assigned a position not meant for the pitch - a Witcher, a Jedi,
* Adding a match - unlimited duration of match, we are able to add matches witch very long or negative duration,
* Playing a match:
    * when hovering over an icon, we not always recieve information about its name/purpose, 
    * no time limit for a match, no synchronization which half is actually played with the timer, I can set a negative value,
    * a corner kick is possible from any place on the pitch, the same for a goal, you can add several distant actions in a short period of time,
    * you can specify a different match result in the report form and different number of goals scored on the map,
* Language - some of the options - save, submit, clear, print - do not have their equivalent words in Polish, certain consequence is necessary,
* Reports:
    * in case of a match where the teams scored 2:1 we are able to assign all of the goals to out player - does the app distinguish between an own goal and a regular one? Still 100% efective...
    * when generating a match report a duplicate is sometimes created, with no option to delete it, also, we can intentionally create several reports to a single match,
    * the player's team and the opposing team can be the same,
* Responses from the HTTP server inform about the use of deprecated parameters,
* When generating a view for a smartphone, the sidebar works well and hides, but when the screen is rotated this function dissapeares, the same applies to changes in the window settings and its size,
* Browsing players - the printout prepared for selected players looks different than in the app- it resembles the view from the smartphone screen, and it takes a lot more place than it needs.




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










