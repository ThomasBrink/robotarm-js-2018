# Robotarm

Lees de instructies op de wiki pagina hoe de robotarm bibliotheek werkt. Vervolgens ga je proberen de onderstaande oefeningen te maken.

## Oefening 1
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 1");

  // Je eigen code plaats je hier.
        robotArm.moveRight();
        robotArm.grab();
        robotArm.moveLeft();
        robotArm.drop();

  robotArm.run();
</script>
```
Verplaats het rode blok één plek naar links.

![Oefening 1](readme/exercise1.png)

## Oefening 2
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 2");

  // Je eigen code plaats je hier.
        robotArm.grab();
                for(var i=0; i<9; i++){
                    robotArm.moveRight();
                }

                robotArm.drop();

                for(var i=0; i<5; i++){
                    robotArm.moveLeft();
                }

                robotArm.grab();

                for(var i=0; i<5; i++){
                    robotArm.moveRight();
                }

                robotArm.drop();

                for(var i=0; i<2; i++){
                    robotArm.moveLeft();
                }

                robotArm.grab();

                for(var i=0; i<2; i++){
                    robotArm.moveRight();
                }

                robotArm.drop();
  robotArm.run();
</script>
```
Stappel alle blokken op aan de rechterkant.

![Oefening 2](readme/exercise2.png)

## Oefening 3
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 3");

          for(var i=0; i<4; i++){
                    robotArm.grab();
                    robotArm.moveRight();
                    robotArm.drop();
                    robotArm.moveLeft();
                }
            

  robotArm.run();
</script>
```
Verplaats de hele stapel blokken één plek naar rechts.

![Oefening 3](readme/exercise3.png)

## Oefening 4
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 4");

  // Je eigen code plaats je hier.
            robotArm.grab();

                for(var i=0; i<2; i++){
                    robotArm.moveRight();
                }

                robotArm.drop();

                for(var i=0; i<2; i++){
                    robotArm.moveLeft();
                }

                robotArm.grab();

                for(var i=0; i<3; i++){
                    robotArm.moveRight();
                }

                robotArm.drop();

                for(var i=0; i<3; i++){
                    robotArm.moveLeft();
                }

                robotArm.grab();

                robotArm.moveRight();

                robotArm.drop();

                for(var i=0; i<2; i++){
                    robotArm.moveRight();
                }

                robotArm.grab();

                for(var i=0; i<2; i++){
                    robotArm.moveLeft();
                }

                robotArm.drop();

                robotArm.moveRight();

                robotArm.grab();

                robotArm.moveLeft();

                robotArm.drop();

  robotArm.run();
</script>
```
Verplaats de hele stapel blokken één plek naar rechts. Zorg ervoor dat de volgorde van de blokken gelijk blijft.

![Oefening 4](readme/exercise4.png)

## Oefening 6
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 6");

  // Je eigen code plaats je hier.
        for(var i=0; i<7; i++){
                robotArm.moveRight();
            }

            robotArm.grab();

            robotArm.moveRight();

            robotArm.drop();

            for(var i=0; i<7; i++){
                robotArm.moveLeft();
                robotArm.moveLeft();
                robotArm.grab();
                robotArm.moveRight();
                robotArm.drop();
            }

  robotArm.run();
</script>
```
Verplaats alle blokken één plek naar rechts. Zorg ervoor dat de volgorde van de blokken gelijk blijft. 

![Oefening 5](readme/exercise6.png)

## Oefening 7
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 7");

  // Je eigen code plaats je hier.
                var block = 0;

                while(block < 6){

                    for(var i=0; i<4; i++){
                            robotArm.moveRight();
                            robotArm.grab();
                            robotArm.moveLeft();
                            robotArm.drop();


                            robotArm.moveRight();
                            robotArm.moveRight();
                            
                       }
                            robotArm.moveRight();
                            robotArm.grab();
                            robotArm.moveLeft();
                            robotArm.drop();

                        for(var i=0; i<10; i++){
                            robotArm.moveLeft();
                        }

                        block++;
                }
  robotArm.run();
</script>
```
Verplaats iedere stapel één plek naar links.

Je mag maximaal 13 regels code gebruiken!

![Oefening 6](readme/exercise7.png)

## Oefening 8
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 8");

  // Je eigen code plaats je hier.
                var blok = 0;

                    robotArm.moveRight();

                    while(blok < 7){
                        robotArm.grab();
                        for(var i=0; i<8; i++){
                            robotArm.moveRight();
                            }
                                robotArm.drop();

                                    for(var i=0; i<8; i++){
                                        robotArm.moveLeft();
                            }
                        blok++;
                    }

                    robotArm.moveLeft();

  robotArm.run();
</script>
```
Verplaats de stapel naar de rechterkant.

Je mag maximaal 13 regels code gebruiken!

![Oefening 7](readme/exercise8.png)

## Oefening 9
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 9");

  // Je eigen code plaats je hier.
                var blok = 0;
            var blok2 = 0;
            var blok3 = 0;
            var blok4 = 0;
                    while(blok < 1 ){
                        robotArm.grab();

                        for(var i=0; i<6; i++){
                            robotArm.moveRight();
                        }

                        robotArm.drop();

                        for(var i=0; i<6; i++){
                            robotArm.moveLeft();
                        }

                        blok++;

                    }

                robotArm.moveRight();

                    while(blok2 < 2){
                        robotArm.grab();

                        for(var i=0; i<6; i++){
                            robotArm.moveRight();
                        }

                        robotArm.drop();

                        for(var i=0; i<6; i++){
                            robotArm.moveLeft();
                        }

                        blok2++;

                    }

                robotArm.moveRight();

                    while(blok3 < 3){
                        robotArm.grab();

                        for(var i=0; i<6; i++){
                            robotArm.moveRight();
                        }

                        robotArm.drop();

                        for(var i=0; i<6; i++){
                            robotArm.moveLeft();
                        }

                        blok3++;

                    }

                robotArm.moveRight();

                    while(blok4 < 4){
                        robotArm.grab();

                        for(var i=0; i<6; i++){
                            robotArm.moveRight();
                        }

                        robotArm.drop();

                        for(var i=0; i<6; i++){
                            robotArm.moveLeft();
                        }

                        blok4++;

                    }
            

  robotArm.run();
</script>
```
Verplaats alle stapels vijf stappen naar rechts.

Je mag maximaal 15 regels code gebruiken!

![Oefening 8](readme/exercise9.png)

## Oefening 10
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 10");

  // Je eigen code plaats je hier.
        var Op = 0;
                var Right = 1;
                var Tw = 2;
                var EnP = 2;
                var TwP = 2;

                for(var i=0; i<4; i++){
                        robotArm.moveRight();
                    }

                do{

                    robotArm.grab();

                    for(var i=0; i<Right; i++){
                        robotArm.moveRight();
                    }

                    robotArm.drop();

                    for(var i=0; i<Tw; i++){
                        robotArm.moveLeft();
                    }

                    for(var i=0; i<EnP; i++){
                        Right++
                    }

                    for(var i=0; i<TwP; i++){
                        Tw++
                    }

                    EnP--
                    TwP--
                    Op++
                    EnP++
                    TwP++

                }


                while(Op < 5)

  robotArm.run();
</script>
```
Draai de volgorde van de blokken om.

Je mag maximaal 20 regels code gebruiken!

![Oefening 9](readme/exercise10.png)

## Oefening 11
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 11");

  // Je eigen code plaats je hier.

  robotArm.run();
</script>
```
Verplaats alle witte blokken één plek naar rechts. 

Let op, de blokken zijn iedere keer anders als je het programma start!

![Oefening 10](readme/exercise11.png)

## Oefening 12
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.loadLevel("exercise 12");

  // Je eigen code plaats je hier.

  robotArm.run();
</script>
```
Verplaats alle rode blokken naar het einde.

Let op, de blokken zijn iedere keer anders als je het programma start!

![Oefening 11](readme/exercise12.png)

## Oefening 13
```javascript
<script>
  var canvas = document.getElementById("canvas");
  var robotArm = new RobotArm(canvas);

  robotArm.randomLevel( 1, 8);

  // Je eigen code plaats je hier.
          var Left = 10;
                var rechts = 10;

                var move = true;
                while(move == true){
                    robotArm.moveRight();
                    robotArm.grab();
                    var color = robotArm.scan();
                    if(color != null){
                        rechts--

                        for(var i=0; i<rechts; i++){

                            robotArm.moveRight();
                            }

                            

                            robotArm.drop();

                            Left--

                        for(var i=0; i<Left; i++){
                            robotArm.moveLeft();
                        }



                    } 
                    else {
                        move = false;
                    }
                }

                    for(var i=0; i<11; i++){
                        robotArm.moveLeft();
                    }
                    robotArm.grab();

                    for(var i=0; i<11; i++){
                        robotArm.moveRight();
                    }

                    robotArm.drop();

                    for(var i=0; i<11; i++){
                        robotArm.moveLeft();
                    }

  robotArm.run();
</script>
```
Verplaats alle blokken over de lege plaatsen, zodra er geen blokken meer zijn moet de arm stoppen.

[Bonus opdrachten](https://www.dropbox.com/s/7q4o3xboi5whgop/RobotArm%20Puzzels.docx?dl=0)

Succes!
