### screenshot
![](./screenshot.png)

### problem
	1. the commandline trace script is not intuitive, so i use the PyQt draw UI.
	2. * maybe has some bug, please fix when using..

### usage
	1. require `PyQt5` & `frida`.
	2. manage Match/Black Pattern of target in `Action`.
	3. support double match mode: 'M'(match),'E'(equal); such as: 'M:android.content.', 'E:android.content.ContextImpl'.
	4. `Import jadx-jobf` can modify classname to sync jadx deobfuscate.
	5. `Export\Import JSON` can save\restore call tree.
