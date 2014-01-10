## Comment.js

A simple js library to get user feedback on a website. Sends posts to a firebase for easy setup.

**Requires jQuery.** please load it before Comment.js.

===

### Usage

Setup a firebase at http://firebase.com. Make sure that the security rules includes `".write": true`

Add the comment.js (or minified comment.min.js) to the head of any document you wish to have it displayed on:

```html
<script src='comment.min.js' firebase='https://MY_FIREBASE.firebaseio.com/'></script></head>
```

The 'firebase' attribute should point to your firebase, and end with a slash (as above). You should see the comment box on the middle-right of your page after it loads. 

This is a very new project, please add issues here on github so I can fix them.  :-)

Feel free to fork / modify as you like!