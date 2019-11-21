# Rails 2.5+ Template

Welcome to our rails template meant to be used for [Microverse](https://www.microverse.org/)'s projects on Rails!

# Pre requisites

The script needs you to have

- Some compatible Linux OS (We tested on Debian/Ubuntu derivatives)
- `nodejs` latest LTS version
- `ruby` 2.5+
- `rails` 5.2+
- `git` and normal development stuff
- Basic terminal and script knowledge
- Some common sense

Now, this is meant to be used as a [GitHub Template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template),
so please don't clone this repository (unless you want to collaborate), 
use [this button](https://github.com/Israel-Laguan/rails-2.5-app/generate) instead.

<style>
/* https://www.w3schools.com/css/css3_buttons.asp */
    button {
        background-color: #4CAF50;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        transition-duration: 0.4s;
    }

    button:hover{
        background-color: white;
        color: black;
    }
</style>
<div align="center">
    <a href="https://github.com/Israel-Laguan/rails-2.5-app/generate" target="_blank">
        <button>
            Use This Template
        </button>
    </a>
</div>

## Creating a new Ruby on Rails project

> Please note that this is for linux only. On windows use [WSL](https://dev.to/hminaya/how-to-run-ruby-on-rails-with-windows-10-and-wsl-1-4he2) or visit
> [this link](https://lmgtfy.com/?q=install+rails+on+windows)

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

Last but not least remove this README and substitute for the renamed [README.TEMPLATE](README.TEMPLATE.md) (meant to be used for _Microverse Projects_).

## Troubleshooting

If the script fails try to run from the folder:

`rails new .` < === don't forget the point at the end!!

If it continue failing maybe you don't have the correct versions of any of the [pre requisites](#pre-requisites),
so try to install all necesary before running the script. Also you can [tell us](https://github.com/Israel-Laguan/rails-2.5-app/issues) and we'll try to address the issue.

# Authors

- [Israel Laguan](https://github.com/Israel-Laguan)
- [Aheebwa Ramadhan](https://github.com/raheebwa)

# License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
