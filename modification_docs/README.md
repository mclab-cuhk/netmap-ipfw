
This is the modification on dummynet-over-netmap

(1) To accept bandwidth limit profiles, variable over time

(2) Added a web UI for dummynet-over-netmap:

 (a) for managing rulesets (containing multiple pipes)

 (b) enforcing the pipes settings through web visually

 (c) allow restarting the dummynet core through web

 (d) real-time display of traffic activity in and out of the pipes

The bandwidth profile data is supplied as pair-wise "START TIME, BANDWIDTH LIMIT" per row in the data file.

The time slots per bandwidth limit can be variable with a granularity of down to 0.2 ms.
