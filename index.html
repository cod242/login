<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Klawy | Sohbet ve Topluluk Platformu</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <style>
        :root {
            --background-primary: #1e2124;
            --background-secondary: #2c2f33;
            --text-normal: #e0e1e2;
            --text-muted: #8e9297;
            --accent-color: #7289da;
            --input-background: #18191c;
            --error-color: #ed4245;
            --green-button: #43b581;
        }

        body {
            margin: 0;
            padding: 0;
            font-family: 'Whitney', 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #000000;
            color: var(--text-normal);
            height: 100vh;
            overflow: hidden;
        }

        /* Genel Konteyner */
        .page {
            display: none;
            height: 100vh;
            width: 100vw;
            overflow: auto;
        }

        .page.active {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Giriş Sayfası */
        .login-container {
            background-color: var(--background-primary);
            border-radius: 10px;
            padding: 40px;
            width: 400px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            text-align: center;
        }

        .login-form h2 {
            font-size: 28px;
            margin-bottom: 10px;
            color: var(--accent-color);
            text-shadow: 0 0 10px rgba(114, 137, 218, 0.5);
        }

        .login-form p {
            color: var(--text-muted);
            font-size: 16px;
            margin-bottom: 30px;
        }

        .login-form label {
            display: block;
            font-size: 14px;
            color: var(--text-muted);
            text-transform: uppercase;
            margin-bottom: 8px;
            text-align: left;
        }

        .login-form input {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            background-color: var(--input-background);
            border: 1px solid #40444b;
            border-radius: 8px;
            color: var(--text-normal);
            font-size: 14px;
            box-sizing: border-box;
            transition: border-color 0.3s;
        }

        .login-form input:focus {
            border-color: var(--accent-color);
            outline: none;
        }

        .login-form a {
            color: var(--accent-color);
            text-decoration: none;
            font-size: 12px;
            display: block;
            text-align: left;
            margin-bottom: 20px;
        }

        .login-form a:hover {
            text-decoration: underline;
        }

        .login-form button {
            width: 100%;
            padding: 12px;
            background-color: var(--accent-color);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .login-form button:hover {
            background-color: #5a6eb2;
            transform: scale(1.05);
            box-shadow: 0 0 15px rgba(114, 137, 218, 0.5);
        }

        .register-link {
            font-size: 14px;
            color: var(--text-muted);
            margin-top: 20px;
        }

        .register-link a {
            color: var(--accent-color);
            text-decoration: none;
            cursor: pointer;
        }

        .register-link a:hover {
            text-decoration: underline;
        }

        .error-message {
            color: var(--error-color);
            font-size: 14px;
            margin-bottom: 20px;
            display: none;
        }

        /* Kayıt Sayfası */
        .register-container {
            background-color: var(--background-primary);
            border-radius: 10px;
            padding: 40px;
            width: 400px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.5);
            text-align: center;
        }

        .register-form h2 {
            font-size: 28px;
            margin-bottom: 10px;
            color: var(--accent-color);
            text-shadow: 0 0 10px rgba(114, 137, 218, 0.5);
        }

        .register-form p {
            color: var(--text-muted);
            font-size: 16px;
            margin-bottom: 30px;
        }

        .register-form label {
            display: block;
            font-size: 14px;
            color: var(--text-muted);
            text-transform: uppercase;
            margin-bottom: 8px;
            text-align: left;
        }

        .register-form input {
            width: 100%;
            padding: 12px;
            margin-bottom: 20px;
            background-color: var(--input-background);
            border: 1px solid #40444b;
            border-radius: 8px;
            color: var(--text-normal);
            font-size: 14px;
            box-sizing: border-box;
            transition: border-color 0.3s;
        }

        .register-form input:focus {
            border-color: var(--accent-color);
            outline: none;
        }

        .register-form button {
            width: 100%;
            padding: 12px;
            background-color: var(--accent-color);
            color: white;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .register-form button:hover {
            background-color: #5a6eb2;
            transform: scale(1.05);
            box-shadow: 0 0 15px rgba(114, 137, 218, 0.5);
        }

        .login-link {
            font-size: 14px;
            color: var(--text-muted);
            margin-top: 20px;
        }

        .login-link a {
            color: var(--accent-color);
            text-decoration: none;
            cursor: pointer;
        }

        .login-link a:hover {
            text-decoration: underline;
        }

        /* Ana Arayüz (Discord Tarzı) */
        .dashboard-page {
            flex-direction: column;
            justify-content: flex-start;
            height: 100vh;
        }

        .top-bar {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            background-color: var(--background-secondary);
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 30px;
            z-index: 10;
        }

        .top-bar .left span {
            margin-left: 10px;
        }

        .top-bar .right i {
            margin-left: 15px;
            color: var(--text-muted);
            cursor: pointer;
        }

        .top-bar .right i:hover {
            color: var(--text-normal);
        }

        .container {
            display: grid;
            grid-template-columns: 72px 240px 1fr 240px;
            grid-template-areas: "servers channels chat members";
            height: calc(100vh - 50px);
            margin-top: 50px;
            width: 100%;
        }

        .servers {
            grid-area: servers;
            background-color: #202225;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 10px 0;
        }

        .server-icon {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-bottom: 10px;
            background-color: var(--background-secondary);
            position: relative;
            cursor: pointer;
        }

        .server-icon.active::before {
            content: '';
            position: absolute;
            left: -10px;
            top: 50%;
            transform: translateY(-50%);
            width: 8px;
            height: 20px;
            background-color: var(--text-normal);
            border-radius: 4px;
        }

        .channels {
            grid-area: channels;
            background-color: var(--background-secondary);
            padding: 10px;
        }

        .channels h2 {
            font-size: 16px;
            margin: 10px 0;
        }

        .channel-category h3 {
            color: var(--text-muted);
            font-size: 12px;
            text-transform: uppercase;
            margin: 10px 0;
        }

        .channel-category ul {
            list-style: none;
            padding: 0;
        }

        .channel-category li {
            padding: 5px 0;
            color: var(--text-muted);
            cursor: pointer;
        }

        .channel-category li:hover {
            color: var(--text-normal);
        }

        .chat {
            grid-area: chat;
            background-color: var(--background-primary);
            display: flex;
            flex-direction: column;
        }

        .messages {
            flex: 1;
            padding: 20px;
            overflow-y: auto;
        }

        .message {
            display: flex;
            margin-bottom: 20px;
        }

        .avatar {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
            background-color: #40444b;
        }

        .message-content h4 {
            margin: 0;
            font-size: 14px;
        }

        .timestamp {
            font-size: 12px;
            color: var(--text-muted);
            margin-left: 5px;
        }

        .message-content p {
            margin: 5px 0 0 0;
        }

        .call-controls {
            padding: 10px;
            background-color: var(--background-secondary);
            display: flex;
            justify-content: space-around;
            align-items: center;
        }

        .call-controls button {
            padding: 8px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
        }

        .call-controls .voice-btn {
            background-color: #5865f2;
            color: white;
        }

        .call-controls .video-btn {
            background-color: #43b581;
            color: white;
        }

        .call-controls .screen-share-btn {
            background-color: #faa61a;
            color: white;
        }

        .call-controls button:hover {
            transform: scale(1.1);
            box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
        }

        .input-area {
            padding: 10px;
            background-color: var(--background-secondary);
            display: flex;
            align-items: center;
        }

        .input-area i {
            margin: 0 10px;
            color: var(--text-muted);
        }

        .input-area input {
            flex: 1;
            padding: 10px;
            border: none;
            background-color: #40444b;
            color: var(--text-normal);
            border-radius: 5px;
        }

        .members {
            grid-area: members;
            background-color: var(--background-secondary);
            padding: 10px;
            position: relative;
        }

        .user-profile {
            background-color: #292b2f;
            padding: 20px;
            text-align: center;
            position: absolute;
            top: 10px;
            width: 200px;
            border-radius: 5px;
        }

        .user-profile img {
            width: 80px;
            height: 80px;
            border-radius: 50%;
        }

        .user-profile h3 {
            margin: 10px 0 5px;
        }

        .user-profile p {
            color: var(--text-muted);
            font-size: 12px;
            margin: 0 0 10px;
        }

        .user-profile button {
            padding: 8px 15px;
            margin: 0 5px;
            border: none;
            border-radius: 3px;
            cursor: pointer;
            font-weight: bold;
        }

        .user-profile .join {
            background-color: var(--green-button);
            color: white;
        }

        .user-profile .decline {
            background-color: #747f8d;
            color: white;
        }
    </style>
</head>
<body>
    <!-- Giriş Sayfası -->
    <div class="page login-page" id="loginPage">
        <div class="login-container">
            <div class="login-form">
                <h2>Merhaba, Hoş Geldin!</h2>
                <p>Hesabına giriş yap ve hemen sohbete başla!</p>
                <div class="error-message" id="loginErrorMessage">Aradığınız hesap bulunamadı!</div>
                <label>E-POSTA VEYA TELEFON</label>
                <input type="text" id="emailOrPhone" placeholder="E-posta veya telefon numarası" required>
                <label>ŞİFRE</label>
                <input type="password" id="password" placeholder="Şifreni gir" required>
                <a href="#">Şifremi unuttum, ne yapacağım?</a>
                <button onclick="handleLogin()">Hemen Giriş Yap</button>
                <div class="register-link">
                    Henüz üye değil misin? <a onclick="showPage('registerPage')">Hemen Kaydol</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Kayıt Sayfası -->
    <div class="page register-page" id="registerPage">
        <div class="register-container">
            <div class="register-form">
                <h2>Hemen Kaydol!</h2>
                <p>Yeni bir hesap oluştur ve topluluğa katıl!</p>
                <div class="error-message" id="registerErrorMessage">Lütfen tüm alanları doldur!</div>
                <label>KULLANICI ADI</label>
                <input type="text" id="username" placeholder="Kullanıcı adını gir" required>
                <label>E-POSTA</label>
                <input type="email" id="email" placeholder="E-posta adresini gir" required>
                <label>ŞİFRE</label>
                <input type="password" id="registerPassword" placeholder="Şifreni oluştur" required>
                <button onclick="handleRegister()">Kaydol ve Başla!</button>
                <div class="login-link">
                    Zaten bir hesabın var mı? <a onclick="showPage('loginPage')">Giriş Yap</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Ana Arayüz Sayfası -->
    <div class="page dashboard-page" id="dashboardPage">
        <header class="top-bar">
            <div class="left">
                <i class="fas fa-bars"></i>
                <span id="currentUser"></span>
            </div>
            <div class="right">
                <i class="fas fa-phone"></i>
                <i class="fas fa-video"></i>
                <i class="fas fa-search"></i>
                <i class="fas fa-cog"></i>
            </div>
        </header>
        <div class="container">
            <div class="servers">
                <div class="server-icon active"><img src="https://placehold.co/50x50" alt="Server 1"></div>
                <div class="server-icon"><img src="https://placehold.co/50x50" alt="Server 2"></div>
                <div class="server-icon"><img src="https://placehold.co/50x50" alt="Server 3"></div>
            </div>
            <div class="channels">
                <h2>Klawy Ekibi</h2>
                <div class="channel-category">
                    <h3>METİN KANALLARI</h3>
                    <ul>
                        <li># genel</li>
                        <li># sohbet</li>
                    </ul>
                </div>
                <div class="channel-category">
                    <h3>SES KANALLARI</h3>
                    <ul>
                        <li>Genel Ses</li>
                        <li>Oyun</li>
                    </ul>
                </div>
            </div>
            <div class="chat">
                <div class="messages" id="messages">
                    <div class="message">
                        <div class="avatar"></div>
                        <div class="message-content">
                            <h4 id="initialUser">Kullanıcı1 <span class="timestamp">Bugün 14:12</span></h4>
                            <p>Merhaba, nasılsın?</p>
                        </div>
                    </div>
                </div>
                <div class="call-controls">
                    <button class="voice-btn" onclick="startVoiceCall()">Sesli Sohbet</button>
                    <button class="video-btn" onclick="startVideoCall()">Görüntülü Sohbet</button>
                    <button class="screen-share-btn" onclick="startScreenShare()">Ekran Paylaşımı</button>
                </div>
                <div class="input-area">
                    <i class="fas fa-paperclip"></i>
                    <input type="text" id="messageInput" placeholder="Mesaj yaz...">
                    <i class="fas fa-microphone"></i>
                </div>
            </div>
            <div class="members">
                <div class="user-profile">
                    <img src="https://placehold.co/80x80" alt="Kullanıcı">
                    <h3 id="profileUser">Kullanıcı1</h3>
                    <p>Gelen Arama</p>
                    <button class="join" onclick="joinCall()">Aramaya Katıl</button>
                    <button class="decline" onclick="declineCall()">Reddet</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Kullanıcı verileri (simüle edilmiş veritabanı)
        let users = [];
        let currentUser = null;

        // Sayfalar arasında geçiş
        function showPage(pageId) {
            document.querySelectorAll('.page').forEach(page => {
                page.classList.remove('active');
            });
            document.getElementById(pageId).classList.add('active');
        }

        // Rastgele kullanıcı adı oluştur
        function generateUsername() {
            const names = ['Kullanıcı', 'Sohbetçi', 'ChatMaster', 'Kral', 'Koç'];
            const randomName = names[Math.floor(Math.random() * names.length)];
            const randomNum = Math.floor(Math.random() * 1000);
            return `${randomName}${randomNum}`;
        }

        // Giriş işlemi
        function handleLogin() {
            const emailOrPhone = document.getElementById('emailOrPhone').value;
            const password = document.getElementById('password').value;
            const errorMessage = document.getElementById('loginErrorMessage');

            const user = users.find(u => u.email === emailOrPhone && u.password === password);
            if (!emailOrPhone || !password) {
                errorMessage.textContent = 'Lütfen tüm alanları doldur!';
                errorMessage.style.display = 'block';
            } else if (!user) {
                errorMessage.textContent = 'Aradığınız hesap bulunamadı!';
                errorMessage.style.display = 'block';
            } else {
                errorMessage.style.display = 'none';
                currentUser = user;
                document.getElementById('currentUser').textContent = user.username;
                document.getElementById('profileUser').textContent = user.username;
                document.getElementById('initialUser').textContent = `${user.username} <span class="timestamp">Bugün 14:12</span>`;
                showPage('dashboardPage');
            }
        }

        // Kayıt işlemi
        function handleRegister() {
            const username = document.getElementById('username').value;
            const email = document.getElementById('email').value;
            const password = document.getElementById('registerPassword').value;
            const errorMessage = document.getElementById('registerErrorMessage');

            if (!username || !email || !password) {
                errorMessage.style.display = 'block';
            } else if (users.some(u => u.email === email)) {
                errorMessage.textContent = 'Bu e-posta zaten kullanılıyor!';
                errorMessage.style.display = 'block';
            } else {
                errorMessage.style.display = 'none';
                const newUsername = username || generateUsername();
                const newUser = { username: newUsername, email, password };
                users.push(newUser);
                alert('Kayıt başarılı! Giriş sayfasına yönlendiriliyorsun...');
                showPage('loginPage');
            }
        }

        // Sesli sohbet, görüntülü sohbet ve ekran paylaşımı simülasyonu
        function startVoiceCall() {
            alert('Sesli sohbet başlatılıyor... (Simülasyon)');
        }

        function startVideoCall() {
            alert('Görüntülü sohbet başlatılıyor... (Simülasyon)');
        }

        function startScreenShare() {
            alert('Ekran paylaşımı başlatılıyor... (Simülasyon)');
        }

        function joinCall() {
            alert('Aramaya katıldın!');
        }

        function declineCall() {
            alert('Arama reddedildi!');
        }

        // Mesaj gönderme ve arkadaş ekleme
        document.getElementById('messageInput').addEventListener('keypress', function(e) {
            if (e.key === 'Enter' && this.value.trim()) {
                const message = this.value.trim();
                const messagesDiv = document.getElementById('messages');
                if (message.startsWith('#666 arkadaş ekle')) {
                    const friendUsername = message.split(' ')[2];
                    if (friendUsername) {
                        const friendMessage = document.createElement('div');
                        friendMessage.className = 'message';
                        friendMessage.innerHTML = `
                            <div class="avatar"></div>
                            <div class="message-content">
                                <h4>Sistem <span class="timestamp">${new Date().toLocaleTimeString()}</span></h4>
                                <p>${currentUser.username} sana arkadaşlık isteği gönderdi!</p>
                            </div>
                        `;
                        messagesDiv.appendChild(friendMessage);
                        this.value = '';
                    }
                } else {
                    const newMessage = document.createElement('div');
                    newMessage.className = 'message';
                    newMessage.innerHTML = `
                        <div class="avatar"></div>
                        <div class="message-content">
                            <h4>${currentUser ? currentUser.username : 'Kullanıcı1'} <span class="timestamp">${new Date().toLocaleTimeString()}</span></h4>
                            <p>${message}</p>
                        </div>
                    `;
                    messagesDiv.appendChild(newMessage);
                    this.value = '';
                }
            }
        });

        // İlk açılışta giriş sayfasını göster
        document.addEventListener('DOMContentLoaded', () => {
            showPage('loginPage');
        });
    </script>
</body>
</html>
