```python
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


talaba_0 = {
    'ism' : "irismatov shohruzbek",
    'yosh' : 20, 
    't_yil' : 2006,
    }
print(f"{talaba_0['ism'].title()},\
   {talaba_0['yosh']}-yoshda, {talaba_0['t_yil']} - yilda tug'ilgan.")
talaba_0['kurs'] = 1
talaba_0['fakultet'] = 'fizika-matematika'
talaba_0["yo'nalish"] = 'amaliy matematika'
talaba_0['ism'] = 'xujayev sherozbek'
print(talaba_0)
talaba_1 = {}
talaba_1['ism'] = 'qurbonaliyev shahin'
talaba_1['yosh'] = 19
talaba_1['kurs'] = 1
talaba_1['t_yil'] = 2006
print(f"{talaba_1['ism'].title()} {talaba_1['yosh']}-yoshda {talaba_1['kurs']} -kurs {talaba_1['t_yil']}-yilda tug'ilgan")
talaba_1['kurs'] = 4
print(f"{talaba_1['ism'].title()} {talaba_1['yosh']}-yoshda {talaba_1['kurs']} -kurs {talaba_1['t_yil']}-yilda tug'ilgan")
print(talaba_1)
del talaba_1['t_yil']
print(talaba_1)
telefonlar = {
    'shohruz' : 'redmi note 11 pro',
    'shahin' : 'mi note 10',
    'sheroz' : 'honor x6c',
    'mustafo' : 'samsung s21',
    'shohzod' : 'redmi note 10c'
}

print(f"Shohro'zning telefoni: {telefonlar['shohruz']}")

telefonlar = {
    'shohruz' : 'redmi note 11 pro',
    'shahin' : 'mi note 10',
    'sheroz' : 'honor x6c',
    'mustafo' : 'samsung s21',
    'shohzod' : 'redmi note 10c'
}

phone = telefonlar['mustafo']
print(f"Mustafoning telefoni {phone}")
phone = telefonlar.get('mustafo',"Bunday ism mavjud emas")
phone = telefonlar.get('hasan', "Bunday ism mavjud emas")
print(phone)

telefonlar = {
    'shohruz' : 'redmi note 11 pro',
    'shahin' : 'mi note 10',
    'sheroz' : 'honor x6c',
    'mustafo' : 'samsung s21',
    'shohzod' : 'redmi note 10c'
}
ism = input('Ismingizni kiriting: ')
if ism in telefonlar:
    print(telefonlar[ism])
else:
    print("Bunday ism yo'q")