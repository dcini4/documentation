=======
My time
=======

The :guilabel:`My Time` section of the *Time Off* application houses all the various time off
information for the signed-in user.

This includes the main *Time Off* dashboard, which displays an overview of the user's various time
off balances, as well as the user's time off requests and allocations.

.. _time_off/dashboard:

Dashboard
---------

All users have access to the time off dashboard, which is the default view in the *Time Off*
application. The dashboard can also be accessed at any point in the application by navigating to
:menuselection:`Time Off app --> My Time --> Dashboard`.

The current year is displayed, and the current day is highlighted in red.

To change the view, click on the :guilabel:`Year` button to reveal a drop-down menu. Then, select
either :guilabel:`Day`, :guilabel:`Week`, or :guilabel:`Month` to present the calendar in that
corresponding view.

To change the presented dates, click the :icon:`fa-arrow-left` :guilabel:`(left arrow)` or
:icon:`fa-arrow-right` :guilabel:`(right arrow)` icons to the left of the :guilabel:`Year` button.
The calendar view adjusts in increments of the presented view.

For example, if :guilabel:`Year` is selected, the arrows adjust the view by one year.

To change the view at any point to a view that includes the current date, click the
:guilabel:`Today` button.

Above the calendar view is a summary of the user's time off balances. Every time off type that has
been allocated appears in its own summary box. Each summary lists the type of time off, the
corresponding icon, the current available balance (in hours or days), and an expiration date (if
applicable).

To view the full details of a time off balance, click the :icon:`fa-question-circle-o`
:guilabel:`(question mark)` icon at the end of the :guilabel:`(DAYS/HOURS) AVAILABLE` on the time
off summary. The complete details are presented in a popover window, including the
:guilabel:`Allocated` time, future :guilabel:`Accrual` time, :guilabel:`Approved` time off
scheduled, :guilabel:`Planned` time off, and the currently :guilabel:`Available` time off.

.. image:: my_time/balance-details.png
   :align: center
   :alt: A view of the complete time off balance details in the popover window.

A user is also able to see how much time off they will have accrued in the future. On the right side
of the time off summary blocks, there is a :guilabel:`Balance at the (date)` field. Click on the
date, and a calendar selector popover appears.

The current date is the default date selected. Navigate to the desired date, and Odoo displays the
time off balances the user will have on that date. This takes into account all time off currently
planned and approved. To return to the current date, click the :guilabel:`Today` button to the right
of the date field.

On the right side of the calendar, the various time off types are displayed, with their
corresponding colors. The :guilabel:`Legend` explains how the various statuses for time off requests
are presented.

Time off that has been validated appears in a solid color (in the color specified in the
:guilabel:`Time Off Type` section above the :guilabel:`Legend`). Time off requests that still need
to be approved appear with white stripes in the color. Refused time off requests have a colored line
through the dates.

New time off requests can be made from the :guilabel:`Dashboard`. Click the :guilabel:`New` button
at the top of the dashboard, and a :doc:`New Time Off <request_time_off>` pop-up window appears.

New allocation requests can also be made from the :guilabel:`Dashboard`. Click the :guilabel:`New
Allocation Request` button at the top of the :guilabel:`Dashboard` to request more time off, and a
:ref:`New Allocation <time_off/request-allocation>` modal appears.

.. image:: my_time/dashboard.png
   :align: center
   :alt: Time off dashboard view with the legend, time off summaries, and view buttons highlighted.

.. _time_off/my-time-off:

My time off
-----------

To view a list of all the user's time off requests, navigate to :menuselection:`Time Off app --> My
Time --> My Time Off`. Here, all time off requests, both past and present, appear in a list view.

The list includes the following information for each request: the :guilabel:`Time Off Type`,
:guilabel:`Description`, :guilabel:`Start Date`, :guilabel:`End Date`, :guilabel:`Duration`, and the
:guilabel:`Status`.

A new time off request can be made from this view. Click the :guilabel:`New` button to
:doc:`request_time_off`

.. _time_off/my-allocations:

My allocations
--------------

To view a list of all the user's allocations, navigate to :menuselection:`Time Off app --> My Time
--> My Allocations`. All allocations and requested allocations appear in a list view.

The information presented on the :guilabel:`My Allocations` page includes: the :guilabel:`Time Off
Type`, :guilabel:`Description`, :guilabel:`Amount`, :guilabel:`Allocation Type`, and
:guilabel:`Status`.

A new allocation request can be made from this view, as well. Click the :guilabel:`New` button to
:ref:`request an allocation <time_off/request-allocation>`.
