# If you're doing the tutorial at home

If you're doing the tutorial at home, not at one of the [Django Girls events](https://djangogirls.org/events/), you can completely skip this chapter now and go straight to the [How the Internet works](../how_the_internet_works/README.md) chapter.

Good luck!

# Installation
In the workshop you will be building a blog, and there are a few setup tasks in the tutorial which would be good to work through beforehand so that you are ready to start coding on the day.

<!--sec data-title="Chromebook setup (if you're using one)"
data-id="chromebook_setup" data-collapse=true ces-->
{% include "prereq.md" %}
<!--endsec-->


hhhh

# Install Python
{% include "/python_installation/instructions.md" %}
<!--sec data-title="Windows" data-id="python_windows" data-collapse=true ces-->

First check whether your computer is running a 32-bit version or a 64-bit version of Windows, by pressing the Windows key + Pause/Break key which will open your System info, and look at the "System type" line. You can download Python for Windows from the website https://www.python.org/downloads/windows/. Click on the "Latest Python 3 Release - Python x.x.x" link. If your computer is running a **64-bit** version of Windows, download the **Windows x86-64 executable installer**. Otherwise, download the **Windows x86 executable installer**. After downloading the installer, you should run it (double-click on it) and follow the instructions there.

One thing to watch out for: During the installation you will notice a window marked "Setup". Make sure you tick the "Add Python 3.5 to PATH" checkbox and click on "Install Now", as shown here:

![Don't forget to add Python to the Path](../python_installation/images/python-installation-options.png)

In upcoming steps, you'll be using the Windows Command Line (which we'll also tell you about). For now, if you need to type in some commands, go to Start menu → All Programs → Accessories → Command Prompt. You can also hold in the Windows key and press the "R"-key until the "Run" window pops up. To open the Command Line, type "cmd" and press enter in the "Run" window. (On newer versions of Windows, you might have to search for "Command Prompt" since it's sometimes hidden.)

![Type "cmd" in the "Run" window](../python_installation/images/windows-plus-r.png)

Note: if you are using an older version of Windows (7, Vista, or any older version) and the Python 3.5.x installer fails with an error, you can try either:
1. install all Windows Updates and try to install Python 3.5 again; or
2. install an [older version of Python](https://www.python.org/downloads/windows/), e.g., [3.4.4](https://www.python.org/downloads/release/python-344/).


<!--sec data-title="OS X" data-id="python_OSX"
data-collapse=true ces-->

> **Note** Before you install Python on OS X, you should ensure your Mac settings allow installing packages that aren't from the App Store. Go to System Preferences (it's in the Applications folder), click "Security & Privacy," and then the "General" tab. If your "Allow apps downloaded from:" is set to "Mac App Store," change it to "Mac App Store and identified developers."

You need to go to the website https://www.python.org/downloads/release/python-351/ and download the Python installer:

* Download the *Mac OS X 64-bit/32-bit installer* file,
* Double click *python-3.5.1-macosx10.6.pkg* to run the installer.

<!--endsec-->





gitbook-plugin-sectionx
===

<!--sec data-title="Introduction" data-id="intro" data-nopdf="true" ces-->
This page is implemented using the two plugins developed by me: ```gitbook-plugin-sectionx```, please check the [Github repo](https://github.com/ymcatar/gitbook-plugin-sectionx) for the plugin.

The source code for this page is available [here](https://raw.githubusercontent.com/ymcatar/gitbook-test/master/testing_sectionx.md).
<!--endsec-->

<!--sec data-title="Example 1" data-id="section1" ces-->
This is a section that is by default visible. You can toggle this with the button in the title. The next section is hidden by default, you can add a custom button to toggle it (see GitHub for the syntax).

<button class="section" target="section3" show="Show the next section" hide="Hide the next section"></button>
<!--endsec-->

<!--sec data-title="Example 2" data-id="section2" data-collapse=true ces-->
This is a section that is by default closed but visible (with ```data-collapse=true```)
<!--endsec-->

<!--sec data-title="Hidden 3" data-id="section3" data-show=false ces-->
This section can only be opened with that button.
<!--endsec-->