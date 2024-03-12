<p align="center"><a href="https://www.uipath.com/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/de/2/21/UiPath_logo.svg" width="400" alt="Laravel Logo"></a></p>

# Election Automation
This project is a simulation of an automated electoral process using RPA with 'UiPath' tool. Afterwards, it sends the summary of votes to the local database.

## Installation
They should always be in the latest version of Studio. 
Otherwise, you can simply clone this repo and use the templates from here.
Check also the release page here:
https://github.com/UiPath-Services/StudioTemplates/releases

In this project, I'm using Google Forms to automate things. You can check out the form here: https://forms.gle/i2RomEZtgB398vTP6 

Additionally, to send data to the database, I'm recording the contents of the spreadsheet file (the form submissions) and then sending it to the local database. 
Here is the link to the spreadsheet : https://docs.google.com/spreadsheets/d/1aFGP3HuRU1WOkm5drd2T8mAJleHqmd9LEe8F4qOAh5Q/edit?usp=sharing 

## Usage
Remember: A "Template" project cannot be uploaded to Orchestrator. 

If you cloned this repository (instead of using the template from Studio):
1. Open the nuget that comes with the template
2. Otherwise, copy the project into a new *process* and don't use the *template* you cloned. It is not a normal *process*.
3. Don't forget to create the database first before running the robot. Use the local database that you usually use

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
