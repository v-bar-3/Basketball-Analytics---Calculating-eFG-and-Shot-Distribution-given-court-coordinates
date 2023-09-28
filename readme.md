This file was a small project I did for calculating NBA analytics for a side project.
I was provided with an image of a standard basketball court displaying the distances of each shot.

For the provided shot coordinate and outcome dataset, I was asked to determine the effective field goal percentage (eFG%= FGM+(0.5*3PM)/FGA) and percentage of team shots attempted (shot distribution)
within the following shot zones: Two Point (2PT), Non-Corner 3 (NC3), and Corner 3 (C3).

• For all “Non Corner” 3’s (where Y > 7.8), the 3PT line is 23.75 ft from the center of the hoop
• For all “Corner” 3’s (where Y <= 7.8), the 3PT line is 22 feet from the court’s Y-axis at all
points (note the definition of “Corner” 3 is not determined by the “break” in the arc)

The provided dataset had the schema:
• team: name of team (Team A, Team B)
• x: X-coordinate of the shot, measured in feet
• y: Y-coordinate of the shot, measured in feet
• fgmade: boolean value indicating the outcome of the shot (0=Miss, 1=Make)

I lost the original R file and dataset; currently, only the .txt file exists but the scripts are correct. 
