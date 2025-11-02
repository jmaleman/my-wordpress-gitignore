# My WordPress gitignore
This is my own version of gitignore based on official WordPress template gitignore at [Github](https://github.com/github/gitignore/blob/main/WordPress.gitignore).

## Motivation ✨
I always feel the need to update the .gitignore file, and honestly, it's kind of boring. (It's something I should have done a long time ago, and if you haven't done it yet, I recommend you do 😉).

## Content

### WSL
I usually use WSL (Windows Subsystem Linux) for development, and "Zone.Identifier" files are generated automatically when files are copied from Windows to Linux. There is a [solution](https://github.com/microsoft/WSL/issues/4609#issuecomment-2751663954) to avoid this, but if you don't want to “touch” anything, using gitignore will help you avoid having hundreds/thousands of unnecessary files in your repository.

### Package managers
NPM and PNPM
