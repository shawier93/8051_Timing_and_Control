# Traffic Light Sequencer

[Repository overview](../README.md)

Repeatedly send a sequence of signal patterns to three output ports.

## Implementations

The timer-driven version advances through timed states. The software-delay version waits in instruction loops between six explicit patterns. Their timing mechanisms differ; neither delay should be stated in seconds without the clock and instruction timing.

| Implementation | Input | Output | Implementation notes |
| --- | --- | --- | --- |
| [Timer Driven Port States](Timer%20Driven%20Port%20States/README.md) | Reset and timing | P1, P2, P3 signals | Timer-driven output states |
| [Software Delay Six States](Software%20Delay%20Six%20States/README.md) | Reset and timing | P1, P2, P3 signals | Six explicit states with software delays |
