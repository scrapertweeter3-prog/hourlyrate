hourlyrate
==========

Macros for typesetting effective-hourly-rate comparison tables: restate
gig and side-job pay from the stated rate to the real hourly rate it nets
after unpaid drive time, unpaid setup and tool costs. One row per gig,
an assumptions line, and a small-print note under the table.

Usage
-----

    \usepackage{hourlyrate}
    \begin{hourlyrate}{October gig comparison}
      \hrassum{12 mile round trip, 20 minutes unpaid setup per shift}
      \hrrow{Warehouse shift}{\$18.00/hr}{\$2.10/hr}{\$15.90/hr}
      \hrrow{Food delivery block}{\$22.00/hr}{\$6.40/hr}{\$15.60/hr}
      \hrnote{Figures include self-employment tax set-aside.}
    \end{hourlyrate}

Commands: \hrassum, \hrrow, \hrnote. Depends on array only.

License: MIT. Copyright (c) 2026 James Verlander.
