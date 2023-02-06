# Deprem Yardım

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
- [Twitter veri çekme için Keyword (Anahtar Kelime) Listesi](https://docs.google.com/spreadsheets/d/1_w1akARJIKzCxMQnlv9ZObM7m-yXu_XJn-_SvjR6j74/edit)
- [Yardım edebilecek olanların iletişim ve skill bilgileri](https://docs.google.com/spreadsheets/d/1bZ49eLf2ymisuvPwdOFPmcbasnOVJr5-swLGvhySIHI)
- [Workflow](https://excalidraw.com/#room=0571f83dc3c3d9eb9fb8,IdGc97dCxjdYsVsZ2NTEiQ)
- Veriler
  - [Bazı çekilen Tweetler](https://docs.google.com/spreadsheets/d/1GX_37xMMvU-lcMz4XI0uLYPUV6LiZtn9EZOGSwqPuZA)
  - [depremyardim.com-json-data](https://www.depremyardim.com/json.php)
  - [Veri Toplayıcılar](https://docs.google.com/spreadsheets/d/11oiJTFlDLKd7Ykuib4q4J9UCZ3QvB3SgCTrrXISz484/edit) (Google Spradsheets)

### Kullanılan Teknoloji ve Sistemler
- **Frontend:**  Next.js, React / Deployment: Vercel
- **Backend:** Python  - Django, AWS(Elastic Load Balancer, ECS, AWS Fargate), OpenAI (Görsellerin metine çevirilmesi)
- **Database:** Postgres (PostgreSQL), Redis
- **Map Source:** Leaflet
- **Data Scraping:** Twitter, Whatsapp, Telegram, depremyardim.com

## Ben İyiyim Projesi

### Yayına alınan adresler
- http://beniyiyim.com/

### Kullanılan Teknoloji ve Sistemler

- Google Form, Google Docs (Basit inputlardan oluşan durum bildirimi için form)

## 3.Parti geliştirmeler

### Image to Text Adres OCR
Resimde yer alan adres bilgilerini yazıya çevirme kütüphanesi
- Kullanılan Teknolojiler: Python
  - [Github Repo](https://github.com/cobanov/deprem-ocr) [(Canlı)](https://huggingface.co/spaces/mertcobanov/deprem-ocr)
