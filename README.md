# matplotlib-bilan-ishlash-grafiklar
📊 Student Performance Data Analysis (EDA)
Ushbu loyiha talabalarning o'quv natijalari (Matematika, O'qish va Yozish ballari) va ularga ta'sir etuvchi ijtimoiy-demografik omillarni o'rganishga qaratilgan. Ma'lumotlar to'plami talabalarning jinsi, etnik guruhi, ota-onasining ma'lumoti va haftalik dars qilish soatlari kabi ko'plab ustunlardan iborat.

🛠 Texnologiyalar
Loyihada quyidagi kutubxonalardan foydalanildi:

Pandas - Ma'lumotlarni yuklash va qayta ishlash.

Matplotlib & Seaborn - Ma'lumotlarni vizuallashtirish (grafiklar).

NumPy - Matematik hisob-kitoblar.

📈 Tahlil Natijalari (Vizualizatsiya)
1. Talabalarning jins bo'yicha taqsimoti
Ma'lumotlar to'plamidagi ayol va erkak talabalar o'rtasidagi nisbat Pie Chart orqali ko'rsatilgan. Bu bizga namunadagi muvozanatni tushunishga yordam beradi.

2. Ota-onalarining oilaviy holati
Talabalarning ota-onalari qanday oilaviy holatda (turmush qurgan, ajrashgan, bo'ydoq va h.k.) ekanligi tahlil qilingan. Bu omilning talaba psixologiyasi va natijalariga ta'sirini o'rganish muhim ahamiyatga ega.

3. Matematika ballari taqsimoti (Histogram)
Matematika fanidan olingan ballar qanday chastotada taqsimlanganini ko'rishimiz mumkin. Grafikda ko'rinib turibdiki, ko'pchilik talabalar o'rtacha ballar atrofida to'plangan.

📂 Ma'lumotlar tuzilmasi
Faylda quyidagi asosiy ustunlar mavjud:

Gender: Talaba jinsi.

EthnicGroup: Etnik kelib chiqishi.

ParentEduc: Ota-onasining ma'lumot darajasi.

MathScore, ReadingScore, WritingScore: Fanlar bo'yicha ballar.

WklyStudyHours: Haftalik dars qilish vaqti.

🚀 Ishga tushirish
Loyihani ishga tushirish uchun Jupyter Notebook-ni oching va quyidagi buyruqni bajaring:

Python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Ma'lumotni yuklash
df = pd.read_csv("Expanded_data_with_more_features.csv")
df.head()
Muallif: [Ismingiz]
Sana: 2026-yil, 16-aprel
