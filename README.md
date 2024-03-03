# mb
Tools for managing a music library with files that are tagged (associated with) musicbrainz (mb) resources.
These were developed in/for a Fedora Linux environment.
Your mileage may vary elsewhere.

## Deployment

Git this repository as appropriate. For examples,

    git clone https://github.com/rtyle/mb.git
    git clone git@github.com:rtyle/mb.git

Customize for the musicbrainz user, as file comments suggest.

    cd mb
    cp user.py{_,}
    vim user.py

## Dependencies

    sudo dnf install python3-musicbrainzngs
    sudo dnf install python3-mutagen

## Tools

### collectiondiff
Used to report differences between a collection of files and a musicbrainz collection of releases.
See built-in help.

    ./collectiondiff --help
