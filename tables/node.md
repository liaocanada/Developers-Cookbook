| Action                                    | Command(s)                                                                                                                                                                                                                                                                  |
|-------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Install/add dependencies inÂ package.json | `npm install`<br/>`npm install --production`<br/>`npm install --save-dev <some-module>`                                                                                                                                                                                     |
| Run scripts defined in package.json       | `npm run <script>`<br/>`npm run test`                                                                                                                                                                                                                                       |
| Run a file                                | `node <path-to-some-file>`<br/>`node server.js`                                                                                                                                                                                                                             |
| Installation                              | `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash`<br/>`export NVM_DIR="${XDG_CONFIG_HOME/:-$HOME/.}nvm" [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm`<br/>`nvm install --lts`<br/>`npm --version`<br/>`node --version` |