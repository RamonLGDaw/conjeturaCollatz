
# Collatz Conjecture

This project implements an interactive visualization of the Collatz Conjecture, a mathematical problem that involves a sequence of operations on integers. The Collatz Conjecture states that starting with any positive integer, if the number is even, you divide it by 2; if it’s odd, you multiply it by 3 and add 1. This process is repeated, and the conjecture claims that eventually, the sequence will reach the number 1. After reaching 1, the sequence enters an infinite cycle (1 -> 4 -> 2 -> 1).

This project allows users to input a number and see how this sequence develops step-by-step, visualizing the Collatz process interactively.

## Features
- Enter any positive integer to observe how the Collatz sequence unfolds.
- The sequence of operations is displayed step-by-step.
- Once the sequence reaches the cycle (1 -> 4 -> 2 -> 1), the number of operations is shown.

## Live Demo
You can try out the Collatz Conjecture visualizer live by visiting the following link:
[Try the Collatz Conjecture App](https://ramonlgdaw.github.io/conjeturaCollatz/)

## How to Use
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/RamonLGDaw/conjeturaCollatz.git
   ```

2. Open `index.html` in a web browser to start using the Collatz Conjecture visualizer.

3. Enter a positive integer in the input field and click "Calculate" to observe the sequence.

4. The sequence of operations will be displayed, showing the number and the operation applied (divide by 2 or multiply by 3 and add 1) at each step.

5. After reaching the cycle, the total number of operations is displayed.

6. You can enter another number without resetting the entire application.

## Project Structure
- `index.html`: The main HTML file that contains the structure and logic for the visualization. The project uses the **Bulma CSS framework** for styling, which is linked directly through a CDN.

## License
© 2023 Ramon Lage.

## Links
- **Portfolio:** [Visit my portfolio](https://ramonlage-portafolio.vercel.app/)
- **LinkedIn:** [Visit my LinkedIn](https://www.linkedin.com/in/ramonlagegibert/)