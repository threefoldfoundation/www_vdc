> see https://github.com/threefoldfoundation/info_cloud

# www_vdc
 ThreeFold Virtual Private Data Center

Created by @sasha-astiadi
<br>
Managed by @sasha-astiadi @gmachtel @sacha96

### To Install

copy the folling in your terminal

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/threefoldfoundation/www_vdc/development/tools/install.sh)"
```

> remark: if you want to install all webtools at once go to: https://github.com/threefoldfoundation/websites and follow instructions there

### To Run

```
cd ~/code/github/threefoldfoundation/www_threefold_cloud
sh run.sh
```

this will start a local dev server at http://localhost:8080

to now see your website, copy ```http://localhost:8080``` in your browser

### build a static website (production only)

Run `./build.sh` 

## Where is all the content ?

- It is under the direcory [content/docs](content/docs)
- All files are markdown (.md) format

## Editing

- Always use `-` instead of `_` in naming files and directories 
- Create a new folder for each item you want to add to `www_vdc` with the naming convention in the previous point
- inside each directory put
    - `index.md` contains markdown
    - `img` directory with images for that item
- referring to img `crystaltwin.png` from `index.md` of `crystaltwin` item can be done simpy by `![](./img/crystaltwin.png)`
- **Editing md files**

  - All files start with this piece of code, this is meant to control navigation into different sections defined in the sidebar menu.

    ```
    ---
    description: ''
    sidebar: 'docs'
    prev: '/docs/wiki-publisher/'
    next: '/docs/digitalme/'
    ---


## You want to go deeper ?

Read more [here](https://docc-theme.netlify.app)

- 
## Create new project using `threefold gridsome-docc` 

Run `gridsome create app https://github.com/threefoldfoundation/gridsome-docc`
