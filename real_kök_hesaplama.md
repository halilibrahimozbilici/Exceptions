# Exceptions

def kök_hesapla(x,y,z):
    import math
    d = (y * y) - 4 * x * z

    if d < 0:
        print("Reel kök yoktur . ")
    elif d == 0 :
        x1 = (-y + math.sqrt(d) )/ 2 * x
        print("Sonuc : {} ".format(x1))
        print("Bir reel kök vardır . ")
    else:
        x1 = (-y + math.sqrt(d)) / 2 * x
        x2 = (-y - math.sqrt(d)) / 2 * x
        print("Sonuc : {} {} ".format(x1, x2))
        print("2 reel kök vardır.")


kök_hesapla(
    int(input("Lütfen x değerini giriniz : ")),
    int(input("Lütfen y değerini giriniz : ")),
    int(input("Lütfen z değerini giriniz : "))

)
