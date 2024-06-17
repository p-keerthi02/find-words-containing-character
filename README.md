class Solution:
    def findWordsContaining(self, words, x):
        t=[]
        for i in range(len(words)):
            if x in words[i]:
                t.append(i)
        return t
