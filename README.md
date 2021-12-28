## Introduction

This is a code directory for notes using NodeJS.

## Installation

Open [`http://localhost:3000`](http://localhost:3000/) with your browser to see the result.

You can start editing the page by modifying `app.js`. 

```
npm i
```

## Usage

First, run the development server:

```javascript
node app.js
```

You can start to add new note by typing "title, body" note:

```javascript
node app.js add --title="buy" --body="all grocery today"
```

To remove note, type "title note" only:

```javascript
node app.js remove --title="buy"
```

To read body for specific note, type "title note" only:

```javascript
node app.js read --title="buy"
```

To list all your notes:

```javascript
node app.js list
```

