---
type: TutorialStep
date: 2024-10-23
title: Setting an abbreviation
topics:
  - tricks
author: hs
subtitle: Use a unique abbreviation to quickly navigate to the Gradle tool window.
thumbnail: ./thumbnail.png
---

You may have noticed that there are a lot of results when we type "Gradle" into any of the search options. We may want to provide a way to quickly access the Gradle tool window.

You can, of course, [set a keyboard shortcut](https://www.jetbrains.com/help/idea/configuring-keyboard-and-mouse-shortcuts.html#add-keyboard-shortcut) for any IntelliJ IDEA action, and you may want to set one for opening the Gradle tool window.

Alternatively, or even additionally, we can [add an abbreviation](https://www.jetbrains.com/help/idea/configuring-keyboard-and-mouse-shortcuts.html#add-abbreviation).

On the Keymap page of the Settings/Preferences dialog, <kbd>⌘,</kbd> (macOS) / <kbd>Ctrl+Alt+S</kbd> (Windows/Linux), right-click an action and select **Add Abbreviation**.

![Add abbreviation](./add-abbreviation.png)

We can provide a short, memorable text string which we can use when searching for the Gradle tool window. For example, enter "grdl" and press **OK**.

![Enter abbreviation](./abbreviation-to-use.png)

Now, if we bring up the Search Everywhere dialog <kbd>⇧⇧</kbd> (macOS) / <kbd>Shift+Shift</kbd> (Windows/Linux), and we type "grdl" we'll see the _Gradle_ tool window as the first result, it's not hiding in a list of similar looking results.

![Enter abbreviation](./grdl-search-results.png)

Next, let's look at how to run Gradle tasks.
