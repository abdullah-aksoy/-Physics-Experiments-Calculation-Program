# Physics Experiments Calculation Program

This C program performs calculations for various physics experiments. The program calculates results for free fall, Atwood machine, air table, and ballistic pendulum experiments and displays them to the user.

## Features

- Calculates average time, experimental acceleration, delta acceleration, and error percentage for the free fall experiment.
- Calculates average time, experimental acceleration, expected acceleration, delta acceleration, and error percentage for the Atwood machine experiment.
- Calculates speed and acceleration for the air table experiment.
- Calculates the height reached by the ball, speed before collision, and speed immediately after collision for the ballistic pendulum experiment.

## Requirements

- C compiler (e.g., GCC)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/abdullah-aksoy/fizik-deneyleri
    cd fizik-deneyleri
    ```

2. Compile the program:
    ```sh
    gcc -o fizik-deneyleri fizik-deneyleri.c -lm
    ```

## Usage

1. Run the compiled program:
    ```sh
    ./Physics-Experiments-Calculation-Program 
    ```

2. Select an experiment from the menu and enter the required values.

## Code Explanation

The program performs the following steps:

1. Asks the user to select an experiment.
2. Takes the necessary values from the user based on the selected experiment.
3. Performs the calculations and displays the results.
4. Repeats these steps until the user exits.
