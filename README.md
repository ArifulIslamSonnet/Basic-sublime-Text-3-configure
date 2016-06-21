#Basic-sublime-Text-3-configure
Basic configuration of sublime text 3 to get start with this.  

As a front end developer, I need some basic configuration to prepare my sublime text 3 for work with any project.   

When I reset my system , every time, I need to search online for configure sublime text with nessesary tools. 
This is why I am writting this manual for me , to keep track what to do at the very first time after installing sublime text. Now get started. 

##Install Package control 
To install package control , go here [Package Control](https://packagecontrol.io/ "Package Control")
Simply follow the instruction to the given link. 

##Install Must Needed plugin for sublime Text 3 
- [Bootstrap 3 Snippets](https://github.com/JasonMortonNZ/bs3-sublime-plugin#installation "Bootstrap 3 Snippets")
- [DocBlockr](https://github.com/spadgos/sublime-jsdocs "DocBlockr")
- [Emmet](https://github.com/sergeche/emmet-sublime/ "Emmet")
- [jQuery](https://github.com/SublimeText/jQuery "jQuery")
- [Sublime Text 2 WordPress](https://github.com/purplefish32/sublime-text-2-wordpress "Sublime Text 2 WordPress")
- [Search Word​Press Codex](https://github.com/welovewordpress/SublimeWordPressCodex "Search Word​Press Codex")
- [Word​Press Developer Resources](https://packagecontrol.io/packages/WordPress%20Developer%20Resources "Word​Press Developer Resources")

For some case, We need to debug our Javascript code. It's painful to find error on large javascript code. This is why I normally use SublimeLinter-jshint. 

Now get started to install Jshint . You must installed `NodeJs` in order to use `sublimeLinter` and `sublimelinter-jslint` .  
After installed NodeJS run this code in commandline. 
`npm install -g jshint` 
Linux user need to use `sudo`. 

Now open sublime text and search and install these (`sublimeLinter` and `sublimelinter-jslint`) package using sublime text  package manager. 

Now open javascript file into sublime text 3 and check it's working. If you write any error , it will fire a error notice. 


## Ovverright Some default Settings. 
Go to `Preference -> Settings-User` and paste this configuration. 

```json
{
    "auto_indent": true,
    "default_line_ending": "unix",
    "detect_indentation": true,
    "font_options":
    [
        "directwrite"
    ],
    "font_size": 11,        
    "ignored_packages":
    [
        "Vintage"
    ],
    "indent_to_bracket": false,
    "smart_indent": true,
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_automatic_white_space": true,
    "use_tab_stops": true,
    "auto_complete_selector": "source, text",
    "auto_complete_triggers": [{"selector": "text.html", "characters": "<"},{"selector": "text.html", "characters": "bs3"}],
    "word_wrap": "true"
}
```

That's it. You are ready to go.  
Happy Coding :) 

