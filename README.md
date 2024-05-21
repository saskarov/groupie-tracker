### Description

Groupie Trackers consists on receiving a given API and manipulate the data contained in it, in order to create a site, displaying the information.

API consists in four parts:

The first one, artists, containing information about some bands and artists like their name(s), image, in which year they began their activity, the date of their first album and the members.

The second one, locations, consists in their last and/or upcoming concert locations.

The third one, dates, consists in their last and/or upcoming concert dates.

And the last one, relation, does the link between all the other parts, artists, dates and locations.

Groupie-tracker-search-bar consists of creating a functional program that searches, inside the website, for a specific input text.

    The program handles at least these search cases :
        artist/band name
        members
        locations
        first album date
        creation date
    The program handle case sensitive.
    The search bar has typing suggestions as you write.
        The search bar identifies and displays in each suggestion the individual type of the search cases. (ex: Freddie Mercury -> member)
        For example if you start writing "phil" it would appear as suggestions Phil Collins - member and Phil Collins - artist/band. This is just an example of a display.



## Run Locally
- Clone the project
- Go to the project directory
- Start the server

```bash
  go run main.go
```
