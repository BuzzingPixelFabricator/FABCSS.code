# Fabricator Code Styling

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

## Installing

With Fabricator and NPM, simply require this library into your project and restart the Fabricator Grunt build process.

`npm install fabcss.code --save`

If you are not using Fabricator, you will need to include into your Less build `src/FABCSS.code.les`.

## Usage

Variables available in this file you can override:

```
@codeBackground: lighten(#000, 90%);
@codeBorderColor: false;
@codeColor: lighten(#000, 25%);
@codeFont: monospace;
@codeFontSize: 16px;
@codeLineHeight: 1.4em;
@codePaddingHorizontal: .5em;
@codePaddingVertical: .2em;
@codeRounded: 0;

@codeBlockColor: lighten(#000, 90%);
@codeBlockFont: @codeFont;
@codeBlockFontSize: 13px;
@codeBlockBackground: lighten(#000, 25%);
@codeBlockBorderColor: false;
@codeBlockRounded: 0;
@codeBlockMarginBottom: 20px;
@codeBlockTabSize: 4;

@codeBlockWrap: false;
@codeBlockPaddingHorizontal: 20px;
@codeBlockPaddingVertical: 14px;
```

## License

Copyright 2017 TJ Draper, BuzzingPixel, LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
