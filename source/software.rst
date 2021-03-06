Appendix: Course Software
-------------------------

You can choose either or both of the following options.

Cloud-based development environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This option is recommended if you have any problems with your local setup or if you prefer a basic cloud-based setup.


Pros
````

- consistent, cloud-based environment

Cons
````

- requires good network connection
- lacks code completion


Setup
`````

.. todo:: Update this entire subsection based on OpenShift CHE

- Use your GitHub, Google, Microsoft, or similar account to log into ` <https://codenvy.io>`_.
- If you do not have any of these accounts, create a `GitHub <https://github.com>`_ account. Please see below for more information on GitHub.

- Create a new workspace with the following settings:

  - Create new workspace from stack > Scala SBT
  - Name: myproject-scala
  - Project URL: paste existing GitHub URL into the configuration file

- Wait for the workspace to become available.
  Now you have a persistent, cloud-based, standard Ubuntu/Linux command-line environment that you can work in and come back to from any computer.

- For highly convenient integration of git username and email and SSH keys between IDE profile and console, enable the git agent (this will restart your workspace)::

        workspaces > settings for desired workspace (gear) > agents > git credentials


Zero-install alternative
````````````````````````

Scastie is an interactive playground for Scala with support for sbt configuration.
It allows you to save code snippets to your GitHub account.
To launch, visit https://scastie.scala-lang.org.



Locally installed development environment
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


This option will give you an advanced development environment with code completion, type info, etc.


Pros
````

- provides powerful capabilities, including code completion
- does not require network connection


Cons
````

- might be slow on older machines
- need to maintain on each machine you use



Required components
```````````````````

- `Java 11 and/or newer JDK <http://www.oracle.com/technetwork/java/javase/downloads/>`_
- `Git <http://git-scm.com/>`_ distributed version control system (usually preinstalled on Mac OS and Linux)

  - recommended installation option on Windows: *Use Git and optional Unix tools from the Windows Command Prompt*
  - optional on any platform, especially when not using IntelliJ IDEA: `some GUI-based Git client <https://git-scm.com/downloads/guis>`_


- `sbt <https://www.scala-sbt.org/1.x/docs/Setup.html>`_ Scala build tool
- `IntelliJ IDEA CE <https://www.jetbrains.com/idea/download/>`_ integrated development environment

  - check specific prerequisite details for your platform
  - for the following steps, make sure you have no projects open and are looking at the welcome window as in the attached screenshot
  - *Scala plugin installation:* IntelliJ IDEA > Configure (bottom right) > Plugins > Browse repositories > find and right-click Scala > download and install > close repository browser > OK to restart IDEA
  - *JDK configuration*: IntelliJ IDEA > Configure > Project Defaults > Project Structure > Platform Settings > SDKs > + > JDK > navigate to the installation directory of your most recent JDK > OK


Optional for all IntelliJ users
```````````````````````````````

- These are useful Android Studio/Intellij IDEA plugins. (Installation procedure is the same as for the Scala plugin.)

  - Key Promoter (helps you learn keyboard shortcuts)
  - MultiMarkdown


sbt optional plugins
~~~~~~~~~~~~~~~~~~~~

This section applies to all uses of sbt, whether cloud-based or on the local command line.

These are useful additional sbt plugins. `You can install them per project or globally. <http://www.scala-sbt.org/0.13/tutorial/Using-Plugins.html>`_ Some of the example projects already come with one or more of these plugins.

- `sbt-scoverage <https://github.com/scoverage/sbt-scoverage>`_: uses Scoverage to produce a test code coverage report
- `sbt-updates <https://github.com/rtimush/sbt-updates>`_: checks central repos for dependency updates
- `sbt-scalariform <https://github.com/sbt/sbt-scalariform>`_: automatic source code formatting using Scalariform (see also `this Gist <https://gist.github.com/klaeufer/8981fcdebc8573b06f3d611d049839d3>`_)
- `sbt-native-packager <https://github.com/sbt/sbt-native-packager>`_: creates a script for running your app outside sbt
- `ls-sbt <https://github.com/softprops/ls>`_:  browse available libraries on GitHub using ls.implicit.ly
- `sbt-dependency-graph <https://github.com/jrudolph/sbt-dependency-graph>`_: creates a visual representation of library dependency tree
- `cpd4sbt <https://github.com/sbt/cpd4sbt>`_: copy/paste detection for Scala
- `scalastyle <https://github.com/scalastyle/scalastyle-sbt-plugin>`_: static code checker for Scala
- `wart remover <https://github.com/wartremover/wartremover>`_: code linting tool (another static checker)
- `sbt-stats <https://github.com/orrsella/sbt-stats>`_: simple, extensible source code statistics/metrics


GitHub
~~~~~~

`GitHub <https://github.com>`_ is a provider of hosted Git repositories, which emphasizes community and collaboration. For this reason, we use it to host our course examples.

- Create a GitHub account if you don't already have one.
- Get the `GitHub Student Developer Pack <https://education.github.com/pack/join>`_ using your official ``@luc.edu`` address. This will give you free unlimited private repositories.
- Find and follow a few practitioners you respect. For example, I follow `these developers <https://github.com/klaeufer/following>`_. You'll probably recognize a number of them.
- Review `these notes <https://guides.github.com/activities/contributing-to-open-source>`_ to understand the community-based development process.
- For credit toward class participation, create some meaningful `GitHub issues <https://guides.github.com/features/issues>`_ and/or `GitHub pull requests <https://help.github.com/articles/using-pull-requests>`_ for one or more of our `course examples <https://github.com/lucproglangcourse>`_. (Make sure to navigate to the original repos as these forks do not have their own issue trackers). These can be functional or nonfunctional enhancements, requests for clarification, etc.
- To enhance your visibility in the professional community, start doing the same for some open-source projects you are interested in.

You may find both of these cheat sheets useful:

- `GitHub <https://education.github.com/git-cheat-sheet-education.pdf>`_
- `GitLab <https://about.gitlab.com/images/press/git-cheat-sheet.pdf>`_ (includes useful diagrams)


Remote participation
~~~~~~~~~~~~~~~~~~~~

This software allows you to participating in class remotely in case of weather emergencies, pandemics, etc.
For security and privacy reasons, be sure to update it frequently.

- `Zoom <https://luc.zoom.us>`_

In case of a Zoom outage, we will fall back to MS Teams chat and reorganize from there.

This application enables you to grant others remote access to your desktop. This is helpful for diagnosing and overcoming obstacles without having to pair with the instructor in person. The application is free for personal use and does not require registration.

- `TeamViewer <https://www.teamviewer.com>`_
