# generate:plugin:ckeditorbutton
Generate CKEditor button plugin.

**使い方:**
```
$ drupal generate:plugin:ckeditorbutton [options]
```

## 利用可能なオプション
オプション | 詳細
-------|-------------
--module | モジュール名
--class | Plugin class name
--label | Plugin label
--plugin-id | Plugin ID. NOTE: This corresponds to the CKEditor plugin name. It is the first argument of the CKEDITOR.plugins.add() function in the plugin.js file.
--button-name | Button name. NOTE: This corresponds to the CKEditor button name. They are the first argument of the editor.ui.addButton() or editor.ui.addRichCombo() functions in the plugin.js file.
--button-icon-path | Button icon path. This is the path to the icon/image of the button.
