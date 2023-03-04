Project structure

  / ==> project folder
  
  /               media
  |---------------- |
  |                 |------cat.jpeg
  |-- index.html    |   
  |                 |        person  
  |                 |----------|
  |                            |--> person.png
  |                            |
  |                js
  |                 |
  |-----------------|
  |                 |--- index.js
  |                 |            main
  |                 |--------------|
  |                                |---- main.js
  |                                |
  |                                |      custom
  |                                |--------|
  |                                |        |
  |                                         | ---- others.js => ../../../../media/person/person.png
  |
  |
  |                                     app
  |                                       |
  |                                       |
  |-------------------------------------- |--- properties.config
  |                                       |
  |                                       |------- pom.xml
  |                                       |
  |                                       |------- sample.war
  |                                      
  |
  |
  |
  |      public
  |--------|
  |        |-----index.html
  |        |
  |        |     html
  |        |--------| 
  |        |        |-----index.html
  |
  |
  |
  |------------ Dockerfile
  |
  | 
  |------------ docker-compose.yml
  |
  |
  |
  |                 css
  |                 |
  |-----------------|
  |                 |-- main.css
  |                 |            styles
  |                 |--------------|
  |                                |---- darkmode.css
  |                                |
  |                                |----- clearmode.css
  |                                |
  |                                |     customization
  |                                |--------|
  |                                |        |
  |                                         | ----custom.css