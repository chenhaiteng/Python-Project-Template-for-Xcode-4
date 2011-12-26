Before running your python program, there are something need to be configured.
Following are steps to do:

1. In the menu bar, click "Product" → "Edit Scheme…" (or press ⌘ <) .
2. Select "Run" in the sidebar.
3. In the "Info" tab, click the "Executable" field and then click "Other…".
4. Choose the python interpreter in your system. It should be located as /usr/local/bin/python3 for python 3, and /usr/bin/python for built-in python 2. You may need to use ⇧⌘G to type in the directory if it is hidden.
5. For the "Debugger" field, select "None".
6. Switch to "Arguments" tab, set "Base Expansions On" field to your target.
7. Add a new item in "Arguments Passed On Launch" by click the "+" button below.
8. Type in $(SOURCE_ROOT)/ and then the name of the Python file you want to test. For example: $(SOURCE_ROOT)/MyPython/MyPython.py.
9. Click "OK".

Now you can start coding.