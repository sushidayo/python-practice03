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
