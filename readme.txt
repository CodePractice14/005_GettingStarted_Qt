[Tutorial] Installing Qt Creator on Ubuntu:

1) Go to https://account.qt.io/ and create an account (for now it's better to use a persoanl account so they don't detect as as commercial)
2) Go here https://www.ics.com/blog/getting-started-qt-and-qt-creator-linux and..

    2.1) Follow the instructions from "Installation Steps" (second part of the page where we have to download the online installer)..NOT from "Assumptions and Prerequisites" (first part of the page)

    2.2) If you run the installer and you encounter an error like "libxkbcommon-x11-0 missing" ..follow this steps:
        2.2.1) Open terminal and insert following commands:
                    $ sudo apt update
                    $ sudo apt install libxkbcommon-x11-0
                ..this should do it

    2.3) When the installer runs..
        2.3.1) Log in with the account made at step (1)

    2.4) Wait a while... 
    2.5) Launch Qt Creator :d


