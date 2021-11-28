<h1 align="center">
 <img src="">
  <br />
  Windows Terminal Guide
</h1>

#### A guide covering Windows Terminal including the applications, libraries and tools that will make you a better and more efficient with Windows Terminal development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
<img src="">
<br />
</p>

# Table of Contents

1. [Getting Started with Windows Terminal](https://github.com/mikeroyal/Windows-Terminal-Guide#getting-started-with-windows-terminal)

2. [VSCode Development](https://github.com/mikeroyal/Windows-Terminal-Guide#vscode-development)

    - [VS Code Extensions for Developer Productivity](https://github.com/mikeroyal/-Guide#VS-Code-Extensions-for-Developer-Productivity)

3. [Windows Subsystem for Linux (WSL)](https://github.com/mikeroyal/Windows-Terminal-Guide#windows-subsystem-for-linux-wsl)

4. [Azure Development](https://github.com/mikeroyal/Windows-Terminal-Guide#azure-development)

5. [AWS Development](https://github.com/mikeroyal/Windows-Terminal-Guide#aws-development)

6. [Google Cloud Development](https://github.com/mikeroyal/Windows-Terminal-Guide#google-cloud-development)

7. [Kubernetes](https://github.com/mikeroyal/Windows-Terminal-Guide#kubernetes)

8. [Docker](https://github.com/mikeroyal/Windows-Terminal-Guide#docker)

9. [PowerShell Development](https://github.com/mikeroyal/Windows-Terminal-Guide#powershell-development)

10. [.NET Development](https://github.com/mikeroyal/Windows-Terminal-Guide#net-development)

11. [C# Development](https://github.com/mikeroyal/Windows-Terminal-Guide#c-development)

12. [F# Development](https://github.com/mikeroyal/Windows-Terminal-Guide#f-development)

13. [Xamarin Development](https://github.com/mikeroyal/Windows-Terminal-Guide#Xaramin-Development)

14. [TypeScript Development](https://github.com/mikeroyal/Windows-Terminal-Guide#typescript-development)

15. [Networking](https://github.com/mikeroyal/Windows-Terminal-Guide#networking)

16. [Databases](https://github.com/mikeroyal/Windows-Terminal-Guide#databases)

# Getting Started with Windows Terminal
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

[Windows Terminal](https://github.com/microsoft/terminal) is a new, modern, feature-rich, productive terminal application for command-line users. It includes many of the features most frequently requested by the Windows command-line community including support for tabs, rich text, globalization, configurability, theming & styling, and more. Take a look at the [Windows Terminal GitHub](https://github.com/Microsoft/Terminal).

<p align="center">
 <img src="">
  <br />
  Windows Terminal
</p>

<p align="center">
 <img src="">
  <br />
  Terminal Architecture
</p>

[Git for Windows](https://gitforwindows.org) is a distributed version control system tool that focuses on offering a lightweight, native set of tools that bring the full feature set of the Git SCM to Windows while providing appropriate user interfaces for experienced Git users and novices alike.

[Windows UI Library (WinUI)](https://docs.microsoft.com/en-us/windows/apps/winui/) is a native user experience (UX) framework for both Windows desktop and UWP applications. Take a look at the [Windows UI Library Roadmap](https://github.com/microsoft/microsoft-ui-xaml/blob/main/docs/roadmap.md).

[Windows UI Library (WinUI) 2](https://docs.microsoft.com/en-us/windows/apps/winui/winui2/) is tightly integrated with [Windows 10 and later SDKs](https://developer.microsoft.com/windows/downloads/windows-10-sdk/) and provides official native Windows UI controls and other user interface elements for UWP applications (and desktop applications using [XAML Islands](https://docs.microsoft.com/en-us/windows/apps/desktop/modernize/xaml-islands)).

[XAML Islands](https://docs.microsoft.com/en-us/windows/apps/desktop/modernize/xaml-islands)) is a feature that enables you to enhance the look, feel, and functionality of your existing WPF, Windows Forms, and C++ desktop (Win32) applications with the latest Windows 10 UI features that are only available via WinRT XAML controls. This means that you can use UWP features such as [Windows Ink](https://docs.microsoft.com/en-us/windows/uwp/design/input/pen-and-stylus-interactions) and controls that support the [Fluent Design System](https://docs.microsoft.com/en-us/windows/uwp/design/fluent-design-system/index) in your existing WPF, Windows Forms, and C++ desktop applications.

[Windows Community Toolkit](https://docs.microsoft.com/en-us/windows/communitytoolkit/) is a collection of helper functions, custom controls, and app services. It simplifies and demonstrates common developer tasks building UWP apps for Windows 10. The toolkit can be used to build apps for any Windows 10 device, including PC, Mobile, Xbox, IoT and HoloLens. You can also use the toolkit with an existing desktop app converted to UWP using the Desktop Bridge.

[Windows Pseudo Console (ConPTY)](https://devblogs.microsoft.com/commandline/windows-command-line-introducing-the-windows-pseudo-console-conpty/) is an API that provides a mechanism that is similar to the POSIX PTY model, but in a Windows-relevant manner VT Interactivity. Where it receives incoming UTF-8 encoded text, converts each displayable text character into the corresponding INPUT_RECORD, and stores them in the Input Buffer.

[Comparison of WinUI 3 and WinUI 2](https://docs.microsoft.com/en-us/windows/apps/winui/#comparison-of-winui-3-and-winui-2)

[Introducing Windows Terminal](https://devblogs.microsoft.com/commandline/introducing-windows-terminal/)

[An overview on Windows Terminal | Microsoft Docs](https://docs.microsoft.com/en-us/windows/terminal/)

[Windows Terminal Actions | Microsoft Docs](https://docs.microsoft.com/en-us/windows/terminal/customize-settings/actions)

[Windows Terminal command line arguments | Microsoft Docs](https://docs.microsoft.com/en-us/windows/terminal/command-line-arguments)

[Windows Terminal SSH | Microsoft Docs](https://docs.microsoft.com/en-us/windows/terminal/tutorials/ssh)

[Windows Terminal Themes](https://windowsterminalthemes.dev)

[Top Windows Command Line Courses Online | Udemy](https://www.udemy.com/topic/windows-command-line/)

[Learning Windows Terminal Online Class | LinkedIn Learning](https://www.linkedin.com/learning/learning-windows-terminal)

[Learning the Command Line with Online Courses | edX](https://www.edx.org/learn/command-line)

# VSCode Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/140833078-77973dcf-d3a6-421f-b6a7-b6e63fb1e97c.png">
  <br />
</p>

[Visual Studio Code](https://code.visualstudio.com) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832435-49e53589-e9e1-47fe-a1bd-d9800cfc1274.png">
<br />
VS Code
</p>

[Visual Studio Marketplace](https://marketplace.visualstudio.com/VSCode) is a marketplace for all extensions for Visual Studio, Azure DevOps Services, Azure DevOps Server and Visual Studio Code.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/140832440-0247a088-4eeb-4c57-ae7d-90894d56d629.png">
<br />
VS Code Marketplace
</p>


[VS Code Documentation](https://code.visualstudio.com/docs)

[Working with GitHub in VS Code](https://code.visualstudio.com/docs/editor/github)

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code. Also, from any repo or pull request on GitHub you can simply press the period (.) key on your keyboard to bring up the browser-based VS Code environment with the source code file ready for editing. That dot (.) press to bring up the web-based VS Code editor takes you to https://github.dev/.

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

### VS Code Extensions for Developer Productivity

[Visual Studio Live Share](https://visualstudio.microsoft.com/services/live-share/) is a service/ extension that enables you to collaboratively edit and debug with others in real time, regardless of the programming languages you're using or app types you're building. You can instantly and securely share your current project, start a joint debugging session, share terminal instances, forward localhost web apps, have voice calls, and more.

[GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs) is a Visual Studio Code extension that allows you to edit GitHub Gists and repositories from the comfort of your favorite editor. You can open, create, delete, fork and star gists and repositories, and then seamlessly begin editing files as if they were local, without ever cloning, pushing or pulling anything.

[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) is an extension for Visual Studio Code that launches a development local Server with live reload feature for static & dynamic pages.

[GitHub Pull Requests and Issues](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) is an extension for Visual Studio Code that allows you to review and manage GitHub pull requests and issues in Visual Studio Code.

[Terminal](https://marketplace.visualstudio.com/items?itemName=formulahendry.terminal) is an extension for Visual Studio Code that lets you run terminal command directly in the Editor.

[Profile Switcher](https://marketplace.visualstudio.com/items?itemName=aaronpowell.vscode-profile-switcher) is an extension for Visual Studio Code that allows you to switch between different profiles you have created.

[Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) is an extension for Visual Studio Code that gets the Material Design icons into your VS Code.

[One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme) is an extension for Visual Studio Code that adds Atom's iconic One Dark theme, which is one of the most installed themes for VS Code.

[VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) is an extension for Visual Studio Code that brings icons to your Visual Studio Code setup.

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) is an extension for Visual Studio Code that helps you visualize code authorship at a glance via Git blame annotations and code lens, seamlessly navigate and explore Git repositories, gain valuable insights via powerful comparison commands, and so much more.

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) is an extension for Visual Studio Code that will display inline in the editor the size of the imported/required package. The extension utilizes webpack with babili-webpack-plugin in order to detect the imported size.

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) is an extension for Visual Studio Code that gives you everything you need to write Markdown (keyboard shortcuts, table of contents, auto preview and more).

[Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer) is an extension for Visual Studio Code that allows matching brackets to be identified with colours. The user can define which characters to match, and which colours to use.

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.

[Auto-Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) is an extension for Visual Studio Code that automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text does.

[Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) is an extension for Visual Studio Code that synchronizes Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.

[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) is an extension for Visual Studio Code that lets you mark lines of code and jump to them.

[Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments) is an extension for Visual Studio Code that improves your code commenting by annotating with alert, informational, TODOs, and more.

[Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) is an extension for Visual Studio Code that works as a spelling checker for source code.

[CSS Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek) is an extension for Visual Studio Code that allows peeking to css ID and class strings as definitions from html files to respective CSS. It also allows peek and goto definition.

[Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) is an extension for Visual Studio Code that enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is an extension for Visual Studio Code that is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[NPM Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) is an extension for Visual Studio Code that autocompletes npm modules in import statements.

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) is an extension for Visual Studio Code that autocompletes filenames.

[Relative Path](https://marketplace.visualstudio.com/items?itemName=jakob101.RelativePath) is an extension for Visual Studio Code that gets the relative url paths from files in the current workspace.

[Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) is an extension for Visual Studio Code that provides path completion for visual studio code.

[Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode) is an extension for Visual Studio Code that updates your discord status with a rich presence.

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) is an extension for Visual Studio Code that runs code snippets or code files for multiple languages: C/C++, Java, JavaScript, PHP, Python, Perl, Ruby, Go, Lua, Groovy, PowerShell, BASH/SH, C#, F#, .NET Core, TypeScript, CoffeeScript, Scala, Swift, Julia, OCaml, R, Elixir, Clojure, Haxe, Objective-C, Rust, Racket, Scheme, Kotlin, Dart, Haskell, Nim, D, CUDA, and custom command.

[Kite](https://marketplace.visualstudio.com/items?itemName=kiteco.kite) is an extension for Visual Studio Code that provides an AI-powered programming assistant that helps you write code faster inside Visual Studio Code. Kite works for all major programming languages: Python, Java, Go, PHP, C/C#/C++, Javascript, HTML/CSS, Typescript, React, Ruby, Scala, Kotlin, Bash, Vue and React.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is an extension for Visual Studio Code that provides an AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time in your favorite IDE.

# Windows Subsystem for Linux (WSL)

[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82762656-18de0180-9db7-11ea-9676-ee6fcae615a1.png">
</p>

<img src="https://user-images.githubusercontent.com/45159366/107585931-e6c63700-6bb3-11eb-8f25-f07f8ff05688.png">


## WSL Learning Resources

[WSL 2 Linux Kernel on GitHub](https://github.com/microsoft/WSL2-Linux-Kernel) is the source for the Linux kernel used in Windows Subsystem for Linux 2 (WSL2).

[WSLConf](https://www.youtube.com/playlist?list=PLwFSk464RMxnZkvZ1HKrlNyj-s6Zq4fWe) is a community-initiated event on all things Windows Subsystem for Linux and WSL-related.

[What is the Windows Subsystem for Linux?](https://docs.microsoft.com/en-us/windows/wsl/about)

[Pro Windows Subsystem for Linux (WSL): Powerful Tools and Practices for Cross-Platform Development and Collaboration Book](https://www.amazon.com/Windows-Subsystem-Linux-Cross-Platform-Collaboration/dp/1484268725/ref=sr_1_1?dchild=1&keywords=Pro+Windows+Subsystem+for+Linux+%28WSL%29&qid=1614379171&s=digital-text&sr=1-1-catcorr)

[Windows Subsystem for Linux 2 (WSL 2) Tips, Tricks, and Techniques Book](https://www.amazon.com/Windows-Subsystem-Linux-Tricks-Techniques-ebook/dp/B08K98C7DB/ref=sr_1_1?dchild=1&keywords=WSL+book&qid=1614379053&s=digital-text&sr=1-1)

[Comparing WSL 2 and WSL 1 ](https://docs.microsoft.com/en-us/windows/wsl/compare-versions)

[GPU accelerated machine learning training in the Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/tutorials/gpu-compute)

[CUDA on Windows Subsystem for Linux(WSL) 2](https://developer.nvidia.com/blog/announcing-cuda-on-windows-subsystem-for-linux-2/)

[Developing in Windows Subsystem for Linux (WSL)](https://code.visualstudio.com/docs/remote/wsl)

[Using WSL 2 with Visual Studio Code](https://code.visualstudio.com/blogs/2019/09/03/wsl2)

[WSLG: X11 and Wayland Applications in WSL](https://linuxplumbersconf.org/event/9/contributions/611/attachments/702/1298/XDC2020_-_X11_and_Wayland_applications_in_WSL.pdf)

[How to run Podman on Windows with WSL 2](https://www.redhat.com/sysadmin/podman-windows-wsl2)

[Create a development container in Visual Studio Code](https://code.visualstudio.com/docs/remote/create-dev-container)

[Getting started with MySQL, MongoDB, PostgreSQL, SQLite, Microsoft SQL Server, or Redis to set up a database on WSL](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database)

[Setting up SAP HANA, express edition into WSL 2 (Windows Subsystem for Linux)](https://blogs.sap.com/2020/09/30/installing-sap-hana-express-edition-into-wsl2-windows-subsystem-for-linux/)

[Set up your Node.js development environment with WSL 2](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2)

[Getting started mounting a Linux disk in WSL 2](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2)

[Using Fedora with Microsoft's WSL 2](https://fedoramagazine.org/wsl-fedora-33/)

## WSL Tools & Projects

[wslu](https://github.com/wslutilities/wslu) is a collection of utilities for Windows 10 Linux Subsystem, such as retrieving Windows 10 environment variables or creating your favorite Linux GUI application shortcuts on Windows 10 Desktop.

[Ubuntu on WSL](https://wiki.ubuntu.com/WSL) is a wiki guide on getting started with the latest version of Ubuntu installed and setup on WSL for Windows 10.

[Ubuntu on Windows Community Preview](https://www.microsoft.com/en-us/p/ubuntu-on-windows-community-preview/9p9q5zh1hrr0) is a special build of Ubuntu for WSL as a sandbox for testing new features and getting community feedback. This build is intended for early adopters in the WSL community.

[Ubuntu Pro for Azure](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/canonical.0001-com-ubuntu-pro-focal?tab=Overview) is a premium image designed by Canonical optimized for production environments running on Azure. It includes security and compliance services, enabled by default, in a form suitable for small to large-scale Linux enterprise operations — with no contract needed.

[Azure CLI](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest) is a set of commands used to create and manage Azure resources. The Azure CLI is available across Azure services and is designed to get you working quickly with Azure, with an emphasis on automation.

[Visual Studio Code Remote - WSL extension](https://code.visualstudio.com/docs/remote/wsl) lets you use the Windows Subsystem for Linux (WSL) as your full-time development environment right from VS Code. You can develop in a Linux-based environment, use Linux-specific toolchains and utilities, and run and debug your Linux-based applications all from the comfort of Windows. The extension runs commands and other extensions directly in WSL so you can edit files located in WSL or the mounted Windows filesystem (for example /mnt/c) without worrying about pathing issues, binary compatibility, or other cross-OS challenges.

[Visual Studio Code Remote Development and GitHub Codespaces](https://github.com/Microsoft/vscode-dev-containers) is a  repository of development container definitions for the VS Code Remote - Containers extension and GitHub Codespaces. A development container is a running [Docker](https://www.docker.com/) container with a well-defined tool/runtime stack and its prerequisites. The [VS Code Remote Containers](https://aka.ms/vscode-remote/download/containers) extension allows you to clone a repository or open any folder mounted into (or already inside) a dev container and take advantage of VS Code's full development feature set. [GitHub Codespaces](https://github.com/features/codespaces) both use this same concept to quickly create customized, cloud-based development environments accessible from VS Code or the web.

[Windows Terminal](https://github.com/microsoft/terminal) is a new, modern, feature-rich, productive terminal application for command-line users. It includes many of the features most frequently requested by the Windows command-line community including support for tabs, rich text, globalization, configurability, theming & styling, and more.

[PowerShell Core](https://github.com/PowerShell/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Docker Desktop WSL 2 backend](https://docs.docker.com/docker-for-windows/wsl/) creates an  architectural change that gvies a full Linux kernel built by Microsoft, allowing Linux containers to run natively without emulation. With Docker Desktop running on WSL 2, users can leverage Linux workspaces and avoid having to maintain both Linux and Windows build scripts. In addition, WSL 2 provides improvements to file system sharing, boot time, and allows access to some cool new features for Docker Desktop users.

[Dxgkrnl](https://devblogs.microsoft.com/directx/directx-heart-linux/) is a brand-new kernel driver for Linux that exposes the /dev/dxg device to user mode Linux. /dev/dxg exposes a set of IOCTL that closely mimic the native WDDM D3DKMT kernel service layer on Windows. Dxgkrnl inside of the Linux kernel connects over the VM Bus to its big brother on the Windows host and uses this VM bus connection to communicate with the physical GPU.

[Ansible-WSL](https://github.com/Wintus/Ansible-WSL) is an open source program that makes it easier to provision your Windows from inside of WSL by Ansible.

[WSL-DistroLauncher](https://github.com/Microsoft/WSL-DistroLauncher) is a sample/reference launcher app for WSL distro Microsoft Store packages.

[Pengwin](https://github.com/WhitewaterFoundry/Pengwin) is a Linux distro optimized for WSL based on Debian.

[Pengwin Enterprise](https://github.com/WhitewaterFoundry/Pengwin-Enterprise) is an enterprise Linux solution for Windows Subsystem for Linux (WSL) that is compatible with mainstream enterprise Linux distributions.


## Setting up WSL Linux Distributions

**Requirements**

Before you install any of the Linux Distributions make sure to install/enable the Windows Subsystem for Linux on your Windows 10 machine. Following the instructions below:

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/110054829-ad936980-7d10-11eb-80bd-bc5e96d31d27.png">
<br />
Installing Windows Subsystem Linux
</p>

**OR**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/109565559-7fefbb80-7a97-11eb-8502-4d8f2eeb4842.png">
 </p>

**For more technical users you run this command in Powershell:**

```sh
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
```

[Ubuntu 20.04 LTS](https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563752-0eaf0900-7a95-11eb-9fd7-9be123b57cc1.png">
</p>


[Debian](https://www.microsoft.com/en-us/p/debian/9msvkqc78pk6?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563781-14a4ea00-7a95-11eb-8008-61867e38cf1e.png">
</p>

[Fedora 33 fo WSL](https://fedoramagazine.org/wsl-fedora-33/)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563789-15d61700-7a95-11eb-9c99-c1e68ead8388.png">
</p>

[SUSE Linux Enterprise Server 15 SP1](https://www.microsoft.com/en-us/p/suse-linux-enterprise-server-15-sp1/9pn498vpmf3z?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563809-1bcbf800-7a95-11eb-8be7-e94b2feb74a7.png">
</p>


[openSUSE Leap 15.2](https://www.microsoft.com/en-us/p/opensuse-leap-152/9mzd0n9z4m4h?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563802-1a9acb00-7a95-11eb-9c6a-14bbcde765dd.png">
</p>

[Kali Linux](https://www.microsoft.com/en-us/p/kali-linux/9pkr34tncv07?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563822-1ec6e880-7a95-11eb-8d4b-a051178da3e2.png">
</p>

[Pengwin](https://www.microsoft.com/en-us/p/pengwin/9nv1gv1pxz6p?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563833-225a6f80-7a95-11eb-93e8-f40799469bcc.png">
</p>


[Fedora Remix for WSL](https://www.microsoft.com/en-us/p/fedora-remix-for-wsl/9n6gdm4k2hnc?activetab=pivot:overviewtab)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563839-238b9c80-7a95-11eb-8a41-fc9775c810bb.png">
</p>


[GWSL](https://www.microsoft.com/en-us/p/gwsl/9nl6kd1h33v3?activetab=pivot:overviewtab) is an XServer that lets you easily run graphical Linux apps on Windows 10.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/109563870-2e463180-7a95-11eb-93b1-77c1ff0ef39d.png">
</p>

# Azure Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/118413013-01e09100-b652-11eb-95a9-fdb664687470.png">
  <br />
</p>

**[Visual Studio Code Azure Extensions](https://code.visualstudio.com/docs/azure/extensions)**

## Azure Learning Resources

[Microsoft Azure](https://azure.microsoft.com/en-us/) is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

[Get started with Azure](https://azure.microsoft.com/en-us/get-started/)

[Azure Demo and Q&A](https://azure.microsoft.com/en-us/get-started/webinar/)

[Microsoft Azure Training & Certification Courses](https://www.microsoft.com/en-us/learning/azure-training-certification.aspx)

[Azure on Microsoft Learn](https://docs.microsoft.com/en-us/learn/azure/)

[Microsoft Certified: Azure Fundamentals](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/)

[Microsoft Certified: DevOps Engineer Expert Cert.](https://docs.microsoft.com/en-us/learn/certifications/devops-engineer)

[Introduction to Azure DevOps from A Cloud Guru](https://acloud.guru/learn/introduction-to-azure-devops)

[Microsoft Certified: Azure IoT Developer Specialty](https://docs.microsoft.com/en-us/learn/certifications/azure-iot-developer-specialty)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Microsoft Azure Certification Training Courses on Udemy](https://www.udemy.com/topic/microsoft-azure/)

[Free Microsoft Azure Courses & Tutorials on Udemy](https://www.udemy.com/topic/microsoft-azure/free/)

[Microsoft Azure Certification Training Courses on Coursera](https://www.coursera.org/learn/cloud-azure-intro)

[Microsoft Azure Certification Training Courses on edX](https://www.edx.org/learn/azure)

## Azure Tools

[Microsoft Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)

[Azure command-line interface (Azure CLI)](https://docs.microsoft.com/en-us/cli/azure/) is a command line that provides a set of commands used to create and manage Azure resources.

[Visual Studio Code](https://code.visualstudio.com/docs/azure/extensions) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

[Azure Functions](https://azure.microsoft.com/en-us/services/functions/) is a solution for easily running small pieces of code, or "functions," in the cloud. You can write just the code you need for the problem at hand, without worrying about a whole application or the infrastructure to run it.

[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) is a set of services for teams to share code, track work, and ship software; CLIs Build, deploy, diagnose, and manage multi-platform, scalable apps and services; Azure Pipelines Continuously build, test, and deploy to any platform and cloud; Azure Lab Services Set up labs for classrooms, trials, development and testing, and other scenarios.

[Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15) is a cross-platform database tool for data professionals using on-premises and cloud data platforms on Windows, macOS, and Linux. It offers a modern editor experience with IntelliSense, code snippets, source control integration, and an integrated terminal. It's engineered with the data platform user in mind, with built-in charting of query result sets and customizable dashboards.

[Azure Active Directory (Azure AD)](https://azure.microsoft.com/en-us/services/active-directory/) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access resources in: External resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications.

[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview) is a client tool that helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

[Azure Cognitive Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) is a set of cloud-based services with REST APIs and client library SDKs available to help you build cognitive intelligence into your applications. You can add cognitive features to your applications without having artificial intelligence (AI) or data science skills. All it takes is an API call to embed the ability to see, hear, speak, search, understand, and accelerate decision-making into your apps.

[Azure Data Lake Storage](https://azure.microsoft.com/en-us/solutions/data-lake/) is a storage repository that holds a large amount of data in its native, raw format. Data lake stores are optimized for scaling to terabytes and petabytes of data. The data typically comes from multiple heterogeneous sources, and may be structured, semi-structured, or unstructured.

[Azure Service Fabric](https://azure.microsoft.com/en-us/services/service-fabric/) is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers. Service Fabric also addresses the significant challenges in developing and managing cloud native applications. It powers core Azure infrastructure as well as other Microsoft services such as Skype for Business, Intune, Azure Event Hubs, Azure Data Factory, Azure Cosmos DB, Azure SQL Database, Dynamics 365, and Cortana.

[Microsoft Azure Storage Emulator](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-emulator) is a tool that emulates the Azure Blob, Queue, and Table services for local development purposes. You can test your application against the storage services locally without creating an Azure subscription or incurring any costs.

[Azure Cosmos DB Emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator?tabs=cli,ssl-netstd21) is a tool that provides a local environment that emulates the Azure Cosmos DB service for development purposes. Using the Azure Cosmos DB Emulator, you can develop and test your application locally, without creating an Azure subscription or incurring any costs.

[Microsoft Azure Storage Explorer](https://www.storageexplorer.com/) is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS, and Linux.

[Azure BatchExplorer](https://github.com/Azure/BatchExplorer#batchexplorer) is a  client tool to help create, debug and monitor Azure Batch Applications.

[Azure Key Vault Explorer](https://github.com/microsoft/AzureKeyVaultExplorer/blob/master/README.md)  is a  client tool to help be productive when working with secrets.

[Azurite](https://github.com/Azure/Azurite/blob/master/README.md) is an open source Azure Storage API compatible server (emulator). Based on Node.js, Azurite provides cross platform experiences for customers wanting to try Azure Storage easily in a local environment. Azurite simulates most of the commands supported by Azure Storage with minimal dependencies.

[Azure Cloud Shell](https://shell.azure.com/) is an interactive, authenticated, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work, either Bash or PowerShell.

[Azure Lab Services](https://azure.microsoft.com/en-us/services/lab-services/) is an easy to set up and provide on-demand access to preconfigured virtual machines (VMs) to support your scenarios. Teach a class, train professionals, run a hackathon or a hands-on lab, and more.

[Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) is a cloud-hosted pipelines for Linux, macOS, and Windows. Where you can build web, desktop and mobile applications. Deploy to any cloud or on‑premises.

[Azure Bots Service](https://azure.microsoft.com/en-us/services/bot-services/) is a service that develops intelligent, enterprise-grade bots that help you enrich the customer experience while maintaining control of your data. Build any type of bot—from a Q&A bot to your own branded virtual assistant—to quickly connect your users to the answers they need.

[Azure PlayFab](https://azure.microsoft.com/en-us/services/playfab/) is a service that enables developers to use the intelligent cloud to build and operate games, analyze gaming data and improve overall gaming experiences. Along with the Microsoft Game Stack that includes platforms, tools, and services like Visual Studio, DirectX, Havok, and Xbox.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a tool that makes it fast, easy, and collaborative Apache Spark-based analytics platform. Azure Databricks, set up your Apache Spark™ environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/) is an enterprise-grade machine learning service to build and deploy models faster. It empowers data scientists and developers with a wide range of productive experiences to build, train, and deploy machine learning models and foster team collaboration. Accelerate time to market with industry-leading MLOps—DevOps for machine learning. Innovate on a secure, trusted platform, designed for responsible machine learning.

[Azure Open Datasets](https://azure.microsoft.com/en-us/services/open-datasets/) is a tool that curates open data made easily accessible on Azure.

[Azure Percept](https://azure.microsoft.com/en-us/services/azure-percept/) is a comprehensive, easy-to-use platform with added security for creating edge AI solutions.

[Azure Data Share](https://azure.microsoft.com/en-us/services/data-share/) is a simple and safe service for sharing big data. It  provides full visibility into your data sharing relationships with a user-friendly interface. Share data in just a few clicks, or build your own application using the REST API.

[Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/) is a fully managed, serverless data integration solution for ingesting, preparing, and transforming all your data at scale.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together data integration, enterprise data warehousing, and big data analytics. It gives you the freedom to query data on your terms, using either serverless or dedicated resources at scale.

[Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) is an enterprise-ready, managed cluster service for open-source analytics.It let's you run popular open-source frameworks including Apache Hadoop, Spark, Hive, Kafka, and more.

[Azure Blockchain Service](https://azure.microsoft.com/en-us/services/blockchain-service/) is a service that simplifies the formation, management, and governance of consortium blockchain networks so you can focus on business logic and app development.

[Azure Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/) is a leading integration platform as a service (iPaaS) enables key enterprise scenarios for developers. Built on a containerized runtime that increases scale and portability while automating business-critical workflows anywhere.

[Azure Quantum](https://azure.microsoft.com/en-us/services/quantum/) is an innovative quantum computing and optimization solutions converge in a single marketplace quantum service.

[Azure VMware Solution](https://azure.microsoft.com/en-us/services/azure-vmware/) is a service that seamlessly moves VMware-based workloads from your datacenter to Azure and integrate your VMware environment with Azure. Keep managing your existing environments with the same VMware tools you already know while you modernize your applications with Azure native services.

[Azure Spring Cloud](https://azure.microsoft.com/en-us/services/spring-cloud/) is a fully managed Spring Cloud service, jointly built and operated with VMware.

[Azure CycleCloud](https://azure.microsoft.com/en-us/features/azure-cyclecloud/) is a serviece that creates, manages, operates, and optimizes HPC and big compute clusters of any scale.

[Azure API Apps](https://azure.microsoft.com/en-us/services/app-service/api/) is a service that quickly builds and consumes APIs in the cloud using the language of your choice.

[Azure Web Apps](https://azure.microsoft.com/en-us/services/app-service/web/) is an easy way to create and deploy mission-critical web applications that scale with your business.

[Windows Virtual Desktop](https://azure.microsoft.com/en-us/services/virtual-desktop/) is a service that enables a secure, remote desktop experience from anywhere.

[VMware Horizon Cloud on Microsoft Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/vmware-horizon-cloud/) is a desktop virtualization service available in Azure Marketplace. Simplify your delivery of on-premises and cloud virtual desktops and applications by connecting your instance of Azure to VMware.

[Citrix Virtual Apps and Desktops for Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/citrix-virtual-apps-desktops-for-azure/) is a desktop and app virtualization service available through Azure Marketplace or agreements with Citrix. Use familiar tools to manage on-premises Citrix deployments alongside Windows Virtual Desktop on Azure, supporting cloud modernization while maximizing your existing investment.

[Azure Container Registry](https://azure.microsoft.com/en-us/services/container-registry/) is a registry of Docker and Open Container Initiative (OCI) images, with support for all OCI artifacts.

[Azure Web App for Containers](https://azure.microsoft.com/en-us/services/app-service/containers/) is an easily deploy and run containerized applications on Windows and Linux.

[Azure SQL Edge](https://azure.microsoft.com/en-us/services/sql-edge/) is a service that makes a small-footprint, edge-optimized SQL database engine with built-in AI. This productivity tool for edge computing combines new capabilities such as data streaming and time series with in-database machine learning and graph features. Develop your application once and deploy anywhere across the edge, your datacenter, and Azure.

[Azure Arc](https://azure.microsoft.com/en-us/services/azure-arc/) is a service that offers simplified management, faster app development, and consistent Azure services. Standardize visibility, operations, and compliance across a wide range of resources and locations by extending the Azure control plane. Build cloud-native apps anywhere, at scale.

[Azure Artifacts](https://azure.microsoft.com/en-us/services/devops/artifacts/) is a services that provides fully integrated package management to your continuous integration/continuous delivery (CI/CD) pipelines with a single click. Create and share Maven, npm, NuGet, and Python package feeds from public and private sources with teams of any size.

[Azure Boards](https://azure.microsoft.com/en-us/services/devops/boards/) is a service that helps you plan, track, and discuss work across your teams. It let's you track work with Kanban boards, backlogs, team dashboards, and custom reporting.

[Azure ExpressRoute](https://azure.microsoft.com/en-us/services/expressroute/) is a tool that helps you experience a faster, private connection to Azure.

[Azure Sentinel](https://azure.microsoft.com/en-us/services/azure-sentinel/) is your birds-eye view across the enterprise. It uses the cloud and large-scale intelligence from decades of Microsoft security experience to work. Making your threat detection and response smarter and faster with artificial intelligence (AI).

[Azure Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) is a service that builds and runs hybrid apps across datacenters, edge locations, remote offices, and the cloud.

[Azure Stack HCI](https://azure.microsoft.com/en-us/products/azure-stack/hci/) is a new hyperconverged infrastructure (HCI) operating system delivered as an Azure service that provides the latest security, performance, and feature updates. Deploy and run Windows and Linux virtual machines (VMs) in your datacenter or at the edge using your existing tools, processes, and skill sets.

[Azure Sphere](https://azure.microsoft.com/en-us/services/azure-sphere/) is a comprehensive IoT security solution including hardware (crossover microcontroller), OS, and cloud components for IoT device security to actively protect your devices, your business, and your customers.

[Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) is a service that provides a cloud-hosted solution back end to connect virtually any device. Extend your solution from the cloud to the edge with per-device authentication, built-in device management, and scaled provisioning.

[Azure IoT Edge](https://azure.microsoft.com/en-us/services/iot-edge/) is a fully managed service built on Azure IoT Hub. Deploy your cloud workloads—artificial intelligence, Azure and third-party services, or your own business logic to run on Internet of Things (IoT) edge devices via standard containers.

[Azure Lighthouse](https://azure.microsoft.com/en-us/services/azure-lighthouse/) is a secure managed services and access control for partners and customers.

[Azure Backup](https://azure.microsoft.com/en-us/services/backup/) is a cost-effective, secure, one-click backup solution that’s scalable based on your backup storage needs. The centralized management interface makes it easy to define backup policies and protect a wide range of enterprise workloads, including Azure Virtual Machines, SQL and SAP databases, and Azure file shares.

[Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/) is a tool that enables you to repeatedly deploy your app and have confidence your resources are deployed in a consistent state. You define the infrastructure and dependencies for your app in a single declarative template. This template is flexible enough to use for all of your environments such as test, staging or production.

[Azure Automanage](https://azure.microsoft.com/en-us/services/azure-automanage/) is a tool that implifies IT management with optimized, automated operations across the entire lifecycle of dev/test and production virtual machines (VMs).

[Azure Network Watcher](https://azure.microsoft.com/en-us/services/network-watcher/) is a tool that monitors, diagnoses, and gains insights to your network performance and health.

[Azure Resource Mover](https://azure.microsoft.com/en-us/services/resource-mover/) is a that that Simplifies how you move multiple resources between Global Azure regions.

[Azure Bastion](https://azure.microsoft.com/en-us/services/azure-bastion/) is a fully managed PaaS service that provides secure and seamless RDP and SSH access to your virtual machines directly through the Azure Portal. Azure Bastion is provisioned directly in your Virtual Network (VNet) and supports all VMs in your Virtual Network (VNet) using SSL without any exposure through public IP addresses.

[Azure Load balancing](https://azure.microsoft.com/en-us/products/azure-load-balancing/) is a service that instantly scale your applications with Azure load balancing services for high availability and high performance. Get started with a quick needs assessment and load balancing recommendation—using the service selection tool.

[Azure Orbital](https://azure.microsoft.com/en-us/services/orbital/) is a Ground Station As-a-Service that provides communication and control of your satellite. Orbital enables easy and integrated data processing and scale for your operations directly from Azure. Leverage familiar Azure services to process and store your data at scale.

[Azure Route Server](https://azure.microsoft.com/en-us/services/route-server/) is a tool that enables network appliances to exchange route information with Azure virtual networks dynamically. Configure your network appliances and Azure ExpressRoute and VPN gateways to automatically take the latest route information from Azure Route Server instead of manually talking to each network.

[Azure VPN Gateway](https://azure.microsoft.com/en-us/services/vpn-gateway/) is a service that connects your on-premises networks to Azure through Site-to-Site VPNs in a similar way that you set up and connect to a remote branch office. The connectivity is secure and uses the industry-standard protocols Internet Protocol Security (IPsec) and Internet Key Exchange (IKE).

[Microsoft Azure Attestation](https://azure.microsoft.com/en-us/services/azure-attestation/) is a unified solution for remotely verifying the trustworthiness of a platform and integrity of the binaries running inside it. Azure Attestation receives evidence from the platform, validates it with security standards, evaluates it against configurable policies, and produces an attestation token for claims-based applications. The service supports attestation of trusted platform modules (TPMs) and trusted execution environments (TEEs) like Intel® Software Guard Extensions (SGX) and virtualization-based security (VBS) enclaves.

[Azure Data Box](https://azure.microsoft.com/en-us/services/databox/) is a device that easily moves data to Azure when busy networks aren’t an option. Move large amounts of data to Azure when you're limited by time, network availability, or costs, using common copy tools such as Robocopy. All data is AES-encrypted, and the devices are wiped clean after upload, in accordance with NIST Special Publication 800-88 revision 1 standards.

[Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/) is a massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning.

[PowerShell/PowerShell Core](https://docs.microsoft.com/en-us/powershell/) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) creates virtual machines on Windows 10. Hyper-V can be enabled in many ways including using the Windows 10 control panel, PowerShell or using the Deployment Imaging Servicing and Management tool (DISM).

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.

# AWS Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114322508-7d8c7280-9ad5-11eb-807e-4dc63c9bc0e1.png">
  <br />
</p>

**[AWS Toolkit for Visual Studio Code](https://aws.amazon.com/visualstudiocode/)**

## AWS Learning Resources

[Amazon Web Services](https://aws.amazon.com/about-aws/) is a reliable, scalable, and inexpensive on-demand cloud computing platforms, services and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.

[AWS Training and Certification](https://aws.amazon.com/training/)

[Getting Started with Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/)

[Hands-On Tutorials for Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/hands-on/

[Getting started with AWS IoT Core ](https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html)

[AWS Academy - Amazon Web Services (AWS)](https://aws.amazon.com/training/awsacademy/)

[AWS Educate](https://aws.amazon.com/education/awseducate/)

[Architecting on AWS Classroom Training](https://aws.amazon.com/training/classroom/architecting-on-aws/)

[DevOps Engineering on AWS from AWS Training](https://aws.amazon.com/training/course-descriptions/devops-engineering/)

[AWS Certified DevOps Engineer - Professional from A Cloud Guru](https://acloud.guru/learn/aws-certified-devops-engineer-professional)

[AWS Internet of Things Foundation Series Training](https://www.aws.training/Details/Curriculum?id=27289)

[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[AWS Certification Training Courses on Udemy](https://www.udemy.com/topic/aws-certification/)

[Amazon Web Services Courses on Coursera](https://www.coursera.org/aws)

[Amazon Web Services Courses on edX](https://www.edx.org/school/aws)

## AWS Tools

[AWS Pricing Calculator](https://calculator.aws/)

[AWS Marketplace](https://aws.amazon.com/) is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS.

[AWS Cloud9](https://aws.amazon.com/cloud9/) is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser. It includes a code editor, debugger, and terminal. Cloud9 comes prepackaged with essential tools for popular programming languages, including JavaScript, Python, PHP, and more, so you don’t need to install files or configure your development machine to start new projects.

[AWS Command Line Interface (CLI)](https://aws.amazon.com/cli/) is a unified tool to manage your AWS services through the command line interface.

[AWS Amplify Command Line Interface (CLI)](https://docs.amplify.aws/cli) is a unified toolchain to create, integrate, and manage the AWS cloud services for your app.

[AWS Serverless Application Model (SAM) CLI](https://github.com/aws/aws-sam-cli) is a command line tool for an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines of configuration, you can define the application you want and model it.

[AWS Copilot command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Copilot.html) is a command line tool that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS from a local development environment. The AWS Copilot CLI aligns with developer workflows that support modern application best practices: from using infrastructure as code to creating a CI/CD pipeline provisioned on behalf of a user.

[Amazon Elastic Container Service (Amazon ECS) command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI.html) is a command line tool that  provides high-level commands to simplify creating, updating, and monitoring clusters and tasks from a local development environment. The Amazon ECS CLI supports Docker Compose files, a popular open-source specification for defining and running multi-container applications.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Amazon Simple Storage Service (Amazon S3)](https://aws.amazon.com/s3/) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.

[AWS Cloud Development Kit (AWS CDK)](https://aws.amazon.com/cdk/) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation. It offers a high-level object-oriented abstraction to define AWS resources imperatively using the power of modern programming languages.

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) is an easy-to-use service for deploying and scaling web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.

[AWS IoT Greengrass](https://aws.amazon.com/greengrass/) is an Internet of Things (IoT) open source edge runtime and cloud service that helps you build, deploy, and manage device software. It is used for IoT applications on millions of devices in homes, factories, vehicles, and businesses.

[AWS CodeArtifact](https://aws.amazon.com/codeartifact/) is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process. CodeArtifact can be configured to automatically fetch software packages and dependencies from public artifact repositories so developers have access to the latest versions.

[AWS CodeCommit](https://aws.amazon.com/codecommit/) is a fully-managed source control service that hosts secure Git-based repositories. It makes it easy for teams to collaborate on code in a secure and highly scalable ecosystem. CodeCommit eliminates the need to operate your own source control system or worry about scaling its infrastructure.

[AWS CodePipeline](https://aws.amazon.com/codepipeline/) is a fully managed [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin.

[AWS CodeStar](https://aws.amazon.com/codestar/) is a unified user interface, enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) toolchain in minutes, allowing you to start releasing code faster.

[AWS X-Ray](https://aws.amazon.com/xray/) is a tool that traces user requests as they travel through your entire application. It aggregates the data generated by the individual services and resources that make up your application, providing you an end-to-end view of how your application is performing. It helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[Red Hat OpenShift Service on AWS (ROSA)](https://www.openshift.com/products/amazon-openshift) is a fully-managed and jointly supported Red Hat OpenShift offering that combines the power of Red Hat OpenShift, the industry's most comprehensive enterprise Kubernetes platform, and the AWS public cloud.

[Amazon API Gateway](https://aws.amazon.com/api-gateway/) is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

[AWS Storage Gateway](https://aws.amazon.com/storagegateway/) is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage.

[AWS Transit Gateway](https://aws.amazon.com/transit-gateway/) is a tool that connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router - each new connection is only made once.

[Gateway Load Balancer (GWLB)](https://aws.amazon.com/elasticloadbalancing/gateway-load-balancer/) is a tool that makes it easy to deploy, scale, and manage your third-party virtual appliances. It gives you one gateway for distributing traffic across multiple virtual appliances, while scaling them up, or down, based on demand.

[AWS Chalice](https://aws.amazon.com/blogs/developer/deploying-aws-chalice-application-using-aws-cloud-development-kit/) is a Python Serverless Microframework for AWS and allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda.

[AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) is an AWS supported Open Source cluster management tool to deploy and manage HPC clusters in the AWS cloud.

[AWS Copilot CLI](https://aws.amazon.com/containers/copilot/) is a tool for developers to build, release and operate production ready containerized applications on Amazon ECS and AWS Fargate.

[AWS Fargate](https://aws.amazon.com/fargate/) is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).

[Amazon Chime](https://aws.amazon.com/chime/) is a communications service that lets you meet, chat, and place business calls inside and outside your organization, all using a single application.

[Amazon Virtual Private Cloud (Amazon VPC)](https://console.aws.amazon.com/vpc) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.

[AWS Lightsail](https://aws.amazon.com/lightsail/) is an easy-to-use virtual private server (VPS) that offers you everything needed to build an application or website, plus a cost-effective, monthly plan.

[Amazon Relational Database Service (Amazon RDS)](https://console.aws.amazon.com/rds/home) is a tool that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups.

[Amazon Aurora](https://console.aws.amazon.com/rds/home) is a MySQL and PostgreSQL-compatible relational database built for the cloud, that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.

[Amazon Athena](https://aws.amazon.com/athena/) is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.

[Amazon CloudSearch](https://aws.amazon.com/cloudsearch/) is a managed service in the AWS Cloud that makes it simple and cost-effective to set up, manage, and scale a search solution for your website or application.

[Amazon Kinesis](https://aws.amazon.com/kinesis/) is a tool that makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications.

Amazon EMR is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as [Apache Spark](https://aws.amazon.com/emr/features/spark/), [Apache Hive](https://aws.amazon.com/emr/features/hive/), [Apache HBase](https://aws.amazon.com/emr/features/hbase/), [Apache Flink](https://aws.amazon.com/blogs/big-data/use-apache-flink-on-amazon-emr/),[Apache Hudi](https://aws.amazon.com/emr/features/hudi/), and [Presto](https://aws.amazon.com/emr/features/presto/).

[AWS RedShift](https://aws.amazon.com/redshift/) is a data warehouse tool that makes it as easy to gain new insights from all your data. With Redshift, you can easily query and combine exabytes of structured and semi-structured data across your data warehouse, operational database, and data lake using standard SQL. It lets you easily save the results of your queries back to your S3 data lake using open formats, like Apache Parquet, so that you can do additional analytics from other analytics services like Amazon EMR, Amazon Athena, and Amazon SageMaker.

[AWS Data Pipeline](https://aws.amazon.com/datapipeline/) is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. AWS Data Pipeline, let's you regularly access your data where it’s stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

[AWS Glue](https://aws.amazon.com/glue/) is a serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.

[AWS Lake Formation](https://aws.amazon.com/lake-formation/) is a service that makes it easy to set up a secure data lake in days. A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis.

[Amazon Managed Blockchain](https://aws.amazon.com/managed-blockchain/) is a fully managed service that makes it easy to join public networks or create and manage scalable private networks using the popular open-source frameworks [Hyperledger Fabric](https://aws.amazon.com/blockchain/what-is-hyperledger-fabric/) and Ethereum.

[AWS Wavelength](https://aws.amazon.com/wavelength/) is an AWS Infrastructure offering optimized for mobile edge computing applications. Wavelength Zones are AWS infrastructure deployments that embed AWS compute and storage services within communications service providers’ (CSP) datacenters at the edge of the 5G network, so application traffic from 5G devices can reach application servers running in Wavelength Zones without leaving the telecommunications network.

[AWS Outposts](https://aws.amazon.com/outposts/) is a fully managed service that offers the same AWS infrastructure, AWS services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience. AWS Outposts is ideal for workloads that require low latency access to on-premises systems, local data processing, data residency, and migration of applications with local system interdependencies.

[AWS Batch](https://aws.amazon.com/batch/) is atool that enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch plans, schedules, and executes your batch computing workloads across the full range of AWS compute services and features, such as [AWS Fargate](https://aws.amazon.com/fargate/), [Amazon EC2](https://aws.amazon.com/ec2/) and [Spot Instances](https://aws.amazon.com/ec2/spot/).

[Amazon Forecast](https://aws.amazon.com/forecast/) is a fully managed service that uses machine learning to deliver highly accurate forecasts.

[AWS Snow Family](https://aws.amazon.com/snow/) is a highly-secure, portable devices to collect and process data at the edge, and migrate data into and out of AWS.

[Amazon Neptune](https://aws.amazon.com/neptune/) is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

[Amazon Timestream](https://aws.amazon.com/timestream/) is a fast, scalable, and serverless time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day up to 1,000 times faster and at as little as 1/10th the cost of relational databases.

[AWS IoT](https://aws.amazon.com/iot/) is a service that is built on a secure and proven cloud infrastructure, and scales to billions of devices and trillions of messages. It easily integrates with other AWS services, so you can build complete solutions.

[AWS IoT Core](https://aws.amazon.com/iot-core/) lets you connect IoT devices to the AWS cloud without the need to provision or manage servers. AWS IoT Core can support billions of devices and trillions of messages, and can process and route those messages to AWS endpoints and to other devices reliably and securely.

# Google Cloud Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114321928-639d6080-9ad2-11eb-8297-5e6c10c1c792.png">
  <br />
</p>

**[Cloud Code for VS Code extension](https://cloud.google.com/code/docs/vscode/install)**

## Google Cloud Learning Resources

[Google Cloud Platform] is a public cloud platform that lets you build, deploy, and scale applications, websites, and services on the same infrastructure as Google.

[Google Cloud Courses and Training](https://cloud.google.com/training/)

[Architecting with Google Compute Engine](https://google.qwiklabs.com/courses/1421?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Get started with Cloud Storage on Web with Firebase](https://firebase.google.com/docs/storage/web/start)

[Getting started with BigQuery](https://cloud.google.com/bigquery/docs/quickstarts)

[Machine Learning Crash Course with Google Cloud](https://developers.google.com/machine-learning/crash-course/)

[Architecting with Google Kubernetes Engine in Google Cloud](https://google.qwiklabs.com/courses/1232?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Google Cloud Internet of Things (IoT)](https://developers.google.com/iot/)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Google Cloud Courses on Coursera](https://www.coursera.org/googlecloud)

[Google Cloud Courses on Udemy](https://www.udemy.com/topic/google-cloud/)


## Google Cloud Tools

[Cloud SDK](https://cloud.google.com/sdk/) is a clietn tool used to to manage Google Cloud resources and applications with command-line tools and libraries. The Cloud SDK contains gcloud, gsutil, and bq command-line tools, which you can use to access [Compute Engine](https://cloud.google.com/compute), [Cloud Storage](https://cloud.google.com/storage), [BigQuery](https://cloud.google.com/bigquery), and more.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.

[Cloud Code](https://cloud.google.com/code) is a client tool that writes, debugs, and run cloud-native applications, locally or in the cloud—quickly and easily. Extensions to IDEs such as Visual Studio Code and IntelliJ are provided to let you rapidly iterate, debug, and deploy code to Kubernetes.

[gcloud](https://cloud.google.com/sdk/gcloud/) is a CLI (command line interface) manages authentication, local configuration, developer workflow, interactions with Google Cloud APIs.

[gsutil](https://cloud.google.com/storage/docs/gsutil) is a Python application that lets you access Cloud Storage from the command line.

[Compute Engine](https://cloud.google.com/compute) is a secure and customizable compute service that lets you create and run virtual machines on Google’s infrastructure.

[App Engine](https://cloud.google.com/appengine/) is a client tool that lets you build and run applications on Google's infrastructure. It automatically scales to support sudden traffic spikes without provisioning, patching, or monitoring.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[Cloud Storage](https://cloud.google.com/storage) is a Object storage for companies of all sizes. Where store any amount of data and retrieve it as often as you would like to.

[BigQuery](https://cloud.google.com/bigquery) is a serverless, highly scalable, and cost-effective multi-cloud data warehouse designed for business agility.

[Cloud Bigtable](https://cloud.google.com/bigtable/) is Google's fully managed NoSQL Big Data database service. It's the same database that powers many core Google services, including Search, Analytics, Maps, and Gmail.

[Cloud SQL](https://cloud.google.com/sql/) is a tool that makes it easy to set up, manage, and administer your Postgres databases on Google Cloud.

[Cloud Datastore](https://cloud.google.com/datastore/) is a schemaless database, which allows you to worry less about making changes to your underlying data structure as your application evolves.

[Cloud Pub/Sub](https://cloud.google.com/pubsub/) is a messaging middleware for traditional service integration or a simple communication medium for modern microservices.

[Cloud Dataflow](https://cloud.google.com/dataflow/) is a tool that brings streaming events to Google Cloud's AI Platform and TensorFlow Extended (TFX) to enable predictive analytics, fraud detection, real-time personalization, and other advanced analytics.

[Cloud Dataproc](https://cloud.google.com/dataproc/) is a fully managed and highly scalable service for running Apache Spark, Apache Flink, Presto, and 30+ open source tools and frameworks.

[Cloud Datalab](https://cloud.google.com/datalab/docs/) is a tool that provides a productive, interactive, and integrated tool to explore, visualize, analyze and transform data, bringing together the power of Python, SQL, JavaScript, and the Google Cloud Platform with services such as BigQuery and Storage.

[Cloud Vision API](https://cloud.google.com/vision/) is a library that offers powerful pre-trained machine learning models through REST and RPC APIs.

[Cloud Speech API](https://cloud.google.com/speech-to-text/) is a library that enables developers to convert audio to text by applying powerful neural network models. The API recognizes over 80 languages and variants, to support your global user base.

[Cloud Build](https://cloud.google.com/cloud-build) is a continuous build, test, and deploy software across all languages and in multiple environments—including VMs, serverless, Kubernetes, and Firebase.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Jenkins on Google Cloud](https://cloud.google.com/jenkins) is a client tool that helps speed up, scale, and security from your Jenkins pipeline.

[Tekton on Google Cloud](https://cloud.google.com/tekton) is a client tool that standardizes CI/CD pipelines across languages, and tools on premises or in the cloud with a Kubernetes native open source framework.

[Artifact Registry](https://cloud.google.com/artifact-registry) is a client tool to manage container images and language packages such as Maven and npm all in one place, fully integrated with Google Cloud’s tooling and runtimes.

[Cloud Deployment Manager](https://cloud.google.com/deployment-manager) is a client that creates and manages cloud resources with simple templates. Specify all the resources needed for applications in a declarative format using yaml.

[Red Hat OpenShift on Google Cloud](https://cloud.google.com/solutions/partners/openshift-on-gcp) is a fully-managed and jointly supported Red Hat OpenShift offering that enables you to deploy stateful and stateless apps with nearly any language, framework, database, or service. It gives you a hosted environment entirely on Google Cloud. A hybrid environment where you maintain part of your workload on-premises or in a private hosting environment and migrate the rest to Google Cloud.

# Kubernetes
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
  <br />
</p>

**[Working with Kubernetes in Visual Studio Code](https://code.visualstudio.com/docs/azure/kubernetes)**

<img src="https://user-images.githubusercontent.com/45159366/105645195-db9ea780-5e4e-11eb-8357-fb38b2f06d74.png">

**Building Highly-Availability(HA) Clusters with kubeadm. Source: [Kubernetes.io](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/high-availability/)**

## Kubernetes Learning Resources

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications.

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Azure Red Hat OpenShift ](https://azure.microsoft.com/en-us/services/openshift/)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[Red Hat OpenShift on IBM Cloud](https://www.ibm.com/cloud/openshift)

[Enable OpenShift Virtualization on Red Hat OpenShift](https://developers.redhat.com/blog/2020/08/28/enable-openshift-virtualization-on-red-hat-openshift/)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Intro Local Process with Kubernetes for Visual Studio 2019](https://devblogs.microsoft.com/visualstudio/introducing-local-process-with-kubernetes-for-visual-studio%E2%80%AF2019/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

[Kubernetes Tutorials from Pulumi](https://www.pulumi.com/docs/tutorials/kubernetes/)

[Kubernetes Playground by Katacoda](https://www.katacoda.com/courses/kubernetes/playground)

[Scalable Microservices with Kubernetes course from Udacity ](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

## Kubernetes Tools, Frameworks, and Projects

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments.

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking.

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[kind](https://kind.sigs.k8s.io/) is a tool for running local Kubernetes clusters using Docker container “nodes”. It was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

[Platform9 Managed Kubernetes (PMK)](https://platform9.com/managed-kubernetes/) is a Kubernetes as a service that ensures fully automated Day-2 operations with 99.9% SLA on any environment, whether in data-centers, public clouds, or at the edge.

# Docker
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521410-2e32c900-954e-11eb-8311-065fa0099546.png">
  <br />
</p>

**[Get started with Docker using Visual Studio Code](https://docs.microsoft.com/en-us/visualstudio/docker/tutorials/docker-tutorial)**

**[Developing inside a Container with Visual Studio Code](https://code.visualstudio.com/docs/remote/containers)**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

## Docker Learning Resources

[Docker Training Program](https://www.docker.com/dockercon/training)

[Docker Certified Associate (DCA) certification](https://training.mirantis.com/dca-certification-exam/)

[Docker Documentation | Docker Documentation](https://docs.docker.com/)

[The Docker Workshop](https://courses.packtpub.com/courses/docker)

[Docker Courses on Udemy](https://www.udemy.com/topic/docker/)

[Docker Courses on Coursera](https://www.coursera.org/courses?query=docker)

[Docker Courses on edX](https://www.edx.org/learn/docker)

[Docker Courses on Linkedin Learning](https://www.linkedin.com/learning/topics/docker)

## Docker Tools

[Docker](https://www.docker.com/) is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly working in collaboration with cloud, Linux, and Windows vendors, including Microsoft.

[Docker Enterprise](https://www.mirantis.com/software/docker/docker-enterprise/) is a subscription including software, supported and certified container platform for CentOS, Red Hat Enterprise Linux (RHEL), Ubuntu, SUSE Linux Enterprise Server (SLES), Oracle Linux, and Windows Server 2016, as well as for cloud providers AWS and Azure. In [November 2019 Docker's Enterprise Platform business was acquired by Mirantis](https://www.mirantis.com/company/press-center/company-news/mirantis-acquires-docker-enterprise/).

[Docker Desktop](https://www.docker.com/products/docker-desktop) is an application for MacOS and Windows machines for the building and sharing of containerized applications and microservices. Docker Desktop delivers the speed, choice and security you need for designing and delivering containerized applications on your desktop. Docker Desktop includes Docker App, developer tools, Kubernetes and version synchronization to production Docker Engines.

[Docker Hub](https://hub.docker.com/) is the world's largest library and community for container images Browse over 100,000 container images from software vendors, open-source projects, and the community.

[Docker Compose](https://docs.docker.com/compose/) is a tool that was developed to help define and share multi-container applications. With Docker Compose, you can create a YAML file to define the services and with a single command, can spin everything up or tear it all down.

[Docker Swarm](https://docs.docker.com/engine/swarm/) is a Docker-native clustering system swarm is a simple tool which controls a cluster of Docker hosts and exposes it as a single "virtual" host.

[Dockerfile](https://docs.docker.com/engine/reference/builder/) is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

[Docker Containers](https://www.docker.com/resources/what-container) is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

[Docker Engine](https://www.docker.com/products/container-runtime) is a container runtime that runs on various Linux (CentOS, Debian, Fedora, Oracle Linux, RHEL, SUSE, and Ubuntu) and Windows Server operating systems. Docker creates simple tooling and a universal packaging approach that bundles up all application dependencies inside a container which is then run on Docker Engine.

[Docker Images](https://docs.docker.com/engine/reference/commandline/images/) is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings. Images have intermediate layers that increase reusability, decrease disk usage, and speed up docker build by allowing each step to be cached. These intermediate layers are not shown by default. The SIZE is the cumulative space taken up by the image and all its parent images.

[Docker Network](https://docs.docker.com/engine/reference/commandline/network/) is a that displays detailed information on one or more networks.

[Docker Daemon](https://docs.docker.com/config/daemon/) is a service started by a system utility, not manually by a user. This makes it easier to automatically start Docker when the machine reboots. The command to start Docker depends on your operating system. Currently, it only runs on Linux because it depends on a number of Linux kernel features, but there are a few ways to run Docker on MacOS and Windows as well by configuring the operating system utilities.

[Docker Storage](https://docs.docker.com/storage/storagedriver/select-storage-driver/) is a driver controls how images and containers are stored and managed on your Docker host.

[Kitematic](https://kitematic.com/) is a simple application for managing Docker containers on Mac, Linux and Windows letting you control your app containers from a graphical user interface (GUI).

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

# PowerShell Development

[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/115297904-9918fe00-a111-11eb-887c-774b939f1bdf.png">
  <br />
</p>


## PowerShell Learning Resources

[Windows Remote Management in Ansible using PowerShell](https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html)

[Getting Started with PowerShell](https://docs.microsoft.com/en-us/powershell/)

[Start building with PowerShell on Azure](https://docs.microsoft.com/en-us/powershell/azure/install-az-ps)

[Azure PowerShell Documentation](https://docs.microsoft.com/en-us/powershell/azure/)

[PowerShell in Azure Cloud Shell](https://aka.ms/cloudshell/powershell-docs)

[Azure Functions using PowerShell](https://docs.microsoft.com/en-us/azure/azure-functions/functions-create-first-function-vs-code?pivots=programming-language-powershell)

[Azure Automation runbooks](https://docs.microsoft.com/en-us/azure/automation/automation-runbook-types)

[Using Visual Studio Code for PowerShell Development](https://docs.microsoft.com/en-us/powershell/scripting/dev-cross-plat/vscode/using-vscode?view=powershell-7)

[Integrated Terminal in Visual Studio Code](https://code.visualstudio.com/docs/editor/integrated-terminal)

[AWS Tools for Windows PowerShell](https://aws.amazon.com/powershell/)

[Start building with PowerShell on Google Cloud](https://cloud.google.com/powershell/)

[PowerShell Documentation](https://cloud.google.com/powershell/docs/)

[PowerShell Best Practices and Style Guide](https://poshcode.gitbooks.io/powershell-practice-and-style)


## PowerShell Tools

[PowerShell Core](https://microsoft.com/PowerShell) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (JSON, CSV, XML, etc.), REST APIs, and object models. It also includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/overview) is a set of cmdlets for managing Microsoft Azure resources directly from the PowerShell command line.

[Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/learn/modules/get-started-with-windows-subsystem-for-linux/) is a compatibility layer developed by Microsoft for running Linux binary executables in a Executable/Linkable Format natively on Windows 10 and Windows Server.

[AWS Shell](https://aws.amazon.com/cli/) is a command-line shell program that provides convenience and productivity features to help both new and advanced users of the AWS Command Line Interface.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.

# .NET Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719689-0d1e0400-fb39-11ea-82e5-331a8ff8060d.png">

</p>


## .NET Learning Resources

[.NET](https://dotnet.microsoft.com/learn/dotnet/what-is-dotnet) is a developer platform with tools and libraries for building any type of app, including web, mobile, desktop, games, IoT, cloud, and microservices.

[Announcing .NET 6](https://devblogs.microsoft.com/dotnet/announcing-net-6/)

[.NET documentation](https://docs.microsoft.com/en-us/dotnet/fundamentals/)

[C# documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)

[Getting started with .NET](https://docs.microsoft.com/en-us/dotnet/standard/get-started)

[.NET Application Architecture Guide](https://dotnet.microsoft.com/learn/dotnet/architecture-guides)

[Intro .NET Guide by JetBrains ](https://blog.jetbrains.com/dotnet/2020/07/09/introducing-the-net-guide-tutorials-and-tips-tricks-for-net-rider-and-resharper/)

[.NET on Microsoft Learn | Microsoft Docs](https://docs.microsoft.com/en-us/learn/dotnet/)

[Top .NET Courses Online | Udemy](https://www.udemy.com/topic/net/)

[Top ASP.NET Core Courses Online | Udemy](https://www.udemy.com/topic/aspnet-core/)

[Learn Parallel Programming with C# and .NET | Udemy](https://www.udemy.com/course/parallel-dotnet/)

[Learn to build an e-commerce app with .Net Core and Angular | Udemy](https://www.udemy.com/course/learn-to-build-an-e-commerce-app-with-net-core-and-angular/)

[Dependency Injection in C# and .NET with the Autofac Library | Udemy](https://www.udemy.com/course/di-ioc-dotnet/)

[Modern Application Development with .NET on AWS Specialization | Coursera](https://www.coursera.org/specializations/aws-net-serverless-development)

[Introducing .NET Core Course | Coursera](https://www.coursera.org/lecture/develop-windows-apps-gcp/introducing-net-core-JkSfp)

[Learn .NET with Online Courses | edX](https://www.edx.org/learn/.net)

[.NET Training Course | LearningTree](https://www.learningtree.com/training-directory/net-visual-studio-training/)

[.NET Training: Introduction | Pluralsight](https://www.pluralsight.com/courses/becoming-dotnet-developer)

## .NET Tools and Frameworks

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[Visual Studio Code](https://code.visualstudio.com/) is a code editor redefined and optimized for building and debugging modern web and cloud applications.

[Code Server](https://coder.com/) is a tool that allows you to run [VS Code](https://code.visualstudio.com/) on any machine anywhere and access it in the browser.

[Language Server Protocol (LSP)](https://microsoft.github.io/language-server-protocol/) is a tool that defines the protocol used between an editor or IDE and a language server that provides language features like auto complete, go to definition, find all references.

[Tabnine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode) is the AI code completion tool trusted by millions of developers to code faster with fewer errors. Whether you are a new dev or a seasoned pro, working solo or part of a team, Tabnine will help push your productivity to new heights while cutting your QA time.

[.NET Core](https://docs.microsoft.com/en-us/dotnet/core/introduction) is a cross-platform .NET implementation for websites, servers, and console apps on Windows, Linux, and macOS.The .NET Framework supports websites, services, desktop apps, and more on Windows. Xamarin/Mono is a .NET implementation for running apps on all the major mobile operating systems.

[.NET runtime](https://github.com/dotnet/runtime) is a collection of libraries and shared host (dotnet) installers for all supported platforms, as well as the sources to .NET runtime and libraries.

[ASP.NET Core](https://asp.net/) is a cross-platform .NET framework for building modern cloud-based web applications on Windows, Mac, or Linux.

[Mono](https://www.mono-project.com/) is a software platform designed to allow developers to easily create cross platform applications. It is an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[dotTrace](https://www.jetbrains.com/profiler/) is an .NET performance Profiler developed by Jet Brains. It helps users locate performance bottlenecks in a variety of .NET applications: desktop applications, .NET Core, ASP.NET, ASP.NET Core applications hosted on IIS or IIS Express web servers, Silverlight, WCF services, Windows services, Universal Windows Platform applications, and unit tests.

[dotMemory](https://www.jetbrains.com/dotmemory/) is an .NET memory Profiler developed by Jet Brains. It allows the user to analyze memory usage in a variety of .NET and .NET Core applications: desktop applications, Windows services, ASP.NET web applications, IIS, IIS Express, arbitrary .NET processes, and more.

[dotCover](https://www.jetbrains.com/dotcover/) is an .NET unit test runner and code coverage tool developed by Jet Brains. It helps the user figure out on-the-fly which unit tests are affected by your latest code changes, and automatically re-runs the affected tests for you. The continuous testing mode can be switched on for any unit test session.

[Avalonia](https://avaloniaui.net/) is a cross-platform XAML-based UI framework providing a flexible styling system and supporting a wide range of Operating Systems such as Windows via .NET Framework and .NET Core, Linux via Xorg, macOS.

[Polly](https://github.com/App-vNext/Polly) is a .NET resilience and transient-fault-handling library that allows developers to express policies such as Retry, Circuit Breaker, Timeout, Bulkhead Isolation, and Fallback in a fluent and thread-safe manner.

[IdentityServer](https://identityserver.io/) is a free, open source [OpenID Connect](https://openid.net/connect/) and [OAuth 2.0](https://tools.ietf.org/html/rfc6749) framework for ASP.NET Core. IdentityServer4 incorporates all the protocol implementations and extensibility points needed to integrate token-based authentication, single-sign-on and API access control in your applications.

[ILSpy](https://github.com/icsharpcode/ILSpy) is the open-source .NET assembly browser and decompiler.

[Hangfire](https://www.hangfire.io/) is an easy way to perform background job processing in your .NET and .NET Core applications with no Windows Service or Task Scheduler required.

[React Native Windows](https://microsoft.github.io/react-native-windows/) is a framework for building native Windows apps with React. [React Native](https://reactnative.dev/) is a framework developed by Facebook that enables you to build world-class application experiences on native platforms using a consistent developer experience based on JavaScript and React.

[ReactiveUI](https://reactiveui.net/) is a composable, cross-platform model-view-viewmodel framework for all .NET platforms that is inspired by functional reactive programming, which is a paradigm that allows you to abstract mutable state away from your user interfaces and express the idea around a feature in one readable place and improve the testability of your application.

[Refit](https://reactiveui.github.io/refit/) is the automatic type-safe REST library for .NET Core, Xamarin and .NET.It's heavily inspired by Square's Retrofit library, Refit turns your REST API into a live interface.

[MAUI](https://github.com/dotnet/maui) is the .NET Multi-platform App UI, a framework for building native device applications spanning mobile, tablet, and desktop.

[Quasar](https://github.com/quasar/Quasar) is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.


# C# Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306457-d6c0fa00-ff27-11ea-85dc-83dbb8f3e3e6.png">
  <br />

</p>

**[Start building with C# on Azure](https://docs.microsoft.com/en-us/azure/search/tutorial-csharp-create-first-app)**

**[C# Documentation](https://docs.microsoft.com/en-us/dotnet/csharp/)**

## C# Learning  Resources

[C#](https://docs.microsoft.com/en-us/dotnet/csharp/) is a modern and object-oriented programming language developed by Microsoft to write any application using the C# programming language on the .NET platform.

[Taking your first steps with C#](https://docs.microsoft.com/en-us/learn/paths/csharp-first-steps/)

[Learning C#](https://dotnet.microsoft.com/learn/csharp)

[C# development with Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/)

[C# programming with Visual Studio Code](https://code.visualstudio.com/Docs/languages/csharp)

[Working with data in C#](https://docs.microsoft.com/en-us/learn/paths/csharp-data/)

[C# Tutorial by W3Schools](https://www.w3schools.com/cs/)

[Windows Forms for .NET 5 and .NET Core 3.1](https://docs.microsoft.com/en-us/dotnet/desktop/winforms/?view=netdesktop-5.0)

[Xamarin documentation](https://docs.microsoft.com/en-us/xamarin/)

[Advanced Topics in C# by Udemy](https://www.udemy.com/course/advanced-topics-csharp/)

[The complete C# tutorial](https://csharp.net-tutorials.com/)

[Unity C# Survival Guide](https://learn.unity.com/course/unity-c-survival-guide)

[RabbitMQ .NET/C# Client API](https://www.rabbitmq.com/dotnet-api-guide.html)

## C# Tools

[Mono](https://www.mono-project.com/) is a software platform designed to allow developers to easily create cross platform applications. It is an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime.

[Visual Studio](https://visualstudio.microsoft.com/) is an integrated development environment (IDE) from Microsoft; which is a feature-rich application that can be used for many aspects of software development. Visual Studio makes it easy to edit, debug, build, and publish your app. By using Microsoft software development platforms such as Windows API, Windows Forms, Windows Presentation Foundation, and Windows Store.

[MSBuild](https://github.com/dotnet/msbuild) is the build platform for .NET and Visual Studio. MSBuild, provides an XML schema for a project file that controls how the build platform processes and builds software. Visual Studio uses MSBuild to perform team builds through Azure DevOps Server, but MSBuild can run without Visual Studio.

[Roslyn](https://docs.microsoft.com/dotnet/csharp/roslyn-sdk/) is a .NET compiler developed by Microsoft that provides C# and Visual Basic languages with rich code analysis APIs.

[Bot Framework](https://github.com/microsoft/botframework-sdk) is a framework developed by Microsoft that provides the most comprehensive experience for building conversation applications. Developers can model and build sophisticated conversation using their favorite programming languages including C#, JS, Python and Java or using Bot Framework Composer, an open-source, visual authoring canvas for developers and multi-disciplinary teams to design and build conversational experiences with Language.

[Uno Platform](https://platform.uno/) is a Universal Windows Platform Bridge that allows UWP-based code (C# and XAML) to run on iOS, Android, macOS, WebAssembly, Linux and Windows 7. It provides the full definitions of the UWP [Windows 10 2004 (19041)](https://docs.microsoft.com/en-us/windows/uwp/whats-new/windows-10-build-19041), and the implementation of a growing number of parts of the UWP API, such as Windows.UI.Xaml, to enable UWP and WinUI applications to run on these platforms.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[dotPeek](https://www.jetbrains.com/decompiler/) is a tool developed by JetBrains based on ReSharper's bundled decompiler. It can reliably decompile any .NET assembly into equivalent C# or CIL code.

[dotTrace](https://www.jetbrains.com/profiler/) is an .NET performance Profiler developed by Jet Brains. It helps users locate performance bottlenecks in a variety of .NET applications: desktop applications, .NET Core, ASP.NET, ASP.NET Core applications hosted on IIS or IIS Express web servers, Silverlight, WCF services, Windows services, Universal Windows Platform applications, and unit tests.

[dotMemory](https://www.jetbrains.com/dotmemory/) is an .NET memory Profiler developed by Jet Brains. It allows the user to analyze memory usage in a variety of .NET and .NET Core applications: desktop applications, Windows services, ASP.NET web applications, IIS, IIS Express, arbitrary .NET processes, and more.

[dotCover](https://www.jetbrains.com/dotcover/) is an .NET unit test runner and code coverage tool developed by Jet Brains. It helps the user figure out on-the-fly which unit tests are affected by your latest code changes, and automatically re-runs the affected tests for you. The continuous testing mode can be switched on for any unit test session.

[Json.NET](https://www.newtonsoft.com/json) is a popular high-performance JSON framework for .NET.

[Quasar](https://github.com/quasar/Quasar) is a fast and light-weight remote administration tool coded in C#. The usage ranges from user support through day-to-day administrative work to employee monitoring. Providing high stability and an easy-to-use user interface, Quasar is the perfect remote administration solution for you.

[CodeMaid](https://github.com/codecadwallader/codemaid) is an open source Visual Studio extension to cleanup and simplify our C#, C++, F#, VB, PHP, PowerShell, JSON, XAML, XML, ASP, HTML, CSS, LESS, SCSS, JavaScript and TypeScript coding.

[.NET Fiddle](https://dotnetfiddle.net/) is an advanced online compiler for C# that allows you to create, run and share your code online.

[Octopus Deploy](https://octopus.com/) is a single place for your team to manage releases, automate deployments, and automate the runbooks that keeps your software operating.

[Appveyor](https://ci.appveyor.com/) is a cloud-based continuous integration system that integrates natively with your source control and allows CI configuration files to live alongside your projects.

[AppHarbor](https://appharbor.com/) is a .NET Platform-as-a-Service that let's developers deploy and scale any standard .NET application to the cloud.

[ANTLR (ANother Tool for Language Recognition)](https://www.antlr.org/) is a powerful parser generator for reading, processing, executing, or translating structured text or binary files. It's widely used to build languages, tools, and frameworks. From a grammar, ANTLR generates a parser that can build parse trees and also generates a listener interface that makes it easy to respond to the recognition of phrases of interest.

[AutoRest](https://github.com/Azure/autorest) is a tool generates client libraries for accessing RESTful web services using the [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) format. It Supports C#, PowerShell, Go, Java, Node.js, TypeScript, Python, Ruby.

[Markdig](https://github.com/lunet-io/markdig) is a fast, powerful, [CommonMark](https://commonmark.org/) compliant, extensible Markdown processor for .NET.


# F# Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/94306464-da548100-ff27-11ea-8934-e9830a549cf1.png">
  <br />
</p>

**[Start building with F# on Azure](https://docs.microsoft.com/en-us/dotnet/fsharp/using-fsharp-on-azure/)**

**[F# Documentation](https://docs.microsoft.com/en-us/dotnet/fsharp/)**

##  F# Learning Resources

[F#](https://fsharp.org/) is a mature, open source, cross-platform, functional-first programming language. It empowers users and organizations to tackle complex computing problems with simple, maintainable and robust code.

[What is F#](https://docs.microsoft.com/en-us/dotnet/fsharp/what-is-fsharp)

[F#, the Functional programming for .NET](https://dotnet.microsoft.com/languages/fsharp)

[Cloud Programming with F#](https://fsharp.org/guides/cloud/)

[F# style guide](https://docs.microsoft.com/en-us/dotnet/fsharp/style-guide/)

[F# Programming Wikibook](http://en.wikibooks.org/wiki/Programming:F_Sharp)

[F# Developer Network (FSDN)](http://fsdn.azurewebsites.net/)

[Learning F# from The F# Software Foundation ](https://fsharp.org/learn/)

[F# Programming groups | Meetup](https://www.meetup.com/topics/f-programming/)

## F# Tools

[Python.NET](http://pythonnet.github.io/) is a package that gives Python programmers nearly seamless integration with the .NET Common Language Runtime (CLR) and provides a powerful application scripting tool for .NET developers. It allows Python code to interact with the CLR, and may also be used to embed Python into a .NET application.

[Fable](https://fable.io) is an F# to JavaScript compiler powered by [Babel](https://babeljs.io/), designed to make F# a first-class citizen of the JavaScript ecosystem.

[.NET for Apache Spark](https://dot.net/spark) provides high performance APIs for using Apache Spark from C# and F#. With these .NET APIs, you can access the most popular Dataframe and SparkSQL aspects of Apache Spark, for working with structured data, and Spark Structured Streaming, for working with streaming data. .NET for Apache Spark runs on Windows, Linux, and macOS using .NET Core, or Windows using .NET Framework. It also runs on all major cloud providers including [Azure HDInsight Spark](https://github.com/dotnet/spark/blob/master/deployment/README.md#azure-hdinsight-spark), [Amazon EMR Spark](https://github.com/dotnet/spark/blob/master/deployment/README.md#amazon-emr-spark), [AWS](https://github.com/dotnet/spark/blob/master/deployment/README.md#databricks) & [Azure](https://github.com/dotnet/spark/blob/master/deployment/README.md#databricks) Databricks.

[Giraffe](https://giraffe.wiki/) is a functional ASP.NET Core micro web framework for building rich web applications.

[Suave](https://suave.io/) is a simple web development F# library providing a lightweight web server and a set of combinators to manipulate route flow and task composition. Suave supports Websocket, HTTPS, multiple TCP/IP bindings, Basic Access Authentication, Keep-Alive.

[FsCheck](https://fscheck.github.io/FsCheck/) is a tool for testing .NET programs automatically. The programmer provides a specification of the program, in the form of properties which functions, methods or objects should satisfy, and FsCheck then tests that the properties hold in a large number of randomly generated cases.

[Elmish](https://elmish.github.io/elmish/) implements core abstractions for F# apps that can be used to build applications following the “model view update” style of architecture made famous by Elm. The library however does not model any "view" and is intended for use in conjuction with a DOM/renderer, like React/ReactNative or VirtualDOM.

[Saturn](https://saturnframework.org/) is a web development framework written in F# which implements the server-side MVC pattern. Many of its components and concepts will seem familiar to anyone with experience in other web frameworks like Ruby on Rails or Python’s Django.

[Pulumi](https://www.pulumi.com/) is Infrastructure as Code SDK is the easiest way to create and deploy cloud software that use containers, serverless functions, hosted services, and infrastructure, on any cloud. Simply write code in your favorite language and Pulumi will automatically provisions and manages your AWS, Azure, Google Cloud Platform, and/or Kubernetes resources, using an infrastructure-as-code approach.

[FsPickler](https://github.com/mbraceproject/FsPickler) is a serialization library that facilitates the distribution of .NET objects. The implementation focuses on performance and completeness in supported types, including F# types. It supports multiple, pluggable serialization formats including Binary, Xml, JSON and BSON. The library is based on the functional programming concept of [pickler combinators](https://www.microsoft.com/en-us/research/publication/functional-pearl-pickler-combinators/) which has been adapted to accommodate the object oriented nature of the .NET framework.

[Paket](https://fsprojects.github.io/Paket/) is a dependency manager for .NET with support for NuGet packages and git repositories.

[Fantomas](https://fsprojects.github.io/fantomas-tools/#/fantomas/preview) is a F# source code formatter.

[SQLProvider](http://fsprojects.github.io/SQLProvider) is a general F# SQL database erasing type provider, supporting LINQ queries, schema exploration, individuals, and CRUD operations.

[FsUnit](http://fsprojects.github.io/FsUnit/) makes unit-testing with F# more enjoyable. It adds a special syntax to your favorite .NET testing framework.

#  Xaramin Development
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127785363-75cd0a8d-928f-4669-9383-0b3a7110e08e.png">
  <br />
</p>

## Xaramin Learning Resources
[Back to the Top](https://github.com/mikeroyal/Xaramin-Guide#table-of-contents)

[Xamarin](https://docs.microsoft.com/en-us/xamarin/get-started/what-is-xamarin) is an open-source platform for building modern and performant applications for iOS, Android, and Windows with.NET. Xamarin is an abstraction layer that manages communication of shared code with underlying platform code. Xamarin runs in a managed environment that provides conveniences such as memory allocation and garbage collection.

[Xamarin documentation](https://docs.microsoft.com/en-us/xamarin/)

[Xaramin GitHub](https://github.com/xamarin)

[Visual Studio Tools for Xamarin](https://visualstudio.microsoft.com/xamarin/?WT.mc_id=dotnet-35129-website)

[NuGet Gallery | Xamarin](https://www.nuget.org/profiles/Xamarin)

[Xamarin App Development with Visual Studio](https://visualstudio.microsoft.com/xamarin/)

[Xamarin and Azure](https://azure.microsoft.com/en-us/features/xamarin/)

[Application Icons in Xamarin.iOS - Xamarin](https://docs.microsoft.com/en-us/xamarin/ios/app-fundamentals/images-icons/app-icons)

[Android & iOS Apps With Xamarin](https://dotnet.microsoft.com/apps/xamarin/mobile-apps)

[Xaramin Learn](https://dotnet.microsoft.com/learn/xamarin)

[Top Xamarin Courses Online | Udemy](https://www.udemy.com/topic/xamarin/)

[Xamarin: Build Native Cross Platform Apps with C# Codes | Udemy](https://www.udemy.com/course/xamarin-build-native-cross-platform-apps-with-c-codes/)

[Xamarin Online Training Courses | LinkedIn Learning](https://www.linkedin.com/learning/topics/xamarin)

[Online Xamarin Classes | Skillshare](https://www.skillshare.com/browse/xamarin)

## Xaramin Tools, Libraries, and Frameworks
[Back to the Top](https://github.com/mikeroyal/Xaramin-Guide#table-of-contents)

[Xamarin.Forms](https://dotnet.microsoft.com/apps/xamarin/xamarin-forms) is an open source cross-platform framework from Microsoft for building iOS, Android, & Windows apps with .NET from a single shared codebase.

[Rider](https://www.jetbrains.com/rider/) is a fast and powerful, cross-platform .NET IDE devloped by JetBrains to develop .NET, ASP.NET, .NET Core, Xamarin; or Unity applications for Windows, Mac, Linux.

[Resharper](https://www.jetbrains.com/resharper/) is a [Visual Studio](https://visualstudio.microsoft.com/) Extension for .NET Developers that has On-the-fly code quality analysis for C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. Letting you know right away if your code needs to be improved.

[SkiaSharp](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/graphics/skiasharp/?WT.mc_id=dotnet-35129-website) is a 2D graphics system for .NET and C# powered by the open-source Skia graphics engine that is used extensively in Google products. This can be use in your Xamarin.Forms applications to draw 2D vector graphics, bitmaps, and text.

[MonoGame](https://github.com/MonoGame/MonoGame) is a cross-platform gaming framework based on Microsoft's XNA framework that's extremely easy to learn. Best of all, games you build with MonoGame will run on iOS, Android, Mac OS X, tvOS, Windows, Linux, PlayStation 4, and more—write once, play anywhere.

[Stride](https://stride3d.net/) is an open-source C# game engine for realistic rendering and VR. The engine is highly modular and aims at giving game makers more flexibility in their development. Stride comes with an editor that allows you to create and manage the content of your games or applications visually and intuitively.

[Wave Engine](https://waveengine.net) is a  graphics development engine for business and industry. Build high-quality 3D and 2D solutions and deploy to any platform.

[FlatRedBall](https://flatredball.com) is a cross-platform game engine, focused on 2D game development and proven across multiple shipped game projects. It’s a perfect choice for small indies or large teams.

[App Builder](http://www.getappbuilder.com/) is a complete IDE for Microsoft Windows which allows to create HTML5 and native apps without programming knowledge. Offers dozens of controls and actions ready to be used in your apps and lot of app samples to learn it.

[Monaca](https://monaca.io/) is a comprehensive cloud-powered and framework-agnostic set of tools Monaca supports both online and offline development, debugging with live-reload feature and cloud build experience.

[Onsen UI](http://onsen.io/) is a custom Elements-based HTML5 framework offers a large selection of components and responsive layout support. Onsen UI lets you create professionally designed multiplatform apps without acquiring additional skillset.

# TypeScript Development

[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133287-d1dc8a80-f68b-11ea-94d3-bba83dd5b0bb.png">
  <br />

</p>

**[Start building with TypeScript on Azure](https://aka.ms/azsdk/js)**

**[TypeScript Documentation](https://aka.ms/azsdk/js/docs)**

## TypeScript Learning Resources

[TypeScript](https://www.typescriptlang.org) is a language for application-scale JavaScript. TypeScript adds optional types to JavaScript that support tools for large-scale JavaScript applications for any browser, for any host, on any OS. TypeScript compiles to readable, standards-based JavaScript.

[TypeScript support for Webpack](https://webpack.js.org/guides/typescript/)

[TypeScript Support for Nuxt.js](https://typescript.nuxtjs.org)

[TypeScript Support for Vue.js](https://vuejs.org/v2/guide/typescript.html)

[TypeScript Support for React Native](https://reactnative.dev/docs/typescript)

[TypeScript Support for Angular](https://angular.io/guide/typescript-configuration)

[Ionic/TypeScript Starter Project](http://justin-credible.github.io/Ionic-TypeScript-Starter/)

[GitHub Actions for JavaScript and TypeScript](https://docs.github.com/en/actions/language-and-framework-guides/github-actions-for-javascript-and-typescript)

## TypeScript Tools, Libraries, and Frameworks

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[ReSharper](https://www.jetbrains.com/resharper/) is a Visual Studio Extension for .NET Developers. It comes with code quality analysis, which is available in C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. You'll know right away if your code needs to be improved. ReSharper is one of many powerful tools developed by [JetBrains](https://www.jetbrains.com).

[ts-migrate](https://github.com/airbnb/ts-migrate) is a tool for helping migrate code to TypeScript. It takes a JavaScript, or a partial TypeScript, project in and gives a compiling TypeScript project out. ts-migrate is intended to accelerate the TypeScript migration process. The resulting code will pass the build, but a followup is required to improve type safety.

[Deno](https://deno.land) is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

[gulp-typescript](https://github.com/ivogabe/gulp-typescript) is an TypeScript compiler for gulp with incremental compilation support.

[React](https://reactjs.org/) is a declarative, efficient, and flexible JavaScript library for building user interfaces.

[React Native](https://reactnative.dev) is a framework for building native apps for iOS and Android with React.

[Vue.js](http://vuejs.org/) is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.

[Angular](https://www.angular.io/) is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.

[Ionic Framework](https://ionicframework.com/) is a powerful cross-platform UI toolkit for building native-quality iOS, Android, and Progressive Web Apps with HTML, CSS, and JavaScript.

[Stencil](https://stenciljs.com/) is a simple compiler for generating Web Components and static site generated progressive web apps (PWA). Stencil was built by the Ionic team for its next generation of performant mobile and desktop Web Components.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[Prettier](https://prettier.io/) is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It is built with TypeScript and combines elements of Object Oriented Programming(OOP), Functional Programming, and Functional Reactive Programming(FRP).

[Definitely Typed](https://github.com/DefinitelyTyped/DefinitelyTyped) is a repository for high quality TypeScript type definitions.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[NativeScript](https://www.nativescript.org/) empowers you to access native APIs from JavaScript directly. The framework currently provides iOS and Android runtimes for rich mobile development and can be utilized in a number of diverse use cases.

[AssemblyScript](https://assemblyscript.org/) compiles a strict variant of TypeScript to [WebAssembly](http://webassembly.org/) using [Binaryen](https://github.com/WebAssembly/binaryen).

[React Hook Form](https://react-hook-form.com/) is a performant, flexible and extensible forms with easy to use validation(Web + React Native).

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[TensorFlow.js](https://js.tensorflow.org/) is an open-source WebGL hardware-accelerated JavaScript library for training and deploying machine learning models.

[Rome](https://romefrontend.dev/) is a linter, compiler, bundler, and [more](https://romefrontend.dev/#development-status) for JavaScript, TypeScript, JSON, HTML, Markdown, and CSS.

[Eclipse Theia](https://github.com/eclipse-theia/theia) is an extensible platform to develop full-fledged multi-language Cloud & Desktop IDE-like products with state-of-the-art web technologies.

[InversifyJS](https://github.com/inversify/InversifyJS) is a powerful and lightweight inversion of control(IoC) container for JavaScript & Node.js apps powered by TypeScript. An IoC container uses a class constructor to identify and inject its dependencies.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript.

[TypeScript ESLint](https://typescript-eslint.io/) is a monorepo for all the tooling which enables ESLint to support TypeScript.

[TS node](https://github.com/TypeStrong/ts-node) is a TypeScript execution and REPL for node.js.

# Networking
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82833053-d1687b80-9e71-11ea-8c6d-074100f2f54b.png">
  <br />
</p>

## Network Learning Resources

[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Cisco Security Certifications](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/security.html)

[The Red Hat Certified Specialist in Security: Linux](https://www.redhat.com/en/services/training/ex415-red-hat-certified-specialist-security-linux-exam)

[Linux Professional Institute LPIC-3 Enterprise Security Certification](https://www.lpi.org/our-certifications/lpic-3-303-overview)

[Cybersecurity Training and Courses from IBM Skills](https://www.ibm.com/skills/topics/cybersecurity/)

[Cybersecurity Courses and Certifications by Offensive Security](https://www.offensive-security.com/courses-and-certifications/)

[Citrix Certified Associate – Networking(CCA-N)](http://training.citrix.com/cms/index.php/certification/networking/)

[Citrix Certified Professional – Virtualization(CCP-V)](https://www.globalknowledge.com/us-en/training/certification-prep/brands/citrix/section/virtualization/citrix-certified-professional-virtualization-ccp-v/)

[CCNP Routing and Switching](https://learningnetwork.cisco.com/s/ccnp-enterprise)

[Certified Information Security Manager(CISM)](https://www.isaca.org/credentialing/cism)

[Wireshark Certified Network Analyst (WCNA)](https://www.wiresharktraining.com/certification.html)

[Juniper Networks Certification Program Enterprise (JNCP)](https://www.juniper.net/us/en/training/certification/)

[Networking courses and specializations from Coursera](https://www.coursera.org/browse/information-technology/networking)

[Network & Security Courses from Udemy](https://www.udemy.com/courses/it-and-software/network-and-security/)

[Network & Security Courses from edX](https://www.edx.org/learn/cybersecurity)

## Networking Tools & Concepts

[cURL](https://curl.se/) is a computer software project providing a library and command-line tool for transferring data using various network protocols(HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP LDAPS, MQTT, POP3, POP3S, RTMP, RTMPS, RTSP, SCP, SFTP, SMB, SMBS, SMTP or SMTPS). cURL is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations.

[cURL Fuzzer](https://github.com/curl/curl-fuzzer) is a quality assurance testing for the curl project.

[DoH](https://github.com/curl/doh) is a stand-alone application for DoH (DNS-over-HTTPS) name resolves and lookups.

[Authelia](https://www.authelia.com/) is an open-source highly-available authentication server providing single sign-on capability and two-factor authentication to applications running behind [NGINX](https://nginx.org/en/).

[nginx(engine x)](https://nginx.org/en/) is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/) is a complete open-source platform for enterprise virtualization. It inlcudes a built-in web interface that you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools on a single solution.

[Wireshark](https://www.wireshark.org/) is a very popular network protocol analyzer that is commonly used for network troubleshooting, analysis, and communications protocol development. Learn more about the other useful [Wireshark Tools](https://wiki.wireshark.org/Tools) available.

[HTTPie](https://github.com/httpie/httpie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[HTTPStat](https://github.com/reorx/httpstat) is a tool that visualizes curl statistics in a simple layout.

[Wuzz](https://github.com/asciimoo/wuzz) is an interactive cli tool for HTTP inspection. It can be used to inspect/modify requests copied from the browser's network inspector with the "copy as cURL" feature.

[Websocat](https://github.com/vi/websocat) is a ommand-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions.

    • Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.

    • Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.

Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

    • Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.

A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

    • LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.

    • WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

    • Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers.

Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

    • Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.

    • Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.

    • NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.

    • VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.

## Network Layers

	While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.

	As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.

	One method of talking about the different layers of network communication is the OSI model. OSI stands for Open Systems Interconnect.This model defines seven separate layers. The layers in this model are:

    • Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.

    • Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.

    • Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.

    • Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

    • Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.

    • Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.

    • Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).

The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

    • Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user.
The communication takes place between peers network.

    • Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.

    • Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.

    • Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.

### Interfaces
**Interfaces** are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Network Protocols

Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

**Media Access Control(MAC)** is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

**The IP protocol** is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

**ICMP: internet control message protocol** is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

**TCP: Transmission control protocol** is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

**UDP: User datagram protocol** is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

**HTTP: Hypertext transfer protocol** is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

**FTP: File transfer protocol** is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

**DNS: Domain name system** is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

**SSH: Secure shell** is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

[REST(REpresentational State Transfer)](https://www.codecademy.com/articles/what-is-rest) is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

# Databases
[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279004-daec0700-bbdd-11eb-9662-b1fc86ec8448.png">
  <br />
</p>

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/119279002-da537080-bbdd-11eb-9d7a-44efb52f3506.png">
  <br />
</p>

## SQL/NoSQL Learning Resources

[SQL](https://en.wikipedia.org/wiki/SQL) is a standard language for storing, manipulating and retrieving data in relational databases.

[NoSQL](https://www.ibm.com/cloud/blog/sql-vs-nosql) is a database that is interchangeably referred to as "nonrelational, or "non-SQL" to highlight that the database can handle huge volumes of rapidly changing, unstructured data in different ways than a relational (SQL-based) database with rows and tables.

[Transact-SQL(T-SQL)](https://docs.microsoft.com/en-us/sql/t-sql/language-reference) is a Microsoft extension of SQL with all of the tools and applications communicating to a SQL database by sending T-SQL commands.

[Introduction to Transact-SQL](https://docs.microsoft.com/en-us/learn/modules/introduction-to-transact-sql/)

[SQL Tutorial by W3Schools](https://www.w3schools.com/sql/)

[Learn SQL Skills Online from Coursera](https://www.coursera.org/courses?query=sql)

[SQL Courses Online from Udemy](https://www.udemy.com/topic/sql/)

[SQL Online Training Courses from LinkedIn Learning](https://www.linkedin.com/learning/topics/sql)

[Learn SQL For Free from Codecademy](https://www.codecademy.com/learn/learn-sql)

[GitLab's SQL Style Guide](https://about.gitlab.com/handbook/business-ops/data-team/platform/sql-style-guide/)

[OracleDB SQL Style Guide Basics](https://oracle.readthedocs.io/en/latest/sql/basics/style-guide.html)

[Tableau CRM: BI Software and Tools](https://www.salesforce.com/products/crm-analytics/overview/)

[Databases on AWS](https://aws.amazon.com/products/databases/)

[Best Practices and Recommendations for SQL Server Clustering in AWS EC2.](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/aws-sql-clustering.html)

[Connecting from Google Kubernetes Engine to a Cloud SQL instance.](https://cloud.google.com/sql/docs/mysql/connect-kubernetes-engine)

[Educational Microsoft Azure SQL resources](https://docs.microsoft.com/en-us/sql/sql-server/educational-sql-resources?view=sql-server-ver15)

[MySQL Certifications](https://www.mysql.com/certification/)

[SQL vs. NoSQL Databases: What's the Difference?](https://www.ibm.com/cloud/blog/sql-vs-nosql)

[What is NoSQL?](https://aws.amazon.com/nosql/)

## SQL/NoSQL Tools and Databases

[Netdata](https://github.com/netdata/netdata) is high-fidelity infrastructure monitoring and troubleshooting, real-time monitoring Agent collects thousands of metrics from systems, hardware, containers, and applications with zero configuration. It runs permanently on all your physical/virtual servers, containers, cloud deployments, and edge/IoT devices, and is perfectly safe to install on your systems mid-incident without any preparation.

[Azure Data Studio](https://github.com/Microsoft/azuredatastudio) is an open source data management tool that enables working with SQL Server, Azure SQL DB and SQL DW from Windows, macOS and Linux.

[Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)  is the intelligent, scalable, relational database service built for the cloud. It’s evergreen and always up to date, with AI-powered and automated features that optimize performance and durability for you. Serverless compute and Hyperscale storage options automatically scale resources on demand, so you can focus on building new applications without worrying about storage size or resource management.

[Azure SQL Managed Instance](https://azure.microsoft.com/en-us/services/azure-sql/sql-managed-instance/) is a fully managed SQL Server Database engine instance that's hosted in Azure and placed in your network. This deployment model makes it easy to lift and shift your on-premises applications to the cloud with very few application and database changes. Managed instance has split compute and storage components.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together enterprise data warehousing and Big Data analytics. It gives you the freedom to query data on your terms, using either serverless or provisioned resources at scale. It brings together the best of the SQL technologies used in enterprise data warehousing, Spark technologies used in big data analytics, and Pipelines for data integration and ETL/ELT.

[MSSQL for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql) is an extension for developing Microsoft SQL Server, Azure SQL Database and SQL Data Warehouse everywhere with a rich set of functionalities.

[SQL Server Data Tools (SSDT)](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt) is a development tool for building SQL Server relational databases, Azure SQL Databases, Analysis Services (AS) data models, Integration Services (IS) packages, and Reporting Services (RS) reports. With SSDT, a developer can design and deploy any SQL Server content type with the same ease as they would develop an application in Visual Studio or Visual Studio Code.

[Bulk Copy Program](https://docs.microsoft.com/en-us/sql/tools/bcp-utility) is a command-line tool that comes with Microsoft SQL Server. BCP, allows you to import and export large amounts of data in and out of SQL Server databases quickly snd efficeiently.

[SQL Server Migration Assistant](https://www.microsoft.com/en-us/download/details.aspx?id=54258) is a tool from Microsoft that simplifies database migration process from Oracle to SQL Server, Azure SQL Database, Azure SQL Database Managed Instance and Azure SQL Data Warehouse.

[SQL Server Integration Services](https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services?view=sql-server-ver15) is a development platform for building enterprise-level data integration and data transformations solutions. Use Integration Services to solve complex business problems by copying or downloading files, loading data warehouses, cleansing and mining data, and managing SQL Server objects and data.

[SQL Server Business Intelligence(BI)](https://www.microsoft.com/en-us/sql-server/sql-business-intelligence) is a collection of tools in Microsoft's SQL Server for transforming raw data into information businesses can use to make decisions.

[Tableau](https://www.tableau.com/) is a Data Visualization software used in relational databases, cloud databases, and spreadsheets. Tableau was acquired by [Salesforce in August 2019](https://investor.salesforce.com/press-releases/press-release-details/2019/Salesforce-Completes-Acquisition-of-Tableau/default.aspx).

[DataGrip](https://www.jetbrains.com/datagrip/) is a professional DataBase IDE developed by Jet Brains that provides context-sensitive code completion, helping you to write SQL code faster. Completion is aware of the tables structure, foreign keys, and even database objects created in code you're editing.

[RStudio](https://rstudio.com/) is an integrated development environment for R and Python, with a console, syntax-highlighting editor that supports direct code execution, and tools for plotting, history, debugging and workspace management.

[MySQL](https://www.mysql.com/) is a fully managed database service to deploy cloud-native applications using the world's most popular open source database.

[PostgreSQL](https://www.postgresql.org/) is a powerful, open source object-relational database system with over 30 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance.

[Amazon DynamoDB](https://aws.amazon.com/dynamodb/) is a key-value and document database that delivers single-digit millisecond performance at any scale. It is a fully managed, multiregion, multimaster, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications.

[Apache Cassandra™](https://cassandra.apache.org/) is an open source NoSQL distributed database trusted by thousands of companies for scalability and high availability without compromising performance. Cassandra provides linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure make it the perfect platform for mission-critical data.

[Apache HBase™](https://hbase.apache.org/) is an open-source, NoSQL, distributed big data store. It enables random, strictly consistent, real-time access to petabytes of data. HBase is very effective for handling large, sparse datasets. HBase serves as a direct input and output to the Apache MapReduce framework for Hadoop, and works with Apache Phoenix to enable SQL-like queries over HBase tables.

[Hadoop Distributed File System (HDFS)](https://www.ibm.com/analytics/hadoop/hdfs) is a distributed file system that handles large data sets running on commodity hardware. It is used to scale a single Apache Hadoop cluster to hundreds (and even thousands) of nodes. HDFS is one of the major components of Apache Hadoop, the others being [MapReduce](https://www.ibm.com/analytics/hadoop/mapreduce) and [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html).

[Apache Mesos](http://mesos.apache.org/) is a cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks. It can run Hadoop, Jenkins, Spark, Aurora, and other frameworks on a dynamically shared pool of nodes.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning and graph processing.

[ElasticSearch](https://www.elastic.co/) is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java.

[Logstash](https://www.elastic.co/products/logstash) is a tool for managing events and logs. When used generically, the term encompasses a larger system of log collection, processing, storage and searching activities.

[Kibana](https://www.elastic.co/products/kibana) is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

[Trino](https://trino.io/) is a Distributed SQL query engine for big data. It is able to tremendously speed up [ETL processes](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl), allow them all to use standard SQL statement, and work with numerous data sources and targets all in the same system.

[Extract, transform, and load (ETL)](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl) is a data pipeline used to collect data from various sources, transform the data according to business rules, and load it into a destination data store.

[Redis(REmote DIctionary Server)](https://redis.io/) is an open source (BSD licensed), in-memory data structure store, used as a database, cache, and message broker. It provides data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes, and streams.

[FoundationDB](https://www.foundationdb.org/) is an open source distributed database designed to handle large volumes of structured data across clusters of commodity servers. It organizes data as an ordered key-value store and employs ACID transactions for all operations. It is especially well-suited for read/write workloads but also has excellent performance for write-intensive workloads. FoundationDB was acquired by [Apple in 2015](https://techcrunch.com/2015/03/24/apple-acquires-durable-database-company-foundationdb/).

[IBM DB2](https://www.ibm.com/analytics/db2) is a collection of hybrid data management products offering a complete suite of AI-empowered capabilities designed to help you manage both structured and unstructured data on premises as well as in private and public cloud environments. Db2 is built on an intelligent common SQL engine designed for scalability and flexibility.

[MongoDB](https://www.mongodb.com/) is a document database meaning it stores data in JSON-like documents.

[OracleDB](https://www.oracle.com/database/) is a powerful fully managed database helps developers manage business-critical data with the highest availability, reliability, and security.

[MariaDB](https://mariadb.com/) is an enterprise open source database solution for modern, mission-critical applications.

[SQLite](https://sqlite.org/index.html) is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine.SQLite is the most used database engine in the world. SQLite is built into all mobile phones and most computers and comes bundled inside countless other applications that people use every day.

[SQLite Database Browser](https://sqlitebrowser.org/) is an open source SQL tool that allows users to create, design and edits SQLite database files. It lets users show a log of all the SQL commands that have been issued by them and by the application itself.

[InfluxDB](https://www.influxdata.com/) is an open source time series platform.  This includes APIs for storing and querying data, processing it in the background for [ETL](https://docs.microsoft.com/en-us/azure/architecture/data-guide/relational-data/etl) or monitoring and alerting purposes, user dashboards, Internet of Things sensor data, and visualizing and exploring the data and more. It also has support for processing data from [Graphite](http://graphiteapp.org/).

[Atlas](https://github.com/Netflix/atlas) is an in-memory dimensional [time series database](https://en.wikipedia.org/wiki/Time_series_database).

[CouchbaseDB](https://www.couchbase.com/) is an open source distributed [multi-model NoSQL document-oriented database](https://en.wikipedia.org/wiki/Multi-model_database). It creates a key-value store with managed cache for sub-millisecond data operations, with purpose-built indexers for efficient queries and a powerful query engine for executing SQL queries.

[dbWatch](https://www.dbwatch.com/) is a complete database monitoring/management solution for SQL Server, Oracle, PostgreSQL, Sybase, MySQL and Azure. Designed for proactive management and automation of routine maintenance in large scale on-premise, hybrid/cloud database environments.

[Cosmos DB Profiler](https://hibernatingrhinos.com/products/cosmosdbprof) is a real-time visual debugger allowing a development team to gain valuable insight and perspective into their usage of Cosmos DB database. It identifies over a dozen suspicious behaviors from your application’s interaction with Cosmos DB.

[Adminer](https://www.adminer.org/) is an SQL management client tool for managing databases, tables, relations, indexes, users. Adminer has support for all the popular database management systems such as MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Firebird, SimpleDB, Elasticsearch and MongoDB.

[DBeaver](https://dbeaver.io/) is an open source database tool for developers and database administrators. It offers supports for JDBC compliant databases such as MySQL, Oracle, IBM DB2, SQL Server, Firebird, SQLite, Sybase, Teradata, Firebird, Apache Hive, Phoenix, and Presto.

[DbVisualizer](https://dbvis.com/) is a SQL management tool that allows users to manage a wide range of databases such as Oracle, Sybase, SQL Server, MySQL, H3, and SQLite.

[AppDynamics Database](https://www.appdynamics.com/supported-technologies/database) is a management product for Microsoft SQL Server. With AppDynamics you can monitor and trend key performance metrics such as resource consumption, database objects, schema statistics and more, allowing you to proactively tune and fix issues in a High-Volume Production Environment.

[Toad](https://www.quest.com/toad/) is a SQL Server DBMS toolset developed by Quest. It increases productivity by using extensive automation, intuitive workflows, and built-in expertise. This SQL management tool resolve issues, manage change and promote the highest levels of code quality for both relational and non-relational databases.

[Lepide SQL Server](https://www.lepide.com/sql-storage-manager/) is an open source storage manager utility to analyse the performance of SQL Servers. It provides a complete overview of all configuration and permission changes being made to your SQL Server environment through an easy-to-use, graphical user interface.

[Sequel Pro](https://sequelpro.com/) is a fast MacOS database management tool for working with MySQL. This SQL management tool helpful for interacting with your database by easily to adding new databases, new tables, and new rows.


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Windows-Terminal-Guide/pulls).


## License

[Back to the Top](https://github.com/mikeroyal/Windows-Terminal-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/)

