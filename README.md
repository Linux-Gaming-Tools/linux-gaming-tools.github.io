# Linux Gaming Utils

The goal of this site is having a list with several tools, such as drivers and gaming oriented programs like wheels, joysticks and mice configurators and such and GNU/Linux distributions specially created to ready to play.

This project is under the GNU/GPL 3 license and everybody is welcomed to help to add new entries to the list.

### Howto add a new utility or driver:

To add a new utility or driver you must follow these steps:

* Go to **_data** folder on the repo. This folder is the one that contains two subfolders, one for the tools (**tools**) and other for GNU/Linux distributions (**distro**) and on these the files with the data of what it shows me on the web. In it you will see a file, _template.yml, that you can use as a template, or use [this form for tools](https://linux-gaming-tools.github.io/form-tools) or  [this form for distros](https://linux-gaming-tools.github.io/form-distros) for make the file easily.
* Click on **Create new file** on the folder (tools or distros) and copy the content of _template.yml and edit the variables, or copy the result of the form. The name of the file can only have lowercase letters, numbers underscores (\_) and minus (-), and the extension .yml.
* At the end of the page fill the fields and press **Propose new file**. This generates automatically a new pull request.
* And that's it Once your contribution has been reviewed the request will be accepted and will automatically appear on the web ;)
* You can also fork the project, make your changes and make a pull request, although this method is slower, but it can be worth it if you are going to make many contributions, or include changes in the rest of the project.

### Credits:

Thanks to all Jugando En Linux's Telegram channel for help me.

### Software use in this project:

* [Jekyll](https://jekyllrb.com): For generate the site.
* [NanoCSS](https://son-link.github.io/NanoCSS/): the CSS framework use on the design
* [pykwalify-webform](https://github.com/Linux-Gaming-Tools/pykwalify-webform): use for generate the form for make a new data file.