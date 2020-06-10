# Useful Software

This is a list of IDEs, extensions, student discounts, and any other software-related stuff that students who do anything CS-related might find useful.

## Online Tools/Student Discounts

### GitHub Student Developer Pack

First and foremost, GitHub has a student developer package that gives you a ton of benefits not only from GitHub, but also from some big names in the CS industry, like free AWS credits, MongoDB credits, free paid app subscriptions while you are a student, and more!  When I applied about a year ago, APU was not on the list of pre-approved univerisities, so it took a week for my verification to go through.  It's definitely worth getting, as it's valid for the duration that you are a student.  Details and form to submit [here](https://education.github.com/pack).

## Cross-Platform Software

### JetBrains IDEs

JetBrains is an IDE development company that makes a good deal of IDEs all based off of the same "core" platform.  Their most famous IDE is IntelliJ IDEA, which is for Java development.  You can also use it for Python development and some other languages.  They also have a separate IDE called PyCharm that is specifically for Python development.  They make a ton more IDEs as well, including ones for C/C++, PHP, HTML/JavaScript, Ruby, Go, and others, but only IntelliJ IDEA and PyCharm have "community" editions that are free to use.  However, if you are currently an undergraduate student, graduate student, or professor, you can get all of their paid IDEs, including the "professional" versions of PyCharm and IntelliJ IDEA, for free!  You can renew this annually while you are a student.  I personally have stopped using Eclipse, VS Code, and Arduino because IntelliJ and the rest of the JetBrains suite is leaps and bounds better than Ecplise and VS Code.  IntelliJ launches and compiles code so much faster than Eclipse does, and it has smart autocompletion, meaning it actually suggests the most likely piece of code using machine learning.  It also has an extensive collection of plugins, and the UI is so much cleaner.  I would highly recommend the JetBrains suite to anyone.  

**However**, JetBrains does ***not*** allow any of their IDEs to be used for commercial development if you have an educational license.  This means you can *only* do "educational activities" or "academic research" with an educational license.  Still worth having, but if you want to distribute or sell an app that isn't open-source, you have to buy a standard license to do so.

Before you download, I would recommend downloading JetBrains Toolbox to manage all of your updates.  Updating each app individually can be a hassle since there are so many, so Toolbox manages all of your updates in one place.  Link to Toolbox [here](https://www.jetbrains.com/toolbox-app/).  

You can verify your student eligibilty in a variety of ways, but if you already have the GitHub student developer pack, you can get instant verification and access to the full suite.  Link to verify eligiibiliity and download [here](https://www.jetbrains.com/community/education/#students).  If you just want to use the always-free community editions of IntelliJ IDEA and PyCharm, you can download those from the Toolbox app directly once it is installed.

### JetBrains Plugins

Since the JetBrain's IDEs are all based off of the same JetBrains "Core", most plugins can be installed in all of their IDEs, although there are some exceptions (mainly language support plugins depending on the IDE's compiler).  I have provided links alongside each of these, but I think it's better to go to the built-in plugin manager in each IDE and install from there.  Go to Preferences (Mac) or Settings (Windows) > Plugins > Marketplace and search for the name of each one.  Super easy and conveinient.

#### Material Theme UI

This plugin is absolutely essential in my opinion.  The stock UI look and feel in JetBrains IDEs isn't as bad as it is in Eclipse, but it's definitrely not beautiful.  This plugin gives you a dozen or so different UI theme options that look modern and clean, and they completely restyle every component of the UI to match.  My favorite is Material Oceanic.  Link to download [here](https://plugins.jetbrains.com/plugin/8006-material-theme-ui), but once again, installing from the plugin manager in each IDE is easier.

#### Extra Icons

All of the JetBrains IDEs have some IDE-specific config files that live in a folder called `.idea` at the root of your project directory.  Additoinally, each IDE usually creates a `.gitignore` file that lives in the root folder of your project directory.  You might also have Travis or CircleCI config files.  All of these will use generic file or folder icons in the project navigator by default, but this plugin adds custom file and folder icons for each of these special files/folders.  It supports many more files than I've listed here, so it's definitely worth the download.  Link [here](https://plugins.jetbrains.com/plugin/11058-extra-icons), but again, just use the plugin manager in each IDE.

#### Indent Rainbow

Languages that are whitespace-dependent (like Python) or just have a lot of necessary syntax (like Java) can often have lots of nested loops or functions, and making sure that all of your code is indented properly can be a hassle.  This plugin shows you the indentation level of every line of code in the file you're working on by assigning each level of indentation a different color.  It also highlights any anomalies in indentation in red, so finding and fixing indentation errors is super easy.  Link [here](https://plugins.jetbrains.com/plugin/13308-indent-rainbow).  Just use the plugin manager.

#### String Manipulation

This is a simple plugin that provides the ability to switch a statement or variable name from camelCase to kebab-lowercase to snake_case and more.  It also escapes or unescapes strings with literals in them, converts ASCII to Unicode and vice versa, and more.  Link [here](https://plugins.jetbrains.com/plugin/2162-string-manipulation).  Two words: plugin manager.

#### WakaTime

This plugin works with many other IDEs in addition to the JetBrains suite, including Eclipse, VSCode, Xcode, Notepad++, Visual Studio, and more.  It accurately keeps track of the amount of time you spend coding, breaking it down into statistics on the amount of time spent in each lanugage, in each IDE, in each project, and on each computer.  You get emailed a weekly report, all for free.  If you want to keep a history of the time you spend coding (besides the emails), you can purchase a paid plan.  Link to plugin [here](https://plugins.jetbrains.com/plugin/7425-wakatime) and website with instructions for non-JetBrains IDEs [here](https://wakatime.com/).

#### Battery Status

This plugin is really simple, but really useful on a laptop: it displays your current laptop battery percentage in the toolbar at the bottom of the IDE.  This is really helpful in fullscreen mode since your battery indicator is usually hidden in fullscreen.  Link [here](https://plugins.jetbrains.com/plugin/12321-battery-status).

## Platform Specific Software (Mac)

### Flycut Clipboard Manager

This is a free utility avaliable from the Mac App Store that keeps a history of everything you cut/copied.  You can specifiy the number of "clippings" you'd like it to remember, and you can even sync your clippings across devices with iCloud.  This app is very helpful when coding because you can copy many pieces of code and paste the exact ones you want wherever you want them.  Link to Flycut in the Mac App Store [here](https://apps.apple.com/us/app/flycut-clipboard-manager/id442160987?mt=12).