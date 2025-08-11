# Chess Online

Site de xadrez online inspirado no Chess.com.

## Como rodar localmente

### Backend
```bash
cd server
npm install
npm start
```

### Frontend
```bash
cd client
npm install
npm run dev
```

## Deploy

### 1. Subir para GitHub
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/chess-online.git
git push -u origin main
```

### 2. Deploy Backend no Render
- Vá para https://render.com
- Clique em "New Web Service"
- Conecte seu repositório
- Escolha o diretório `/server`
- Render detectará o `render.yaml` e fará o deploy automaticamente

### 3. Deploy Frontend no Vercel
- Vá para https://vercel.com
- Clique em "New Project"
- Conecte seu repositório
- Escolha o diretório `/client`
- Vercel detectará o `vercel.json` e fará o deploy
