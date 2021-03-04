s=input()
n=int(input())
if s.count("a")==0:
    print(0)
elif len(s)<n:
    r = s.count("a")
    f = n - len(s)
    o = f // len(s)
    k= f%len(s)
    h=s[:k]
    p=h.count("a")
    g = r + o * r + p
    print(g)
else:
    l=s[0:n]
    print(l.count("a"))
