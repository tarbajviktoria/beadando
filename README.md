# beadando

def piglatin(s):
    uj = ""
    for i in range(len(s)):
        if len(s)<3:
            uj=s
            s[0]=uj[2]



    return uj

s =input("Adj egy szót: ")
print(piglatin(s))
