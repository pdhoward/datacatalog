# Data Catalog App

This is a REACT frontend designed for OpenAI testing

## Structure of the app

This is meant to be a blueprint for your frontend, from which you can make minor color and logo changes or major component or page layout customizations.

    ├── cypress           # Integration tests
    ├── build             # The output of the build process
    ├── public            # The base files that the app builds with, like `index.html`
    ├── src               # This directory will contain all of the source code
    |   ├── assets        # Place to store images and content/config files
    |   ├── components    # Configure your page structure with the layout component
    │   ├── pages         # Components in this directory become pages automatically with paths based on their file name
    │   ├── services      # Provides the connections to the backend api
    |   └── templates     # Ideas for how to assemble components to display the data
    │   └── theme         # Add custom fonts, colors, and css here
    ├── package.json      # App dependencies

## Basic Customizations

- Edit the `src/assets/config.json` file to change the site title, slogan, logo, and container class.
- Edit the `src/theme/styles/_variables.scss` file to change the colors and fonts of your site.
- Add custom .scss files to `src/theme/styles/` to override the default css classes with your new color variables and other changes.
- Import your .scss files to `src/theme/styles/index.scss`
