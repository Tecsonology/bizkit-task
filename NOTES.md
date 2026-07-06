1. The overlapping date issue: The logic is not correct leading to allowing booking to duplicate since the logic only checks if the dates cannot book prior to a start date. To fix this, i compare the booking start and due date to the iterated booking array or list in the dates_overlap funtion.  

2.  