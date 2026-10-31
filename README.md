# Bus CARD for the QBUS64 of the PDP-11/Hack

A small bus card with 5 slots for the PDP-11/Hack. 

## QBUS64

The QBUS64 is derived from the Q-BUS of PDP-11. The QBUS64 uses the same
protocol and timing as the real Q-BUS. Main differences are

- The bus uses Eurocard sized PCBs
- QBUS64 uses DIN41612 connectors
- QBUS64 provides only 5V


## Power

The QBUS64 can either be powered via an USB-C power plug or via the
terminal block. 

## VBAT

The QBUS64 has a VBAT signal that allows to provide battery backup power
to the cards. The QBUS64 card has a vertical coin battery holder for
CR2032 cells. This cell allows for more battery baackup power than the
battery backup from the CR1220 used for the RTC on the PDP-11 CPU V2-3.
