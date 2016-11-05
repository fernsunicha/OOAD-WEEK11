# OOAD-WEEK11
State Diagram
ภาพที่ 1


@startuml
[*] --> tv
tv --> [*]
tv : watch
tv -> Remote
Remote --> [*]
Remote :change the channel
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuOhMYbNGrRLJA2dZAYa3iu0Y8AQLGdbYIN86MDHE8IWrDxyabGj2mPL1kLR96ObvwQaA9Hcf2Y1cNceEbqDgNWhGV000)


ภาพที่ 2


@startuml
[*] --> coffeemaker
coffeemaker --> [*]
coffeemaker :make coffee
coffeemaker -> glass
glass --> [*]
glass :Coffee
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuOhMYbNGrRLJICvFIqjDpKtCJYtYGcA3vO1gKCIiG1HK1wfYEuNqdCJYOYum2TSBuLavGpGufEQb06q60000)


ภาพที่ 3


@startuml
[*] --> everydaylife
everydaylife --> wakeup
wakeup --> makework
makework --> sleep
sleep --> [*]
@endumll


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBYYjQALT3LjLD8BKijgan9hCp9J4lbGkQ0PSiJirDB2xWW55Wa5yWipo_Ave8nmAB5EQcf1LnW4im7ciu51WwfUIb02m40)


ภาพที่ 4


@startuml
[*] --> BoiledEgg
state BoiledEgg {
  state egg
  state pot
  state fire
  egg --> pot
  pot --> fire
  fire --> egg
}
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuOhMYbNGrRLJSChFp4bDSKrFv-BY0agMf2945Agv51GWOgb0UHYx8By4paxBB4e5Se3IOCCWKa0Ip8DAWYWm7sH8BHUNGsfU2j050000)


ภาพที่ 5


@startuml
[*] --> bangkok
bangkok --> ChiangMai
bangkok : SiamParagon
ChiangMai :Doi Inthanon National Park 
@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUAArefLqDMrKqXAp4lFpi_cWj9WCUUCJ23FDp4JBcgb49oPc1kGM9IOdf_7nGLNe63baf-fu9bNaf6Obv-du9TOafcVbvYZ05IPhS35vP2QbmAq3G00)
