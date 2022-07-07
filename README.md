# Holy Grail Application

### Description

This program is a full-stack application which demonstrates how to create the Holy Grail of web design in combination with a back end server using node js and express as well as a datastore using redis which has been added on top of a docker container. The program maintains state locally but also reads from and updates the database as the user clicks the plus or minus icons within each section of the page. 

### How to Run

1. Navigate to [Get Docker](https://docs.docker.com/get-docker/) if you do not already have Docker installed, and install Docker for your machine.
2. Download the zip file in github and navigate to the **Holy-Grail-Application-main** directory in the terminal.
3. Run `docker run -p 6379:6379 --name some-redis -d redis` in the terminal.
4. Run `npm install`.
5. Run `node index.js`.
6. When that is complete, load **localhost:3000** in the browser. This will load the project in the browser.
7. Click on the plus and minus icons in the sections on the page to interact with the program.

### Roadmap of Future Improvements

- **Reset to Zero** - I plan to add a reset button which will allow the user to reset all the sections to zero.
- **Styling** - I plan to improve the styling of the page using bootstrap. 

### License Information
Completed as an assignment for the [MIT Professional Certificate in Coding: Full Stack Development with MERN](https://executive-ed.xpro.mit.edu/professional-certificate-coding?utm_source=Google&utm_medium=c&utm_term=mit%20coding&utm_location=1027726&utm_campaign=B-365D_US_GG_SE_PCC_Brand&utm_content=MIT-Coding___School_Duration&gclid=Cj0KCQiAweaNBhDEARIsAJ5hwbe5iGViYiDsRYlBGKAHHLbH-GiiJ16dKOBbV7tvosiu9UTfbS7tAygaAkW1EALw_wcB).

See [MIT license](https://github.com/brandontanner/Holy-Grail-Application/blob/main/LICENSE).
