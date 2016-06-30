# CollocationFinder
基于WordNet和句法依存树，实现对英语短语的搭配提取，包括连续的和非连续的英语短语词组。
连续的提取可以是任意长度的。非连续的对句法分析得到的任意长的词组，只提取长度为2的非连续词组。
StanfordCollocationFinder.java是入口函数，主要是根据句法分析的结果得到词组搭配的结果。并与WordNet建立连接。
WordNet.java是判断短语搭配是否在WordNet中，并返回提取出的词组。
