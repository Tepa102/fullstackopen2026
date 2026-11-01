käyttäjä kirjoittaa uuden muistiinpanon

painaa tallenna jolloin se menee ja serverille

sequenceDiagram
    User ->> Page: Makes a new note
    User ->> Page: Presses the save button
    Page ->> Server: Send the note to be saved
    Server -->> Page: Confirmation of the save

