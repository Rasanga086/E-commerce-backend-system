# How to Upload Your Code to GitHub

This guide explains step-by-step how to add your code to the GitHub repository using your own branch.

## Step 1: Open Terminal or Command Prompt
Open your terminal (on Mac/Linux) or Command Prompt / Git Bash (on Windows). Navigate to the project folder.
```bash
cd "path/to/E-Commerce Backend System"
```

## Step 2: Get the Latest Code
Before making any changes, always make sure you have the newest code from the main project.
```bash
git checkout main
git pull origin main
```

## Step 3: Create Your Own Branch
Create a new branch with your name or your feature. This keeps your work separate from others until it is ready.
```bash
git checkout -b feature/your_name_or_module
```
*For example: `git checkout -b feature/product_module` or `git checkout -b feature/dinal_product`*

## Step 4: Add Your Files
Make sure your files are saved in the correct place inside the `src` folder. Once your code is ready, tell Git to track your changes.
```bash
git add .
```
*(The dot `.` means add all changed files. You can also type specific file names instead of the dot.)*

## Step 5: Save (Commit) Your Changes
Save your changes with a short, clear message explaining what you did.
```bash
git commit -m "Added my module files"
```

## Step 6: Push to GitHub
Send your branch and your code to the GitHub website.
```bash
git push -u origin feature/your_name_or_module
```

## Step 7: Create a Pull Request (PR)
1. Go to the project page on the GitHub website.
2. You will see a green button that says "Compare & pull request". Click it.
3. Write a small description of what you did.
4. Click "Create pull request".
5. Ask your team members to check your code and merge it into the main branch.

You are done! Good job!
