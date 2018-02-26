

# 1.Import
如果要引用的脚本与本脚本不在同一个目录级，可以在本脚本开通添加一下代码：
```
import sys
sys.path.append(path)
```
注： path为绝对路径

例如：
```
import sys
sys.path.append('C:/001Work/001Automation/svn/QualityAnalyzer_local1/')
```
