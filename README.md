# Emberjs with Nanobox
This is the companion application for the [Emberjs: Getting Started](https://guides.nanobox.io/emberjs/) guide on [guides.nanobox.io](https://guides.nanobox.io) and is pre-configured and ready to run with [nanobox](https://desktop.nanobox.io/)!

## Up and Running

``` bash

# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-emberjs.git

# cd into the emberjs app
cd nanobox-emberjs

# build runtime and compile application
nanobox build

# deploy runtime to dev environment
nanobox dev deploy

# add a convenient way to access your app from the browser
nanobox dev dns add emberjs.nanobox.dev

# console into the dev environment
nanobox dev console

# run the application
ember server
```

Visit the app from your favorite browser at: `emberjs.nanobox.dev:8080`

### Now What?
For more details about how this works or for more advanced topics related to running Emberjs applications with nanobox visit [guides.nanobox.io/emberjs/](https://guides.nanobox.io/emberjs/)
