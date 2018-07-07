# VFX compositing wiki
@ author: Jakub Jezek, jezschaj@gmail.com

A research project aiming to map all knowledge regarding vfx compositing techniques.

## Why this projet has started
There is a lot of books on the market which is trying to teach basic tachiques usable for evryday life of vfx compositor. You could spend ours of looking the appropriate method for the problem you are trying to learn or hack during your work. Year spend in the industry and you still thing it would be better if someone could just simply write a keywords of the problem and magically like in Google you would get at least three options to select from to quickly get the hack and use it for every day life and this is what should matter most.

## Project's bio 
As the previous has described, it should be simple vfx search engine. No distruction and acces to it could be provided by simple API for R&D guy simply connect it to inhouse intranet wiki or front end pipeline panel perhaps inside Nuke/Fusion/Maya/Blender and so on. There would be only *.md files in database with keyword classifications for easy acces of search engine. As the project would be Open Source and is very humbly dependent on users to share. Most of it will be GitHub clonable so anyone could share simply with others.

## Teaching item template
> Name of the topic to be teach
* keywoards
* poster image
* short introduction of method
* necesery apps to have acces to for this session
* if video tutorial avalable then url to it
* if any link to discusion forum then embded soluton or link to it
* embded images linked from git sub repository (submodule)
* links to downloadable snippets of code, image, alembic under Open source filosofy
* body of the teaching not longer then 2x A4 comperable size
  - it is important to try harder and simplify the explanation at the core of te problem and not to use unecessery distructions
  - images could be cropped snapshots of taidy node tree


## What do you need to be able to connect to the project
- any text editor will do but easyer is to download and install [Atom.io](http://atom.io) on any platform
- install Atom's packages:

><div style="float:left;margin:0 10px 10px 0">
![](assets/markdown-img-paste-2018062720120129.png)</div>
> for writing posts which all our content will be based on

><div style="float:left;margin:0 10px 10px 0">
![](assets/markdown-img-paste-20180627201345373.png)</div>
> this will help you to se the markdown code easyer with colored syntax

><div style="float:right;margin:0 10px 10px 0">
![](assets/markdown-img-paste-20180627201421366.png)</div>
> usefull tool for synchronized scrolling with the markdown text preview window

><div style="float:right;margin:0 10px 10px 0">
![](assets/markdown-img-paste-2018062720150706.png)</div>
> very usefull toolbar like in any document editor

><div style="float:right;margin:0 10px 10px 0">
![](assets/markdown-img-paste-20180627201532286.png)</div>
> in case you need to work with tables

><div style="float:right;margin:0 10px 10px 0">
![](assets/markdown-img-paste-20180627201556678.png)</div>
  > it is great tool but it is having still usolved problem on my platform so in case it tells you after first try that it is broken then follow this instructions <https://github.com/cocoakekeyu/markdown-img-paste/issues/23>. It worked for me. enough to just simply go to `[HOME_DIR].atom\packages\markdown-img-paste\lib\markdown-img-paste.coffee` file and change `img.toPng` to `img.toPNG` on line 54.

- very usefull free app for windows is Snipping Tool, which allows you to simply grab only rectangular crop of your screen and then **ctrl-v** it in the new line and it will automatically create link to savet image in relative folder of your clone of repository.

- i found handy to quickly skim some basic of markdown syntax from [Mastering markdown](https://guides.github.com/features/mastering-markdown/)
- it will take while to setup and get used to it. This is my breakdown:
  - istall Atom and addons: 30 mins
  - install Snipping Tool: 10 mins
  - register Github and cloning this repository: 15 mins
  - read and learn from project guidlines

--------------------------------------
> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> Here's some example code:

```shell
return shell_exec("echo $input | $markdown_script")
```

<br>

```python
def foo():
    if not bar:
        return True
```

this i a style
### Documentation

Below is the current and full documentation of QML.

- [Supported hosts](#supported-hosts)
- [Data](#data)

<br>

#### Supported Hosts

These are the hosts automatically recognised by pyblish-qml.

- Maya
- Nuke
- Houdini
- Hiero

<br>

#### Data

Some data within each Instance and Context are special to QML.

| Member    | Applies to       | Behavior
|:----------|:-----------------|:-------------------
| `publish` | Instance         | The on/off state of the toggle.
| `label`   | Context/Instance | Draw this instead of an instance's `name`
| `comment` | Context          | Display and edit comment in GUI
