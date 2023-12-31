### Repl.it (recommended)


- Visit the [dashboard](https://replit.com/~)
- Click the badge below.<br/>
   [![Run on Repl.it](https://replit.com/badge/github/localip/nitro-sniper)](https://repl.it/github/localip/nitro-sniper)

- Visit the environment variables tab.<br/>
   ![Image](https://media.wtf/52361997)

- Set the key as `settings` and paste [this](https://github.com/slow/nitro-sniper/wiki/Default-Configuration) inside the value text box; proceed to edit your configuration.

- After you are done editing your configuration, click `Add new secret`. (You can go back to that tab whenever to change your settings)<br/>
   ![Image](https://media.wtf/49612563)

- You can now use <kbd>CTRL</kbd> + <kbd>ENTER</kbd> or  <kbd>CMD</kbd> + <kbd>ENTER</kbd> to start the sniper or by using the `Run` button at the top of the page.

- Tips:
   - If you want to keep the sniper running 24/7 even when you shut down your PC, use [uptime robot](https://uptimerobot.com/) to ping the repl.it URL as seen here <br />
   ![Image](https://media.wtf/88041379) <br />
   - To see the output of the sniper, go to the `Console` tab. <br />
   ![Image](https://media.wtf/37329719)

### Local
- Make sure [Node v14+](https://nodejs.org/en/) is installed on your system and open a command prompt/terminal.
- Run `git clone https://github.com/localip/nitro-sniper nitro-sniper`
- Run `cd nitro-sniper`
- Run `npm install`
- Edit the .env file.
- Run `node .`

### Docker
- ```docker run -d -v `pwd`/.env:/app/.env nitro-sniper```