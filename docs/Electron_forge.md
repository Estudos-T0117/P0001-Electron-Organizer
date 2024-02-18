# About Electron Forge

Electron Forge is an all-in-one tool for packaging and distributing Electron applications. It combines many single-purpose packages to create a full build pipeline that works out of the box, complete with code signing, installers, and artifact publishing.

## Using Electron Forge

To use Electron Forge with your application, you can follow these steps:

1. **Starting your app:** Navigate to your app directory and start your app with the following commands:

    ```bash
    cd my-app
    npm start
    ```

2. **Building distributables:** Electron Forge can generate platform-specific distributables for you to share with everyone. You can build your app with the following command:

    ```bash
    npm run make
    npm start
    ```

3. **Publishing your app:** Electron Forge can publish the platform-specific distributables for you, using the publishing method of your choice. You can publish your app with the following command:

    ```bash
    npm run publish
    ```

## Advanced Usage

Once you’ve got a basic app starting, building, and publishing, it’s time to add your custom configuration, which can be done in the `forge.config.js` file.

For more detailed information, you can refer to the [Electron Forge](https://www.electronforge.io/) documentation.
