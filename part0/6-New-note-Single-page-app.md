sequenceDiagram
     participant browser
     participant server
     Note right of browser: spa page is already rendered in the browser
     browser->>>: POST https://studies.cs.heliskini.fi/exampleapp/new_note_spa    
     Note right of browser: note data is sent in json form     
     server-->>: Status Code: 201    
     Note right of browser: browser renders the notes with the new content

Example diagrams from the course were used in the creation of these diagrams.
