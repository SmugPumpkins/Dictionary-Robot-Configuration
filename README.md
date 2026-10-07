# Dictionary Robot Configuration

## Basic Premise

A robot stores its current configuration as a dictionary. Each setting has a meaningful label, making a dictionary more useful than a list for storing the information.

Your program will begin with the following dictionary:

```python
robot = {
    "name": "Atlas",
    "model": "RX-7",
    "battery": 85,
    "speed": 6,
    "mode": "exploration"
}
```

Your task is to access, modify, add, remove, and display information stored in the robot's configuration.

## Basic File Structure

```text
basic/
└── main.py
```

## Basic Requirements

* [ ] Use the provided `robot` dictionary and display the robot's `name` and `model` by accessing their keys.
* [ ] Change the value of `battery` to `100`.
* [ ] Add a new key named `color` with a value of your choice.
* [ ] Remove the `mode` key-value pair using `pop()`.
* [ ] Use `len()` to display how many key-value pairs are stored after the changes.
* [ ] Use a `for` loop with `items()` to display every remaining key and value in a readable format.

> Fully completing the Basic Requirements earns **16/20 marks, or 80%**.

## Basic Assessment — 16 Marks

| Assessment Item | Criteria | Marks |
|---|---|---:|
| Accessing Values | Correctly accesses and displays values using dictionary keys. | 2 |
| Changing Values | Correctly changes the value associated with an existing key. | 3 |
| Adding Data | Correctly adds a new key-value pair to the dictionary. | 3 |
| Removing Data | Correctly removes the required key-value pair using `pop()`. | 3 |
| Dictionary Length | Correctly uses `len()` to report the number of stored key-value pairs. | 2 |
| Traversing the Dictionary | Uses `items()` and a loop to clearly display all remaining keys and values. | 3 |
|  | **Total** | **16** |

## Advanced Premise

Extend the Basic program into an interactive **Robot Configuration Manager**.

The user should be able to look up and modify settings in the robot dictionary without needing to change the program's code.

Students can begin by copying their completed Basic program into the Advanced folder.

## Advanced File Structure

```text
advanced/
└── main.py
```

## Advanced Requirements

* [ ] Repeatedly display a menu that allows the user to **View All Settings**, **Look Up a Setting**, **Change a Setting**, **Add a Setting**, or **Exit**.
* [ ] Allow the user to enter a key and use `get()` to display its value without crashing if the key does not exist.
* [ ] Allow the user to change the value of an existing key.
* [ ] Allow the user to add a new key-value pair to the dictionary.
* [ ] Validate menu choices and prevent attempts to change keys that do not exist.
* [ ] Use error handling where appropriate so invalid user input does not crash the program and the user can try again.

## Advanced Assessment — 4 Marks

| Assessment Item | Criteria | Marks |
|---|---|---:|
| Dictionary Lookup | Allows the user to safely look up dictionary values using a key. | 1 |
| Editing Dictionary Data | Allows the user to change existing values and add new key-value pairs. | 1 |
| Input Validation | Prevents invalid menu choices and invalid dictionary operations. | 1 |
| Error Handling | Handles expected input errors without crashing and allows the user to try again. | 1 |
|  | **Total** | **4** |
