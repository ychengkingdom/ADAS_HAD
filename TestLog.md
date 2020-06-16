#Test Car Name     NIO ES6    Tesla Model3    Li ONE    GAC Aion LX 80
#Camera Number     7          8               5         5
#Radar Number      5          1               1         5
#UlRadar Number    12         12              12        12
#Total Price       398 k      271.55 k        328 k     279.6 k

#Test Item
##ACC
1. the distance following by the testing car can be adjustable.
   There may be several level of the distance.
2. the cruise speed can be set at whole range of the car.
   for example 80km/h.
3. test loop: the cruise speed is 80km/h, and the distance
   between front car and testing car is the shortest level.
   the front car brake to stop, and re-start again.

##High speed lane keep on curve
1. keep the cruise speed at 80km/h, and driving on the curve road.

##Autonomous Lane Change

##Special Scenario Recognization
1. cone obstacle on the road, and two lane combine to one.
   the testing car should recognize the cone obstacle, give positive
signals for the driver, take action to avoid the collision with obstacles
2. narrow road parking with obstacle. 
----------------------------------------
     ||||||       P    ||||||
     ||||||            ||||||
----------------------------------------
          ||||||
          ||||||
----------------------------------------
    ||||||   ||||||
    ||||||   ||||||
----------------------------------------

##AEB
1. Static obstacle, human model + tunnel inside
2. moving human model across the road. 5km/h
3. human model come out from other cars suddenly
4. cut-in cars

the speed of testing car is 40km/h

##Open public road testing
the distance of the test drive is 53km, and count the times of take-over.