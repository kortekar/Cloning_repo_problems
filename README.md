# Cloning_repo_🔪🔪🔪🔪🔪🔪🔪

#### Cloning needs Authentication sometimes ✍🏻 if its a private repo ❗️🚷
## ✅ Through SSH  ( open terminal enter the command below ) 👨🏻‍💻
      ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
### -> Add SSH key to SSH agent 🧑🏻‍💼
### -> start agent 👨🏻‍💻
      eval "$(ssh-agent -s)"
### -> add key 👩🏻‍🔧
      ssh-add ~/.ssh/id_rsa  
### -> to display the key  🧚🏻
      cat ~/your_key.pub 
### -> copy the entire  key🧟

## Add this Key to Gitlab💁🏻
👉🏻 Go to your GitLab account.

👉🏻 Navigate to "Settings" > "SSH Keys."

👉🏻 Paste the copied SSH key into the "Key" field and add a relevant title.

👉🏻 Click "Add Key."

### later you can clone through gitlab SSH url using 🪢
      git clone "your_ssh_url_copied_from_gitlab_repo"

# 🔪🔪🔪🔪🔪🔪🔪

## ✅ Through Access Token📲
### 🉐㊙️㊗️ Generate a GitLab access token
### 👉🏻 Use this command 
    git clone https://oauth2:<your-access-token>@gitlab.com/repo/project_name.git
### that’s eezy peezy  🐳





    
