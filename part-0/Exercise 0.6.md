sequenceDiagram
    

    Browser->>+Server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa (sending submission)
    
    Server-->>-Browser: receiving JSON file (without reloading whole page)
   
