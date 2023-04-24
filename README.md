**Hi, 本仓库将记录本人阅读过的源码、手写轮子、某技术的code demo、学习教程、学习的心得等**

1. 手写的 [promise 实现](https://github.com/xiaochengzi6/Promise)
2. [JavaScript](https://github.com/xiaochengzi6/javascript-demo) 复习和一些题目练习
3. [quill源码调试](https://github.com/xiaochengzi6/quill-scource-code)
4. [rollup初版源码的仿写](https://github.com/xiaochengzi6/pack)
5. [ahook源码的阅读及注释](https://github.com/xiaochengzi6/rx-hook)
6. [react-router源码的阅读及注释](https://github.com/xiaochengzi6/mini-react-router)
7. [如何进行测试代码片段](https://github.com/xiaochengzi6/react-test-learn)
8. [history源码阅读及心得](https://github.com/xiaochengzi6/history)
9. [redux源码实现](https://github.com/xiaochengzi6/react-redux-demo)
10. [underscore源码阅读后的做了一个翻版](https://github.com/xiaochengzi6/rx-utils)
11. [immer原理的学习](https://github.com/xiaochengzi6/immer-tiny)
12. [jsx的原理、其中顺便看了react.createElement() 源码、babel插件的编写，顺便实现了一个简单版本的 jsx babel插件](https://github.com/xiaochengzi6/jsx)
13. [accorn 源码阅读](https://github.com/xiaochengzi6/rx-acorn)

**总结及计划**

大部分源码的阅读都是处于实习工作期间(2022.6-2022.12)，这些源码有些就看过一遍甚至就看过我认为重点的部分，为了避免知识遗漏所以都开了仓库去记录自己看过的源码和心得。

我最早看的源码是 `undescore` 它的源码比较简单、有很多精彩的部分比如它如何进行链式调用、工具函数之间如何进行挂载...，由于公司项目中使用到了 `react-router` 我对其实现很是疑惑，于是去阅读了它和 `history` 源码，又去看了`react-redux`的实现，本来计划是想看 `react` 源码的，在挣扎一周之后就放弃，感觉知识储备还不够。

在项目中使用到了 react 自定义 hook 但自己写的太丑陋，遂去看了 `ahook` 想更深入的了解 react-hook，在看代码期间学习了如何对代码进行单元测试，找了一些关于测试的资源才有了 [如何进行测试代码片段](https://github.com/xiaochengzi6/react-test-learn) 

2023.3-2.23.4 这个时间段在学习 ast 方面的东西，最开始是对 文本编辑器非常感兴趣 在看源码的过程中发现了自己能力不足以自己去实现一个，于是脑洞大开不如学习编译器吧，以"农村包围城市"的计划就诞生了,我定下了"三步走"战略，最终目的是想向编辑器那边靠拢看看，能不能实现一版。 

1. 编译器
2. 打包器
3. 编辑器


看完了`the-super-tiny-compiler`项目代码后，自己去简单实现了一个es3版本的 js ast 转化的项目，期间也是遇到了很多问题，参考了 `accorn 的初版代码`一路坎坎坷坷，紧接着我就去学习打包器，去阅读了`rollup`最初的代码，想自己实现，但是发现左右为难，刚好 `magicast` 项目横空出世，我 fork 下来后想基于这个项目做文件 ast 分析的 这样就能解决打包器的核心代码。

不过一直到目前为止，还没有完全实现一个完整版的 打包器，我发现我并不能这样下去了，毕业即将来临，也该准备毕设和工作的事情了，剩下的时间就准备复习直至找到工作，然后在慢慢实现自己订下的目标吧...
