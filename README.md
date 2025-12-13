# TAILWIND

I - Instalar o Node
    The best way to install Node.js on Linux is to use a package manager or Node Version Manager (NVM). Using NVM is generally recommended because it allows you to easily switch between multiple Node.js versions.


    * STEPS
    
        1. Open your terminal
        2. Install NVM by running the following command. You can always find the latest install script on the official NVM GitHub page (https://github.com/nvm-sh/nvm):

            > curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash

            Note: The version number (v0.39.5) might be outdated; check the GitHub page for the most current script version.

        3. Close and reopen your terminal for NVM to be properly sourced in your shell.
        4. Verify NVM installation by running command -v nvm. It should output nvm.
        5. Install Node.js.

            * To install the latest stable version, run:
                > nvm install --lts
                OR
                > nvm install node

            * To install a specific version (e.g., LTS version 20), run:
                > nvm install 20



II - Criar um pacote json
    > npm init -y

III - Instalar o Tailwind
    > npm install tailwindcss