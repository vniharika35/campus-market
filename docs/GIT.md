# Git & GitHub (Terminal + Browser)
Memory: R→S→C→P = Remote, Stage, Commit, Push

## Setup
git config --global user.name "Niharika Verma"
git config --global user.email "vniharika35@gmail.com"

## SSH
ssh-keygen -t ed25519 -a 100 -C "vniharika35@gmail.com" -f ~/.ssh/id_ed25519_campus
eval "$(ssh-agent -s)"
ssh-add --apple-use-keychain ~/.ssh/id_ed25519_campus
ssh -T git@github.com

## Branching model
- main: protected, release snapshots
- develop: integration branch
- feature/*: short-lived; PR → develop

## Daily loop
git switch -c feature/<thing>
# edit
git add .
git commit -m "feat: <summary>"
git push -u origin feature/<thing>
# open PR → develop → merge → git switch develop && git pull

## Protecting main
Use GitHub settings to require PRs (approvals=0 for solo). Back-merge main→develop when main changes.
