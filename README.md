# Python-darslari
Bu yerda boshlang'ich python kodlari joylab boriladi.
#6.03.2026
#Python darslari. Mohirdev(YouTube)
#if-elif-else operatorlari.
narh = 15000
choy = 1
salat = 0
non = 1
kompot = 1
assorti = 0
if choy: #agar mijoz choy olsa
    print("Siz choy oldingiz")
    narh = narh + 2000
if salat:
    print("Siz salat oldingiz")
    narh = narh + 5000
if non:
    print("Siz non oldingiz")
    narh += 4000
if kompot:
    print("Siz kompot oldingiz")
    narh += 3000
if assorti:
    print("Siz assorti oldingiz")
    narh += 4000
print(f"Siz ja'mi {narh} so'm to'lashingiz kerak")

#6.03.2026
#Python darslari. Mohirdev(YouTube)
#if-elif-else operatorlari.
kun = input("Bugun haftaning qaysi kuni: ")
if kun.lower() == 'shanba' or kun.lower() == 'yakshanba':
    print("Bugun dam olish kuni.")
else:
    print("Bugun ish kuni.")
day = input("Bugun haftaning qaysi kuni? \n>>>")
temperature = float(input("Ob-havo harorati qay darajada? \n>>>"))
if (day.lower() == 'shanba' or day.lower() == 'yakshanba') and temperature >=30:
    print("Bugun cho'milgani boramiz.")
else:
    print("Bugun cho'milgani bormaymiz")
narh = 15000  #mijoz 15000 ga taom oldi
choy = True   #mijoz choy ham oldi
salat = False   # mijoz salat olmadi
if choy and salat: #mijoz choy ham salat ham oldi
    narh += 10000  #narh = narh +10000
elif choy or salat: #mijoz choy yoki salat oldi
    narh += 5000  #narh = narh +5000
print(f"Ja'mi narh {narh}-ga teng.")

