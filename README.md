# OOAD-WEEK11
##State Diagram  5 ภาพ และ Activity Diagram 5 ภาพ


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


##Activity Diagram 5 ภาพ


ภาพที่ 1


@startuml

(*) --> "walk"
"walk" --> (*)

@enduml



![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBIqD9KqDMrKr0gJyp9LkA2K60He0mNbqDgNWfG7G00)

ภาพที่ 2


@startuml

(*) --> "gotoschool"
-->"get in a car"
--> (*)

@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBIqD9KqDMrKr1Apo_9BqxEoC_FKU822YYbfvOePEOf92ea9nQ1HHI0Ihcu75BpKe0Q0G00)


ภาพที่ 3


@startuml
(*) --> "to night"

if "go party" then
  -->[true] "meeting friends"
  --> "dressed up"
  -right-> (*)
else
  ->[false] "take a shower"
  -->[sleep] (*)
endif

@enduml


![](http://www.plantuml.com/plantuml/img/BOv13eD024NtdEA7LTl4AnZlOLnCCimugOvcm3IzVL6xWZm-3mQrqEnO5tgydkYw7cmRQicpCL59uBnXzyYNORDKmXaQhHqoWLSHApKZjI8rAjzJS6oYAX77Vg5swfpx2P95vMJzc8AtBh7m5WJel7sa_HMZBYBxT6_KM1BHuDN__040)


ภาพที่ 4


@startuml
(*)  --> "go gym"
If "what paly" then
--> [Yes] "weight training"
--> "cardio"
else
--> "cardio"
Endif
-->(*)
@enduml


![](http://www.plantuml.com/plantuml/img/LOqn2iCm301tlK9eQWlvGiZIeKy8fOEe5LlWAC5MAVbzd6nPxmvkgCx5VtE6s-EEs7KzKbmmRZF1QqBw9tPSEM-4diJW2DwZr4zJeZ4vUc4rjKYdeo-Ne0k1v2fNyhIWqu7Q2GQnqAux)

ภาพที่ 5


@startuml

(*) --> ===B1=== 
--> "go paris"
--> ===B2===

===B1=== --> "go japan"
--> ===B2===

--> (*)

@enduml


![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBIqD9KqDMrKx2rjNKo118AN22UKdg-Ga5YKMQn4XTCqWX8S771bS5KPIKM9EQXgmBnW0PpSJcavgK0hG40)
