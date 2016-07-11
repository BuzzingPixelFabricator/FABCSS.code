# Fabricator CSS/Less Reset

While this component is designed with the [BuzzingPixel Fabricator Build Process](https://github.com/tjdraper/buzzing-pixel-fabricator) in mind, it can be used anywhere (in theory).

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