# TextMate Bundle for Testing with Steak

To install with Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git@github.com:neilmiddleton/Steak.tmbundle.git "Steak.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'


To install without Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    wget https://github.com/neilmiddleton/Steak.tmbundle/tarball/master
    tar zxf neilmiddleton-Steak.tmbundle-*.tar.gz
    rm neilmiddleton-Steak.tmbundle-*.tar.gz
    mv neilmiddleton-Steak.tmbundle-* "Steak.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Ruby 1.8.7 or greater is required.