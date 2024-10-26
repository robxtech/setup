# setup
New mac. Fresh code.

## Font
Fira Code - [https://fonts.google.com/specimen/Fira+Code]([url](https://fonts.google.com/specimen/Fira+Code))

## VS Code Settings
```
{
    "workbench.colorTheme": "Solarized Dark",
    "editor.fontFamily": "FiraCode Nerd Font Mono",
    "editor.fontLigatures": true,
}
```

Theme: Cobalt_RC
Theme: Tiny Light 
Font: FiraCode Nerd Font Mono
Extensions: 
- Better Folding
- Github Co Pilot
- Bracket Pair Color
- Code Spell Checker
- Error Lens
- GitLens
- Path Intellisense
- Prettier
- Pretty Typescript Error
- TODO Highlight
- TypeScript Import Sort
- Vue VSCode Snippets
- Vue language support
  
## Terminal
- install `zsh`
- zsh powerlevel10k
- zsh autosuggestions
- zsh syntaxhighlighting
- zsh autocomplete
- nvm (node version manager)

## SSH (Authorise pull from Github/Gitlab)
- Generate SSH keypair, add them to Github/Gitlab (Settings -> SSH keys), then add the private SSH key to your profile locally

  ```
  ssh-keygen -t ed25519-sk -C "<comment>"
  cat ~/.ssh/id_ed25519.pub (Add pub key to gitlab ssh keys)
  add ssh key to gitlab (https://gitlab.com/-/user_settings/ssh_keys/15437378)
  ssh-add ~/.ssh/id_ed25519 (add private key to local identity)
  ssh -T git@gitlab.com:ORGANISATION (get gitlab instance url)
  ```
  _NOTE: Do not copy paste the above code directly as it contains comments with instruction_
    
## OS
- Ice (menu bar hider)
- battery
- Flux

## Credentials
- Bitwarden (Chrome extension on each Chrome profile + App on iOS and Mac)


  <img width="395" alt="image" src="https://github.com/user-attachments/assets/22bd3797-ab87-45a2-bf24-9142a4734756">

## Business
- Slack
- Notion
- Trello
