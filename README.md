import random
Karakterler=("+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890")
Uzunluk=int(input("Uzunluğu Giriniz:"))
sifre=""
for i in range(Uzunluk):
    sifre+=random.choice(Karakterler )
print(sifre)
