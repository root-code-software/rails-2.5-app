<!-- PROJECT SHIELDS -->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues-open][issues-open-shield]][issues-url]
[![Issues-closed][issues-closed-shield]][issues-url]
[![Contributors][contributors-shield]][contributors-url]
[![Framework][badge-framework]][framework-url]
[![contributions welcome][contributions-welcome]][issues-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://">
	  <img src="https://img.icons8.com/clouds/150/000000/ruby-programming-language.png" alt="Logo"/>
  </a>

  <h1 align="center">
	Rails 2.5+ Template
  </h1>

  <p align="center">
    Generate your Rails project the easy way!
    <br />
    🐞
    <a href="https://github.com/Israel-Laguan/rails-2.5-app/issues">Report a Bug</a>
    🙋‍♂️
    <a href="https://github.com/Israel-Laguan/rails-2.5-app/issues">Request Feature</a>
  </p>
</p>

# The Project

Welcome to our rails template meant to be used for [Microverse](https://www.microverse.org/)'s projects on Rails!
Generate your Rails project the easy way! 

## Features

* Setup a complete Rails app wit a single script or few commands
* Makes `rspec` ready to use
* Uses `bcrypt` so you can start diggest-ing your passwords
* Spins up home route on request
* Sets `stickler` on the repo
* Sets `rubocop` rules
* Gives you a great README to start with
* Easy to generate projects in GitHub
* Meant to be useful for Microverse students and anyone that wants a Rails' App

# Pre Requisites

The script requires you to have:

- Some compatible Linux OS (I've tested on Debian/Ubuntu derivatives)
- `nodejs` latest LTS version
- `ruby` 2.5+
- `rails` 5.2+
- `git` and normal development stuff
- Basic terminal and script knowledge

Now, this is meant to be used as a [GitHub Template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template),
so please don't clone this repository (unless you want to collaborate), 
use [this button](https://github.com/Israel-Laguan/rails-2.5-app/generate) instead.

<div align="center">
    <a href="https://github.com/Israel-Laguan/rails-2.5-app/generate" target="_blank">
        <img src="doc/template-button.png">
    </a>
</div>

## Creating a new Ruby on Rails project

> Please note that this is for linux only. On windows use [WSL](https://dev.to/hminaya/how-to-run-ruby-on-rails-with-windows-10-and-wsl-1-4he2) or visit
> [this link](https://lmgtfy.com/?q=install+rails+on+windows), 
then run [commands](run_me.sh) from your Terminal.

After you used the template in your project, clone your project in you PC and 
open a terminal inside your project: 

```
git clone <your-repo-link>
cd <Your-project>
````

First run the [script](run_me.sh) provided:

```
chmod -x ./run_me.sh
bash ./run_me.sh
```

Answer the following prompts

`Do you wish to generate a root controller? (y/n)`

The idea is to start with some code to play with, but you can start
without a root controller. If you decide to create a root controller you will be asked:

`What do you want to call it?`

The usual name is _home_ but you can get creative.

Then all the project basic files will be generated for you. The last step of the
script is to launch a server, so at the end you should see something like this:

```
=> Booting Puma
=> Rails 5.2.3 application starting in development
=> Run `rails server -h` for more startup options
Puma starting in single mode...
* Version 3.12.1 (ruby 2.5.5-p157), codename: Llamas in Pajamas
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://localhost:3000

```

If you open on a browser `http://localhost:3000` you should see the following text:

---

<h1>Home#show</h1>

<p>Find me in app/views/home/show.html.erb</p>

---

Last but not least the script remove this README and substitute for the renamed [README.TEMPLATE](README.TEMPLATE.md) (meant to be used for _Microverse Projects_), so if you are running each command instead of using the script make the change of READMEs manually.

## Troubleshooting

If the script fails try to run from the folder:

`rails new .` < === don't forget the point at the end!!

`rails g rspec:install` < === to make `rspec` available!

If it continue failing maybe you don't have the correct versions of any of the [pre requisites](#pre-requisites),
so try to install all necesary packages/gems before running the script. Also you can [tell us](https://github.com/Israel-Laguan/rails-2.5-app/issues) and we'll try to address the issue.

# Author

<table style="width:100%">
  <tr>
    <td>
        <div align="center">
            <a href="./docs/img/photo.png" target="_blank" rel="author">
                <img src="https://avatars2.githubusercontent.com/u/36519478?s=460&v=4" style="border-radius: 10%; min-width: 100px;" alt="Israel Laguan's Photo" width="200px">
            </a>
            <h2>
                <a href="https://israel-laguan.github.io/" target="_blank" rel="author">
                    Israel Laguan
                </a>
            </h2>
        </div>
    </td>
    <td>
        <div align="center">
            <a href="mailto:israellaguan@gmail.com" target="_blank" rel="author">
                <img src="https://img.icons8.com/color/48/000000/message-squared.png" style="border-radius: 10%" alt="My GitHub" height="45px">
                <h3>
                    Email me to 
                    <a href="mailto:israellaguan@gmail.com">
                        israellaguan@gmail.com
                    </a>
                </h3>
            </a>
            <a href="https://www.linkedin.com/in/israellaguan/" target="_blank" rel="author">
                <img src="https://img.icons8.com/color/48/000000/linkedin.png" alt="My Linkedin" height="45px">
                <h3>
                    Connect to my Linkedin
                </h3>
            </a>
            <a href="https://github.com/Israel-Laguan" target="_blank" rel="author">
                <img src="https://img.icons8.com/color/48/000000/github--v1.png" 
			style="border-radius: 10%" alt="My GitHub" height="45px"
		>
                <h3>
                    Check my GitHub Profile
                </h3>
            </a>
        </div>
    </td>
  </tr>
</table> 

# Contributing

[![contributions welcome][contributions-welcome]][issues-url]

🤝 Contributions, issues and feature requests are welcome!
Feel free to check the [issues page][issues-url].

# Show your support

🤗 Give a ⭐️ if you like this project!

Icons from:

<a href="https://icons8.com/icon/64516/ruby-programming-language">Ruby Programming Language icon by Icons8</a>

# License

[![License][badge-license]](http://badges.mit-license.org)

📝 This project is licensed under the [MIT](LICENSE)\
Feel free to fork this project and improve it

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/Israel-Laguan/rails-2.5-app?style=for-the-badge
[contributors-url]: https://github.com/Israel-Laguan/rails-2.5-app/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Israel-Laguan/rails-2.5-app?style=for-the-badge
[forks-url]: https://github.com/Israel-Laguan/rails-2.5-app/network/members
[stars-shield]: https://img.shields.io/github/stars/Israel-Laguan/rails-2.5-app?style=for-the-badge
[stars-url]: https://github.com/Israel-Laguan/rails-2.5-app/stargazers
[issues-open-shield]: https://img.shields.io/github/issues/Israel-Laguan/rails-2.5-app?style=for-the-badge
[issues-url]: https://github.com/Israel-Laguan/rails-2.5-app/issues
[issues-closed-shield]: https://img.shields.io/github/issues-closed/Israel-Laguan/rails-2.5-app?style=for-the-badge
[badge-framework]: https://img.shields.io/badge/framework-RubyOnRails-red?style=for-the-badge
[framework-url]: https://rubyonrails.org/
[contributions-welcome]: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=for-the-badge
[badge-license]: https://img.shields.io/:license-mit-blue.svg?style=for-the-badge
