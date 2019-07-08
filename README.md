# summernote-case-converter
Case converter plugin for the [Summernote](https://github.com/summernote/summernote/) WYSIWYG editor.

Adds a button to the Toolbar with a dropdown in the Toolbar that allows case converting in any text in the editor.

Functions of this plugin:
- Case convert between upper, lower, sentence and title case.

### Installation

#### 1. Include JS

Include the following code after including Summernote:

```html
<script src="summernote-case-converter.js"></script>
```

#### 2. Supported languages
Currently available in English and Spanish!

#### 3. Summernote options
Finally, customize the Summernote Toolbar.

```javascript
$(document).ready(function() {
  $('#summernote').summernote({
    toolbar:[
      ['custom',['caseConverter']], // The button
      ['style',['style']],
      ['font',['bold','italic','underline','clear']],
      ['fontname',['fontname']],
      ['color',['color']],
      ['para',['ul','ol','paragraph']],
      ['height',['height']],
      ['table',['table']],
      ['insert',['media','link','hr']],
      ['view',['fullscreen','codeview']],
      ['help',['help']]
    ]
  });
});
```

#### 4. Check out my Github page.
- [Piranga8](https://github.com/piranga8/)
