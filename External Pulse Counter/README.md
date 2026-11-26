# External Pulse Counter

[Repository overview](../README.md)

Count external pulses and display the count when the display event is detected.

## Implementations

Timer 0 is used as an event counter rather than a time delay. The code clears the count when a sampled value equals 10; it does not implement a general multi-digit decimal counter.

| Implementation | Input | Output |
| --- | --- | --- |
| [Timer Zero Pulse Display](Timer%20Zero%20Pulse%20Display/README.md) | External pulses and display event | LCD count |
