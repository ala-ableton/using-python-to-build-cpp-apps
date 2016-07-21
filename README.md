# Python as the keystone of building and testing C++ applications


## EuroPython 2016

This talk was given at [EuroPython 2016][EuroPython 2016]. It was recorded and
is available on [YouTube](https://youtu.be/CU178HUiPMA?t=2000).


## Abstract

At Ableton, we make [Live][Live], [Push][Push] and [Link][Link], unique software
and hardware for music creation and performance. Live is a C++ desktop
application built from a 15-year old code base. Push is an instrument embedding
a multicolor display which renders a [Qt Quick][Qt Quick] scene powered by
[Qt][Qt]. Link is a technology that keeps music devices in time and is available
to app developers as [LinkKit][LinkKit], an iOS SDK. “But what does all that
have to do with Python?”, you might ask.

This talk answers that question by explaining how our developers use Python to
build and test C, C++ and Objective-C source code. Based on [GYP][GYP], what we
call “build-system” is a collection of Python scripts that simplify our
workflows, and help us write better software. The three top-level scripts,
“configure.py”, “build.py” and “run.py”, share a common design which makes them
easy to use by developers, as well as easy to maintain and extend. This talk
describes the essence of that design, so you can apply it to your own project.


## Agenda

1. Ableton [[goto](https://youtu.be/CU178HUiPMA?t=2000)]
2. Building *Live* with Python [[goto](https://youtu.be/CU178HUiPMA?t=2122)]
3. *build-system*'s Hello World! [[goto](https://youtu.be/CU178HUiPMA?t=2335)]
4. Building complex applications with *build-system* [[goto](https://youtu.be/CU178HUiPMA?t=2601)]
5. Three scripts, one design [[goto](https://youtu.be/CU178HUiPMA?t=2671)]
6. Fail early, loud and clear [[goto](https://youtu.be/CU178HUiPMA?t=2758)]
7. Support custom defaults [[goto](https://youtu.be/CU178HUiPMA?t=2920)]
8. Do not integrate project specific features [[goto](https://youtu.be/CU178HUiPMA?t=3082)]
9. To wrap it up [[goto](https://youtu.be/CU178HUiPMA?t=3599)]


[EuroPython 2016]: https://ep2016.europython.eu/en/
[GYP]: https://gyp.gsrc.io/
[Link]: https://www.ableton.com/link/
[LinkKit]: https://ableton.github.io/linkkit/
[Live]: https://www.ableton.com/live/
[Push]: https://www.ableton.com/push/
[Qt Quick]: https://www.qt.io/qt-quick/
[Qt]: http://www.qt.io/
