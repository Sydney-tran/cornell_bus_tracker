# cornell bus tracker

raspberry pi cornell bus tracker helps you to make the cornell bus on time!
with cornell_bus_tracker.py and a raspberry pi connected to led light strips, you will know when to leave your dorm room to catch the tcat bus from any stop just by looking at the leds in your room! just input the route, stop, direction, departure number and recieve real time departure info!

how it works and what it does:
- web scrapes tompkins tcat (aka cornell university bus) website that has real time information
- outputs departure time and minutes until departure which are updated every 20 seconds
- controls led light strips connected to raspberry pi to show minutes until departure
  - color slowly changes from blue to red as departure time approaches
  - number of pixels lit up in a row = number of minutes until departure time
  - at 5 minutes until departure, flashes leds on and off
