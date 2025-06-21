## Instalasi

- Download the starter project [citycareapp-starter-project.zip](https://raw.githubusercontent.com/dicodingacademy/a219-web-intermediate-labs/099-shared-files/citycareapp-starter-project.zip).
- Unzip the downloaded ZIP file. You can use the following command for Linux::
  ```bash
  unzip ./citycareapp-starter-project.zip
  ```

- Enter the project directory:
  ```bash
  cd citycareapp-starter-project
  ```

- Install all dependencies:
  ```bash
  npm install
  ```

## Scripts

- `npm run build`: Creates a production build using Webpack.
- `npm run start-dev`: Runs the development server using Webpack Dev Server.
- `npm run serve`: Runs a HTTP server for the built project.
- `npm run prettier`: Checks code formatting using Prettier.
- `npm run prettier:write`: Reformats code using Prettier.

## Struktur Proyek

```plaintext
citycareapp
├── package.json            # Project dependencies information
├── package-lock.json       # Lock file for dependencies
├── README.md               # Project documentation
├── webpack.common.js       # Webpack configuration (common)
├── webpack.dev.js          # Webpack configuration (development)
├── webpack.prod.js         # Webpack configuration (production)
└── src                     # Main directory for source code
    ├── index.html          # Main HTML file
    ├── public              # Public assets directory
    │   ├── favicon.png     # Site icon
    │   └── images          # Images used in the project
    ├── scripts             # Directory for JavaScript code
    │   ├── data            # Folder for API or data sources
    │   ├── pages           # Main pages
    │   ├── routes          # Routing settings
    │   ├── utils           # Helpers and utilities
    │   ├── templates.js    # Dynamic HTML templates
    │   ├── config.js       # Project configuration
    │   └── index.js        # Application entry point
    └── styles              # CSS files
        ├── responsives.css # Styles for responsiveness
        └── styles.css      # General styles
```
