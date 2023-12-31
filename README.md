# EpicFreeGamesBot

### Description
This is a Discord bot built with Node.js that shows what games are currently free on the Epic Games Store.

### Installation
1. Clone the repository: git clone https://github.com/eldoradomukaj/EpicFreeGamesBot.git
2. Navigate to the project directory: cd EpicFreeGamesBot
3. Install the dependencies: npm install

### Configuration
1. Rename the .env.example file to .env.
2. Open the .env file and provide the necessary configuration values:

        DISCORD_TOKEN=your_discord_bot_token
        CLIENT_ID=your_application_client_id
        GUILD_ID=your_server_id

### Usage
To start the bot, run the following command:
> npm run start

### Available Commands
    /free
    /ping 
    /server 
    /user

### Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.  


## Docker

### Building the docker image
1. Open a terminal or command prompt.
2. Navigate to your project directory where the Dockerfile is located.
3. Run the following command to build the Docker image:
> docker build -t <image_name> .

Replace <image_name> with the desired name for your Docker image. The . at the end of the command specifies the build context, which is the current directory.

### Run the docker image
1. After the image is successfully built, you can run it using the following command:
> docker run -e DISCORD_TOKEN=value -e CLIENT_ID=value -e GUILD_ID=value <image_name>