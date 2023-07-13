# linguafranca-cart
## Using the Lingua Franca Environment

To utilize the capabilities of the Lingua Franca language in a Windows system, it is most convenient to install the Lingua Franca extension for the Visual Studio Code environment (along with necessary additional tools such as Visual Studio Build Tools 2022 and Java SE Development Kit 17).

### State Machine Diagram

![cartmovement](https://github.com/kamilczernuszka/linguafranca-cart/assets/139373087/6676a1bd-0bd9-4d9b-b509-93cc1737a4b4)



The diagram represents the movement of the trolleys and includes identified and named individual places. The passages between the places are designed with conditions.

### Control Sequence

The control sequence for the trolleys' movement is as follows:

1. Press the Start button (signal m active) to initiate the movement of the trolleys.
2. The trolleys start from the leftmost positions, a and c, and independently reach points b and d.
3. The return of the trolleys is also independent of each other.
4. The process ends when both trolleys reach the leftmost positions, a and c.
5. Only when both trolleys have returned to their initial positions can the process be restarted by pressing the Start button.

### Repository Files

This repository includes the following files:

- `cartmovement.lf`: The Lingua Franca file in text (.lf) format.

Please refer to these files for further details and implementation.
