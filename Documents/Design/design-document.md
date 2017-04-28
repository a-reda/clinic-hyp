---
header-includes:
  - \usepackage[T1]{fontenc}
  - \usepackage{fancyhdr}
  - \usepackage{pdflscape}
  - \graphicspath{ {Design/resources/diagrams/} }
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
\fancypagestyle{peculiar}{% use whatever name you please
  \fancyhf{}% clear
  \fancyfoot[R]{\thepage}
}
\includegraphics[width=20cm]{C-IDM}
\pagebreak
\includegraphics[width=20cm]{L-IDM}
\pagebreak
\includegraphics[width=20cm]{P-IDM}
\pagebreak
\endgroup

\newpage
\paperwidth=\pdfpageheight
\paperheight=\pdfpagewidth
\pdfpageheight=\paperheight
\pdfpagewidth=\paperwidth
\headwidth=\textwidth



## Bla bla bla

"sOn the other hand, we denounce with righteous indignation and dislike men who are so beguiled and demoralized by the charms of pleasure of the moment, so blinded by desire, that they cannot foresee the pain and trouble that are bound to ensue; and equal blame belongs to those who fail in their duty through weakness of will, which is the same as saying through shrinking from toil and pain. These cases are perfectly simple and easy to distinguish. In a free hour, when our power of choice is untrammelled and when nothing prevents our being able to do what we like best, every pleasure is to be welcomed and every pain avoided. But in certain circumstances and owing to the claims of duty or the obligations of business it will frequently occur that pleasures have to be repudiated and annoyances accepted. The wise man therefore always holds in these matters to this principle of selection: he rejects pleasures to secure other greater pleasures, or else he endures pains to avoid worse pains."


## Scenarios

### Scenario 1

**User** : Potential client

**Situation** : In need of a small surgery, the client is looking for clinics on Internet

**Goals** :
          - Check if the service is offered

**Actions** :  The user is on the homepage of the website. Since he doesn't know anything about the clinic, he first click on "Departments" on the menu bar to see the departments. After going through the departments, he finds the "General surgery" department. From there, he clicks on "Services offered" to check if the specific surgery he needs is offered. The website displays all the services offered by the General Surgery department. He can then click on the surgery he wants to learn more information.

### Scenario 2

**User** : Erick, usual client

**Situation** : Headache, is looking for Dr.Louis Hall

**Goals** :
            - To check if the doctor still works here and to make a reservation

**Actions** : Erick is on the home page and he goes by clicking the bottom “Doctors” on the menu onto the page of doctors and there will be displayed doctors in alphabetical order. He can easily then find the doctor and browse all his information. To make an appointment, he has to click “Practical info” on the menu bar and then go to “Make a reservation” the to fill out the form. The client is asked for his name, e-mail and preferred date when the client would like to visit.

### Scenario 3  

**Persona** : Claire, usual client

**Situation** : Claire likes the services of the clinic and wants to see what are the other services offered by the clinic

**Goals** :
            - Find other services offered by the clinic
            - Discover new locations

**Actions** : In the homepage of the website, the users sees a "Locations" button on the menu bar. After clicking, a map and list of all locations are displayed. The user can go and browse the services offered by each locations. Claire discovers that a location is very close to her mother and they are offering "Therapeutic nutrition". She recommend it to her mother as she thinks it can be beneficial to her.
