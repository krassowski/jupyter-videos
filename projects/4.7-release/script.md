# JupyterLab 4.7 release video: narration

This is the voice-over of the combined cut, one section per shot, with the time each line starts. "The point 7 releases" names JupyterLab 4.7 and Notebook 7.7 together. The source is `edit.py` in this folder.

## 0:00 Faster output

- 0:00.4 Introducing the point 7 releases of JupyterLab and Notebook.
- 0:05.1 Let's start with an example of the performance improvements.
- 0:08.9 One thousand lines of logging output appear.
- 0:12.2 JupyterLab 4.7 shows them in about a second. 4.6 took nine times longer.

## 0:20 Title card

No narration.

## 0:23 Read-only files open view-only

- 0:23.3 Ever edited a notebook, only to find that you cannot save it?
- 0:27.6 In the point 7 releases, such notebooks open in view-only mode instead.
- 0:33.1 To edit or run the code, save a copy.

## 0:37 Read-only cells show a lock

- 0:37.6 As an option useful for teaching, a lock icon marks the cells that students cannot edit.
- 0:44.2 Clicking it asks before the cell becomes editable,
- 0:47.9 so the author of an exercise can still add a test.

## 0:52 Help opens in a panel below

- 0:53.1 Help from a question mark can open in a panel under the notebook, as in the classic notebook.
- 0:58.8 This works in code consoles too.

## 1:02 Undo brings back a running cell

- 1:05.1 Deleted the wrong cell while it was still running?
- 1:09.1 The Undo command brings it back as it was,
- 1:12.6 and a notification offers the output that it printed in the meantime.

## 1:18 Recent commands come first

- 1:18.0 To run a command again, you no longer have to search for it.
- 1:22.0 The command palette lists your recent commands first.

## 1:26 Jump to a tab by position

- 1:26.9 With many tabs open, Control, Alt and a number jump to the tab at that position.
- 1:33.3 Nine jumps to the last one, however many are open.

## 1:38 Reorder sidebar sections

- 1:38.2 Once you turn on reordering, you can drag the sections of a sidebar into the order you like.
- 1:44.9 The order is saved with your workspace.

## 1:48 Terminal titles in the Running panel

- 1:50.6 A program can set the title of its terminal.
- 1:53.8 In 4.7 the Running panel shows these titles too, so you can follow a long job at a glance.

## 2:02 Search inside rendered math

- 2:02.0 Markdown previews can be searched in 4.7, even inside rendered formulas.
- 2:07.9 The same works for formulas in cell outputs.

## 2:12 Long formulas wrap

- 2:13.8 The point 7 releases update MathJax to version 4.1.
- 2:18.9 Long formulas no longer run past the edge of the cell, and a double backslash starts a new line again.

## 2:26 Mermaid diagrams follow the theme

- 2:29.2 Mermaid diagrams no longer keep the colors of the old theme: they are drawn again when you switch between light and dark.

## 2:37 CSV comment lines

- 2:37.7 Comment lines at the top of a CSV file used to break its header.
- 2:42.4 Pick a comment character, and they are shown as comments.
- 2:46.1 Search in CSV files was also improved: it shows the number of matches.

## 2:52 Shortcuts for R operators

- 2:52.7 R users get two familiar shortcuts:
- 2:55.8 Alt and minus for the assignment arrow,
- 2:59.0 and Control, Shift and M for the pipe.

## 3:03 Kernel sources as a tree

- 3:03.7 The kernel sources in the debugger used to be one long list.
- 3:08.3 This release groups them by package, in a tree.

## 3:12 Settings from the keyboard

- 3:13.1 Parts of the Settings Editor used to need a mouse.
- 3:16.4 Now the Tab key and the arrow keys reach the plugin list,
- 3:20.7 and every shortcut of the Keyboard Shortcuts editor, with the buttons next to it.

## 3:26 Notebook 7.7: Help opens below by default

- 3:26.7 Notebook 7.7 shares most of these changes.
- 3:30.6 Help from a question mark opens below the notebook by default.

## 3:35 JupyterLite 0.9: Turn extensions off

- 3:35.3 JupyterLite 0.9 brings the point 7 releases to the browser, with no server.
- 3:41.6 Its new Extension Manager can turn off an extension, such as the tour that shows these notifications.

## 3:49 And more

- 3:49.9 There is much more in this release.
- 3:52.6 The release notes list every change.

## 3:57 Upgrade

- 3:57.8 The point 7 releases are available for testing.
- 4:01.4 Thank you to the contributors, reviewers, and everyone who tested the betas and reported issues.

## 4:11 AI, when you want it

- 4:11.6 One more thing: to add AI features to JupyterLab, install the optional jupyter-ai or jupyterlite-ai packages alongside JupyterLab

## 4:18 Jupyter AI Lite: A local model next to your notebook

- 4:20.1 When you want AI, extensions bring assistants and agents, with the model of your choice,
- 4:26.6 including one that runs on your own machine, through a local API.
- 4:31.2 A cell fails? Ask about it, and put the answer straight back into the notebook.
- 4:38.6 When using a local model, the question and the answer stay on this machine.

## 4:57 Get started with AI in Jupyter

- 4:57.8 Jupyter AI brings agents such as Claude Code and Codex into JupyterLab. Jupyter AI Lite runs an assistant in the browser.

## JupyterLab cut

The JupyterLab cut leaves out the Notebook 7.7 and JupyterLite 0.9 shots and changes these lines:

- 0:00.4 "Introducing JupyterLab 4.7." for "Introducing the point 7 releases of JupyterLab and Notebook."
- 0:27.0 "In 4.7, such notebooks open in view-only mode instead." for "In the point 7 releases, such notebooks open in view-only mode instead."
- 2:13.1 "JupyterLab 4.7 updates MathJax to version 4.1." for "The point 7 releases update MathJax to version 4.1."
- 3:29.2 adds "Notebook 7.7 and JupyterLite 0.9 build on JupyterLab 4.7, with changes of their own."
- 3:41.8 adds "JupyterLab 4.7 is available for testing."
