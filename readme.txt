首先感谢hp的工作付出和Google的维护，侵权必删

主要逻辑和思想，

1. 基于python的tkinter写的简单显示界面

2. 后端调用的是tesseract-ocr.exe程序，这里需要注意的一个点是pytesseract包的时候要把cmd改一下

3. 封装的exe可执行文件是通过PyInstaller完成的  这里需要注意的一点就是  命令参数要用D   封装完成之后把对应的pytesseract包放在封装的文件中就OK
 
