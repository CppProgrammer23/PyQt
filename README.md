# PyQt in Visual Studio 2019

If you're using MVS, then you have to instal PyQt5-tools and the PySide2 then under the folder 'Shared' in Visual Studio installation folder **Microsoft Visual Studio\Shared\Python37_64\Lib\site-packages\qt5_applications\Qt\bin**, you will find the Qt Designer or you can use the Loader.

**Convert design file(UI) to python file(py):**
You have to add the following folder to path (environment variables): ..\Microsoft Visual Studio\Shared\Python37_64\Scripts
Go where you ui file is located and write cmd and write pyuic5 -x youFile.ui -o youFile.py
A new python file will be created.
