## Bug report 1: Clicking the helicopter icon in Urban Routes Custom mode doesn't calculate travel time

# Description: 
Clicking Custom mode-> helicopter icon in the app Urban Routes doesn’t return calculation of the travel time of the chosen mode; after clicking the helicopter icon in Custom mode returns blank page

# Preconditions: 
The Server has already started.
Open the Network panel in DevTools 
Find the response types 
Right-click on Types-> Override content
Input the text which overrides sent: [{"id":"car","name":"Car","icons":{"inactive":"car.svg","active":"car-active.svg"}},{"id":"walk","name":"Walk","icons":{"inactive":"walk.svg","active":"walk-active.svg"}},{"id":"taxi","name":"Taxi","icons":{"inactive":"taxi.svg","active":"taxi-active.svg"}},{"id":"bike","name":"Bike","icons":{"inactive":"bike.svg","active":"bike-active.svg"}},{"id":"scooter","name":"Scooter","icons":{"inactive":"scooter.svg","active":"scooter-active.svg"}},{"id":"drive","name":"Drive","icons":{"inactive":"car.svg","active":"car-active.svg"}},{"id":"aero","name":"Air taxi","icons":{"inactive":"helicopter.svg","active":"helicopter-active.svg"}}]

# Steps: 
Type in the field From "East"
Type in the field To "1300"
Choose Custom mode from options below
Choose helicopter icon

# Expected result: 
In the Custom mode will appear helicopter icon. Choosing this icon will show approximate total time of travel by Aero Taxi(travel time(distance between points*the average speed of the vehicle during specific day time)

# Actual result: 
Choosing the icon helicopter refreshes the page. After refreshing the page is blank, nothing is displayed.

# Environment
Windows 11, Google Chrome Browser; Google Chrome version 130.0.6723.92 (Official Build) (64-bit)

## Bug report 2: Clicking the helicopter icon in Urban Routes Custom mode doesn't calculate travel cost

# Description:
Clicking Custom mode-> helicopter icon in the app Urban Routes doesn’t return calculation of the travel cost of the chosen mode; after clicking the helicopter icon in Custom mode returns blank page

# Preconditions:
The Server has already started.
Open the Network panel in DevTools
Find the response types
Right-click on Types-> Override content
Input the text which overrides sent: [{"id":"car","name":"Car","icons":{"inactive":"car.svg","active":"car-active.svg"}},{"id":"walk","name":"Walk","icons":{"inactive":"walk.svg","active":"walk-active.svg"}},{"id":"taxi","name":"Taxi","icons":{"inactive":"taxi.svg","active":"taxi-active.svg"}},{"id":"bike","name":"Bike","icons":{"inactive":"bike.svg","active":"bike-active.svg"}},{"id":"scooter","name":"Scooter","icons":{"inactive":"scooter.svg","active":"scooter-active.svg"}},{"id":"drive","name":"Drive","icons":{"inactive":"car.svg","active":"car-active.svg"}},{"id":"aero","name":"Air taxi","icons":{"inactive":"helicopter.svg","active":"helicopter-active.svg"}}]

# Steps:
Type in the field From "East"
Type in the field To "1300"
Choose Custom mode from options below
Choose helicopter icon

# Expected result: 
In the Custom mode will appear helicopter icon. Choosing this icon will show approximate total cost of travel by Aero Taxi(travel cost(travel time*average cost of the vehicle)

# Actual result: 
Choosing the icon helicopter refreshes the page. After refreshing the page is blank, nothing is displayed.

# Environment
Windows 11, Google Chrome Browser; Google Chrome version 130.0.6723.92 (Official Build) (64-bit)

## Bug report 3: Choosing helicopter icon in Custom mode of Urban Routes app doesn't retuen the approximate travel time and cost for Aero Taxi

# Description:
Clicking Custom mode-> helicopter icon in the app Urban Routes doesn’t return calculation of the travel time and cost for Aero Taxi; after clicking the helicopter icon in Custom mode returns blank page

# Preconditions: 
The Server has already started.
Open the Network panel in DevTools 
Find the response types 
Right-click on Types-> Override content
Input the text which overrides sent: [{"id":"car","name":"Car","icons":{"inactive":"car.svg","active":"car-active.svg"}},{"id":"walk","name":"Walk","icons":{"inactive":"walk.svg","active":"walk-active.svg"}},{"id":"taxi","name":"Taxi","icons":{"inactive":"taxi.svg","active":"taxi-active.svg"}},{"id":"bike","name":"Bike","icons":{"inactive":"bike.svg","active":"bike-active.svg"}},{"id":"scooter","name":"Scooter","icons":{"inactive":"scooter.svg","active":"scooter-active.svg"}},{"id":"drive","name":"Drive","icons":{"inactive":"car.svg","active":"car-active.svg"}},{"id":"aero","name":"Air taxi","icons":{"inactive":"helicopter.svg","active":"helicopter-active.svg"}}]

# Steps: 
Type in the field From "East"
Type in the field To "1300"
Choose Custom mode from options below
Choose helicopter icon

# Expected result: 
In the Custom mode will appear helicopter icon. Choosing this icon will show approximate total cost and travel time for Aero Taxi

# Actual result: 
Choosing the icon helicopter refreshes the page. After refreshing the page is blank, nothing is displayed.

# Environment
Windows 11, Google Chrome Browser; Google Chrome version 130.0.6723.92 (Official Build) (64-bit)