# Web API haqida bilib olamiz

## 1) Web API larni tushunish va ulardan foydalanish

![alt text](https://codetime.co.il/wp-content/uploads/2022/07/api.jpg)




Web API internetni o’z ichiga olgan global resourcelar tarmog’I - World Wide Webning bri qismi Web API’lar. Net Web  API sifatida ham tanilgan, shuning uchun Internet orqali maxsus turdagi resoucelari mavjud.

Oxirgi o’n yilda, bu o’zaro bog’langan API tarmog’I – yoki API web- o’sib borayotgan innovatsiya va biznesda texnologiyasing hayojondagi boshqaruvchisi kabi bo’lib tezlikda rivojlanib kelayabdi. Nima uchun Web API’lar bugungi kunda Internet tarmogʻida tezlikda o’zib borayogan, mashinaning divegetili kabi  asosiy ko’zga tashlangan omillardan biri bo’lib kelayabdi.

Bu savolga javob, va Firmlar Web API’lardan qanday daromad olishligini o’rganamiz, quyidagi tavsifta ko’rishingiz mumkin:

> [!NOTE]
>	Web API’ning asosiy xarakteriskasi bu firmalarning iste'molchilariga ta’sir qilish


## 2) API,Client, and Server

API bu ilovaning tarkibi qismi bo’lin bu orqali boshqa ilovalarga xizmat     ko’rsa-
tishni ta’minlab beradi. Xizmatni taqdim etuvchi dastur bu “ server “ deb nomlanadi va “ server “ dan foydalanayotgan foydalanuvchi “ client “ deb ataladi. “ Service “ bu har qanday vazifani bajaradigan , foydalanuvchi yoki ilova uchun foydali bo’lgan har qanday vazifa yoki topshiriq. Misol uchun, parvoz haqidagi ma’lumotlar ilovasi parvoz vaqtida xizmat (service) ko’rsatish sifatida foydalaniladi masalan parvoz vaqtida turium ilovasidan foydalanishligi mumkin. Parvoz ma’lumotlari bu server ilovasi  va turistik dastur( yoki dasturdan foydalanayotgan shaxs) client(mijoz) xisoblanadi.


<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:700/0*PSxcvFBVaufSCuwt.png" >
</p>
Web API’larni ustida amaliy tajriblar o’tkazish uchun [Web API'lar darsligiga](https://docs.appian.com/suite/help/20.1/Web_API_Tutorial.html) tashrif buyuring


Web API-lar nima degan savolga yanada ochiqroq javob bersak?

Qachonki ilova clientga internet orqali biror xizmat taklif qilsa, bu xizmat
" Web Xizmat " deb nomlanadi. Bunday xizmatning API’si " Web API " deb
Nomlanadi.


### Qoidalarni aniqlash.

`Qoidalarni aniqlash` - Xizmatning Web API – bu xizmatga kirish uchun client         ilovalari amal qilishlik kerak bo’lgan qoidalarni aniqlaydigan(belgilaydigan) component

### Web API

`Web API` - Web Api World Wide web( butun jahon internet) qismi bo’lib URL deb nomlash orqali bilib olish mumkin, Butun dunyo URL-larining to’plami API veb yoki  API vebsiteda tanilgan.

### Request and Response

`Request and Response` - Servicega kirish uchun client message yoki request yuboradi servicening API’ga, API yo’naltiradi requestni service applicationga, bu xizmatni bajaradi va qayta Response yuboradi. API resourcelari internetda bo’lganligi uchun messagelar odatda HTTP protocolidan foydalanib yuboriladi.

### Interface Only  

`Interface Only` - Web API-lar odatda interfeyslardir . Ular server application va cclient application o’rtasidagi aloqalarni belgilaydi. Client bilishligi shart emas bo’ladi ichki xizmatlarni ya’ni API ASP.Net yoki Node.js yoki Python tillarida yozilgan  yoki yo’qligini. Natijada firmalar o’zlarining API va xizmatlarini o’zlari uchun strategik ma’noga ega bo’lgan tillarda yaratishda erkindirlar va ushbu mavhum tilning agnostic interfeysi – APIdan foydalanadilar .


Vedio orqali o'rganish [yuklanmadi]()

![alt text](https://media.geeksforgeeks.org/wp-content/uploads/20230216170349/What-is-an-API.png)


## 3)Web API-larning muxim xususiyatlari

Web API - lar tarmoq orqali ishlaganligi uchun va ko’pincha bir vaqtning o’zida 
Minglab so’rovlarni yuboradigan bir nechta clientlarni ko’rib chiqadi, shu vaqtda ular moslashvchan, tez, xavsiz, boshqaruvchan va osan foydalanildigan bo’lishligi kerak bo’ladi. Biz pastagi xususiyatlar bilan muhokama qilamiz.

:::tip
•	Web-APIlar ishlab chiquvchiga qo’lay bo’lishligi kerak bo’ladi. Web API – larning ma’lum turlari mashhur bo’lishiga eng katta sababi – ulardan foydalanish qulayligi. Ishlab chiqaruvchilar o’zlarining client ilovalariga bir necha qator code qo’shishlari kerak.

•	Veb API-lar turli mijozlarning ehtiyojlarini qondirish uchun etarlicha moslashuvchan bo'lishi kerak. Barcha clientlarga servicedan bir xil ma’lumot kerak emas 

•	Web APIlar clientlarga kerakli ma’lumotlarni so’rashga imkon beradigan darajada tuzilgan bo’lishlik kerak,masalan. Natijalarni filter qilishda Header va path parameterlaridan foyldalanishda

•	Web API lar kengaytirilgan bo’lishligi kerak. Internet orqali foydalanilgan API odatda minglab so’rov yuboradi Shuning uchun API ish faoliyatini yaxshilashga intilayotgan firmalar Gravitee.io shlyuzi kabi API shlyuzlaridan foydalanadilar, ular 20 000 dan ortiq bir vaqtda qo'ng'iroqlarni(so’rovlar) amalga oshirishi mumkin.

•	Veb API-lar boshqarilishi kerak. Bitta API boshqarish oson. Biroq, agar firma bir nechta API-larni ishlatsa, API boshqaruv tizimi zarur. Cockpit kabi vositalar Web API dizaynerlariga oʻz veb-APIlarini bitta qulay interaktiv boshqaruv panelidan boshqarishga yordam beradi
:::

### endi [FOLLOW ](https://github.com/fayzullohblog)  bosing 




[![My Skills](https://skillicons.dev/icons?i=python,django,postgresql,git,aws,html,css)](https://skillicons.dev)


