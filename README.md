# Mee6-xp-tracker-thing

## Setup

### Packages

#### Normal Installation
- `pip install mee6-py-api` and `pip install discord.py`

#### Repl.it
- Go to packages tab and install `mee6-py-api` and `discord.py`

### Inserting Variables

#### IDE

- Replace `os.environ['API']` with the guild id of the server you want to use
  - To find guild id enable **Developer Mode** in discord
  - Right click the server 
  - Press **Copy ID**
- Replace `os.environ['CHANNELID']` with the channel you want the bot to send messages in
  - To find channel id enable **Developer Mode** in discord
  - Right click the channel  
  - Press **Copy ID**
- Replace `os.environ['TOKEN']` with the token of your bot 
  - To find bot token go to [discord](https://discord.com/developers/applications)
  - Select the application you want use
  - Go to sidebar and select **Bot**
  - Press **Copy** under **TOKEN**

#### Repl.it

- Go to sidebar and select **Secrets (Environment Variables)**
- Make three secrets with **key**: **API**, **CHANNELID**, and **TOKEN**
- Follow **IDE** steps to insert values

Run script and shit