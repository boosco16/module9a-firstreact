# Module 9A - Build Your First React Component

## Description
This is a React app created using Vite that renders a UserProfile component. The component includes a name, bio, and image styled with inline CSS.

## What I Learned
- How to set up a React project using Vite
- How to write and structure a functional React component
- How to use JSX and inline styles
- How to render a component in App.jsx

## Challenges
The biggest issue I ran into was that my project accidentally got created inside `C:\Windows\System32` instead of a normal folder, probably because I had Command Prompt open as Administrator. I didn't notice until I tried to save `UserProfile.jsx` in VS Code and got a permissions error (`EPERM: operation not permitted`), Windows doesn't let regular file edits happen in that system folder. I fixed it by closing everything, reopening a normal non-administrator Command Prompt, navigating to my Documents folder instead, and recreating the whole project there with `npm create vite@latest` again.

I also had a small hiccup pushing to GitHub — I accidentally typed `git remote add origin` twice in one line and included `< >` brackets around the URL from the instructions, which caused a syntax error. Removing the extra command and the brackets fixed it.

## Screenshot