<img src="/timetable-vcs-logo.svg" height="200px" alt="Logo" />

# Timetable to Calendar
This script allows Loughborough University students to easily import all lectures as events into a calendar.

_For those who don't have access to a lboro timetable, and for future reference, see the [example pages](./example/README.md)._

## How Do I Use It?
It's quite easy really and it should only take a miniute.

1. Download and install a userscript manager extension from the following:
    - [Tampermonkey](https://www.tampermonkey.net/)
    - [Violentmonkey](https://violentmonkey.github.io/)
2. Install this script [HERE](https://github.com/pavidal/timetable-userscript/releases/latest/download/script.user.js)
3. Open [your timetable](https://lucas.lboro.ac.uk/its_apx/f?p=250) and set the `Period` dropdown box as "Semester 1" or "Semester 2".
4. Click the `Download Calendar` button and save the `lectures.ics` file.
5. Import this file with your calendar service (such as Outlook or Google Calendar).

## For The Nerds
So the normies don't get scared off, the [documentation for nerds](/NERDS.md) is separate.

Report any issues or feature suggestions using the [issue tracker](https://github.com/pavidal/timetable-userscript/issues).
