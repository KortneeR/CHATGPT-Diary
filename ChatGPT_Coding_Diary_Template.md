
# ChatGPT Coding Diary

## Project Name: _Maze Thing_

### Date: _1/7/2025_

---

## 1. **Task/Problem Description**

Briefly describe the problem you're trying to solve or the task you're working on.

> I am writing a program to create a maze that the player can navigate through.

---

## 2. **Initial Approach/Code**

Describe the initial approach you took to solving the problem. If you started writing code, include it here.

```python

def puzzle_one():
    if player_pos == [5, 5]:
        print("what has hands but cannot clap?")
        answer_one = "a clock".upper()
        user_input = input("Your answer: ").upper()
        if user_input == answer_one:
            print("what is not living, but can die?")
            answer_two = "a battery".upper()
            user_input = input("Your answer: ").upper()
            if user_input == answer_two:
                print("i have keys but no locks. I have space but no room. you can enter but you can't go outside. what am I?")
                answer_three = "a keyboard".upper()
                user_input = input("Your answer: ").upper()
                if user_input == answer_three:
                    print("wowie, first puzzle done!")
 
```

- What was your plan for solving the problem?

My problem was the error handling system not functioning. 

- Did you have any initial thoughts or strategies before using ChatGPT?

I reorganized it in different ways but it still did not work. 

---

## 3. **Interaction with ChatGPT**

### Questions/Requests to ChatGPT
Write down the questions or requests you made to ChatGPT. 
Also include what code from ChatGPT you are unsure of and craft a question that asks for further clarification. 

- "How can I customize a maze using ascii?"
- "How to call the puzzle function the momemnt the player interacts with the number icon?"
- "How to use a variable in multiple locations?"

---

## 4. **ChatGPT's Suggestions/Code Changes**

Record the code or suggestions ChatGPT provided. Include any changes or improvements ChatGPT suggested and how it influenced your approach.

```python
# ChatGPT suggested using a custom sorting algorithm to improve efficiency
def optimized_sort(numbers):
    # Implementation of a more efficient sorting algorithm
    pass
```

- What was ChatGPT's solution or suggestion?
- How did it differ from your original approach?

---

## 5. **Reflection on Changes**

Reflect on the changes made to your code after ChatGPT's suggestions. Answer the following questions:

- Why do you think ChatGPT's suggestions are helpful or relevant?
- Did the suggestions improve your code? How?
- Did you understand why the changes were made, or are you still uncertain about some parts?

Example:
> ChatGPT recommended using a more efficient sorting algorithm like quicksort. I think this will improve the runtime for large inputs, but I need to review the algorithm's complexity to fully understand its advantages.

---

## 6. **Testing and Results**

After making the changes, did you test your code? What were the results?

- Did you run any tests (e.g., unit tests, edge cases)?
- Did the code work as expected after incorporating ChatGPT's changes?

```python
# Example: Testing the updated sorting function
numbers = [5, 2, 9, 1]
print(optimized_sort(numbers))  # Expected output: [1, 2, 5, 9]
```

- Did you encounter any bugs or issues during testing?

---

## 7. **What Did You Learn?**

In this section, reflect on what you learned from this coding session. Did you gain any new insights, or were there areas you still struggled with? 

Example:
> I learned how to implement an efficient sorting algorithm, and I now understand the time complexity differences between various sorting methods.

---
