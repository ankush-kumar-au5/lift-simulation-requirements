# Lift-Simulation
Create a web app where you can simulate lift mechanics for a client

# UI Example
![Lift-Simulation-Example](https://user-images.githubusercontent.com/35886769/221520388-fe72b031-bb56-43f8-9c5e-a08ba93478d4.png)


# Requirements
  1. Have a page where you input the number of floors and lifts from the user
  2. An interactive UI is generated, where we have visual depictons of lifts and buttons on floors
  3. Upon clicking a particular button on the floor, a lift goes to that floor

  Milestone 1:
   - Data store that contains the state of your application data
   - JS Engine that is the controller for which lift goes where
   - Dumb UI that responds to controller's commands
   
  Milestone 2:
   - Lift having doors open in 2.5s, then closing in another 2.5s
   - Lift moving at 2s per floor
   - Lift stopping at every floor where it was called
   - Mobile friendly design

  Milestone 3:
  ![image](https://user-images.githubusercontent.com/35886769/221520578-56ca5f13-fbd1-4b69-8d1d-362d81a307a8.png)
  
  Requirements:
  Please provide a text box and a button to enter a lift number.
  This will immediately disable the lift and visually add a red border around the lift.
  This disabled lift will immediately go to the nearest floor and open the doors and keep it open. The lift will display the floor number its heading to.
  This lift should no longer participate in picking up other users who are requesting lifts on their floor.


