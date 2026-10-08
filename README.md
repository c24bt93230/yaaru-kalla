# Yaaru Kalla

Simple GitHub guide for school project teamwork.

## What is GitHub?
GitHub is a website where students can save code, share files, and work together on the same project.

## How classmates can work together
1. One student creates the GitHub repository.
2. Everyone else clones the project on their laptop.
3. Each student makes their own changes.
4. Everyone commits and pushes the files.
5. GitHub keeps the latest version in one place.

## Step 1: Clone the project
```bash
git clone https://github.com/c24bt93230/yarukalla.git
cd yarukalla
```

## Step 2: Check the latest version before starting
```bash
git checkout main
git pull origin main
```

## Step 3: Create your own branch
```bash
git checkout -b feature/your-name
```

Example:
```bash
git checkout -b feature/anu
```

## Step 4: Save your work
```bash
git add .
git commit -m "Updated project files"
```

## Step 5: Upload your work to GitHub
```bash
git push -u origin feature/your-name
```

## Step 6: Merge into main
After pushing, open GitHub and click:
- Compare & pull request
- Merge pull request

Then update your local project:
```bash
git checkout main
git pull origin main
```

## Easy daily workflow
```bash
git checkout main
git pull origin main
git checkout -b feature/your-name
# do your work

git add .
git commit -m "My changes"
git push -u origin feature/your-name
```

## Important rules
- Always pull before starting work.
- Do not overwrite other students’ files.
- Use your own branch.
- Commit with a clear message.
- Push your work after saving.

## Quick commands summary
```bash
git clone https://github.com/c24bt93230/yarukalla.git
cd yarukalla
git checkout main
git pull origin main
git checkout -b feature/your-name
git add .
git commit -m "My project update"
git push -u origin feature/your-name
```

## Simple Kannada meaning
ಮೊದಲಿಗೆ `pull` ಮಾಡಿ.\nನಂತರ ನಿಮ್ಮ ಕೆಲಸ ಮಾಡಬೇಕು.\nಅನಂತರ `commit` ಮಾಡಿ.\nಕೊನೆಯದಾಗಿ `push` ಮಾಡಿ.

This helps all classmates work together and keep the project updated.