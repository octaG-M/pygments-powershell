# pygments-powershell

A slightly modified version of the PowerShell lexer from the [Pygments highlighter](http://pygments.org).

To install the file ``shell.py``, go to your local Python installation folder (it is assumed that the Pygments have been already installed) and simply place the file in the following sub-folder:

```
%installation-folder%\Lib\site-packages\pygments\lexers
```
Ensure that everything is up-to-date as regards the lexers by running the following command:

```powershell
   python _mapping.py
```
