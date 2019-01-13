无字碑不是无字的，但是看不出什么线索。
一般遇到乱序的内容，先是考虑凯撒加密，或者扩展的凯撒加密——每一个字母的偏移是递增/递减的。但是有这么多字，显然是一篇文章，而一篇文章不可能成为flag，因此flag应该藏在原文中。
原文中有两个特殊符号，一般文章不会在里面加特殊符号，很可能就是flag。因为在凯撒加密等字母替换中，符号会保持原样。
观察各个字母出现的频次。我们经常可以看到g这个字母出现在分句前。所以很可能是冠词 a
解题思路：词频分析
https://quipqiup.com/是一个很好的网站，可以帮助我们推断里面的内容。
输入之后就可以得到部分词语，它不确定的字母则以？显示，但是解开不难，就是还原几个单词就可以获得全部字母的替换顺序了。
注意：两个符号需要转换为{}