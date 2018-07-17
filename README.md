# RedditSat

[![Join the chat at https://gitter.im/RedditSat/Lobby](https://badges.gitter.im/RedditSat/Lobby.svg)](https://gitter.im/RedditSat/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

An Atmega 328P AU powered pocketqube satellite focused on education and research, simplicity is a main focus. The craft will transmit a LoRa signal which can be heard using simple and cheap hardware. It will hopefully be the first 1P satellite to have deployable solar cells and a LoRa transmitter. More specific info on each system can be read in each section. No actual files have been uploaded due most of them being on my main PC while I am on holiday.

## Contributing
Any ideas & contributions are deeply apreciatted.

### Software
This plans to be in space, where it cannot be maintained. For that reason, the number one software priority is software. To help with this, keep the following in mind:

#### Use OTBS
This project uses [OTBS style](https://en.wikipedia.org/wiki/Indentation_style#1TBS) (K&R style but with braces whenever possible). This helps ensure code clarity and avoid mistakes that come from ambiguity.

#### Use The JPL Institutional Coding Standard 
The JPL created a coding standard with IEEE and NASA that you can read [here](https://lars-lab.jpl.nasa.gov/JPL_Coding_Standard_C.pdf). This standard makes sure that any code being produced will be as robust as possible. Please don't be intimidated by it, just keep the [Power of Ten](https://en.wikipedia.org/wiki/The_Power_of_10:_Rules_for_Developing_Safety-Critical_Code) in mind and we'll ask you to correct a merge request if necessary.

### Hardware
Please use KiCad or a file format that can be interpreted by KiCad. This makes sure that anyone can access and modify the hardware in this project without needing access to proprietary software.
