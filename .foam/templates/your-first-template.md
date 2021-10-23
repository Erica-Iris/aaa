# 泡泡笔记模板

泡泡笔记提供了一些笔记的模板！ 
这使您可以轻松创建具有类似结构的注释，而无需使用复制/粘贴：）

Templates support the [VS Code's Snippet Syntax](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_snippet-syntax), which means you can:

- 给新创建的笔记添加一些变量(variables)
- add tabstop to automatically navigate to the key parts of the note, just like a form
Below you can see an example showing a todo list and a timestamp.

## TODO

1. ${1:First tabstop}
2. ${2:A second tabstop}
3. ${3:A third tabstop}

Note Created: ${CURRENT_YEAR}-${CURRENT_MONTH}-${CURRENT_DATE}

---

Try out the above example by running the `Foam: Create New Note From Template` command and selecting the `your-first-template` template. Notice what happens when your new note is created!

To remove this template, simply delete the `.foam/templates/your-first-template.md` file.

Enjoy!
