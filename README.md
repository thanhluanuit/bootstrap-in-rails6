## How to use Bootstrap in Rails 6

#### Step 1: Install Bootstrap
```
yarn add bootstrap
```

#### Step 2: Install Bootstrap dependencies: jQuery and popper.js

```
yarn add jquery popper.js
``` 

#### Step 3: Import JavaScript Bootstrap and dependencies
```
# app/javascript/packs/application.js
import "jquery";
import "popper.js";
import "bootstrap";
```

#### Step 4: Import CSS Bootstrap
Add a folder name stylesheets in app/javascript/

Add application.scss file in app/javascript/stylesheets

Add below code to import bootstrap css:

```
# In app/javascript/stylesheets/application.scss
@import "~bootstrap/scss/bootstrap"; 
```
    
Import CSS to application.js
```
# In app/javascript/packs/application.js
import "../stylesheets/application" 
```

### DONE!

#### See folder structure
```cassandraql

app/javascript
├── channels
├── packs
│   └── application.js
└── stylesheets
    └── application.scss

```

More details in Luanotes.com: https://luanotes.com/blogs/using-bootstrap-with-webpacker-in-rails-6

