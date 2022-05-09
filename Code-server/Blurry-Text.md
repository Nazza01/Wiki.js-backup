---
title: Blurry Text
description: How to fix blurry terminal text
published: true
date: 2021-11-10T06:35:02.848Z
tags: 
editor: markdown
dateCreated: 2021-11-10T06:35:01.370Z
---

# Blurry Terminal Text
So the terminal text was annoyingly blurry
So I had to figure out what setting was causing it to be blurry inside of code-server
This lead to the following solution:
Set <code>terminal.integrated.gpuAcceleration</code> to off will fix the terminal to be not blurry anymore

From the following GitHub Issue
https://github.com/microsoft/vscode/issues/122718#issuecomment-834710408