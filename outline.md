Men hozir yaratayotgan dasturimni tahlil qilib chiqishim kerak, bu yerga esa esdan chiqib ketmasligi uchun yozib qo'yaman :)

Men hozirda Geym kutubxonasining bir qismi bo'lmish grafika bilan ishlayapman, albatta u eng asosiy qismi, chunki u qismi o'yinning qanchalik sifatli chiqishiga javob beradi, shuning uchun shoshilmaymiz ;).
Nega aynan grafika? Chunki har qanday o'yin yaratilayotganda grafikadan foydalanamiz.
grafika hozirgi kunda yuqori sifatli bo'lib ketgan va hozirgi kunda sifatsiz grafikadan foydalanish uning samarasiz bo'lib chiqishiga olib keladi, shuning uchun uni qayta ko'rib chiqishga hojat qolmaydigan darajada yaxshiroq qilib yaratishimiz shart.
Grafikaning sifati kompyuter tezligiga katta ta'sir o'tkazadi, chunki bir vazifa 16 millisekund ichida kamida million marotaba amalga oshirilishi kerak, ya'ni 1 sekundda 60 marta shuncha vazifa bajaradi, eng yomoni uning o'lchami qanchalik katta bo'lsa tezlik shuncha kamayadi.
Biz esa eng yuqori o'lchamdagi grafika uchun tezkor bo'la oladigan yechimni ishlab chiqishimiz kerak.
Menda hozircha uni yaratish borasida dastlabki yo'nalish bor:
(python uchun)
* Birinchi o'rinda Python uchun eng yuqori tezlikda piksellarni manipulatsiya qiluvchi kutubxonani aniqlash,
buning uchun Pixel Manipulation sinov loyihasini ustida ishlashim kerak, ushbu test bizga qaysi usuldagi grafikadan foydalanish biz uchun samaraliroq ekanligini aniqlashga yordam beradi
* Ikkinchi o'rinda biz foydalanmoqchi bo'lgan usul haqiqatdan ham tezkormi yo'qmi, bizning talabimizga mos keladimi, shuni aniqlash kerak bo'ladi
* Uchinchi o'rinda biz yaratmoqchi bo'lgan kutubxona uchun rang tizimini ishlab chiqishimiz kerak
(yaxshisi bunaqa oldi qochdi gaplarni bas qilaylik)

Men allaqachon piksellarni manipulatsiya qilish sinovini yaratganman, lekin u hali ohiriga yetmagani bois keyingi qadamlarni tashashimga halaqit berayapti, shuning uchun uni qayta ko'rib chiqishim va uni 100% to'g'ri ishlashini ta'minlashim kerak bo'ladi.
Rang tizimiga keladigan bo'lsak baribir eng tezkori bu int tipidagi rang hisoblanadi, shuning uchun oddiy intdan foydalanganimiz yaxshiroq
Ranglarni yaratishga keladigan bo'lsak, har xil usulda yaratishni qo'llab quvvatlaydigan qilishimiz kerak, lekin eng asosiy usul float point usuli bo'lib qoladi

Xullas, adi badi deb o'tirmasdan ishni boshlayman, ya'ni Pixel Manipulation ustida ishlayman :)
Meni sinov natijalari unchalik quvontirmadi, chunki 2D matritsani yaratib keyin uni pygameda ko'rsatish uchun 460 ms vaqt kerak ekan, bu degani biz displeyni sekundiga faqat 2 marta yangilay olamiz degani, bu judayam sekin, shuning uchun biz juda ko'p pikselni o'zgartirishga to'g'ri kelganida matrix_2d dan foydalanamiz va faqat piksel o'zgargan joyini pixel_arrayga e'lon qilamiz, aks holda pixel_arrayni o'zi yetarli
