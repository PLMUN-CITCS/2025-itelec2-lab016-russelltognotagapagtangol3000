# 2025-ITELEC2-LAB016
Week 05 - Working with Functions

Laboratory # 16 - Guided Coding Exercise: Basic Function Definition and Calling

## **Instructions**

### **Step 1.1: Accept the Assignment**

   1. Click on the assignment link provided by your instructor.
   2. GitHub Classroom will create a **private repository** under your GitHub account.
   3. After the repository is created, click **"Go to Repository"** to view your assignment.

---

### **Step 1.2: Setup your Git Environment**
Only perform this if this is the first time you will setup your Git Environment

   1. Create a GitHub Account:
   ```bash
   https://github.com/signup?source=login
   ```
      
   2. Download and Install Git on your Laptop/Desktop:
   ```bash
   https://git-scm.com/downloads
   ```
   
   3. Create a Folder in your Laptop/Desktop
   4. Right-click anywhere in the created folder and select "Open Git Bash Here".
   5. In the Git Bash Terminal, set your git name, perform command:
   ```bash
   git config --global user.name "Your Name"
   ```
   
   6. In the Git Bash Terminal, set your git email, perform command:
   ```bash
   git config --global user.email "your.email@example.com"
   ```
   
   7. Create your SSH Key, just follow the instructions, no need to provide filename and passphrase. In the Git Bash Terminal, perform command:
   ```bash
   ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
   ```
   
   8. Copy your SSH Keys into clipboard. In the Git Bash Terminal, perform command:
   ```bash
   clip < ~/.ssh/id_rsa.pub
   ```
   
   9. Log in to your GitHub account.
   10. In the upper-right corner of GitHub, click your profile picture and select Settings.
   11. In the left sidebar, click on SSH and GPG keys.
   12. Click the New SSH key button.
   13. In the Title field, give the key a recognizable name (e.g., "My Windows Laptop").
   14. In the Key field, CTRL + V or paste the keys copied into your clipboard. Save the key.
   15. Go Back to terminal, use command:
   ```bash
   ssh -T git@github.com
   ```

### **Step 2: Clone the Repository to Your Local Machine**

   1. On your repository page, click the green **"Code"** button.
   2. Copy the repository URL (choose HTTPS for simplicity).
   3. Open your terminal (or Git Bash, Command Prompt, or PowerShell) and run:
   
   ```bash
   git clone <git_repo_url>
   ```
   
   4. Navigate into the cloned folder:
   
   ```bash
   cd <git_cloned_folder>
   ```

### **Step 3: Complete the Assignment**

**Laboratory # 16 - Guided Coding Exercise: Basic Function Definition and Calling**

   **Objective:**
   - Understand how to define and call a simple user-defined function.
   - Learn the basic syntax of a function, including the use of the def keyword.
   - Recognize why functions are useful (code reuse, modularity, and clarity).

   **Desired Output (Example 1):**
   ```bash
   Hello, Python Students!
   ```
      
   **Notable Observations (to be discussed after completing the exercise):**
   - Functions are blocks of reusable code. Defining a function allows you to give a name to a specific task or set of actions.
   - Calling a function executes the code within its definition.
   - Functions promote code organization and make your programs more modular and easier to understand.
   - Docstrings are a valuable way to document your functions and explain what they do.

   **Python Best Practices**
   - Descriptive Function Names: Choose clear and descriptive names for your functions (e.g., greet is better than g).
   - Docstrings: Include a docstring for every function you write. This helps explain the function's purpose, arguments (if any), and return value (if any).
   - Indentation: Consistent indentation (4 spaces per level is standard) is crucial in Python. It defines the structure of your code and determines which code belongs to which function.
   - Function Purpose: Each function should ideally perform one specific task. This makes your code more modular and easier to maintain.
   - Test Thoroughly: Test your functions to ensure they work as expected.

   **Step-by-Step Instructions:**

   1. Setting up: Open your preferred Python environment or Text Editor, and create a Python Script.
      - Required Filename: `basic_function.py`
      
   2. Define the function (using def):
      - Use the def keyword followed by the function name (e.g., greet).
      - Add parentheses () after the function name. In this case, the function doesn't take any arguments, so the parentheses are empty.
      - End the line with a colon :.
```python
def greet():
```
      
   3. Add a docstring (optional but recommended):
      - Inside the function definition (indented), add a docstring. A docstring is a string literal enclosed in triple quotes ("""Docstring goes here""") that describes what the function does. It's good practice to include a docstring for every function you write.
```python
def greet():
    """Prints a greeting message."""  # Docstring
```

   4. Write the function body (indented):
      - Inside the function definition (indented), write the code that you want the function to execute. In this case, you want to print the greeting message.
```python
    print("Hello, Python Students!")  # Function body
```

   5. Call the function:
      - After the function definition (not indented), call the function by its name followed by parentheses (). This will execute the code inside the function.
```python
greet()
```

   6. Complete Code: Combine the steps above to form the complete program.
   7. Run the code: Execute your Python code.
   8. Observe the output: You should see the greeting message printed to the console.

   **Conclusion**
   This exercise introduced the fundamental concept of defining and calling functions in Python. You learned the basic syntax of a function, including the def keyword, parentheses, and the function body.  You also learned about the importance of docstrings and the benefits of using functions for code reuse, organization, and clarity. Functions are essential building blocks for creating more complex and maintainable Python programs.

### **Step 4: Push Changes to GitHub**
Once you've completed your changes, follow these steps to upload your work to your GitHub repository.

1. Check the status of your changes:
   Open the terminal and run:
   
```bash
git status
```
   This command shows any modified or new files.
   
2. Stage the changes:
   Add all modified files to staging:
   
```bash
git add .
```
   
3. Commit your changes:
   Write a meaningful commit message:
   
```bash
git commit -m "Submitting Python Week 04 - Laboratory # 16"
```
   
4. Push your changes to GitHub:
   Upload your changes to your remote repository:
   
```bash
git push origin main
```
