# FLAMES Game

FLAMES is a fun childhood game that determines the nature of the relationship between two individuals based on their names. The game results in one of the following outcomes: Friendship, Love, Affection, Marriage, Enemy, or Siblings.

## Game Rules

1. **Players**: Two participants input their names.
2. **Process**:
    - Both names are stripped of spaces and compared character by character.
    - Common letters between the names are removed.
    - The remaining letters are counted to generate a final number.
3. **FLAMES Calculation**:
    - The count is used to cycle through the letters F, L, A, M, E, S.
    - The final letter that remains determines the relationship outcome:
        - **F** stands for Friends.
        - **L** stands for Love.
        - **A** stands for Affection.
        - **M** stands for Marriage.
        - **E** stands for Enemy.
        - **S** stands for Siblings.
4. **Example**:
    ```python
    Enter Name1: Alice
    Enter Name2: Bob
    The relationship between Alice and Bob will end with Friendship.
    ```

## Input Format

When prompted to enter names:

- **Name1**: Enter the first name (e.g., Alice).
- **Name2**: Enter the second name (e.g., Bob).

Ensure the names are entered without any spaces, as spaces will be automatically removed.

## Usage

To run the FLAMES game:

1. Clone the repository to your local machine.
2. Run the Python script `flames.py`.
3. Follow the on-screen prompts to input the names.
4. View the relationship result based on the FLAMES algorithm.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please fork the repository and submit a pull request.

