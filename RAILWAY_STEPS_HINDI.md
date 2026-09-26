# Railway deploy (Hindi)

## 1) GitHub
- Naya repo ya purana Telegram-bot1
- Is folder ki SAARI files upload (bot.py, requirements.txt, ...)
- .env MAT upload

## 2) Railway
- railway.app → Login GitHub
- New Project → Deploy from GitHub → apna repo
- worker → Variables:

BOT_TOKEN=...
SOURCE_CHAT_ID=-1003415196836
TARGET_CHAT_ID=-1004389329782
ADMIN_IDS=8467972004,6312515331
BLOCKED_WORDS=spam,scam,fraud

## 3) Logs
Bot starting bulk+filter ...
Application started

## 4) Test
/start
/listblocks
/bulk 1 20

Agar Config missing → Variables incomplete
Agar Conflict → dusri jagah same bot band karo
