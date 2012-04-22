---
layout: blogpost
title: Live Coding with AutoHotkey.dll.
description: Implementing something like light table for autohotkey. 
tags: [ahk]
---

When I am coding in autohotkey, I always bind the reload command to `!r`.  The `Listvars` window and the `ListLines` window are always available as a debugging aid.  Now running a script in AutoHotkey.dll, you can modify variables in a running script using `ahkgetvar` and `ahkassign`.  I think with the com interface to vim, it wouldn't be hard to make changes flow into the source code.  AutoHotkey.dll also allows you to load a script but not execute it.  Then you can access the abstract syntax tree of the script using the dll's introspective capabilities.  
