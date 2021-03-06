# Mini Project: Memories Application - Client

### Tech-Stack

- redux@4.0.5
- redux-thunk@2.3.0
- axios@0.21.0
- react-file-base64@1.0.3
- moment@2.29.1
- @material-ui/core
- @material-ui/icons

### Directory Structure

```
.
├── .gitignore
├── package.json
├── README.md
├── deploy-firebase
├── build
├── public
└── src
    ├── images
    ├── api
    ├── constants
        └── actionTypes.js
    ├── actions
        ├── posts.js
    ├── reducers
        ├── posts.js
        ├── index.js
    ├── components
        ├── Form
        └── Posts
            └── Post
    ├── App.js
    ├── styles.js
    ├── index.css
    └── index.js
```

### How to name a folder and a file

- Folder name: - Ex: `InfoSection`
- Component file name: should be -- Ex: `InfoSection.js`
- Style component file name: should be -- Ex: `styles.js`

### How to import and export module?

- Import:

```js
//import every thing
import * as React from "react";
import * as ReactDOM from "react-dom";

//for default export
import InfoSection from "./InfoSection";

//for named export
import { InfoSec, InfoRow } from "./InfoSection.elements";
```

### How to style for each component?

- Create a styled-component file. Ex: `styles.js`
- Import to `js` file

```js
// InfoSection.js

import { InfoSec, InfoRow } from "./styles.js";
```

### How to setup Redux, Redux Thunk

### How to deploy to firebase

### How to fetch data from server
