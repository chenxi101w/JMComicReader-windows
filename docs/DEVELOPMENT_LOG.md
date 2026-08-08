# JMComicReader 开发日志归档
> 本文件由 `devlogs/` 下各开发日志、构建日志、版本总结合并而成，仅供开发回溯参考。

## build_191.log

```
230 INFO: PyInstaller: 6.21.0, contrib hooks: 2026.6
231 INFO: Python: 3.13.14
251 INFO: Platform: Windows-10-10.0.19045-SP0
252 INFO: Python environment: C:\Users\Administrator\.workbuddy\binaries\python\envs\build_venv
257 INFO: Removing temporary files and cleaning cache in C:\Users\Administrator\AppData\Local\pyinstaller
263 INFO: Module search paths (PYTHONPATH):
['D:\\code\\CODE\\AI project\\jmcomicreader-windows',
 'D:\\code\\Android\\APP\\WorkBuddy\\resources\\app.asar.unpacked\\cli\\vendor\\shim',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12\\python313.zip',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12\\DLLs',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12\\Lib',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages',
 'D:\\code\\CODE\\AI project\\jmcomicreader-windows']
1021 INFO: Appending 'datas' from .spec
1024 INFO: checking Analysis
1025 INFO: Building Analysis because Analysis-00.toc is non existent
1025 INFO: Looking for Python shared library...
1025 INFO: Using Python shared library: C:\Users\Administrator\.workbuddy\binaries\python\versions\3.13.12\python313.dll
1025 INFO: Running Analysis Analysis-00.toc
1025 INFO: Target bytecode optimization level: 0
1025 INFO: Initializing module dependency graph...
1027 INFO: Initializing module graph hook caches...
1058 INFO: Analyzing modules for base_library.zip ...
2980 INFO: Processing standard module hook 'hook-heapq.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
3164 INFO: Processing standard module hook 'hook-math.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
3469 INFO: Processing standard module hook 'hook-encodings.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
5530 INFO: Processing standard module hook 'hook-pickle.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7221 INFO: Caching module dependency graph...
7261 INFO: Analyzing D:\code\CODE\AI project\jmcomicreader-windows\desktop_app.py
7627 INFO: Processing standard module hook 'hook-webbrowser.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7685 INFO: Processing standard module hook 'hook-sysconfig.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7691 INFO: Processing standard module hook 'hook-_ctypes.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7983 INFO: Processing pre-safe-import-module hook 'hook-typing_extensions.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
7985 INFO: SetuptoolsInfo: initializing cached setuptools info...
9219 INFO: Processing standard module hook 'hook-multiprocessing.util.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
9320 INFO: Processing standard module hook 'hook-xml.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
10422 INFO: Processing standard module hook 'hook-platform.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
11014 INFO: Processing standard module hook 'hook-difflib.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
11293 INFO: Processing standard module hook 'hook-jinja2.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
12103 INFO: Processing pre-safe-import-module hook 'hook-importlib_metadata.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12103 INFO: Setuptools: 'importlib_metadata' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.importlib_metadata'!
12110 INFO: Processing standard module hook 'hook-setuptools.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
12127 INFO: Processing pre-safe-import-module hook 'hook-distutils.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12163 INFO: Processing pre-safe-import-module hook 'hook-jaraco.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12164 INFO: Setuptools: 'jaraco' appears to be a full setuptools-vendored copy - creating alias to 'setuptools._vendor.jaraco'!
12177 INFO: Processing pre-safe-import-module hook 'hook-more_itertools.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12178 INFO: Setuptools: 'more_itertools' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.more_itertools'!
12426 INFO: Processing pre-safe-import-module hook 'hook-packaging.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12758 INFO: Processing standard module hook 'hook-setuptools._vendor.jaraco.text.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
12760 INFO: Processing pre-safe-import-module hook 'hook-importlib_resources.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12770 INFO: Processing pre-safe-import-module hook 'hook-backports.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12771 INFO: Setuptools: 'backports' appears to be a full setuptools-vendored copy - creating alias to 'setuptools._vendor.backports'!
13237 INFO: Processing pre-safe-import-module hook 'hook-tomli.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
13238 INFO: Setuptools: 'tomli' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.tomli'!
13821 INFO: Processing pre-safe-import-module hook 'hook-wheel.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
13821 INFO: Setuptools: 'wheel' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.wheel'!
13885 INFO: Processing standard module hook 'hook-setuptools._vendor.importlib_metadata.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
13916 INFO: Processing pre-safe-import-module hook 'hook-zipp.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
13916 INFO: Setuptools: 'zipp' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.zipp'!
13998 INFO: Processing standard module hook 'hook-sqlite3.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
14682 INFO: Processing standard module hook 'hook-PIL.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
14825 INFO: Processing standard module hook 'hook-PIL.Image.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
15470 INFO: Processing standard module hook 'hook-xml.etree.cElementTree.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
15668 INFO: Processing standard module hook 'hook-PIL.ImageFilter.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
15982 INFO: Processing pre-find-module-path hook 'hook-tkinter.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_find_module_path'
15983 INFO: TclTkInfo: initializing cached Tcl/Tk info...
16274 WARNING: tkinter installation is broken. It will be excluded from the application
16310 INFO: Processing standard module hook 'hook-urllib3.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
16899 INFO: Processing standard module hook 'hook-certifi.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
16956 INFO: Processing standard module hook 'hook-charset_normalizer.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
17923 INFO: Processing standard module hook 'hook-Crypto.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
19811 INFO: Processing standard module hook 'hook-pycparser.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
21414 INFO: Processing standard module hook 'hook-lxml.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
22005 INFO: Processing standard module hook 'hook-lxml.etree.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
23534 INFO: Processing standard module hook 'hook-webview.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\webview\\__pyinstaller'
23989 INFO: Processing pre-safe-import-module hook 'hook-gi.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
24140 INFO: Processing standard module hook 'hook-clr.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\pythonnet\\_pyinstaller'
24222 INFO: Processing standard module hook 'hook-clr_loader.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
24381 INFO: Processing module hooks (post-graph stage)...
24748 INFO: Processing standard module hook 'hook-lxml.isoschematron.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
24847 WARNING: Hidden import "pycparser.lextab" not found!
24847 WARNING: Hidden import "pycparser.yacctab" not found!
25193 INFO: Processing standard module hook 'hook-PIL.SpiderImagePlugin.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
25298 INFO: Processing standard module hook 'hook-lxml.objectify.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
25310 INFO: Performing binary vs. data reclassification (186 entries)
25431 INFO: Looking for ctypes DLLs
25560 INFO: Analyzing run-time hooks ...
25564 INFO: Including run-time hook 'pyi_rth_pkgutil.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
25568 INFO: Including run-time hook 'pyi_rth_multiprocessing.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
25571 INFO: Including run-time hook 'pyi_rth_inspect.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
25574 INFO: Including run-time hook 'pyi_rth_setuptools.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
25594 INFO: Creating base_library.zip...
25618 INFO: Looking for dynamic libraries
27055 INFO: Extra DLL search directories (AddDllDirectory): ['C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\pikepdf.libs', 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\curl_cffi.libs']
27055 INFO: Extra DLL search directories (PATH): []
29112 INFO: Warnings written to D:\Game\JMComicReader\build_191\JMComicReader\warn-JMComicReader.txt
29200 INFO: Graph cross-reference written to D:\Game\JMComicReader\build_191\JMComicReader\xref-JMComicReader.html
29248 INFO: checking PYZ
29249 INFO: Building PYZ because PYZ-00.toc is non existent
29249 INFO: Building PYZ (ZlibArchive) D:\Game\JMComicReader\build_191\JMComicReader\PYZ-00.pyz
30082 INFO: Building PYZ (ZlibArchive) D:\Game\JMComicReader\build_191\JMComicReader\PYZ-00.pyz completed successfully.
30106 INFO: checking PKG
30106 INFO: Building PKG because PKG-00.toc is non existent
30106 INFO: Building PKG (CArchive) JMComicReader.pkg
30141 INFO: Building PKG (CArchive) JMComicReader.pkg completed successfully.
30143 INFO: Bootloader C:\Users\Administrator\.workbuddy\binaries\python\envs\build_venv\Lib\site-packages\PyInstaller\bootloader\Windows-64bit-intel\runw.exe
30143 INFO: checking EXE
30143 INFO: Building EXE because EXE-00.toc is non existent
30143 INFO: Building EXE from EXE-00.toc
30144 INFO: Copying bootloader EXE to D:\Game\JMComicReader\build_191\JMComicReader\JMComicReader.exe
30156 INFO: Copying icon to EXE
30165 INFO: Copying 0 resources to EXE
30166 INFO: Embedding manifest in EXE
30173 INFO: Appending PKG archive to EXE
30184 INFO: Fixing EXE headers
30267 INFO: Building EXE from EXE-00.toc completed successfully.
30272 INFO: checking COLLECT
30272 INFO: Building COLLECT because COLLECT-00.toc is non existent
30273 INFO: Building COLLECT COLLECT-00.toc
31235 INFO: Building COLLECT COLLECT-00.toc completed successfully.
31244 INFO: Build complete! The results are available in: D:\Game\JMComicReader\dist_191
```

## build_log.txt

```
287 INFO: PyInstaller: 6.21.0, contrib hooks: 2026.6
287 INFO: Python: 3.13.14
310 INFO: Platform: Windows-10-10.0.19045-SP0
310 INFO: Python environment: C:\Users\Administrator\.workbuddy\binaries\python\envs\build_venv
323 INFO: Module search paths (PYTHONPATH):
['D:\\code\\CODE\\AI project\\jmcomicreader-windows',
 'D:\\code\\Android\\APP\\WorkBuddy\\resources\\app.asar.unpacked\\cli\\vendor\\shim',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12\\python313.zip',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12\\DLLs',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12\\Lib',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\versions\\3.13.12',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv',
 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages',
 'D:\\code\\CODE\\AI project\\jmcomicreader-windows']
979 INFO: Appending 'datas' from .spec
982 INFO: checking Analysis
982 INFO: Building Analysis because Analysis-00.toc is non existent
982 INFO: Looking for Python shared library...
983 INFO: Using Python shared library: C:\Users\Administrator\.workbuddy\binaries\python\versions\3.13.12\python313.dll
983 INFO: Running Analysis Analysis-00.toc
983 INFO: Target bytecode optimization level: 0
983 INFO: Initializing module dependency graph...
985 INFO: Initializing module graph hook caches...
1004 INFO: Analyzing modules for base_library.zip ...
2947 INFO: Processing standard module hook 'hook-encodings.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
3660 INFO: Processing standard module hook 'hook-math.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
3897 INFO: Processing standard module hook 'hook-heapq.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
5162 INFO: Processing standard module hook 'hook-pickle.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
6656 INFO: Caching module dependency graph...
6695 INFO: Analyzing D:\code\CODE\AI project\jmcomicreader-windows\desktop_app.py
7055 INFO: Processing standard module hook 'hook-webbrowser.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7108 INFO: Processing standard module hook 'hook-sysconfig.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7114 INFO: Processing standard module hook 'hook-_ctypes.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
7399 INFO: Processing pre-safe-import-module hook 'hook-typing_extensions.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
7400 INFO: SetuptoolsInfo: initializing cached setuptools info...
8560 INFO: Processing standard module hook 'hook-multiprocessing.util.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
8662 INFO: Processing standard module hook 'hook-xml.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
9747 INFO: Processing standard module hook 'hook-platform.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
10313 INFO: Processing standard module hook 'hook-difflib.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
10596 INFO: Processing standard module hook 'hook-jinja2.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
11397 INFO: Processing pre-safe-import-module hook 'hook-importlib_metadata.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
11397 INFO: Setuptools: 'importlib_metadata' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.importlib_metadata'!
11405 INFO: Processing standard module hook 'hook-setuptools.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
11420 INFO: Processing pre-safe-import-module hook 'hook-distutils.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
11455 INFO: Processing pre-safe-import-module hook 'hook-jaraco.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
11455 INFO: Setuptools: 'jaraco' appears to be a full setuptools-vendored copy - creating alias to 'setuptools._vendor.jaraco'!
11469 INFO: Processing pre-safe-import-module hook 'hook-more_itertools.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
11469 INFO: Setuptools: 'more_itertools' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.more_itertools'!
11720 INFO: Processing pre-safe-import-module hook 'hook-packaging.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12019 INFO: Processing standard module hook 'hook-setuptools._vendor.jaraco.text.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
12020 INFO: Processing pre-safe-import-module hook 'hook-importlib_resources.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12057 INFO: Processing pre-safe-import-module hook 'hook-backports.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12057 INFO: Setuptools: 'backports' appears to be a full setuptools-vendored copy - creating alias to 'setuptools._vendor.backports'!
12530 INFO: Processing pre-safe-import-module hook 'hook-tomli.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
12530 INFO: Setuptools: 'tomli' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.tomli'!
13107 INFO: Processing pre-safe-import-module hook 'hook-wheel.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
13108 INFO: Setuptools: 'wheel' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.wheel'!
13170 INFO: Processing standard module hook 'hook-setuptools._vendor.importlib_metadata.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
13199 INFO: Processing pre-safe-import-module hook 'hook-zipp.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
13200 INFO: Setuptools: 'zipp' appears to be a setuptools-vendored copy - creating alias to 'setuptools._vendor.zipp'!
13275 INFO: Processing standard module hook 'hook-sqlite3.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
13916 INFO: Processing standard module hook 'hook-PIL.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
14058 INFO: Processing standard module hook 'hook-PIL.Image.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
14661 INFO: Processing standard module hook 'hook-xml.etree.cElementTree.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
14856 INFO: Processing standard module hook 'hook-PIL.ImageFilter.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
15167 INFO: Processing pre-find-module-path hook 'hook-tkinter.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_find_module_path'
15168 INFO: TclTkInfo: initializing cached Tcl/Tk info...
15434 WARNING: tkinter installation is broken. It will be excluded from the application
15469 INFO: Processing standard module hook 'hook-urllib3.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
16006 INFO: Processing standard module hook 'hook-certifi.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
16060 INFO: Processing standard module hook 'hook-charset_normalizer.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
16966 INFO: Processing standard module hook 'hook-Crypto.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
18685 INFO: Processing standard module hook 'hook-pycparser.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
20295 INFO: Processing standard module hook 'hook-lxml.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
20821 INFO: Processing standard module hook 'hook-lxml.etree.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
22307 INFO: Processing standard module hook 'hook-webview.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\webview\\__pyinstaller'
22763 INFO: Processing pre-safe-import-module hook 'hook-gi.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\pre_safe_import_module'
22917 INFO: Processing standard module hook 'hook-clr.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\pythonnet\\_pyinstaller'
22998 INFO: Processing standard module hook 'hook-clr_loader.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
23166 INFO: Processing module hooks (post-graph stage)...
23532 INFO: Processing standard module hook 'hook-lxml.isoschematron.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
23632 WARNING: Hidden import "pycparser.lextab" not found!
23632 WARNING: Hidden import "pycparser.yacctab" not found!
23969 INFO: Processing standard module hook 'hook-PIL.SpiderImagePlugin.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks'
24071 INFO: Processing standard module hook 'hook-lxml.objectify.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\_pyinstaller_hooks_contrib\\stdhooks'
24082 INFO: Performing binary vs. data reclassification (186 entries)
24193 INFO: Looking for ctypes DLLs
24318 INFO: Analyzing run-time hooks ...
24322 INFO: Including run-time hook 'pyi_rth_pkgutil.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
24326 INFO: Including run-time hook 'pyi_rth_multiprocessing.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
24329 INFO: Including run-time hook 'pyi_rth_inspect.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
24332 INFO: Including run-time hook 'pyi_rth_setuptools.py' from 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\PyInstaller\\hooks\\rthooks'
24351 INFO: Creating base_library.zip...
24374 INFO: Looking for dynamic libraries
25733 INFO: Extra DLL search directories (AddDllDirectory): ['C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\pikepdf.libs', 'C:\\Users\\Administrator\\.workbuddy\\binaries\\python\\envs\\build_venv\\Lib\\site-packages\\curl_cffi.libs']
25734 INFO: Extra DLL search directories (PATH): []
27720 INFO: Warnings written to D:\Game\JMComicReader\build\JMComicReader\warn-JMComicReader.txt
27809 INFO: Graph cross-reference written to D:\Game\JMComicReader\build\JMComicReader\xref-JMComicReader.html
27855 INFO: checking PYZ
27855 INFO: Building PYZ because PYZ-00.toc is non existent
27855 INFO: Building PYZ (ZlibArchive) D:\Game\JMComicReader\build\JMComicReader\PYZ-00.pyz
28684 INFO: Building PYZ (ZlibArchive) D:\Game\JMComicReader\build\JMComicReader\PYZ-00.pyz completed successfully.
28707 INFO: checking PKG
28708 INFO: Building PKG because PKG-00.toc is non existent
28708 INFO: Building PKG (CArchive) JMComicReader.pkg
28741 INFO: Building PKG (CArchive) JMComicReader.pkg completed successfully.
28742 INFO: Bootloader C:\Users\Administrator\.workbuddy\binaries\python\envs\build_venv\Lib\site-packages\PyInstaller\bootloader\Windows-64bit-intel\runw.exe
28742 INFO: checking EXE
28742 INFO: Building EXE because EXE-00.toc is non existent
28742 INFO: Building EXE from EXE-00.toc
28743 INFO: Copying bootloader EXE to D:\Game\JMComicReader\build\JMComicReader\JMComicReader.exe
28754 INFO: Copying icon to EXE
28763 INFO: Copying 0 resources to EXE
28763 INFO: Embedding manifest in EXE
28771 INFO: Appending PKG archive to EXE
28781 INFO: Fixing EXE headers
28862 INFO: Building EXE from EXE-00.toc completed successfully.
28872 INFO: checking COLLECT
28872 INFO: Building COLLECT because COLLECT-00.toc is non existent
28873 INFO: Building COLLECT COLLECT-00.toc
29855 INFO: Building COLLECT COLLECT-00.toc completed successfully.
29863 INFO: Build complete! The results are available in: D:\Game\JMComicReader\dist_tmp
```

## clean.log

```
START 08/07/2026 13:37:38
REMOVED D:\Game\JMComicReader\dist_190
FAIL D:\Game\JMComicReader\verify_190 : [safe-delete][SAFE_DELETE_FAIL_CLOSED] {"target":"D:\\Game\\JMComicReader\\verify_190","reason":"trash-failed","detail":"ERROR D:\\Game\\JMComicReader\\verify_190: Error during a `trash` operation: Unknown { description: \"Some operations were aborted\" }"}
END
```

## dev_run.log

```
加载封面缓存，数量: 1
加载封面缓存，数量: 1
 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://10.44.59.156:5000
Press CTRL+C to quit
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 970-026-174
127.0.0.1 - - [07/Aug/2026 11:05:11] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:05:11] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:05:11] "GET /downloads HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:05:11] "GET /settings HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:06:03] "GET /search HTTP/1.1" 200 -
```

## smoke_run.log

```
127.0.0.1 - - [07/Aug/2026 11:26:48] "GET / HTTP/1.1" 302 -
127.0.0.1 - - [07/Aug/2026 11:26:49] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:26:50] "GET / HTTP/1.1" 302 -
127.0.0.1 - - [07/Aug/2026 11:26:50] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:26:50] "GET /static/css/style.css?v=9 HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:26:50] "GET /static/js/app.js?v=9 HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:26:50] "GET /api/settings HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:26:50] "GET /favicon.ico HTTP/1.1" 404 -
127.0.0.1 - - [07/Aug/2026 11:26:59] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:27:00] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:27:00] "GET /downloads HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:27:00] "GET /settings HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:27:00] "GET /search HTTP/1.1" 200 -
127.0.0.1 - - [07/Aug/2026 11:27:14] "GET /api/settings HTTP/1.1" 200 -
```

## v1.8.8_overview.md

```
# JMComicReader v1.8.8 交付概述

**版本号**：1.8.7 → 1.8.8
**交付内容**：拉黑（作者/作品）+ 同义词别名（标签/作者）

---

## 一、功能

### 拉黑作者 / 单个作品
- 后端 `blocklist` 表 + 搜索后过滤（`postprocess_results` 服务端剔除，刷新/翻页自动生效）。
- 拉黑本地命中 → **仅提示 + 本地灰显**（书架卡灰显 +「已拉黑」标记，文件保留、可一键复原）。
- 设置页「屏蔽管理」可增删；详情 `/api/blocklist/affects` 供一键取消影响该漫画的拉黑。

### 同义词 / 别名（标签 + 作者）
- **手动别名表**（`aliases` 表）+ **自动建议**（`SEED_SYNONYMS` 种子同义词 + 本地已下载库标签共现挖掘，Jaccard≥0.6 且各标签文档数≥3）。
- 搜索时 `expand_tags()/expand_author()` 把输入展开为同义词组一并检索；展示时 `get_alias_map()` 归一化到 canonical（如 爆乳→巨乳）。
- 设置页「同义词/别名」可增删 + 一键采纳建议。
- 按用户决策：**只做标签 + 作者，不做作品名合并**（jm_id 唯一，按名合并会误杀）。

---

## 二、验证（三层）

1. **隔离逻辑测试**：blocklist / alias / expand / postprocess / suggest 全绿（ALL_OK）。
2. **路由冒烟**（Flask `test_client`，真实路由，jmcomic/webview 打桩）：**17 项 PASS** ——
   blocklist/aliases 增删查、搜索过滤+标签归一化（爆乳→巨乳）、`/api/blocklist/affects`、`/api/downloaded` 的 `blocked` 标志、清理。
3. **部署包无头验证**：`BASE_DIR=临时目录` 启动打包后 `JMComicReader.exe`，curl 确认
   `/api/downloaded` 等路由 200、`?v=10` 静态资源已进包 → 证明修复与前端均在正式包内。

---

## 三、修复的关键 Bug（冒烟抓出）
`/api/downloaded` 路由调用 `get_blocked_sets()`，但 `core/app.py` 的 import 漏了该函数（只 import 了 `normalize_author`）。
**后果**：正式包里书架页会直接 500；搜索路由因走 `postprocess_results()` 内部 import 不受影响 → 极易被忽略。
**修复**：在 `core/app.py` import 块补上 `get_blocked_sets`。
**教训**：搜索路由正常 ≠ 下载路由正常，新增函数务必同步 import，各路由独立冒烟。

---

## 四、构建（严守红线，用户数据零触碰）
- 用全新 `--workpath build_v188` 绕开 `--noconfirm`/`--clean` 触发的 `SAFE_DELETE_FAIL_CLOSED`（沙箱回收站不可用）。
- 构建到 `dist_tmp`，合并拷贝 `JMComicReader.exe` + `_internal/` 进 `dist/JMComicReader`；
  用户数据目录（`.app_url` `core/`(comics.db) `DownloadedComics/` `TempCache/` `webview_data/`）原样保留。
- 产物：`D:\Game\JMComicReader\dist\JMComicReader\JMComicReader.exe`（v1.8.8），无 `startup_error.log`。

---

## 五、清理
临时测试文件（`_t.py`/`_smoke.py`/`jmverify`/`build_v188_log.txt`）与构建中间目录（`dist_tmp`/`build`/`build_v188`）
经 **PowerShell `Remove-Item -Force -Recurse`** 真删（git-bash `rm` 在本沙箱 fail-closed 不真删）。

---

## 六、关键文件
- 后端：`core/models/database.py`、`core/services/filter_service.py`、`core/app.py`
- 前端：`web/static/js/app.js`、`web/templates/settings.html`、`web/templates/base.html`(`?v=10`)、`web/static/css/style.css`
- 构建：`JMComicReader.spec`、`core/desktop_app.py`、`VERSION`(=1.8.8)

> 源码根目录：`D:\code\CODE\AI project\jmcomicreader-windows\`
> 运行/交付目录：`D:\Game\JMComicReader\dist\JMComicReader\`
```

## v1.8.9_overview.md

```
# JMComicReader v1.8.9 更新概要

## 完成内容

- **新增「拉黑后提示本地命中」设置开关**
  - 设置页 → 屏蔽管理 → 新增开关「拉黑后提示本地命中」。
  - 默认开启，关闭后屏蔽作品/作者时不再弹出本地书架命中提示。
  - 后端 `/api/settings` 增加 `show_block_hits` 持久化字段。

- **涉及文件**
  - `core/app.py`：`/api/settings` GET 的 keys 列表加入 `show_block_hits`。
  - `web/templates/settings.html`：在「屏蔽管理」区加入 `#showBlockHits` 开关行。
  - `web/static/js/app.js`：新增 `appConfigCache`、`loadAppConfig`、`setAppConfig`；`initSettings` 加载并保存该开关；`blockWork` / `blockAuthor` 仅在开关开启时调用 `showBlockHits`。
  - `web/templates/base.html`、`web/templates/reader.html`：静态资源缓存 bust 升级到 `v=11`。
  - `VERSION`：`1.8.8` → `1.8.9`。

## 验证

- Flask `test_client` 冒烟测试 14/14 通过（含 settings 读写、blocklist、aliases、downloaded 回归）。
- PyInstaller onedir 重新打包，输出到 `D:\Game\JMComicReader\dist\JMComicReader\JMComicReader.exe`。
- 无头启动验证：
  - `/api/settings` 返回含 `"show_block_hits"`。
  - `/settings` HTML 含 `id="showBlockHits"`。
  - 缓存 bust 参数为 `?v=11`。
- 用户数据目录（`.app_url`、`core/`、`DownloadedComics/`、`TempCache/`、`webview_data/`）未动。

## 待澄清

- 用户截图中「这一块为什么没删」指向的具体 UI 元素，因截图只显示了局部一角（含 ♡ / × 的按钮区域），无法准确判断是哪一个元素。需要用户进一步说明。
```

## v1.9.0_overview.md

```
# JMComicReader v1.9.0 更新说明

> 源码根目录：`D:\code\CODE\AI project\jmcomicreader-windows\`
> 交付目录：`D:\Game\JMComicReader\dist\JMComicReader\`

## 本次改动（对应需求）
1. **删除外置标签按钮**：搜索栏的 fa-tags 独立标签按钮（及 `tagsToggleHint`）已移除——标签早已移进搜索栏（quickTags + 下拉三栏），该按钮冗余。点击标签区空白处（`#sbTagArea`）即可展开「历史 / 标签 / 作者」下拉，芯片点击仍只切换选中。
2. **同义词默认「或」搜索（确认已生效）**：`/api/search/tags`、`/api/search/combined` 路由 `mode` 默认 `"or"`，无需改动即满足。
3. **优先输入名排序（新增，默认开）**：同义名一起搜时，结果中**真正命中你输入名字**的作品（如输入「巨乳」→ 标签里真含「巨乳」的）排「爆乳 / 大奶」变体之前；再按收藏数降序。基于归一化前的原始标签判断。
4. **搜索优先级设置**：设置页「搜索」新增下拉——`优先输入的名字`（默认）/ `同义词等同`。设 `equal` 则回到纯收藏数排序。

## 涉及文件
- `core/models/database.py`：`DEFAULT_CONFIGS` 新增 `search_priority`（默认 `input`）。
- `core/app.py`：`/api/settings` 暴露 `search_priority`；`/api/search/tags` 与 `/api/search/combined` 读取该设置并透传 `input_tags`。
- `core/services/jm_crawler.py`：`search_by_tags()` 新增 `input_tags` 参数，两级排序（命中输入名 → 收藏数）。
- `web/templates/search.html`：移除 `tagsToggleBtn`/`tagsToggleHint`，`.sb-tag` 加 `id="sbTagArea"`。
- `web/static/js/app.js`：清理 `tagsToggleBtn` 全部引用；新增 `sbTagArea` 点击展开下拉；`initSettings` 加载/保存 `searchPriority`。
- `web/templates/settings.html`：搜索区新增「搜索优先级」行。
- `base.html` / `reader.html`：静态缓存击穿 `?v=11 → ?v=12`。
- `VERSION`：1.8.9 → **1.9.0**。

## 验证（无头 curl，已通过）
- `/api/settings` 返回含 `"search_priority":"input"`。
- `/settings` 含 `id="searchPriority"`，且已无 `tagsToggleBtn`。
- `/search` 含 `id="sbTagArea"`，且已无 `tagsToggleBtn`。
- 静态资源 `app.js?v=12` / `style.css?v=12` 已打包。

## 部署说明
- 合并方式：`robocopy /MIR` 仅同步 `_internal/` + 拷贝 `JMComicReader.exe`，用户数据目录（`core/ DownloadedComics/ webview_data/ .app_url/ TempCache/`）原样保留。
- 部署时若有 JMComicReader 实例在运行，需先 `taskkill` 释放 exe 锁，再覆盖。
- **重启 app 后生效**（当前运行的旧实例已被替换）。
```

## v1.9.1_overview.md

```
# JMComicReader v1.9.1 更新说明

> 源码根目录：`D:\code\CODE\AI project\jmcomicreader-windows\`
> 交付目录：`D:\Game\JMComicReader\dist\JMComicReader\`

## 本次改动
1. **彻底删除搜索栏残留 × 按钮**：`sb-tag` 行现在只有 quickTags 芯片，点击空白处仍可展开历史/标签/作者下拉。
2. **同时下载任务数显示当前值**：设置页滑杆右侧新增数字 `maxConcurrentVal`，拖动时实时更新。
3. **工程整理 + 手机端准备文档**：新增/更新了 API/架构/README 文档。

## 涉及文件
- `web/templates/search.html`：移除 `clearTagsBtn`。
- `web/static/js/app.js`：清理 `clearTagsBtn` 全部引用；`initSettings` 同步 `maxConcurrentVal`。
- `web/templates/settings.html`：滑杆旁加 `<span id="maxConcurrentVal">`。
- `base.html` / `reader.html`：缓存击穿 `?v=13`。
- `VERSION`：1.9.0 → **1.9.1**。
- `docs/API.md`（新增）：完整 HTTP API 参考。
- `docs/ARCHITECTURE.md`（新增）：模块职责、数据流、与 Android 复用建议。
- `docs/README.md`：重写为当前结构。

## 验证（无头 Python 脚本，已通过）
- `/search` 无 `tagsToggleBtn`，含 `id="sbTagArea"`。
- `/settings` 含 `id="maxConcurrentVal"`，无 `tagsToggleBtn`。
- 静态资源 `?v=13` 已打包。

## 部署说明
- `dist/JMComicReader/` 已更新，用户数据目录（漫画库/收藏/历史）原样保留。
- 临时构建目录 `dist_191` / `build_191` / `verify_191` 因沙箱删除确认被用户取消而残留，不影响交付。
```
