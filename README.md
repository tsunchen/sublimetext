# sublimetext
SublimeText config
1. 在工具栏点击Preferences，打开Browse Packages。在打开的文件夹中找到Python，并打开这个文件夹。找到文件Python.sublime-build，并打开。
2. 修改以下内容：

{
"cmd": ["python", "-u", "$file"],
"path":"F:/Program Files/Python27",
"file_regex": "^[ ]*File \"(...*?)\", line ([0-9]*)",
"selector": "source.python"
}
