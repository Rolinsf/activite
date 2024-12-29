# rolinsf-activity

## 项目介绍
该项目为 若林轻小说的开发界面，所采用的技术栈都是我在学习过程中的，学到什么就用什么，所以做的不是很好，请群友见谅。  
更新频率为1周到2周，更新一个小页面布局或者其他的，有什么问题和好的建议请群里联系我或者直接提交issue，同时你也想进入开发，就直接提交到main分支即可（给你凑个贡献者或开发者）  
真正发行版本会另外一个分支的，main就是开发分支。  
谁都可以参与开发，只要你愿意即可。当版本功能完善后，我就会进行打tag版本标签为v1.0版本来进行版本控制，大家畅所欲言的大胆去实现和进行开发吧。  
提交规范：采用git语义化提交规范，在提交commit里添加前缀： feat （新功能）、 fix （修复Bug）、 docs （文档修改）、 style （代码格式调整，不影响功能）、 refactor （代码重构）、 test （添加或修改测试用例）、 chore （构建过程或辅助工具的变动），建议先去了解了解。

## 项目启动

1. 先拉取下拉
```
git clone https://github.com/Rolinsf/rolinsf-activity.git
cd rolinsf-activity
```
2. 先创建临时python环境,上传git的时候记得删除临时环境，避免隐私泄露
```
python -m venv myenv
. .\myenv\Scripts\activate
```
3. 再下载依赖包
```
pip install -r requirements.txt
python app.py
```
4.开发完后，如有添加新的依赖包，请将依赖包重新写入requirements.txt
```
pip freeze > requirements.txt
```

## 项目日志  
1. 2024.12.29 初步页面规划，增加左侧边栏（非固定，鼠标滑动显示）——清风
