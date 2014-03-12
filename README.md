# Git publisher for Punch 

Git publisher for [Punch](http://laktek.github.com/punch).

### How to Use 

* Download lib/punch-git-publisher.js into your project.
    
* Configure in your Punch project's configurations (`config.json`):

    "plugins": {
        "publishers": {
            "git_strategy": "./lib/punch-git-publisher.js" 
        }
    },

    "publish": {
        "strategy": "git_strategy",
        "options": {
            "repo_url": "git@bitbucket.org:azhdanov/azhdanov.bitbucket.org.git"
        }
    }


## License

Copyright (c) 2014 Andriy Zhdanov

Licensed under the MIT license.
