## An example of Build Time secrets and Variables on balenaCloud.

This is an example of how to use the "Build time secrets and variables" feature of balenaCloud. You can find more documentation on this feature [here](https://www.balena.io/docs/learn/deploy/deployment/#build-time-secrets-and-variables).

This project is designed to work with [balena push](https://www.balena.io/docs/learn/deploy/deployment/#balena-push) and [balena deploy](https://www.balena.io/docs/learn/deploy/deployment/#balena-build--deploy)

**WARNING!!!** This is just an example and for that reason the `.balena` folder has been committed into the repo along with the code. In an actual project you should add the `.balena` folder to your `.gitignore` file so that your secrets are not exposed.