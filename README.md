# Git Commands Quick Guide

Below is a quick guide to common Git commands for initializing and setting up a new repository on GitHub.

## Initialize a New Git Repository:

```bash
git init

##  Stages to Commit Git Repository:

Stage Changes for Commit:
git add .

Commit Changes:
git commit -m "Your commit message here"

## Rename the Default Branch to 'main':
git branch -M main

## Add a Remote Origin for Your GitHub Repository:
git remote add origin https://github.com/<username>/<repo name>.git


## Push Changes to GitHub:
git push -u origin main

## Solution to (Could get some authentication error)
at first the system asks for the credentials , give it a username and when it asks you a password in place of password give it a token.
## Token
genrate the token from the developers setting in the setting of the Git Hub, give the type of access you want to give to the token.

## Configure Git to Store Credentials:
git config --global credential.helper osxkeychain


## Remove Previous Credentials:
git credential-cache exit


## Check Configured User Name and Email:
git config --global user.name
git config --global user.email


## Remove Previous Remote Origin:
git remote remove origin


## Verify Remote URLs:
git remote -v


