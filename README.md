# cpp_knowledge_points

## 设置github访问权限，管理代码
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account

# 正式开始 [^1]
[^1]: 本仓库主要储存了学习中的知识点总结

## cpp基础知识汇总
### 类
#### 析构函数 ~ClassName()
- 析构函数在对象释放前自动调用
- 作用：对象本身占用的空间会在超出作用范围或者delete时自动释放，如果对象还额外分配了其他资源，就需要在析构函数中手动释放。

