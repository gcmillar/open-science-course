Posts Summer 2019
=================

Week 1: Welcome and first two topics
------------------------------------

Welcome to the Tools for Open Geospatial Science course
which will uncover the world of reproducible science.

In this course, we will use Moodle for communication, assignment
submissions, and feedback. Furthermore, we will use the following
website which contains or links all the learning resources for the
course:

https://ncsu-geoforall-lab.github.io/open-science-course/

Please, read the above page to familiarize yourself with the course
structure, requirements, and schedule.

Each week, we will cover two topics and we will have a help session
which will be both on on-campus and on-line using Zoom.
Note: I may record the Zoom session, please let me know if that's a
problem.

This week's topics are open science and writing in open-science style.
Follow the provided material for each topic on your own and follow
the assignment instructions specified at the end of each topic's
material (links below).

https://ncsu-geoforall-lab.github.io/open-science-course/topics/open-science.html

https://ncsu-geoforall-lab.github.io/open-science-course/topics/writing.html

The first topic is introduction to and motivation for open science.
The second topic dives into writing tools often used in conjunction with
open science principles. It will get us ready for adopting potentially
a very new and very different mindset in the following weeks.

The suggested days for the topics are Tuesday and Thursday. Both
assignments are due on Monday next week.

Help session this week will be on Friday, 2-4pm. You are welcome to come
to campus, Jordan Hall, room 5119 or to join remotely (link will be
provided). In the mean time, post your questions on Moodle.

Heads up for the next week which is the 4th of July week:
The suggested days for the topics will be Monday and Wednesday and the
help session will be Monday afternoon.



Week 2: Revision control systems and command line
-------------------------------------------------

Here are the instructions for this week. Our topics are revision control
systems (topic 3) and command line (topic 4).
Specifically, we will work with Git and Linux.
The recommended order is to do revision control systems first and then
follow with the command line topic. However, if you think you need to
become comfortable with command line before executing any commands in
command line, then feel free to do them in the opposite order.

First, go through the text provided on revision control systems topic
page. Use the additional linked resources if you think it would be
helpful for you to have more context. There is a lot to know about
revision control systems and we will be only scratching the surface,
but that will actually cover almost all you need to know to use these
tools in your work. The linked videos will be good for absolute
beginners and the texts and documentation will be helpful in case you
already know a little bit about Git but want to know more. In any case,
you will need to install Git to be able follow the instructions.
Use NCSU VCL if you want to first try it in an environment where you
don't have to worry about breaking things.

https://ncsu-geoforall-lab.github.io/open-science-course/topics/revision-control.html

Please note also the section about software licenses. Although you can
use revision control systems in a completely private environment,
in context of open science, the typical use would involve publishing
the source code under an open source license. Thus understanding of what
that means is important to communicate to users and potential
collaborators what are your plans with the code. In the same regard,
it is important to know the license of the software or code you are
using.

Second, go through the instructions for the command line topic.
The focus is Linux for several reasons: It is most likely the
environment you will use in context of reproducibility as well as
hight performance computing. Many operating systems and command line
environments use a lot of the same concepts and syntax including
macOS command line and several different environments on Microsoft
Windows.

https://ncsu-geoforall-lab.github.io/open-science-course/topics/linux.html

To follow the instructions on the topic's page and to do the assignment,
you will need to use one of the above mentioned environments.
The easiest way is to use NCSU VCL, specifically one of the Ubuntu
machines. When you login in into the machine, use the terminal
application to input commands. If you have some experience with virtual
machines on your computer, you can run Ubuntu that way.
Alternatively, you can use terminal on macOS or, if you are using
Microsoft Windows, Git Bash from the revision
control systems topic. However, in that case some steps may be different
and thus the Ubuntu VCL machine is recommended if you are a beginner.

As for the assignments, the instructions are again at the end of each
topic's page.

For the revision control systems assignment, you don't need to submit
any link or text on Moodle unless you want to get some feedback.
In that case, ask on Moodle as usually. On the other hand, the last part
of the assignment requires everybody to submit a pull request on GitHub
(see the assignment for what that means).

The command line assignment will require a proper Linux computer.
The NCSU VCL Ubuntu machine is a great and easy choice.
The assignment involves finding out how many CPUs has the machine you
are working on. Although there are tools for that, we will use a
low-level custom approach to practice general command line skills.
Post the command as a (online) text into a Moodle assignment for
topic 4 (this time we are posting solutions privately).

Please do post questions to the forum as you are going through the
provided material, just don't post possible solutions for that CPU
command, so that others can come up with their own solutions.

Before you do the assignments it is highly recommended to actually
follow and try the instructions provided for each topic.

If you see something like Git for the first time, this topic may feel
like the most challenging one in this course. That actually may be true.
So don't get discouraged, give it some time, and ask questions.
We will continue using Git in this class and we will have some
opportunities to reiterate some of the concepts again.

The help session for this week is today (Monday, July 1), 2pm-4pm
on campus in Jordan Hall, room 5119, or remotely with Zoom:

Finally, just as a reminder, assignments for topics 1 and 2 are due
tonight.


Week 3: Geospatial command line and open source GIS
---------------------------------------------------

In the first topic for this week (topic 5), we are covering command line
tools for geospatial work, specifically GDAL and little bit of Python.
Python is considered the main scripting language used in geospatial
field and you have likely already heart about it. GDAL is a library and
a set of command line tools for geospatial data transformations and
processing and even if you have not heard about it, you have likely
used it because it is used in the background by many software packages
both open source and proprietary (You can see
`this list <https://gdal.org/software_using_gdal.html#software-using-gdal>`_
which is not even complete as far as I can tell).

For the second topic, you can choose to focus on QGIS or on GRASS GIS.
Both are good, although hardly the only, representatives of the open
source geospatial processing and desktop GIS landscape. The QGIS
topic is meant as a basic introduction while the GRASS GIS
topic is focused on usage of GRASS GIS in the context of open science.

Go through the instructions and examples about GDAL. For smooth
experience, I recommended to use an NCSU VCL Ubuntu machine, but
testing GDAL on your own computer is highly encouraged.

https://ncsu-geoforall-lab.github.io/open-science-course/topics/geospatial-command-line.html

Then take the part which is resampling the rasters and creating
an animated GIF and create a Bash script which does this procedure
without repeating commands. Optionally, include also download of the
file and its unpacking of needed so that your result can be reproduced
on any computer. Submit this file to Moodle assignment for topic 5.

The assignment for QGIS is to go through one of the text or video
tutorials linked at the instruction page. The recommended resource is
the *NCSU CGA Geospatial Studio by Jeff Essic*. The recommended
resource for GRASS GIS is the workshop called
*From GRASS GIS novice to power user*.

https://ncsu-geoforall-lab.github.io/open-science-course/topics/open-source-gis.html

Many of you already know QGIS or GRASS GIS or both
and no formal submission is required for this assignment
which gives you an opportunity to explore features of QGIS or GRASS GIS
in more depth in the area of your field or interest.
I encourage to share with us through the message board what you have
found.

There is an optional assignment in the GRASS GIS topic which you are
welcome to try. It is reproducing part of a published paper.
Even if you don't finish that, it will give you insights into
what reproducing a scientific paper involves.
We will get back to this in the topic 10 at the end of the course.

As always, ask on message board if you have some issues and you can also
share some things you learned if you want.


Help session announcement template
----------------------------------

The help session for the next week is scheduled for Day, Mon X,
Y-Zpm ET. On campus, we will meet in Jordan Hall, room N, and remotely
with Zoom:


Remote session description template
-----------------------------------

Tools for Open Geospatial Science X

Help Session: Tools for Open Geospatial Science, Week X
