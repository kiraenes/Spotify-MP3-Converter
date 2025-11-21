🇵🇹 README COMPLETO (PT-PT)
🎧 Spotify MP3 Converter

Converte playlists, álbuns e músicas do Spotify para MP3 usando o Google Colab.
Os utilizadores não precisam de editar código — apenas carregam o seu keys.env e, opcionalmente, cookies.txt.

▶️ Abrir no Google Colab


🟩 1. Como obter as API Keys do Spotify

Para ler músicas/playlists/álbuns, precisas de API keys.

1️⃣ Abrir o Spotify Developer Dashboard

<a href="https://developer.spotify.com/dashboard" target="_blank"> <img src="https://img.shields.io/badge/Abrir%20Spotify%20Dashboard-1DB954?style=for-the-badge&logo=spotify&logoColor=white"/> </a>

Faz login com a tua conta Spotify.

2️⃣ Criar uma nova App

Clica Create an App

Dá um nome à app (qualquer coisa serve)

Aceita os termos

Cria a app

3️⃣ Obter o Client ID e Client Secret

Na tua app vais encontrar:

Client ID
Client Secret


⚠️ Nunca partilhes o Client Secret.

🟥 2. Criar o ficheiro keys.env

Cria um ficheiro chamado keys.env com este conteúdo:

SPOTIFY_CLIENT_ID=O_TEUP_CLIENT_ID
SPOTIFY_CLIENT_SECRET=O_TEUP_CLIENT_SECRET


⚠️ Sem aspas
⚠️ Sem redirect URI
⚠️ Exatamente como acima
⚠️ Não envies este ficheiro para o GitHub

🟨 3. Como obter o ficheiro cookies.txt (Opcional)

O cookies.txt só é necessário em playlists muito grandes (1000+ músicas) ou se o YouTube bloquear:

→ “Sign in to confirm you're not a bot”

Caso contrário → não uses cookies.

1️⃣ Instalar a extensão “Get cookies.txt” (Chrome)

<a href="https://chromewebstore.google.com/search/get%20cookies.txt" target="_blank"> <img src="https://img.shields.io/badge/Abrir%20Chrome%20Webstore-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"/> </a>

2️⃣ Exportar cookies do YouTube

Abre o YouTube (logado)

Clica no ícone da extensão

Escolhe Export cookies to cookies.txt

Um ficheiro será criado no teu computador

⚠️ Cuidado: contém informações privadas
⚠️ Nunca o partilhes

🟦 4. Usar o Colab (muito simples)

1️⃣ Abrir o notebook (botão no início)

2️⃣ Fazer upload de keys.env

Quando o Colab pedir:

📁 Faça upload do arquivo keys.env com suas chaves do Spotify:


Seleciona o teu keys.env.

3️⃣ Fazer upload de cookies.txt (Opcional)

Se não precisares → clica Cancelar.

4️⃣ Colar o link do Spotify

O Colab aceita:

Playlists

Álbuns

Músicas individuais

Exemplos:

[https://open.spotify.com/playlist/...](https://open.spotify.com/playlist/37i9dQZF1DZ06evO3GSvAY?si=k_Igr0lMSwikI2SAzjxupg)
[https://open.spotify.com/album/...](https://open.spotify.com/intl-pt/album/6KLrnVqUhPpX4IzgHgsJTg?si=wiH25jU5S4Gh_wDE92awNQ)
[https://open.spotify.com/track/...](https://open.spotify.com/intl-pt/track/3HfKlhohNNTLIv2t9uvmzz?si=5700c37948694aa0)

5️⃣ Esperar o processo terminar

O Colab mostra:

🎵 Baixando 1º: Nome - Artista

6️⃣ Receber o ZIP final

Quando terminar:

✅ Downloads completos! ZIP pronto.


O ZIP é descarregado automaticamente.

7️⃣ Nota importante

O Colab apaga tudo ao reiniciar, por isso:

✔ tens de enviar keys.env sempre
✔ tens de enviar cookies.txt se estiveres a usar

🇬🇧 README COMPLETE (ENGLISH VERSION)
🎧 Spotify MP3 Converter

Convert Spotify playlists, albums and tracks to MP3 using Google Colab.
Users do not need to edit any code — just upload their own keys.env and optional cookies.txt.

▶️ Open in Google Colab

🟩 1. How to Get Spotify API Keys

1️⃣ Open Spotify Developer Dashboard

<a href="https://developer.spotify.com/dashboard" target="_blank"> <img src="https://img.shields.io/badge/Open%20Spotify%20Dashboard-1DB954?style=for-the-badge&logo=spotify&logoColor=white"/> </a>

Log in with your Spotify account.

2️⃣ Create an app

Click Create an App

Choose any name

Accept the terms

Create the app

3️⃣ Copy your credentials

You will see:

Client ID
Client Secret


⚠️ Do NOT share your Client Secret.

🟥 2. Create the keys.env file

Create a file named keys.env with:

SPOTIFY_CLIENT_ID=YOUR_CLIENT_ID
SPOTIFY_CLIENT_SECRET=YOUR_CLIENT_SECRET


⚠️ No quotes
⚠️ No redirect URI
⚠️ Exactly like this
⚠️ Do NOT upload this to GitHub

🟨 3. How to Get cookies.txt (Optional)

This file is only needed if:

Your playlist is very large

YouTube blocks you with
“Sign in to confirm you're not a bot”

Otherwise → skip it.

1️⃣ Install “Get cookies.txt” extension

<a href="https://chromewebstore.google.com/search/get%20cookies.txt" target="_blank"> <img src="https://img.shields.io/badge/Open%20Chrome%20Webstore-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"/> </a>

2️⃣ Export YouTube cookies

Open YouTube (logged in)

Click the extension

Select Export cookies to cookies.txt

Save the file

⚠️ Contains sensitive login info

🟦 4. How to Use the Colab Notebook

1️⃣ Open the notebook

2️⃣ Upload keys.env

When prompted:

Upload the keys.env file


Upload it.

3️⃣ Upload cookies.txt (optional)

If not needed → click Cancel.

4️⃣ Paste your Spotify link

Accepted:

Playlist
Album
Track


Examples:

[https://open.spotify.com/playlist/...](https://open.spotify.com/playlist/37i9dQZF1DZ06evO3GSvAY?si=k_Igr0lMSwikI2SAzjxupg)
[https://open.spotify.com/album/...](https://open.spotify.com/intl-pt/album/6KLrnVqUhPpX4IzgHgsJTg?si=wiH25jU5S4Gh_wDE92awNQ)
[https://open.spotify.com/track/...](https://open.spotify.com/intl-pt/track/3HfKlhohNNTLIv2t9uvmzz?si=5700c37948694aa0)

5️⃣ Wait for downloads

6️⃣ Download the ZIP file

The Colab automatically downloads it.

7️⃣ Reminder: Colab resets everything

So you must re-upload:

✔ keys.env
✔ cookies.txt (if used)

