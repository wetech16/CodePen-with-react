
## Code Setup 
  - [ ] npm i codemirror react-codemirror2
  - [ ] components: <Editor> & <iframe>

## Editor Setup 
  - [ ] components Editor: <displayName> & O/C button 
  - [ ] components Editor: <ControlledEditor>

## CSS
-body
-top pane
-pane
-editor
-override CodeMirror
-code-mirror-wrapper

## Functionality
-SrcDoc passed to iframe to display html,css,javascript
-setTimeout() for SrcDoc
-useEffect for setTimeout

## open close Button
-open state for collapsed css class
-onclick to change state
-add close/open Icon: npm i @fortawesome/react-fontawesome @fortawesome/free-solid-svg-icons @fortawesome/fontawesome-svg-core

# How to Build CodePen with React

## VSCODE 
- es7 snippets
- prettier

## React
- App.js 
    - css
    - iframe {title, sandbox, framebox}
    - srcDoc { useEffect, timeout, useState }
    - Editor { useState, displayName, language, value, onChange}
        - Controlled {onBeforeChange, value, options} from react-codemirror2
        - Button { useState}
        - FontAwesomeIcon {faCompressAlt}
    - useLocalStorage {key, initialValue} //custom hook
        - prefixedKey {PREFIX, key }
        - useState { value, jsonValue, initialValue }
        - useEffect { prefixKey, value }
-----
- FontAwesomeIcon: Icons from Fortawesome github: react-fontawesome
- useLocalStorage: custom hook

## CSS
- flex-grow
- flex-basis
- display: flex
- flex-direction
- justify-content
