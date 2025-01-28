Starting screen of reference: desktop (spotify-lg)

~~- header (upgrade button)~~
~~- navbar (left)~~
- footer (music player)

~~all 3 w/ position fixed & appropriate "z-index" (music player > navbar > header > main)~~

~~1- header w/ just the upgrade button~~
2- left navbar w/ logo on the top
    -> collapse left only @ xs viewport width
    -> behind the music player @ small heights
3- footer music player
    -> align content in 3 flexbox containers with justify-content:space-between & set internal flexboxes to rearrange icons with diminishing viewport width
4- main w/ overflow-y
    -> 6 columns @ viewport big -> then 4 @ viewport mid -> then just 2 @ viewport small & xs
    -> behind the music player @ small heights
    -> discover add highlight functions ~~& line behaves differently, maybe a simple <ul> w/ flexbox & small fixed padding~~ 
