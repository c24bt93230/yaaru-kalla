# Yaru Kalla

This is a simple Kannada quiz game made for a school project.
Open the file `yaaru_kalla.html` in your browser to play the game.

## Project files
- `yaaru_kalla.html` - main game file
- `README.md` - instructions for teamwork and GitHub

## Open the project on your laptop
1. Open the project folder in VS Code.
2. Open `yaaru_kalla.html` in a browser.
3. If you want to run it on a local web server:

```bash
python3 -m http.server 8000
```

Then open this in the browser:

```text
http://localhost:8000/yaaru_kalla.html
```

## GitHub repo
This project is saved in GitHub here:

```text
https://github.com/c24bt93230/yarukalla.git
```

## Very important: how to work as a team
Always follow this order:

1. Pull the latest files
2. Do your work
3. Save changes
4. Commit your work
5. Push to GitHub

This helps everyone work in parallel without losing each other’s updates.

## Step 1: Download the project to your laptop
```bash
git clone https://github.com/c24bt93230/yarukalla.git
cd yarukalla
```

## Step 2: Before starting work, pull the latest version
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

## Step 4: Save your changes
```bash
git add .
git commit -m "Added my school project update"
```

## Step 5: Upload your work to GitHub
```bash
git push -u origin feature/your-name
```

## Step 6: After your work is checked, merge into main
Open GitHub in the browser and click:
- Compare & pull request
- Merge pull request
- Confirm merge

Then update your local project:
```bash
git checkout main
git pull origin main
```

## Simple teamwork flow
```bash
git checkout main
git pull origin main
git checkout -b feature/your-name
# do your changes

git add .
git commit -m "Updated project files"
git push -u origin feature/your-name
```

## If there is a conflict
Sometimes Git says there is a conflict when two people changed the same file.
Follow these steps:

```bash
git status
git pull origin main
```

Then open the conflicted file, fix the problem, and save it:

```bash
git add .
git commit -m "Resolved merge conflict"
git push origin main
```

## Quick command list
```bash
git clone https://github.com/c24bt93230/yarukalla.git
cd yarukalla
git checkout main
git pull origin main
git status
git add .
git commit -m "My update"
git push origin main
```

## Kannada + English summary
- First, `pull` the latest code.
- Then make your changes.
- After that, `commit` your work.
- Finally, `push` to GitHub.

ಮೊದಲಿಗೆ `pull` ಮಾಡಿ.
ನಂತರ ನಿಮ್ಮ ಕೆಲಸ ಮಾಡಬೇಕು.
ಅನಂತರ `commit` ಮಾಡಿ.
ಕೊನೆಯದಾಗಿ `push` ಮಾಡಿ.

This keeps the project safe and helps all project mates work together without overwriting each other’s work.

## Final note for school project team
- Always pull before you start
- Use your own branch
- Commit often
- Push your work safely
- Check the latest version before editing

This is a good way to work as a team and keep the school project organized.
