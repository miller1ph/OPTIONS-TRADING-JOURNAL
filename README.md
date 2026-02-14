# OPTIONS-TRADING
## CUMULATIVE PROFIT (LOSS): $ 2,645.26
##
## ENTRY PARAMETERS:
### STRATEGY: HYBRID CALENDAR (PUT SIDE) & DIAGONAL (CALL SIDE)
### VIX = 14-18; VIX = 16 (Preferred)
### SHORT DTE: 40 DAYS
### LONG DTE: 60 DAYS
### SHORT DELTA: 20
### LONG DELTA: 25
#

## EXIT PARAMETERS (whichever comes first):
### DELTA: > +90 or < -90
### THETA < VEGA * 0.015
### GAMMA > -2
### SHORT DTE </= 14 DAYS
### UNDERLYING PRICE REACHED SHORT STRIKE
#
# TRADE #1: 
### Entry Date: December 26, 2025
### Short Feb 6, 655P; Short Feb 6, 715C; Long Feb 27, 655P; Long Feb 27, 720C
### Date Closed: January 13, 2026
### Reason for Closing: Theta < Vega * 0.015
### Result: WIN +$336.00
#
# TRADE #2: 
### Entry Date: January 14, 2026
### Short Feb 27, 660P; Short Feb 27, 710C; Long Mar 20, 660P; Long Mar 20, 715C
### Date Closed: February 13, 2026
### Reason for Closing: Short DTE = 14, Gamma > -2
### Result: WIN +$2,309.26
### Video: https://www.facebook.com/reel/880625461521377
