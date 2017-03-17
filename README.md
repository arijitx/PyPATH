
      _____       _____     _______ _    _ 
      |  __ \     |  __ \ /\|__   __| |  | |
      | |__) |   _| |__) /  \  | |  | |__| |
      |  ___/ | | |  ___/ /\ \ | |  |  __  |
      | |   | |_| | |  / ____ \| |  | |  | |
      |_|    \__, |_| /_/    \_\_|  |_|  |_|
             __/ |                         
            |___/                          
            
# PyPath-0.1
PyPath is the unoffical Python wrapper of the PathaDisha App . 

# Pathadisha APP Description

This application is for commuters of Kolkata metropolitan area. By this application, commuters can view all incoming or outgoing buses for a particular stop or current location.

Commuter can also view all the buses operating on a particular route in real time on the map along with expected time of arrival (ETA).

<a href="https://play.google.com/store/apps/details?id=com.wbtransport.commuter&hl=en"> PlayStore Link </a>

# Implementations

## PathaDisha API

[:heavy_check_mark:] getAllRoutes<br>
[:heavy_check_mark:] getAllStoppages<br>
[:grey_exclamation:] getVehicleListByRecBoundary<br>
[:grey_exclamation:] getVehicleListByCirBoundary<br>
[:grey_exclamation:] getVehicleETA<br>
[:grey_exclamation:] getVehicleByRoute<br>
[:grey_exclamation:] getPointByRoute<br>
[:grey_exclamation:] getTripPlans<br>
[:grey_exclamation:] findNearestStop<br>
[:grey_exclamation:] getStoppagesInBoundary<br>
[:grey_exclamation:] getVehiclePosition<br>
[:grey_exclamation:] getRoutePathBetween2Stops<br>
[:grey_exclamation:] getTokenForRideShare<br>
[:heavy_check_mark:] getApproachingVehicles<br>
[:heavy_check_mark:] getLastRoueUpdateTime<br>
[:heavy_check_mark:] getKolkataTrafficUpdate<br>

## External API

[:grey_exclamation:] getVehicleETAGoogleTraffic<br>

# Endpoints

baseurl="http://167.114.174.89:8080/"<br>
baseurl_trip_planner="http://167.114.174.89:2080/"<br>

gist : https://gist.github.com/zed41/a9573209d782f8254b0a6694934274ef