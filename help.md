To use cload service we need install firebase tools with:
> npm install firebase-tools -g

In case we get the error: "Error: Command requires authentication, please run firebase login," we could type "firebase login --interactive" then it will take you through the browser to a gmail account to sign in before you could execute your "firebase init" command.

> firebase init functions

To deploy:
> firebase deploy --only functions