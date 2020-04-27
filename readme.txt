[Tutorial] Installing Qt Creator on Ubuntu:

1) Go to https://account.qt.io/ and create an account (for now it's better to use a persoanl account so they don't detect as as commercial)
2) Go here https://www.ics.com/blog/getting-started-qt-and-qt-creator-linux and..

    2.1) From section "Assumptions and Prerequisites" ..
            -> do NOT run first command ($ sudo apt-get install qtcreator) ..it installs a barebone version of Qt
            -> DO run ($ sudo apt-get install build-essential libgl1-mesa-dev ) ..we need this library or we will get error later

    2.2) Follow the instructions from "Installation Steps"

    2.3) If you run the installer and you encounter an error like "libxkbcommon-x11-0 missing" ..follow this steps:
        2.3.1) Open terminal and insert following commands:
                    $ sudo apt update
                    $ sudo apt install libxkbcommon-x11-0

                ..this should do it

    2.4) When the installer runs..
        2.4.1) Log in with the account made at step (1)
        2.4.2) Pick version 5.14.2 [Filter by 'Latest releases' to find it]
        2.4.3) Don't worry if you're not sure what to select from 'Developer and Designer Tools' ..after the inital installation Qt can be easily modified with 'Maintain Qt' Tool (included with the install)

    2.5) Wait a while... 
    2.6) Launch Qt Creator :d
    2.7) In Qt go to Welcome -> Exemples -> Analog Clock Exemple and run it. If it works, everything is up and running.



