``` 
 __          __  _    _____ _____  ______    _____      _   _   _                 
 \ \        / / | |  |_   _|  __ \|  ____|  / ____|    | | | | (_)                
  \ \  /\  / /__| |__  | | | |  | | |__    | (___   ___| |_| |_ _ _ __   __ _ ___ 
   \ \/  \/ / _ \ '_ \ | | | |  | |  __|    \___ \ / _ \ __| __| | '_ \ / _` / __|
    \  /\  /  __/ |_) || |_| |__| | |____ _ ____) |  __/ |_| |_| | | | | (_| \__ \
     \/  \/ \___|_.__/_____|_____/|______(_)_____/ \___|\__|\__|_|_| |_|\__, |___/
                                                                         __/ |    
                                                                        |___/     
                                                                                                                                                                                                                                                                                                                           
```                                                                                                                                                 

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/jsrun/wi.core.settings/master/LICENSE)

WebIDE configuration manager
 
## Usage

```js
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.selectionStyle", "Selection Style", "option", "line", "line:Line|text:Text", "webide.settings.setAceEditor");
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.highlightActiveLine", "Highlight Active Line", "boolean", true, null, "webide.settings.setAceEditor");
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.highlightSelectedWord", "Highlight Selected Word", "boolean", true, null, "webide.settings.setAceEditor");
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.cursorStyle", "Cursor Style", "option", "ace", "ace:Ace|slim:Slim|smooth:Smooth|wide:Wide", "webide.settings.setAceEditor");
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.behavioursEnabled", "Behaviours Enabled", "boolean", true, null, "webide.settings.setAceEditor");
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.wrapBehavioursEnabled", "Wrap Behaviours Enabled", "boolean", true, null, "webide.settings.setAceEditor");
webide.settings.addSettingItem("Code Editor (Ace)", "Editor Options", "ace.editor.autoScrollEditorIntoView", "Auto Scroll Editor Into View", "boolean", false, null, "webide.settings.setAceEditor");
```

## License

  MIT
  
  Copyright (C) 2016 André Ferreira

  Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.