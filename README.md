# Tideman Election

This program simulates an election using the Tideman method. The Tideman method is a voting system that utilizes voter preferences to determine the winning candidate.

## Compilation

To compile the program, use the following command:

`$ gcc -o tideman tideman.c -lcs50`

Make sure the `cs50` library is installed on your system.

## Usage

Run the compiled program with the following command:

`$ ./tideman [candidate1] [candidate2] ...`


Replace `[candidate1]`, `[candidate2]`, etc. with the names of the candidates participating in the election. You can include up to 9 candidates.

Upon running the program, you will be prompted to enter the number of voters and record the vote preferences of each voter. Enter the preference rank of each candidate according to their preference order. For example, if there are 3 candidates and you prefer the second candidate as the first choice, the third candidate as the second choice, and the first candidate as the third choice, you should enter: `2 3 1`.

After recording the preferences of all voters, the program will determine the winner of the election according to the Tideman method and display the result.

## Contributions

Contributions for improvements and bug fixes are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## References

CS50 Library: https://cs50.harvard.edu/x/2023/library/

CS50 - Introduction to Computer Science course: https://cs50.harvard.edu/x/2023/

This program was developed as part of the CS50 - Introduction to Computer Science course at Harvard University.
