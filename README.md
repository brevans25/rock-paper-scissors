# Rock, Paper, Scissors

For this exercise I used conditional statements to generate a simple game of RPS.

Used `import` to use the `random.choice()` method to generate a random response for the computer that got validated against the user's answered captured via `input()`.

Contrary to the exercise's instruction, I stored my options in a tuple named `options` and not a list.

Reason for that is that since the options would be always the same, `rock`, `paper` and `scissors`, I tried to be adventurous and use a tuple, which is inmutable.

To standardize the input, I used `lower()` to make sure user's input would be match items from `options`.

In addition to this, an `if` statement right in the beginning of the conditional block checks if the user entered anything other than the options listed in the tuple.

If that happens, a message alerts the user its input is invalid.

If a valid input is entered, the logic flows and allows the program to print a result to user, letting them know if they won or not.
