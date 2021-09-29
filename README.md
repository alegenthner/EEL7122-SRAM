# EEL7122: SRAM design and simulation

Subject ministred by **Jader Alves de Lima Neto**
Task performed by **Alexandre Genthner**

## Proposed schematics and stimulus applied for read and write operation

Below can be seen the active schematics and its necessary signals for read (left) and write operation (right). It's also provided with a spectated signal output for the bitlines as well as for the charges voltages on the inverters terminals.

![enunciado](https://github.com/alegenthner/EEL7122-SRAM/blob/b26b26e40aaa8d07e686e9567f71016df153efba/img/read-write.png) 

## Cell layout

Simple SRAM layout with 6 transistors acting as memory cell.

![cell-layout](https://github.com/alegenthner/EEL7122-SRAM/blob/bf7b601881b835549e53f4352c26e3de3356b151/img/cell.png)

## Current sensor amplifier

Differently from the DRAM, I used a current-sensor since it's desirable to have a 'OUTPUT' signal.

![sa](https://github.com/alegenthner/EEL7122-SRAM/blob/77120c42368ce6fb165599987abd8ce323ce8669/img/current-sense-amplifier.png)

## Signals

Once defined and designed my SRAM project, the coerent signals stiulation proved to be troublesome. Those were obtain through the source on the image bellow, each with a specific '.txt' acting as a table for changes in voltage in accordance with time progression.

![sources](https://github.com/alegenthner/EEL7122-SRAM/blob/b26b26e40aaa8d07e686e9567f71016df153efba/img/sources.png)

## Write driver circuit

Separately was design the write driver, which can be seen bellow.

![write](https://github.com/alegenthner/EEL7122-SRAM/blob/b26b26e40aaa8d07e686e9567f71016df153efba/img/write-driver.png)

## System schematic

Bellow is the components derived from above topologies and structured as a top-level schematic.

![total-schematic](https://github.com/alegenthner/EEL7122-SRAM/blob/b26b26e40aaa8d07e686e9567f71016df153efba/img/system-schematic.png)

## Simulation results

As can be seen, once all signals were correctly inputed on the project, write and read operations were enable, defining the sucess and end of the task.

![signals](https://github.com/alegenthner/EEL7122-SRAM/blob/b26b26e40aaa8d07e686e9567f71016df153efba/img/signals.png)