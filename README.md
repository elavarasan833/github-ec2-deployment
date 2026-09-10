# Git/GitHub to AWS EC2 Deployment

A static website deployed from GitHub to an AWS EC2 server using Nginx.

## Stack

Git Bash, GitHub, AWS EC2, Nginx

## Workflow

Local → Git → GitHub (main/development) → Pull Request → EC2 → Nginx

## Setup

git clone <your-repo-url>

## Deploy

./deploy.sh

## Update the live site

git pull origin main

./deploy.sh

## Common Commands

| Command | Meaning |

|---|---|

| git status | check changes |

| git add | stage changes |

| git commit | save a version |

| git push | upload to GitHub |

| git pull | download latest |
 
