# endless-sky-trade-balancing-tool
This is designed to assist in balancing trade on large map files with minimal effort.

Intended Features:

*The ability to set the trade prices at specific systems while using sets of rules to generate the rest of the prices automatically.

*A rule that will prevent the difference in price between two systems from being above a threshold that may be set.

*The ability to set a probability function for how much the difference between two systems will be.  (For example, will a price close to the threshold be just as likely as a price far from it.)

*An error message that will display if the slope between two manually set systems is beyond the bounds of the set rules.  (For example, if a system is set to have a price of 500 and a system two links away is set to 1000, then a maximum threshold of 200 would make it impossible to place a price for the middle system without going beyond the set threshold.)
