---
# Don't edit this file directly, it was copied using scripts/download-readmes.js: 
id: version-6.x-babel-helper-builder-react-jsx
title: babel-helper-builder-react-jsx
sidebar_label: babel-helper-builder-react-jsx
original_id: babel-helper-builder-react-jsx
---

```javascript
type ElementState = {
  tagExpr: Object; // tag node
  tagName: string; // raw string tag name
  args: Array<Object>; // array of call arguments
  call?: Object; // optional call property that can be set to override the call expression returned
  pre?: Function; // function called with (state: ElementState) before building attribs
  post?: Function; // function called with (state: ElementState) after building attribs
};

require("babel-helper-builder-react-jsx")({
  pre: function (state: ElementState) {
    // called before building the element
  },

  post: function (state: ElementState) {
    // called after building the element
  }
});
```

