# entornoVirtualAngular
Actividad de la asignatura Desarrollo Web en Entorno Cliente

1

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

2

wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

3

export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

4 Verify Installation

command -v nvm

nvm -v

nvm install v14.15.5 --alias angular-v14

nvm curernt

nvm use 14

npm install -g @angular/cli@14