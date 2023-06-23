<h1 align="center"> :black_nib: Wiola's challenge portfolio </h1>


### :point_right: Table of contents
1. [Task 1](#task-1)
2. [Task 2](#task-2)
3. [Task 3](#task-3)
4. [Task 4](#task-4)
5. [Task 5](#task-5)
6. [Task 6](#task-6)
7. [Feedback](#Feedback)
<br>
<br>


___


# Task 1

## Subtask 1

My test score = 9/10 points :+1:

## Subtask 2

- [x] Add a new repository to GitHub


## Subtask 3


Hello, <br>
My name is Wiola. I decided to participate in this project because I need to determine the direction in my personal advancement. Bothered by stagnation related mostly to lack of new opportunities in my current workplace, I wish to prepare myself for a deep dive into the unknown. I crave for new possibilities, and my creativity awaits the moment it can spread its wings. I expect that the course will prepare me for any upcoming challenges, but don't get me wrong... I know perfectly well that everything, every job, has it's very own bright and dark sides. Like they say, no risk no gain...

*Wiola*
<br>

## Subtask 4

[Scouts Test](https://scouts-test.futbolkolektyw.pl/) is an app designed to create a profile of a soccer player, then, based on matches played by the player, reports are created. Each match can be evaluated in the report, which then translates into the player's average rating. Each player added to the app's database can be compared with other players. What's more, we are able to search for players based on specific characteristics - name, surname, age, main position, rating, etc.

  
<details>
  <summary>Functionalities</summary>
  <br>  
  
* Login to the app - it is used to access the features of the app - the appearance looks extremely simple, poor I should even say; apart from the name, there is no information about the app at which gates we are located, nor the welcome screen. Entering a valid login and password might lead me somewhere, but that's only my guess. Because they are required by the app, their absence results in denied access.

* Adding a new player - creates a profile for a new player, which includes his personal data, features and skills, enabling us to save his contact details and adding links to his social media profiles, YouTube films and other significant sites. Intuitive, although not protected against the user's ill will - more details on this topic available in the error section. Personally, I believe that including information about past injuries or even adding a photo of the player would enrich the profile, as well as make the app's raw view a little more attractive.

* Matches - this option is available after selecting a player, and contains a list of matches in which a player has participated. By using this panel we are able to create a report presenting the player's behaviour on the pitch. Intuitive, when it comes to adding a match. However, the pitch panel is a different story - not visible enough, less clear and enigmatic, also not protected against the user's ill will. For further details, see the error section.

* Reports - this option is available after selecting a player, and contains a list of reports saved for each player, which we can later modify depending on his actions on the pitch. Adding a report is intuitive, however the sheet is not, probably requires more knowledge on the subject. 

* Players - contains a list of players saved in the app. Not all of the elements are intuitive - a panel appears in the header allowing us to search for information, the command is activated by pressing the Enter key, yet you cannot use the mouse button to proceed, because the magnifying glass icon does not respond. In response to the query, we receive a list of records containing the searched word. I believe that the browser panel would work better with the option to manually select a page and  the number of records presented on it. Also, it would be useful for us to manually select the players we want to compare,

* Download CSV - generates a file with selected players. Intuitive. Although the file can be opened via Excel, it is hardly readable,

* Print - option to print selected players. Intuitive, however I'm not satisfied with the way the data is arranged on the printout - the page is overstuffed and yet there is little to no information, waste of paper,

![image](https://user-images.githubusercontent.com/128975245/234106629-f811c9d6-335d-4c92-aa6f-edada4eed640.png)

* View columns - enables the user to choose which attributes are displayed. Intuitive,

* Filter Table - works in a similar way to the search panel, but is a better version of this function and not highlighted enough. It additionally helps us to clarify which particular attribute are we interested in finding,

* Language - used to translate the app into Polish or English. Intuitive, however not all elements are translated to Polish, which should be improved,

* Sign out - used to exit the app - intuitive. Still, there are ways we can improve it, for example adding a popup message in case it was clicked unintentionally -  'Are you sure you want to leave us so soon?', happened to me not once, not twice...

* Activity, Scouts Panel - panel, where you can see information about recently added players, matches, reports, modifications, where you have the ability to contact the dev team - intuitive, makes it easier to navigate within the recently added elements, without having to search for them manually.
</details>

<details>
  <summary> Interface </summary>
  <br>
The interface is simple, not very thrilling, raw I should say. Navigating between the main options is not a problem, the app looks correct both on the computer screen and smartphone with some exceptions, but it does not elicit my sympathy. The app does not adapt to the default colour of my system or browser, it hurts my eyes when I use it for too long. I do not see options that would help visually impaired people to use it, e.g. changing the size of letters or their contrast in relation to other elements on the page. Adding a player is possible only from the main page - this option is nowhere else to be found (although, by looking at the URL address I see where it should be). I would like to be able to use a panel, which will contain only those players, matches and reports added by me. Lack of this option surprises me, especially because it is easy to loose sight of all the changes that were made when many players are added or modified.  
  <br>
  <br>
The app is intuitive until we reach the report creating menu. The available options are not signed, and despite a seemingly simple message, it took me a moment or two to understand that it is necessary to start the timer, also, that we can change the time manually and jump to specific minutes in game. A short tutorial or FAQ would be most welcome. Search options in the player browsing panel appeared to me as poorly designed until I noticed the filter button - I believe it needs a coming out. 
</details>

<details>
  <summary>Errors / irregularities, that caught my attention</summary>
 <br> 
  
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
    * when hovering over an icon, we not always receive information about its name/purpose, 
    * no time limit for a match, no synchronization which half is actually played with the timer, I can set a negative value,
    * a corner kick is possible from any place on the pitch, the same for a goal, you can add several distant actions in a short period of time,
    * you can specify a different match result in the report form and different number of goals scored on the map,
* Language - some of the options - save, submit, clear, print - do not have their equivalent words in Polish, certain consequence is necessary,
* Reports:
    * in case of a match where the teams scored 2:1 we are able to assign all of the goals to out player - does the app distinguish between an own goal and a regular one? Still 100% effective...
    * when generating a match report a duplicate is sometimes created, with no option to delete it, also, we can intentionally create several reports to a single match,
    * the player's team and the opposing team can be the same,
* Responses from the HTTP server inform about the use of deprecated parameters,
* When generating a view for a smartphone, the sidebar works well and hides, but when the screen is rotated this function disappeares, the same applies to changes in the window settings and its size,
* Browsing players - the printout prepared for selected players looks different than in the app- it resembles the view from the smartphone screen, and it takes a lot more place than it needs.
</details>



# Task 2

[Link to my Google Drive](https://drive.google.com/drive/u/1/folders/1VWhxpWYF_y2U7KB0aApo47CPk2D4PEhT), where I store documentation for this task.

## Subtask 1

The task file is available on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1qcSn0Cj1NldS_lztPdzc3xv2Kka49Fbw/edit?usp=sharing&ouid=100493076818843703891&rtpof=true&sd=true) Each Test Case is a separate sheet: for US_01 there are 3, and for US_02 I prepared 4. The ID consists of the User Story number and Test Case number, np. US_01_01. Feel free to use the table of contents for navigation.

## Subtask 2

The task file is available on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1rF0C0XI9mb8PAw-67_fDALD1EyknA0Jl/edit?usp=sharing&ouid=100493076818843703891&rtpof=true&sd=true) Each Test Case is a separate sheet, and for this task I prepared 22. The ID consists of the TC shortcut and a sequential number, np. TC_001. Feel free to use the table of contents for navigation.


## Subtask 3

Test cases help in organising work while developing an app or software. Their presence enables you to catch errors/bugs that could have made their way into the final project. Each written test case covers subsequent areas of the app, when properly formulated they will allow us to draw the right conclusions, thus enabling further development. Also, they provide us with information about how a given element of our system should be working, how it should be designed and whether the product at the current stage of development meets the requirements. 

My first contact with test cases is basically an anecdote I heard in college - a particular test case for a certain game - __*'I get on and off a horse for 8 hours, each time the character has a different weapon in his hand.'*__ Sounds like a boring cliché... And yet, repeating this action will verify many elements, including finding and fixing bugs that could spoil not only the gameplay, but also the studio's reputation.


## Subtask 4

The task file is available on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1ZhTASmDQJxGgv75x1_zy7pYDufsen0Ik/edit?usp=sharing&ouid=100493076818843703891&rtpof=true&sd=true) Each Test Case is a separate sheet, and for this task I prepared 5. The ID consists of the TC shortcut and a sequential number, np. TC_001. Feel free to use the table of contents for navigation.

```diff
! Attention !
```

I also added a file for this task - [a bug report.](https://docs.google.com/spreadsheets/d/10TbJMsx6LU7SKjUg9gTnkqKkNhOahJFW/edit?usp=share_link&ouid=100493076818843703891&rtpof=true&sd=true)


# Task 3

[Link to my Google Drive](https://drive.google.com/drive/folders/1ygTftTjnr1vXe973eaMe125gI1rTPbjw?usp=sharing), where I store documentation for this task.

## Subtask 1

- [x] Create a template to report bugs

## Subtask 2

The task file is available on my Google Drive:
* [here is the direct link](https://docs.google.com/spreadsheets/d/1-AYkNhLGZ5AoWEJO4eGAs5ImMgHG3Hn8/edit?usp=share_link&ouid=100493076818843703891&rtpof=true&sd=true) for the first set of Test Cases,
* [here is the direct link](https://docs.google.com/spreadsheets/d/1EgkgkhU6K02PZsNAel0lJvN9rpkxZtXX/edit?usp=share_link&ouid=100493076818843703891&rtpof=true&sd=true) for the second set of Test Cases.
* and also [Bug Reports](https://docs.google.com/spreadsheets/d/1vd4z9mM8MzV9GQR6afpK-wJp8_OUmU5I/edit?usp=share_link&ouid=100493076818843703891&rtpof=true&sd=true) - except for the first sheet.


The task was to run previously written Test Cases for the Scouts Test app, this time for an older version. 
I must confess... Test Cases TC_003 and TC_004 were a bit modified by me. I've provided the data part with an additional value - for the 'Poprzedni klub' field - and changed a bit the first step. It was alluring. It called to me, and I truly believed it had to be done.

## Subtask 3

The task file is available on my Google Drive, [here is the direct link](https://docs.google.com/spreadsheets/d/1vd4z9mM8MzV9GQR6afpK-wJp8_OUmU5I/edit?usp=share_link&ouid=100493076818843703891&rtpof=true&sd=true).
The report is in the same file as Bug Reports, first sheet.


# Task 4

[Link to my Google Drive](https://drive.google.com/drive/folders/1nCRb0PtQLHZ6ZTjHS_Bk73_ct_sbwntE?usp=sharing), where I store documentation for this task.

## Subtask 1

- [x] Create a template to report bugs

## Subtask 2

The task file is avaliable on my Google Drive, [here is the direct link.](https://docs.google.com/spreadsheets/d/1NKE0xz5pL2klJwpJqtRpYH51nMtYMU4K/edit?usp=share_link&ouid=100493076818843703891&rtpof=true&sd=true)

## Subtask 3

<details>
  <summary>What is this app for? What is its purpose?</summary>
  <br>
OLX - ogłoszenia lokalne is an app imitating bulletin boards that used to be in every city. It works in a simillar way - users are able to bost and browse announcements from various sectors of life (although erotic announcements are rather rare here), from all over Poland, without leaving home. In addition to standard purchase/sale/exchange offers, the apps services are also related to the real estate sector, labor market, rental and charity. <br>
  <br>
By this app, the user is able to view or publish ads, equip them with photos and communicate with other users. There is an option to equip our account with a number of additional elements, such as a CV and a cover letter or payment details. Advertisements are equipped with an attribute that can be simply afeined as an expiry date - if no one is interested in the offer within a period of time, it goes to the archive. <br>
  <br>
As it enables contact with a huge group of customers, it is also used for marketing services - adverts intended for the users are interwinded between the announcements. Its main purpose is to provide services to the uers, including intermediation in all kinds of activities, the list of which is still growing. The app charges us for some of the services provided, for example when you would like to increase the visibility of the offer. These options allow the developers to profit financially and continue to support the app through updates. 
</details>

<details>
  <summary>Who is to be the end user of this app?</summary>
  <br>
The end user of the app os an adult (or a person under the care of an adult) who, as a result of using the app, will purchase or exchange goods through it.
</details>

<details>
  <summary>Do you find this app user friendly?</summary>
  <br>
During many years of its existence, the app has developed not only functional and user-friendly solutions in the field of its activity, but also an accessible and aestethic graphical interface that does ot scare the user with excess functions or complicated appearance.
</details>

<details>
  <summary>How would you improve the app? What would you improve about it? Do you have an idea for an additional funcionality?</summary>
  <br>
When using older versions of the app, while browsing the items, I often accidentally changed the offer when I just wanted to view the photos, and now this option is no longer avaliable. I believe that its complete loquidation was not a good solution. Instead, I would add this option for the user to select, if he truly wants the app to work like this. Surely someone would appreciate this function. 
  <br>
I often help my friends while they look for real estates to buy in Poland, therefore I would like to be able to add the search scope based on the map - mark on it a point or an area that I am particulary interested in.
  
</details>

<details>
  <summary>What differences do you see between testing a web app and a native one?</summary>
  <br>
Testing web apps differs from testing native apps, mostly because in the latter the attention is paid to user-friendly navigation. An important role also plays the functional and spatial arrangements of objects. The native app has to be able to read our phone settings, use our network access and be prepared to take a photo or read our location and messages, depending on the situation and needs. We have to make sure that all phones resources are avaliable for the app, so that it won't crash when in use. Because native apps are designed for a specific system, testing requires the use of more devices. <br>
  So far, I've noticed that when testing native apps it's much easier to find bugs - there are more of them and you need to spend less time to actually find any. 
</details>

## Subtask 4

This task is avaliable on my Jira account, [here is the direct link.](https://innsmouth.atlassian.net/jira/software/projects/CHAL/boards/1/backlog?selectedIssue=CHAL-2)
<br>
I have more bugs recorded - [here is the direct link](https://drive.google.com/drive/folders/1RbiSlnYNpuFu0uLe_c8uBl-WdkFNE0IV?usp=share_link)


# Task 5

SQL part 1

## Subtask 1

Ladies and Gentelmen, I am proud to announce that now I know:
```python
SELECT, FROM, DISTINCT, WHERE, AND, OR, NOT, ORDER BY, IS NULL, MIN, MAX, COUNT, AVG, SUM, LIKE, 
wildcards, IN, BETWEEN, AS, INSERT INTO, 
```
Soon, there will be more.

## Subtask 2

- [x] Environment configuration and uploading the database

## Subtask 3

My SQL homework 😸

<details>
  <summary> 👉 Display the actors table in alphabetical order - sort by the surname column. </summary>
    <br>
  
  ```python
  SELECT * FROM actors
  ORDER BY surname;
  ```
  
  ![A](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/b5ed470a-0846-486f-98ae-3f3edfbe4d71)
</details>
<details>
  <summary> 👉 Display a video, that was made in 2019. </summary>
    <br>
  
  ```python
  SELECT * FROM movies
  WHERE year_of_production = 2019;
  ```
   
  ![B](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/958f99cb-90d6-4731-aa2b-4bbfdf23afe2)

</details>
<details>
 <summary> 👉 Display all movies made between 1900 and 1999. </summary>
    <br>
  
  ```python
  SELECT * FROM movies
  WHERE year_of_production BETWEEN 1900 AND 1999;
  ```
  
  ![C](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/a3841207-6572-4c04-902f-f8f3a484e100)

</details>
<details>
 <summary> 👉 Display only the title and price of movies that cost less than 7$. </summary>
    <br>
  
  ```python
  SELECT title, price FROM movies
  WHERE price < 7;
  ```
  
 ![D](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/6174ec29-1ed8-433a-bf04-a7102ff7599b)
 
</details>
<details>
 <summary> 👉 Use the logical AND operator to display actors with actor_id between 4-7 (4 and 7 should display). Do not use BETWEEN operator. </summary>
    <br>
  
  ```python
  SELECT * FROM actors
  WHERE actor_id >= 4 
  AND actor_id <= 7;
  ```  
  
  ![E](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/7aeccdbc-2c25-43e8-acbe-d286039c6f0a)

</details>
<details>
 <summary> 👉 Display customers with id 2, 4, 6 and use logical condition for this. </summary>
    <br>
  
  ```python
  SELECT * FROM customers
  WHERE customer_id IN (2, 4, 6);
  ```
  
  ![F](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/d945fc1c-89a8-4f7a-9794-092e02c1048b)

</details>
<details>
 <summary> 👉 Display customers with id 1, 3, 5 and use IN operator. </summary>
   <br>
  
  ```python
  SELECT * FROM customers
  WHERE customer_id IN (1, 3, 5);
  ```
  
   ![G](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/90dfe448-a385-4eee-b9ab-999956fa01d2)

</details>
<details>
 <summary> 👉 Display all people in the 'actors' table whose name starts with 'An'. </summary>
   <br>
  
  ```python
  SELECT * FROM actors
  WHERE name LIKE 'An%';
  ```
   
  ![H](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/f662a7f7-5b45-4143-8f2b-014089ce10fb)
 
</details>
<details>
 <summary> 👉 Display details of a customer who does not have an e-mail address provided. </summary>
    <br>
  
  ```python
  SELECT * FROM customers
  WHERE email IS null;
  ```
    
  ![I](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/71e13305-1ea4-4ac3-893e-08d72138558c)

</details>
<details>
<summary> 👉 Display all movies priced over 9$ with movie_id between 2 and 8. </summary>
    <br>
  
  ```python
  SELECT * FROM movies
  WHERE price > 9
  AND movie_id BETWEEN 2 AND 8;
  ```
  
  ![J](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/33bb3787-9b1f-4f1f-a3dc-4eefbb691b15)

</details>

# Task 6

SQL part 2
  
## Subtask 1

<details>
<summary> 👉 I made a mistake typing the name of Ania Miler - I typed Muler. Find and use a function that will correct my error. </summary>
  <br>
  
  ```python
  UPDATE customers
  SET surname = 'Miler'
  WHERE surname = 'Muler';
  ```
  
  ![A](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/3afbf0ce-1511-4515-86a4-d732add71833)

</details>
<details>
<summary> 👉 I charged too much money from a customer who recently bought a video with id 4. Using the JOIN function, check the customer's name and email address. In order to write him a message about the mistake of a fantastic boss. </summary>
<br>
  
  ```python
  SELECT sale.sale_date, cus.name, cus.email, mov.title
  FROM customers AS cus
  JOIN sale ON cus.customer_id = sale.customer_id
  JOIN movies AS mov ON mov.movie_id = sale.movie_id
  WHERE sale.movie_id = 4;
  ```
  
  ![B](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/1efccf0e-1cdd-4354-87d9-051a212822f6)

</details>
<details>
<summary> 👉 Surely you've noticed that the seller forgot to enter the email address of a client, Patrycja. Fill this gap by typing: pati@mail.com </summary>
<br>
  
  ```python
  UPDATE customers
  SET email = 'pati@mail.com'
  WHERE name = 'Patrycja';
  
  ```
  
  ![C](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/8598f5f1-089b-42c8-affe-308171d24503)

</details>
<details>
<summary> 👉 For each purchase display the name and surname of customer, who made the rental and the title of the rented movie (use the INNER JOIN function for this, think which tables will be useful for you to complete the exercise) </summary>
  <br>
  
  ```python
  SELECT cus.name, cus.surname, mov.title
  FROM customers AS cus
  INNER JOIN sale ON cus.customer_id = sale.customer_id
  JOIN movies AS mov ON mov.movie_id = sale.movie_id
  ```
  
  ![D](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/5ceea3d1-971c-4f9d-a247-4a27d3d4e6d3)

</details>
<details>
<summary> 👉 In order to anonymise the data, you want to create pseudonyms for your customers. Add a column named 'pseudonym' to the customers table. Fill in the column, so that the nickname is made of the first two letters of the name and the last letter of the surname, e.g. Natalie Pilling → Nag </summary>
  <br>
  
  ```python
  ALTER TABLE custmers
  ADD pseudonym char(3);
  
  UPDATE customers 
  SET pseudonym = CONCAT(LEFT(name, 2), RIGHT(surname, 1));
  ```
  
  ![E](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/9fd3ffc6-430a-4885-97f8-5ab3c529afaf)

</details>
<details>
<summary> 👉 Display the titles of the purchased movies, display the table in such way, that the titles do not repeat.  </summary>
  <br>
  
  ```python
  SELECT title, sale.sale_date FROM movies
  JOIN sale ON sale.movie_id = movies.movie_id
  GROUP BY title;
  ```
  
  ![F](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/27a4adce-eb4e-4654-982a-4e439821da88)

</details>
<details>
<summary> 👉 Display a common list of names of all actors and clients, and sort them alphabetically (use the UNION function). </summary>
  <br>
  
  ```python
  SELECT name FROM actors
  UNION
  SELECT name FROM customers
  ORDER BY name ASC;
  ```
  
  ![G](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/803c53b2-fb77-4a55-af04-62093e5117d2)

</details>
<details>
<summary> 👉 Inflation has taken over Poland, and our movie shop has also been affected by this problem. Increase the price of all movies made after 2000 by $2.50 (note, that the dollar is a default unit - don't use it anywhere). </summary>
  <br>
  
  ```python
  UPDATE movies
  SET price = price + 2.5
  WHERE year_of_production > 2000;
  ```
  
  ![H](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/bd7b3fcc-371f-4c0c-954f-5a6eea158639)

</details>
<details>
<summary> 👉 Display the name and surname of the actor with id 4 and the title of the movie he starred in. </summary>
  <br>
  
  ```python
  SELECT actors.name, actors.surname, movies.title 
  FROM actors
  JOIN cast ON cast.actor_id = actors.actor_id
  JOIN movies ON movies.movie_id = cast.movie_id
  WHERE actors.actor_id = 4;
  ```
  
  ![I](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/77490a1b-7f5d-40cc-95c5-d224e75c8c53)

</details>
<details>
<summary> 👉 And where is our HONIA!? Add a new entry to the customers table, with customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com and pseudonym = Hoa. </summary>
  <br>
  
  ```python
  INSERT INTO customers
  VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com' 'Hoa');
  ```
  
  ![J](https://github.com/BerylCrescent/challenge_portfolio_Wiola/assets/128975245/a3af31b2-eccf-482a-84dc-bc3e28f8bde2)

</details>
  
## Subtask 2
  
My test score = 15/15 points :+1:
  
## Subtask 3

- [X] Add a [new repository](https://github.com/BerylCrescent/Portfolio) to GitHub

# Feedback

Individual [Feedback](https://dareit.notion.site/Individual-Feedback-for-QA-Zosta-Testerem-Manualnym-Wioletta-Rusiecka-39902ca38917471ea99ee76aac278431) for this challenge

