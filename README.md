# python-practice03

s = 'リンゴ,みかん,ぶどう'
slist = s.split(',')
print(s)

s = 'りんご,みかん,ぶどう レモン  オレンジ'
for ss in s.split():
    print(ss)
    
s = 'りんご,みかん,ぶどう'
for ss in s.split(',', 1):
    print(ss)

s = 'しんぶんはんばい'
n = s.find('ん')
print(s*n)

n = s.find('ん',2,5)

n = s.find('あ')

s = 'しんぶんはんばい'
result = 'ん' in s
print(result)

s = 'しんぶんはんばい'
n = s.count('ん')
print(n)

s1 = '   abc   '
s2 = s1.strip()
print(s1)

s1 = ',,,,abc,,,'
s2 = s1.strip(',')
print(s1)

str(123)
str(True)
str(['a','b','c'])

s = '  りんご  '
l = len (s)
print(s)

s = ' りんご みかん '
s2 = s[2:6]
print(s)

for ss in 'こんにちは':
    print(ss)
