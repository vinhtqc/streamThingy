This repository consists of two binary firmware files for streaming accelerometer data from Thingy52 to PC through a nrf52DK brigde in between. Thing52 stream data to nrf52DK via bluetooth connection, and nrf52DK forward the data to PC via USB.

The firmware file for Thingy52 named datastream.hex, and for nrf52DK named central_uart.hex.
Flash the device using "Programmer" tool in "nrf Connect for Desktop".

After flashing the devices, hold the button on Thingy for 5 sec until it turn to red. Then it auto connects and transfers data to the nrf52DK board, and LED flash quickly in red.
