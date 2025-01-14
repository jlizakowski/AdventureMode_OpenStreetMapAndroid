# AdventureMode_OpenStreetMapAndroid
Why take the boring route? Configure OpenStreetMap on Android (OsmAnd) to take the roads less travelled.

## Purpose
Most maps assume that you want to get to your destination via the fastest or shortest path.  When driving for leisure, it's sometimes desireable to take the smaller roads that are slower, curvier, steeper, and more likely to be interesting. This xml file lets OsmAnd find those routes.

## Quickstart
* Note that OsmAnd can be obscure and difficult to configure at first. Don't give up. The app is very powerful once you understand it.
* Copy or download adventure_routing.xml to your device
* Settings -> New Profile (named "Adventure Mode", base it on 'Driving', pick an icon such as dune buggy, spaceship, or helicopter)  
* New profile -> Navigation Settings -> Navigation Type -> Import routing file (adventure_routing.xml)
* New profile -> Navigation Settings -> Navigation Type -> select adventure_routing.xml :: adventure_car
* New profile -> Navigation Settings -> Route Parameters -> Invert road speeds = On, Use elevation data = On

## Usage
When planning a route, use the top-left button to select the adventure_mode icon (as chosen above).  Routing will automatically use adventure mode in the profile.

## How does it work?
* Creates an alternate routing configuration that you can use when desired
* Inverts the priorities for road curviness, road speed, obstacles, transitions, and road type.
* Adjusts the routing to be more fine-grained to allow for complex routes
* Adds a config option for inverting road speeds.  This should be enabled for max effect, but makes time estimates unreliable.

## Caveats
* It is important to have the right spirit and attitude when using adventure mode.
* Expect the drive to be longer, slower, potentially challenging, and possibly result in backtracking.
* In some cases, the roads less-travelled might not be appropriate for your vehicle or driving skills.
* Occasionally, you will find an error in the map itself, where a hiking trail or private road was accidentally marked as a viable road.
* By inverting speeds, speed and time estimates become unreliable / useless.
* Adventure Routing can be very slow, potentially minutes, as it considers many more routes.
* If you go off the path, you will be re-routed, which now takes more time and battery power - try to keep the phone connected to a charger.


