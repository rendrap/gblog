---
layout: post
title:  "VS Code Studio Latest Update & New Features"
date:   2019-02-11 04:14:07 +0700
categories: SAAS
tags: [vs code, code editor, developer]
image: "blog-img01.jpg"
author: Knut
---

The June release of the popular code editor adds new features, as well as improving debugging and performance. The latest update to Microsoft's Visual Studio Code editor brings a range of improvements for JavaScript, C# and Java developers.

The June release of the code editor, one of the most popular in the world,  adds a variety of features, both general and targeted at developers working in specific languages.

For devs working with JavaScript and its spin-off TypeScript, Microsoft has improved the performance of features for checking and completing code.

Visual Studio Code will now be able to split this work between two TypeScript servers, one of which will handle simple syntax-based operations like code folding, while the other handles advanced features such as IntelliSense code completion and error reporting.

The move to two servers will mean developers will no longer have to wait for the server to evaluate an entire JavaScript or TypeScript project before it can carry out simple operations like code folding or document outline. To enable this dual-server setup, set "typescript.experimental.useSeparateSyntaxServer": true and make sure you are using TypeScript 3.4 or newer in your workspace.

There are debugging improvements too, with Microsoft adding the new 'Jump to cursor' command, accessible via the context menu.

When debugging, 'Jump to cursor' will leap to that line in the code and execute from that point onwards, without executing any of the intervening code. This command is currently only available from the C# extension, but other debug extensions should follow soon.

It should be easier for developers to set up Visual Studio Code for editing Java due to the release's support for the new Java Pack Installer.

When run, the installer automatically detects whether the JDK (Java Development Kit), Visual Studio Code, and required extensions are already installed, and is able to download and configure any missing software dependencies. It can also be used to add Java-related components to an existing Visual Studio Code installation.

Moving to general improvements in the update, the Select Default Shell command can now be used with the macOS and Linux versions of VS Code, allowing users to simply select their preferred terminal shell from those installed on the system. There are also new options for setting the environment for VS Code's Integrated Terminal.

Other additions include support for copying a folder's contents by dragging and dropping it into VS Code's File Explorer, a new context menu option that allows individual entries in the status bar to be hidden, tree indent guides, and support for the new TSLint 1.2 extension.

The update, version 1.36 is available now, and a full list of changes is available here. 

To find out more about Visual Studio Code's bigger brother, Visual Studio 2019, check out our recent guide. If you're interested in finding out more about TypeScript, read TechRepublic's round-up of the best free resources for learning the language online.