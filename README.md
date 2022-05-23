# floating-lamp

A homemade levitating lamp powered by a microcontroller. There are two main parts to this project: levitation and power delivery.

## Levitation

Stable levitation is impossible to achieve with passive elements like magnets or charges, so this needs to be implemented with a combination of active and passive magnets: the lamp itself will contain passive magnets, perhaps in a [Halbach array](https://en.wikipedia.org/wiki/Halbach_array) to maximize their efficiency; the base, which will include the microcontroller, will have electromagnets whose strength will vary in response to the detected position of the lamp (how this should be done is to be determined).

## Power delivery

Resources to look into:

1. https://en.wikipedia.org/wiki/Wireless_power_transfer
