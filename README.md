# PSoC5LP_PC-G850

This is an experiment to connect PC-G850 to PSoC5LP (CY8CKIT-059).

PSoC5LP is tolerance to 5V, so can connect direct to PC-G850 Z80 native bus.

## PSoC TEST Project

### BUS MONITOR

Z80 Bus monitoring expreriment with the /WAIT line pull down.

PSoC 5LP internal pull-up is weak, so needlong time to return HIGH level.


|Command|                        |
|-------|------------------------|
| "=","*" | DUMP BUS Capture FIFO|
| "-" | Reset Counter|
| "L" | Limit Mode (Capture stop when FIFO FULL)|



### IO PORT TEST
PC-G850 IO PORT Extending experiment with PSoC.

* OUT &H20,1 => LED ON