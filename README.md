# Roulette Game
Application inspired by the tv show "the game of roulette of luck".

Java application developed under a client-server architecture. Also used in this:
* Sockets for the communication process.
* Monitors and volatile variables for concurrency management.
* Swing for user views.

### Application Server

#### Configuration view 
Parameters needed for configuration
* Hidden phrase
* Clue
* Port

![img](https://github.com/GILLMtz/RouletteGame/blob/main/media/configurationServerApplication.png?raw=true)

#### Main view
![](mainViewServerApplication.png)



### Application Client

#### Configuration view
Parameters needed for configuration
* Ip Adress
* Port



![](configurationClientApplication.png)

#### Main View
![](mainViewClientApplication.png)

#### Player control to spin the roulette
To spin the spinner, the lever must be moved. This is activated by the following actions:

* Mouse

    By clicking on the lever and dragging the mouse down, the force is increased during the action. When the mouse is released, the desired force with which the roulette will rotate will be obtained.

* keydown 

    pressing the keydown key, this will cause the force to increase and once the desired level of force with which the roulette will turn is reached, only the pressed key should be released.


![](controller1ClientApplication.png)

#### Activating control for roulette spin
![](controller2ClientApplication.png)