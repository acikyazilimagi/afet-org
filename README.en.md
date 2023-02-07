# Earthquake Relief Project

We collect all calls for help from different sources such as Twitter, Instagram, Whatsapp and various websites and refine this data into meaningful, refined data to be used in the field. Our aim is to help relevant organizations and NGOs by using information technologies and to provide an open data platform in times of disaster.

## Data Entry

- https://www.depremyardim.com/

## Disaster Map Project

### Broadcast addresses

- https://afetharita.com/
- API: https://api.afetharita.com/

#### General information and links

- [Discord](https://discord.gg/37MHpdPxh4)
- [Design process](https://www.figma.com/file/sctw6xtcdoFOfmE0gC97Ft/Deprem-Yard%C4%B1m?node-id=0%3A1&t=FUHjVXfXqqXLN5js-1) (Figma)
- [Trello Invitation to Join](https://trello.com/invite/b/d1rYoCUL/ATTId7774aa53af7d5ed9df79d8c32d0f6c2F7837B42/it-yardim) (Trello)
- [Trello](https://trello.com/b/d1rYoCUL/afet-harita)
- [GitHub Repositories](https://github.com/orgs/acikkaynak/repositories)
  - [afetharita.com-frontend](https://github.com/acikkaynak/deprem-yardim-frontend)
    Technology and Systems Used:
    - Next.js, React, Leaflet, Vercel
  - [afetharita.com-backend](https://github.com/acikkaynak/deprem-yardim-backend)
    - Python (Django), Postgres (PostgreSQL), Redis, AWS (Elastic Load Balancer, ECS, AWS Fargate), OpenAI (translation of visuals to text)
  - [beniyiyim.com-frontend](https://github.com/acikkaynak/ben-iyiyim-frontend)
    - Google Forms, Spreadsheet
  - [afetharita.com-data](https://github.com/acikkaynak/deprem-yardim-data)
    - To be updated...
  - [afetharita.com-whatsapp-integration](https://github.com/acikkaynak/deprem-yardim-whatsapp)
    - To be updated...
  - [afetharita.com-twitter-bot](https://github.com/acikkaynak/afet-yardim-twitter-bot)
    The bot to be written to RT to the specified Twit IDs
    - Go
- [Keyword List for Twitter data extraction](https://docs.google.com/spreadsheets/d/1_w1akARJIKzCxMQnlv9ZObM7m-yXu_XJn-_SvjR6j74/edit)
- [Contact and skill information for those who can help](https://docs.google.com/spreadsheets/d/1bZ49eLf2ymisuvPwdOFPmcbasnOVJr5-swLGvhySIHI)
- [Workflow](https://excalidraw.com/#room=0571f83dc3c3d9eb9fb8,IdGc97dCxjdYsVsZ2NTEiQ)
- Data
  - [Some withdrawn Tweets](https://docs.google.com/spreadsheets/d/1GX_37xMMvU-lcMz4XI0uLYPUV6LiZtn9EZOGSwqPuZA)
  - [depremyardim.com-json-data](https://www.depremyardim.com/json.php)
  - [Data Collectors](https://docs.google.com/spreadsheets/d/11oiJTFlDLKd7Ykuib4q4J9UCZ3QvB3SgCTrrXISz484/edit) (Google Spradsheets)

### Technology and Systems Used

- **Frontend:** Next.js, React / Deployment: Vercel
- Backend:\*\* Python - Django, AWS (Elastic Load Balancer, ECS, AWS Fargate), OpenAI (Visualization to text), Go
- Database:\*\* Postgres (PostgreSQL), Redis
- **Map Source:** Leaflet
- **Data Scraping:** Twitter, Whatsapp, Telegram, depremyardim.com

## I'm Fine Project

### Broadcast addresses

- http://beniyiyim.com/

#### General information and links

- [Trello](https://trello.com/b/nSajc3v7/ben-i%CC%87yiyim-app)

### Technology and Systems Used

- Google Form, Google Docs (Form for status reporting with simple inputs)

## Aid Network Project

### Broadcast addresses

- Not yet determined!

### General information and links

- [Workflow](https://excalidraw.com/#room=b09286c9041a10c59719,JnU6aU-5IAvXhmTEkYW2IA)
- [Design process](https://www.figma.com/file/ggMF14osmhGOvKvS0VKuvQ/Yard%C4%B1m-A%C4%9F%C4%B1-App?node-id=0%3A1&t=lnWdXzRpwUmBurZd-1) (Figma)
- [Trello Davet](https://trello.com/invite/b/cU4C34JQ/ATTI6f42a0a0396fdb62e570d423d8fc3e930962B558/deprem-yardim-agis)
- [Trello](https://trello.com/b/RzM8Tia3/yard%C4%B1m-agi-app)
- Github
  - [help-agi-flutter](https://github.com/acikkaynak/yardim-agi-flutter)
  - [help-agi-firebase](https://github.com/acikkaynak/yardim-agi-firebase)

### Technology and Systems Used

- Flutter (Web)
- Google Firebase & Lambda (Cloud Function) & Firestore

## 3rd Party enhancements

#### Image to Text Address OCR

Library for transcribing the address information in the image

- Technologies Used: Python
  - [Github Repo](https://github.com/cobanov/deprem-ocr) [(Live)](https://huggingface.co/spaces/mertcobanov/deprem-ocr)
