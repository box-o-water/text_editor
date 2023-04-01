# text_editor

![license](https://img.shields.io/static/v1?label=license&message=MIT&color=blue)

## Description

A text editor that runs in the browser. This app is a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

<img src="/assets/images/text_editor_preview.png" width="700"/>

Click [here](https://texteditorbow.herokuapp.com/) to see the deployed Heroku application.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [Credits](#credits)
- [License](#license)

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

GIVEN a text editor web application

- [x] WHEN I open my application in my editor
      THEN I should see a client server folder structure

- [x] WHEN I run `npm run start` from the root directory
      THEN I find that my application should start up the backend and serve the client

- [x] WHEN I run the text editor application from my terminal
      THEN I find that my JavaScript files have been bundled using webpack

- [x] WHEN I run my webpack plugins
      THEN I find that I have a generated HTML file, service worker, and a manifest file

- [x] WHEN I use next-gen JavaScript in my application
      THEN I find that the text editor still functions in the browser without errors

- [x] WHEN I open the text editor
      THEN I find that IndexedDB has immediately created a database storage

- [x] WHEN I enter content and subsequently click off of the DOM window
      THEN I find that the content in the text editor has been saved with IndexedDB

- [x] WHEN I reopen the text editor after closing it
      THEN I find that the content in the text editor has been retrieved from our IndexedDB

- [x] WHEN I click on the Install button
      THEN I download my web application as an icon on my desktop

- [x] WHEN I load my web application
      THEN I should have a registered service worker using workbox

- [x] WHEN I register a service worker
      THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets

- [x] WHEN I deploy to Heroku
      THEN I should have proper build scripts for a webpack application

## Installation

- Install `nvm`
- Use `nvm` to install `npm`
- $ git clone git@github.com:box-o-water/text_editor.git
- $ npm install

## Usage

- $ npm run start

* Visit http://localhost:3000/

## Contributing

To contribute, create an issue in this repo, or fork this repo and create a pull request against this repo from your fork.

# Tests

N/A

# Questions

Visit my [box-o-water](https://github.com/box-o-water) profile page.

For any questions about this project, please send an email to <boxooowater@gmail.com>.

## Credits

N/A

## License

Licensed under the [MIT](/LICENSE) license.
