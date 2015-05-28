# Django-Design-Patterns-and-Best-Practices
中文名：《Django 设计模式与最佳实践》  
英文原版：https://www.packtpub.com/web-development/django-design-patterns-and-best-practices  
作者：Arun Ravindran  
出版日期：March 2015  
特色：Easily build maintainable websites with powerful and relevant Django design patterns  
级别：Mastering   
页数：Paperback 222 pages  

-------------------------  
## 简介

所有译文均以 GitHub Issue 的形式发布，[点此阅读](https://github.com/cundi/Django-Design-Patterns-and-Best-Practices/issues?state=open)。


## 版权协议

除注明外，所有文章均采用 [Creative Commons BY-NC-ND 3.0（自由转载-保持署名-非商用-非衍生）](http://creativecommons.org/licenses/by-nc-nd/3.0/deed.zh) 协议发布。

这意味着你可以在非商业的前提下免费转载，但同时你必须：

* 保持文章原文，不作修改。
* 明确署名，即至少注明 `作者：cundi` 字样以及文章的原始链接。

如需商业合作，[请直接联系作者](https://github.com/cundi/Web.Development.with.Django.Cookbook/issues/3)。

目录预览
***********************************

内容目录
-----------------
* Django设计模式与最佳实践
	* 第一章 Django与模式
		1. Django是什么？
		2. Django的故事
			* 一个框架的诞生
			* 移除魔法
			* Django坚持做到更好
			* Django是如何工作的？
		3. 什么是模式？
			* 四人组模式
			* Django是MVC架构吗？
			* 福勒模式
			* 还存在更多的模式吗？
		4. 本书的模式
			* 鉴定模式
			* 如何使用模式
		5. 最佳实践
			* Python之禅和Django的设计哲学
		6. 总结
	* 第二章 应用模式
		1. 如何获取需求
		2. 你会讲故事吗？
		3. HTML模型
		4. 设计应用
			* 将一个项目分成多个App
			* 重新使用还是用自己的？
				 * 我的app沙箱
			* 它是由哪一个包构建的？
		5. 开始项目之前
		6. SuperBook—给你的任务，你应该选择接受它
			* 为什么是Pyhton3？
			* 开始一个项目
		7. 总结
	* 第三章 模型
		1. M比V和C更大
		2. 模型选取
			* 分拆model.py到多个文件
		3. 结构化模型
			* 模式-规范化的模型
				* 具体问题
				* 答案细节
					* 第一个规范表单
					* 第二个规范表单
					* 第三个规范表单
					* Django模型
				* 性能和反规范
				* 我们应该一直遵守规范化吗？
			* 模式-模型mixin
				* 具体问题
				* 答案细节
					* 信号
					* Admin
					* 多账户类型
				* 模式-服务对象
					* 具体问题
					* 答案细节
		4. 检索模式
			* 模式-属性字段
				* 具体问题
				* 答案细节
					* 缓存特性
			* 模式-自定义模型管理
				* 具体问题
				* 答案细节
					* 对QuerySet的操作
					* 链接多个QuerySet
		5. 迁移
		6. 总结
	* 第四章 视图和URL
		1. 来自顶端的视图
			* 让视图更高级
		2. 基于类的通用视图
		3. 混合视图
			* 混合的顺序
		4. 装饰器
		5. 视图模式
			* 模式-访问控制视图
				* 具体问题
				* 详细答案
			* 模式-上下文增强器
				* 具体问题
				* 详细答案
			* 模式-服务
				* 具体问题
				* 详细答案
		6. 设计URL
			* URL剖析
				* 在urls.py中发了什么？
				* URL模式语法
					* Mnemonic – parents question pink action-figures
				* 名字和命名空间
				* 模式顺序
				* URL模式风格
					* 分部门存储URL
					* RESTful　URL
		7. 总结
	* 第五章 模板
		* 理解Django的模板语言特点
			* 变量
			* 属性
			* 过滤器
			* 标签
			* 设计哲学-不要发明一种编程语言
		* 规划模板
			* 支持其他的模板语言
		* 使用Bootstrap
			* 可是，他们看上去都一样！
		* 模板模式
			* 模式-模板继承树
				* 具体问题
				* 详细答案
			* 模式-激活的链接
				* 具体问题
				* 详细答案
					* 仅使用模板的解决方案
					* 自定义标签
		* 总结
	* 第六章 Admin接口
		* 使用admin接口
		1. 对admin使用加强的模型
			* 不是每一个人都应该称为admin
		2. 自定义Admin接口
			* 改变头部
			* 改变base模板和样式表
				* 给WYSIWG编辑添加一个富文本编辑器
			* admin的Bootstrap主题
			* 完成变革
		3. 保护Admin
			* 模式-特性标识
				* 具体问题
				* 详细答案
		4. 总结
	* 第七章 表单
		1. 表单是如何工作的
			* Django中的表单
			* 为什么数据需要清洁？
		2. 显示表单
			* 时间变得很脆弱
		3. 理解CSRF
		4. 使用基于类的表单处理
		5. 表单模式
			* 模式-动态表单生成
				* 具体问题
				* 详细答案
			* 模式-基于用户的表单
				* 具体问题
				* 详细答案
			* 模式-一个视图的多个表单行为
				* 具体问题
				* 详细答案
					* 对单独的行为使用单独的视图
					* 单独的行为使用相同的视图
			* 模式-CRUD视图
				* 具体问题
				* 详细答案
		6. 总结
	* 第八章 处理早期代码
		1. 找到Django版本
			* 激活虚拟环境
		2. 文件放在哪里？这可不是PHP
		3. 从urls.py开始
		4. 跳跃的代码
		5. 理解代码基础
			* 绘制宏伟蓝图
		6. 增量改进还是完全重写？
		7. 做出任何改变之前都要写测试
			* 按步骤写测试
		8.早期数据库
		9.总结
	* 第九章 测试和调试
		1. 为什么要写测试？
		2. 测试驱动的开发
		3. 写一个测试的案例
			* 断言方法
			* 写出更好的测试案例
		4. 建模
		5. 模式-测试装置和工厂
			* 具体问题
			* 详细答案
		6. 学习更多的测试知识
		8. 调试
			* Django的调试页面
				* 一个更好的调试页面
		9. print函数
		10. 写日志
		11. Django调试工具条
		12. Python的调试器pdb
		13. 其他的调试器
		14. 调试Django模板
		15. 总结
	* 第十章 安全
		1. 跨站脚本（XSS）
			* 为什么你的cookies如何有利用价值？
				* Django是如何帮助你的
				* 在什么地方Django也帮不上你
			* 跨站请求伪造（CSRF）
				* Django是如何帮助你的
				* 在什么地方Django也帮不上你
			* SQL注入
				* Django是如何帮助你的
				* 在什么地方Django也帮不上你
			* 点击劫持
				* Django是如何帮助你的
			* Shell注入
				* Django是如何帮助你的
			* 攻击方法的列表还在增长中
		2. 一张便捷的安全检查清单
		3. 总结
	* 第十一章 产品预发布
		1. 产品环境
			* 选择一个web栈
			* 一个栈的组件
		2. 托管
			* 平台即服务
			* 虚拟私有服务
			* 其他的托管方法
		3. 部署工具
			* Fabric
				* 典型的几种部署步骤
			* 配置的管理
		4. 监测
		5. 性能
			* 前端性能
			* 后端性能
				* 模板
				* 数据库
				* 缓存
					* 缓存会话后端
					* 缓存框架
					* 缓存模式
		6. 总结
	* 目录-A Python2 VS Python 3
		* 不过我依旧使用Python2.7！
		1. Python 3
			* Python 3 for Djangonauts
			* 改变所有的 `__unicode__` 方法到 `__str__`方法
			* 所有的类都应该继承自object类
			* 调用super()更简单
			* 必须更明确地相对导入
			* HttpRequest and HttpResponse have str and bytes types
			* 异常语法的改变和提高
			* 重组标准库
			* 新东西
				* 使用Pyvenv和Pip
			* 其他的改变
		2. 更多内容
			
	
				
