---
layout: default
title: Visual Studio Code
nav_order: 2
---

# Visual Studio Code <!-- omit in toc -->

   ![VSC](/assets/images/opengraph-home.png)  

Visual Studio Code (VS Code) is a lightweight source code editor. It runs on desktops and you can use it on Windows, macOS and Linux.  
  
Developers mostly use VS Code for programming in languages like C++, C#, Java, Python, PHP, Go, for example. Technical writers find VS Code helpful when writing in [Markdown](https://zofia-leszczynska.github.io/docs/MarkdownBasics.html).  

In this section, you will learn how to install VS Code and its extensions, as well as how to use the helpful options that VS Code offers.



### Table of Contents

- [How to install VS Code?](#how-to-install-vs-code)
- [How to install extensions to VS Code?](#how-to-install-extensions-to-vs-code)
- [Useful VS Code options](#useful-vs-code-options)
  - [Commands](#commands)
  - [Preview](#preview)
  - [Displaying whitespace](#displaying-whitespace)
  - [Suggestions](#suggestions)
  - [Formatting suggestions](#formatting-suggestions)



# How to install VS Code?

1. To install VS Code, go to [code.visualstudio.com](https://code.visualstudio.com/).
2. Select from the list the operating system you are using.  
   
   ![Installation](/assets/images/Instalacja.jpg)


3. Then select ***Download***.

# How to install extensions to VS Code?

1. Open ***View***.
2. Select ***Extensions***.
3. Find and select from the list the extension you are interested in.

**Recommended extension**: ***Markdown All In One*** - it allows you to generate a table of contents and make it easier to format your document.

# Useful VS Code options 

## Commands

If you want to find the command you need, click **Shift+Ctrl+p**.

## Preview

If you want to generate a preview of your document, select ***Open Preview to the Side*** in the upper right corner.

## Displaying whitespace

If you want to see whitespace between words, select ***View***. Then select ***Render Whitespace***.

## Suggestions

If you want the program to suggest you a word or formatting element, click **Ctrl+Space**.

## Formatting suggestions

If you want to configure the program to suggest you formatting elements rather than words, follow the instructions below:

1. Click **Shift+Ctrl+p**.
2. Find and select ***Preferences: Configure Language Specific Settings***.
3. Then select ***Markdown***.
4. When the ***settings.json*** file opens, type  **`false`** instead of **`true`** after the: **`"editor.suggest.showWords":`**

   ![False](/assets/images/false.jpg)
