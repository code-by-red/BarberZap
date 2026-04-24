# Instruções de Deploy - BarberZap

## 🚀 Passos para subir no GitHub

### 1. Instalar Git
- Execute o instalador: `C:\Users\mauri\Downloads\Git-2.54.0-64-bit.exe`
- Reinicie o PowerShell após instalação

### 2. Comandos Git (execute após instalar)
```bash
# Inicializar repositório
git init

# Adicionar todos os arquivos
git add .

# Primeiro commit
git commit -m "primeiro commit - BarberZap sistema de agendamento"

# Configurar branch main
git branch -M main

# Conectar ao repositório remoto
git remote add origin https://github.com/code-by-red/BarberZap.git

# Enviar arquivos para GitHub
git push -u origin main
```

### 3. Deploy na Vercel
1. Acesse [vercel.com](https://vercel.com)
2. Conecte sua conta GitHub
3. Importe o repositório BarberZap
4. O deploy será automático com o arquivo `vercel.json`

## 📁 Arquivos prontos para deploy:
- ✅ index.html (página principal)
- ✅ style.css (estilos)
- ✅ script.js (funcionalidades)
- ✅ favicon-updated.svg (ícone)
- ✅ package.json (configuração)
- ✅ vercel.json (deploy automático)
- ✅ README.md (documentação)
- ✅ .gitignore (arquivos ignorados)

## 🔗 Links úteis:
- GitHub: https://github.com/code-by-red/BarberZap
- Vercel: https://vercel.com
- Site após deploy: https://barbercode.vercel.app
