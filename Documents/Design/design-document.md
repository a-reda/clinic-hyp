---
header-includes:
  - \usepackage[T1]{fontenc}
  - \usepackage{fancyhdr}
  - \usepackage{pdflscape}
  - \graphicspath{ {Design/resources/diagrams/} {Design/resources/mockups/} }
---
\pagestyle{fancy}
\fancyhf{}
\fancyhead[RE,LO]{Reda Aissaoui, Zhanat Shengelbayeva and Lidong Zhang}

\input{Design/coverpage.tex}

\paperwidth=\pdfpageheight
\paperheight=\pdfpagewidth
\pdfpageheight=\paperheight
\pdfpagewidth=\paperwidth
\headwidth=\textheight

\begingroup
\large \textbf{C-IDM}
\includegraphics[width=20cm]{C-IDM}
\pagebreak
\large \textbf{L-IDM}
\includegraphics[width=20cm]{L-IDM}
\pagebreak
\large \textbf{P-IDM}
\includegraphics[width=20cm]{P-IDM}
\endgroup

\newpage
\paperwidth=\pdfpageheight
\paperheight=\pdfpagewidth
\pdfpageheight=\paperheight
\pdfpagewidth=\paperwidth
\headwidth=\textwidth

## Scenarios

### Scenario 1

**User** : Potential client

**Situation** : In need of a small surgery, the client is looking for clinics on Internet

**Goals** :
          - Check if the service is offered

**Actions** :  The user is on the homepage of the website. Since he doesn't know anything about the clinic, he first click on "Departments" on the menu bar to see the departments. After going through the departments, he finds the "Diagnostic imaging" department and read the description at the right text blok. And in the page all services in the department are displayed in "service offered area". From there, he clicks on "CT Scanning" to check if it is the specific service that he needs. After reading the service dscription he finds that it is the exactly one that he needs then he selects a doctor and clicks "view" in doctor list where lists doctors operating the service. Then the new page displays the doctors basic information.

### Scenario 2

**User** : Erick, usual client

**Situation** : Headache, is looking for Dr.August Collett

**Goals** :
            - To check if the doctor still works here and to make a reservation

**Actions** : Erick is on the home page and he goes by clicking the bottom “Doctors” on the menu onto the page of doctors and there will be displayed doctors in alphabetical order. He can easily then find the doctor and browse all his information. Just to make sure the doctor is still operating the same service as before then he clicks on "the service name" which is in the information table. Finally, to make an appointment, he has to click “Reservation” on the menu bar and then go to a page the to fill out the form. The client is asked for his name, e-mail and preferred date when the client would like to visit. After all that he will get the reservation E-mail.

### Scenario 3  

**Persona** : Claire, usual client

**Situation** : Claire likes the services of the clinic and wants to see what are the other services offered by the clinic

**Goals** :
            - Find other services offered by the clinic
            - Discover new locations

**Actions** : In the homepage of the website, the users sees a "Locations" button on the menu bar. After clicking, a map and list of all locations are displayed. The user can go and browse the services offered by each locations via clicking "read more". Claire discovers that a location is very close to her mother and they are offering "CT Scanning". She recommend it to her mother as she thinks it can be beneficial to her.

\pagebreak

## Wireframes
### Home Page
\includegraphics[width=\textwidth]{home-page}
\pagebreak

### Doctors
\includegraphics[width=\textwidth]{doctors}
\pagebreak

### Single doctor
\includegraphics[width=\textwidth]{single-doctor}
\pagebreak

### Departments
\includegraphics[width=\textwidth]{departments}
\pagebreak

### Locations
\includegraphics[width=\textwidth]{locations}
\pagebreak

### Single location
\includegraphics[width=\textwidth]{single-location}
\pagebreak

### Reservation form
\includegraphics[width=\textwidth]{reservation}

This page is used to create a reservation, the user needs to input his data and the reservation is created. After user input everything properly then all the data will be saved into database then **a confirming e-mail** will be sent to user and the e-mail contains all reservation information.

\pagebreak

### Services
\includegraphics[width=\textwidth]{services}
\pagebreak

### Single service
\includegraphics[width=\textwidth]{single-service}
\pagebreak

### News
\includegraphics[width=\textwidth]{news}
\pagebreak

### FAQ
\includegraphics[width=\textwidth]{faq}
\pagebreak

## Interactive mock-up

We used Axure RP 8.0 to design our website. Considering the conpatibility problem of different version of the app and also it might be a little bit bothering to download the app to check the project, we generated our project(.rp file) as html file for convenience. By opening start.html to start check out our mock-up.   

In case there is a problem to check the mock-up via previous way or you want to check the source file, please download the Axure latest version, check here https://www.axure.com/. After installing the app then open the .rp file in 'File' section then click preview which is at right top of menu bar. Besides also zooming the browser in a suitable viewing size in case of the mock-up is presented in a over size.
