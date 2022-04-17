The audios I did other than the intro (login) page's keyclack are all done by me. The keyclack is royalty free. The audios themselves and where they appear are listed below:

    index.html
    |   keyClack.wav        - When entering information into the input fields, had to create child elements so that audio could be played over itself
    mainPage.html
    |   bg_quiet.m4a        - Top right of page, user opts to play
    |   countdown.m4a       - When user presses 'Start' under Blastoff Countdown
    |   burnSeqInit.m4a     - When user pressed 'Start Burn' OR when countdown reaches 0
    |   maxQ.m4a            - When the apoapsis value reaches 13km (press Start Burn to begin)
    |   apoKarman.m4a       - When the apoapsis value reaches 95km
    |   stageSeperation.m4a - When the apoapsis value reaches 150km (also pauses loop for ~4s)
    |   apoGSO.m4a          - When the apoapsis value reaches 35,786km (don't worry, apoapsis climbs exponentially thanks to the equation on line 132)

The files that relate to this project specifically are (they have comments relating to what I did to complete the assignment):

    index.html              (Line 33)
    config/mainPage.html    (Lines 13-15 -- Lines 52-69)
    config/js/logincode.js  (Lines 48-57)
    config/js/code.js       (Line 12 -- Line 126 -- Lines 137-147)


-+-+-+-+-+- FILE SYSTEM -+-+-+-+-+-

    ├── index.html
    ├── README.md
    └── _config
        ├── mainPage.html
        ├── transition.html
        └── _content
        |   ├── apoGSO.m4a
        |   ├── apoKarman.m4a
        |   ├── bg_quiet.m4a
        |   ├── blastOffPic.gif
        |   ├── burnSeqInit.m4a
        |   ├── countdown.m4a
        |   ├── keyClack.wav
        |   ├── Logo.jpg
        |   ├── maxQ.m4a
        |   └── stageSeperation.m4a
        ├── _css
        |   ├── login.css
        |   └── styling.css
        └── _js
            ├── code.js
            └── logincode.js