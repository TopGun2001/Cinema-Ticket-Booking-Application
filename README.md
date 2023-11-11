# Cinema Ticket Booking Application (C++)

![Intro Screen](https://github.com/TopGun2001/Cinema-Ticket-Booking-Application/blob/master/Images/Intro%20Screen.png)

##

### <ins>**Introduction**</ins>

RAP CINEMAS is a fictional theatre application developed in C++ for booking cinema tickets for three different languages. A new user is required to register for the first time and login with the system to book tickets of his/her own choice. A simulation of the theatre hall will be provided for users to choose their seats. A bill will be displayed for final payment and confirmation. The tickets will then be successfully booked. Users are also provided with various other features which will be discussed below.

##


### <ins>**Features of Application**</ins>

1. **Register/Login:**
  - A new user is requested to register a new profile by giving a suitable Username and Password.
  - An already existing user can login if they already have registered themselves.

2. **Main Screen:**
  - Once a user has logged in, he/she can do certain operations which are available on the screen.
  - For help, they can press the ‘HELP’ button for assistance.

3. **Book / Cancel Tickets:**
  - The user can book tickets by clicking the ‘Book Tickets’ button. This section consists of 9 movies which are divided into 3 languages consisting of 3 movies each.
  - The user can book a show for the next 3 days of which the first date is the system date. The user can select any movie and a simulation of the theatre hall will be provided.
  - Similarly, if the user wants to cancel the tickets, they can do it by clicking the ‘Cancel Tickets’ button and do the cancelation.

4. **Change Account Details / Deleting Account:**
  - The user can change account details and delete account by clicking the respective buttons on the screen.
  - These operations can be done only if legal account details are given for authorization.

5. **Ticket Details:**
  - Users can check their latest tickets they have booked.
  - Movie name, timing and date will be displayed.

6. **Admin Page:**
  - This page is for the admin of the theatre. Only the admin can access this page. The password and username is known only to him.
  - Page will be displayed only after the credentials of the admin are authorized by the system. It is available  to update movies.
    
##


### <ins>**Concepts Used**</ins>

- Structures
- Pointers
- Polymorphism (Function Overloading)
- Graphics
- Binary Files:
  - Usern.dat: File to store usernames
  - Userp.dat: File to store passwords
  - Nousers.dat: File to store count of users
  - Date.dat: Movie date (x3 files)
  - Movie.dat: Movie names

##


### <ins>**Note**</ins>

Users are required to take note that the source code only works in Turbo C++ 1.0 version. This is because Turbo C++ IDE has all the required header files installed during installation process that are required for successful compilation of this application.

##

### <ins>**Images**</ins>

![Help](https://github.com/TopGun2001/Cinema-Ticket-Booking-Application/blob/master/Images/Help.png)
##

![Movies](https://github.com/TopGun2001/Cinema-Ticket-Booking-Application/blob/master/Images/Movies.png)
##

![Theatre](https://github.com/TopGun2001/Cinema-Ticket-Booking-Application/blob/master/Images/Theatre.png)
##









