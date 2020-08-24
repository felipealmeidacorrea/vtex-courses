```store/blocks/home.jsonc
{
  "store.home": {
    "blocks": [
      "responsive-layout.desktop#desktop",
      "responsive-layout.mobile#mobile"
    ]
  },
  "responsive-layout.desktop#desktop": {
    "children": [
      "rich-text#desktop",
      "image#desktop"
    ]
  },

  "responsive-layout.mobile#mobile": {
    "children": [
      "rich-text#mobile",
      "image#mobile"
    ]
  },
  "image#desktop": {
    "props": {
      "src": "https://appliancetheme.vteximg.com.br/arquivos/Responsive-Image-Desktop.jpg?q=1",
      "maxWidth": "100%",
      "link": {
        "url": "/small-appliances/coffee-makers"
      } ,
      "alt": "Coffee Makers Collection"
    }
  },

  "image#mobile": {
    "props": {
      "src": "https://appliancetheme.vteximg.com.br/arquivos/Responsive-Image-Mobile.jpg?q=1",
      "maxWidth": "100%",
      "link": {
        "url": "/small-appliances/coffee-makers"
      } ,
      "alt": "Coffee Makers Collection"
    }
  },

  "rich-text#desktop": {
    "props": {
      "text": "# Your Coffee, Your Way \n ### New Coffee Makers Collection",
      "textPosition": "CENTER",
      "textAlignment": "CENTER"
    }
  },

  "rich-text#mobile": {
    "props": {
      "text": "### Your Coffee, Your Way \n #### New Coffee Makers Collection",
      "textPosition": "CENTER",
      "textAlignment": "CENTER"
    }
  },
  ...
  ```