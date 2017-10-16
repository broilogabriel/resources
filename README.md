## General

- [The Twelve-factor App](https://12factor.net/)

  >In the modern era, software is commonly delivered as a service: called web apps, or software-as-a-service. The twelve-factor app is a methodology for building software-as-a-service apps that:
  >
  >- Use declarative formats for setup automation, to minimize time and cost for new developers joining the project;
  >- Have a clean contract with the underlying operating system, offering maximum portability between execution environments;
  >- Are suitable for deployment on modern cloud platforms, obviating the need for servers and systems administration;
  >- Minimize divergence between development and production, enabling continuous deployment for maximum agility;
  >- And can scale up without significant changes to tooling, architecture, or development practices.
  >
  >The twelve-factor methodology can be applied to apps written in any programming language, and which use any combination of backing services (database, queue, memory cache, etc).

-----

## Scala

- [sbt-start-script](https://github.com/sbt/sbt-start-script)

  >This plugin allows you to generate a script target/start for a project. The script will run the project "in-place" (without having to build a package first).

- [SBT Native Packager](https://github.com/sbt/sbt-native-packager)

  >SBT native packager lets you build application packages in native formats. It offers different archetypes for common configurations, such as simple Java apps or server applications.

- [sbt Cached Resolution](http://www.scala-sbt.org/0.13/docs/Cached-Resolution.html)

  >Cached resolution is an experimental feature of sbt added since 0.13.7 to address the scalability performance of dependency resolution.

- ### Events
   - http://typelevel.org/events/

-----

## Java

-----

## Linux

- [Vim Cheat Sheet](https://www.linuxtrainingacademy.com/vim-cheat-sheet/)

  >Global
  >
  >:help keyword – open help for keyword
  >
  >:o file – open file
  >
  >:saveas file – save file as
  >
  >:close – close current window
  >
  >....

- Useful Commands

  >Biggest dirs: `du -sh ./* | sort -nr | head -n 20`
  >
  >Count lines: `wc -l test.csv`

## Python

- [Structuring Your Project](http://docs.python-guide.org/en/latest/writing/structure/)

  >By “structure” we mean the decisions you make concerning how your project best meets its objective. We need to consider how to best leverage Python’s features to create clean, effective code. In practical terms, “structure” means making clean code whose logic and dependencies are clear as well as how the files and folders are organized in the filesystem.
  >
  >Which functions should go into which modules? How does data flow through the project? What features and functions can be grouped together and isolated? By answering questions like these you can begin to plan, in a broad sense, what your finished product will look like.

- [Pipenv](http://docs.pipenv.org/en/latest/): Sacred Marriage of Pipfile, Pip, & Virtualenv

  > Pipenv is an experimental project that aims to bring the best of all packaging worlds to the Python world. It harnesses Pipfile, pip, and virtualenv into one single toolchain. It features very pretty terminal colors.

- [Fabric](http://docs.fabfile.org/en/1.13/tutorial.html)

  >Fabric is a Python (2.5-2.7) library and command-line tool for streamlining the use of SSH for application deployment or systems administration tasks.

-----

## Docker

- [Docker - How to cleanup (unused) resources](https://gist.github.com/broilogabriel/71760018cc9bcd99809dd6550d38c92a#docker---how-to-cleanup-unused-resources)

  >Once in a while, you may need to cleanup resources (containers, volumes, images, networks) ...

- [Docker on Windows: Interactive TTY](https://dzone.com/articles/docker-on-windows-interactive-tty-session-gives-ca)

  >When running a Docker shell container on Windows 7, you'll get a very specific error. Luckily, there's a simple workaround.

-----

## Markdown

- [Markdown using Visual Studio Code](http://thisdavej.com/build-an-amazing-markdown-editor-using-visual-studio-code-and-pandoc/)

-----

## Extra

- Youtube Playlist: [Dev](https://www.youtube.com/playlist?list=PLUWSoB51HXsetaP2bMbzRHcRcEEymBu3l)
- [Software Engineering at Google](https://arxiv.org/ftp/arxiv/papers/1702/1702.01715.pdf): We catalog and describe Google’s key software engineering practices.
