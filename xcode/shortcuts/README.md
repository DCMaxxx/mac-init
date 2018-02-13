# Adds delete / duplicate line(s)
[Source](http://stackoverflow.com/questions/10266170/xcode-duplicate-line)

Edit this file : `/Applications/Xcode.app/Contents/Frameworks/IDEKit.framework/Versions/A/Resources/IDETextKeyBindingSet.plist`

Add this at the bottom :
```
<key>Customized</key>
<dict>
    <key>Duplicate Lines</key>
    <string>selectLine:, copy:, moveToEndOfLine:, insertNewline:, paste:, deleteBackward:</string>
    <key>Duplicate Current Line</key>
    <string>moveToBeginningOfLine:, deleteToEndOfLine:, yank:, insertNewline:, moveToBeginningOfLine:, yank:</string>
    <key>Delete Current Line</key>
    <string>selectLine:, delete:</string>
</dict>
```

Add custom keyboard shortcuts in Xcode :  
`⌃⌥⌘D` = Duplicate lines  
`⌘D` = Duplicate current line  
`⌃⇧K` = Delete current line  
