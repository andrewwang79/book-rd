# 面试
* 考卷在仓库目录/s/file/面试题/

## 通用面试题
### 逻辑题
1. 两个单向链表，找出它们的第一个公共结点。
1. 如何检测单向链表是否有环。
1. 一个岔路口分别通向诚实国和说谎国。诚实国永远说实话，说谎国永远说谎话。路口来了两个人，一个是诚实国的，另一个是说谎国的。现在你要去说谎国，但不知道应该走哪条路，需要问这两个人。请问应该怎么问？
1. 有2个玻璃瓶，分別是3升和5升，请倒出4升的水。
1. 照镜子左右互换的原理是什么

### 编程
* [最高频的K个单词](https://www.lintcode.com/problem/top-k-frequent-words/description)

### 资料
* [微软公司等数据结构+算法面试100题(第1-100题)全部出炉](https://blog.csdn.net/v_JULY_v/article/details/6057286)
* [互联网公司最常见的面试算法题](https://www.zhihu.com/question/24964987)

## C++
* https://cpp.wangyaqi.cn/

### 知识点
* 开发体系：单元测试
* 开发工具：conan，cmake
* 基础知识：fork，动态链接，内存泄漏
* 现代：智能指针，右值引用，GO

### 题目
```
int value = 1;
auto copy_value = [value] {
    return value;
};
value = 100;
auto stored_value = copy_value();
lambda:stored_value是多少？
答案：
lambda:stored_value是1
```

* baidu的C++题目：https://zhuanlan.zhihu.com/p/89708816, https://zhuanlan.zhihu.com/p/112442730
