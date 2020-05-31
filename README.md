## tomelvidge.com
[![Netlify Status](https://api.netlify.com/api/v1/badges/637ba405-ef83-4441-8eb9-736c369de35f/deploy-status)](https://app.netlify.com/sites/tomelvidge/deploys)


A Gatsby blog based on the Gatsby starter [Lumen](https://github.com/alxshelepenok/gatsby-starter-lumen).

### Access Locally
```
$ git clone https://github.com/tom-elvidge/tomelvidge.com.git
$ cd tomelvidge.com
$ gatsby develop
```
To test the CMS locally, you'll need run a production build of the site:
```
$ npm run build
$ gatsby serve
```

### Folder Structure

```
└── content
    ├── pages
    └── posts
└── static
    ├── admin
    └── media
└── src
    ├── assets
    │   └── scss
    │       ├── base
    │       └── mixins
    ├── cms
    │   └── preview-templates
    ├── components
    │   ├── Feed
    │   ├── Icon
    │   ├── Layout
    │   ├── Page
    │   ├── Pagination
    │   ├── Post
    │   │   ├── Author
    │   │   ├── Comments
    │   │   ├── Content
    │   │   ├── Meta
    │   │   └── Tags
    │   └── Sidebar
    │       ├── Author
    │       ├── Contacts
    │       ├── Copyright
    │       └── Menu
    ├── constants
    ├── templates
    └── utils

```