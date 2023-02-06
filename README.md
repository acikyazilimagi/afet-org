# Deprem Yardım Projesi

Twitter, Instagram, Whatsapp ve çeşitli web siteleri gibi farklı kaynaklardan gelen tüm yardım çağrılarını topluyoruz ve bu veriyi sahada kullanılmak üzere anlamlı, rafine hale getiriyoruz. Amacımız bilgi teknolojilerini kullanarak ilgili kurum ve STK'lara yardımcı olmak ve afet zamanlarında açık bir veri platformu sağlamak.


## Veri Girişi
- https://www.depremyardim.com/

## Afet Harita Projesi

### Yayına alınan adresler
- https://afetharita.com/
- API: https://api.afetharita.com/

### Genel bilgilendirme ve bağlantılar

- [Discord](https://discord.gg/37MHpdPxh4)
- [Tasarım süreci](https://www.figma.com/file/sctw6xtcdoFOfmE0gC97Ft/Deprem-Yard%C4%B1m?node-id=0%3A1&t=FUHjVXfXqqXLN5js-1) (Figma)
- [Trello Katılım Daveti](https://trello.com/invite/b/d1rYoCUL/ATTId7774aa53af7d5ed9df79d8c32d0f6c2F7837B42/it-yardim) (Trello)
- [Trello](https://trello.com/b/d1rYoCUL/afet-harita)
- [GitHub Depoları](https://github.com/orgs/acikkaynak/repositories)
  - [afetharita.com-frontend](https://github.com/acikkaynak/deprem-yardim-frontend)
    Kullanılan Teknoloji ve Sistemler:
    - Next.js, React, Leaflet, Vercel
  - [afetharita.com-backend](https://github.com/acikkaynak/deprem-yardim-backend)
    - Python (Django), Postgres (PostgreSQL), Redis, AWS (Elastic Load Balancer, ECS, AWS Fargate), OpenAI (Görsellerin metine çevirilmesi)
  - [beniyiyim.com-frontend](https://github.com/acikkaynak/ben-iyiyim-frontend)
    - Google Forms, Spreadsheet
  - [afetharita.com-data](https://github.com/acikkaynak/deprem-yardim-data)
    - Güncellenecek..
  - [afetharita.com-whatsapp-entegrasyon](https://github.com/acikkaynak/deprem-yardim-whatsapp)
    - Güncellenecek..
  - [afetharita.com-twitter-bot](https://github.com/acikkaynak/afet-yardim-bot)
  Belirlenmiş olan Twit ID 'lerine RT atmak için yazılacak bot
    - Go
- [Twitter veri çekme için Keyword (Anahtar Kelime) Listesi](https://docs.google.com/spreadsheets/d/1_w1akARJIKzCxMQnlv9ZObM7m-yXu_XJn-_SvjR6j74/edit)
- [Yardım edebilecek olanların iletişim ve skill bilgileri](https://docs.google.com/spreadsheets/d/1bZ49eLf2ymisuvPwdOFPmcbasnOVJr5-swLGvhySIHI)
- [Workflow](https://excalidraw.com/#room=0571f83dc3c3d9eb9fb8,IdGc97dCxjdYsVsZ2NTEiQ)
- Veriler
  - [Bazı çekilen Tweetler](https://docs.google.com/spreadsheets/d/1GX_37xMMvU-lcMz4XI0uLYPUV6LiZtn9EZOGSwqPuZA)
  - [depremyardim.com-json-data](https://www.depremyardim.com/json.php)
  - [Veri Toplayıcılar](https://docs.google.com/spreadsheets/d/11oiJTFlDLKd7Ykuib4q4J9UCZ3QvB3SgCTrrXISz484/edit) (Google Spradsheets)

### Kullanılan Teknoloji ve Sistemler
- **Frontend:**  Next.js, React / Deployment: Vercel
- **Backend:** Python  - Django, AWS(Elastic Load Balancer, ECS, AWS Fargate), OpenAI (Görsellerin metine çevirilmesi), Go
- **Database:** Postgres (PostgreSQL), Redis
- **Map Source:** Leaflet
- **Data Scraping:** Twitter, Whatsapp, Telegram, depremyardim.com

## Ben İyiyim Projesi

### Yayına alınan adresler
- http://beniyiyim.com/


### Genel bilgilendirme ve bağlantılar
- [Trello](https://trello.com/b/nSajc3v7/ben-i%CC%87yiyim-app)


### Kullanılan Teknoloji ve Sistemler
- Google Form, Google Docs (Basit inputlardan oluşan durum bildirimi için form)

## Yardım Ağı Projesi

### Yayına alınan adresler
- Henüz belirlenmedi!

### Genel bilgilendirme ve bağlantılar
- [Workflow](https://excalidraw.com/#room=b09286c9041a10c59719,JnU6aU-5IAvXhmTEkYW2IA)
- [Tasarım süreci](https://www.figma.com/file/ggMF14osmhGOvKvS0VKuvQ/Yard%C4%B1m-A%C4%9F%C4%B1-App?node-id=0%3A1&t=lnWdXzRpwUmBurZd-1) (Figma)
- [Trello Davet](https://trello.com/invite/b/cU4C34JQ/ATTI6f42a0a0396fdb62e570d423d8fc3e930962B558/deprem-yardim-agis)
- [Trello](https://trello.com/b/RzM8Tia3/yard%C4%B1m-agi-app)
- Github
  - [yardim-agi-flutter](https://github.com/acikkaynak/yardim-agi-flutter)
  - [yardim-agi-firebase](https://github.com/acikkaynak/yardim-agi-firebase)

### Kullanılan Teknoloji ve Sistemler
- Flutter (Web)
- Google Firebase & Lambda (Cloud Function) & Firestore

## 3.Parti geliştirmeler

### Image to Text Adres OCR
Resimde yer alan adres bilgilerini yazıya çevirme kütüphanesi
- Kullanılan Teknolojiler: Python
  - [Github Repo](https://github.com/cobanov/deprem-ocr) [(Canlı)](https://huggingface.co/spaces/mertcobanov/deprem-ocr)
