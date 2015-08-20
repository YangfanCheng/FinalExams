Final Exams Schedule Builder
==============
Helps NJIT students build a schedule of their final exams. This is done using DOM manipulations of the table found on NJIT's [final exams website.](http://www.njit.edu/registrar/exams/finalexams.php)

The DOM manipulations are done client-side using jQuery. The `*.php` file is used to bypass [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS).

This project is hosted on https://web.njit.edu/~ss2666/finalexams.html

Components
--------------
This project makes use of the following libraries:

* [Bootstrap](https://github.com/twbs/bootstrap) for design.
* [Font Awesome](https://github.com/FortAwesome/Font-Awesome/) for icons.
* [jQuery](https://github.com/jquery/jquery) for making everything easier.
* [lunr.js](https://github.com/olivernn/lunr.js) for searching.
* [FileSaver.js](https://github.com/eligrey/FileSaver.js) to save the `*.ics` file.
* Google Drive API library to upload the file to your Google Drive.

Contributors
--------------
Project by Shahar Sarfati. Personal website can be found at https://web.njit.edu/~ss2666/.

License
--------------
No license, feel free to use this project as you like.
