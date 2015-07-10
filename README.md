
```
                     ________
M               M   /_  __/ /  ___
M M           M M    / / / _ \/ -_)
M M M       M M M   /_/_/_//_/\__/         __        ____
M M M M   M M M M     /  |/  /__ ________ / /  ___ _/ / /
M M M M M M M M M    / /|_/ / _ `/ __(_-</ _ \/ _ `/ / /
M M M M M M M M M   /_/__/_/\_,_/_/ /___/_//_/\_,_/_/_/  
M M M M M M M M M     / _ \_______    (_)__ ____/ /_
M M M M M M M M M    / ___/ __/ _ \  / / -_) __/ __/
M M M M M M M M M   /_/  /_/  \___/_/ /\__/\__/\__/
                                 |___/  
```

#Life Without Parole
##Authority and accountability in America's parole boards

Parole boards are vested with almost unlimited discretion to make decisions on almost any basis. Hearsay, rumor and instinct are all fair game. And unlike politicians, who are bound by open records and disclosure laws and are accountable to their constituents, parole boards often operate behind closed doors. Their decisions are largely unreviewable by courts — or anyone else.

A months-long Marshall Project investigation discovered that, in many states, parole boards are so deeply cautious about releasing prisoners who could come back to haunt them that they release only a small fraction of those eligible — and almost none who have committed violent offenses, even those who pose little danger and whom a judge clearly intended to go free. A recent revision of the Model Penal Code, an influential document written by legal scholars, declared parole boards “failed institutions.”

Our story, "[Life Without Parole](https://www.themarshallproject.org/2015/07/10/life-without-parole)," was published on July 10, 2015, with the Washington Post.

Included in this repo is [a csv](/data/parole_board_data.csv) of the [data](/data) collected by reporter Beth Schwartzapfel in the course of writing this story. Gabriel Dance and Tom Meagher used the data to make the charts that accompanied the story.

##Data sources and caveats

Beth Schwartzapfel collected information from each state using a combination of phone calls and emails with board staffers, information from the board websites and states' administrative codes and statutes. She also talked to many states about how they measure their release rates. If you're interested in seeing how your state grants parole, be sure to read [her tutorial on finding that data and the pitfalls to avoid](https://www.themarshallproject.org/2015/07/09/how-to-investigate-parole-release-rates-in-your-state).

##Walkthrough

###Columns in the CSV

* State: The state or the U.S. Parole Commission
* state_abbrev: USPS state abbreviations
* gov_appoint: Does the governor (or president, in the case of the U.S. Parole Commission), appoint the members?
* legis_confirm: Does the legislature confirm the board appointments?
* appointment_notes: Reporting notes on who appoints board members in that state
* release_authority: This column began with [a 2005 survey](http://www.apaintl.org/resources/documents/surveys/2005.pdf) by the Association of Paroling Authorities International and was confirmed and updated by reporting. The definition of each category confirms to those used in the APAI survey.
* authority_notes: Notes on limitations of the board's release discretion.
* authority_links: Links to additional information on the board.
* open_hearing: Are parole hearings open to the public? The category "UCC" means "Under certain circumstances". The limiting circumstances are generally explained in the accompanying notes field.
* file_available_to_public: Is an inmate's parole file, including risk assessments, prison disciplinary reports, and the like, available to the public via a Freedom of Information Act request or other means?
* file_available_to_prisoner: Is the file available to the prisoner himself?
* reason_issued: Must the board issue a reason to the prisoner for making its decision?
* transparency_notes: Additional notes on any of the transparency categories, particularly regarding meetings and files.
* transparency_links: Links to statutes and policies governing openness.

##Get Involved
If you write a story in your state using this data or our methodology, please tell us! Email audience editor Blair Hickman at bhickman@themarshallproject.org

##Contributors
* Beth Schwartzapfel
* Tom Meagher

##Bugs
If you have questions about the data, please email Tom at ```tmeagher@themarshallproject.org``` or file a [Github issue](https://github.com/themarshallproject/parole-boards/issues).
