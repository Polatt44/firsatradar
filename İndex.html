<!DOCTYPE html>  <html lang="tr">  
<head>  
  <meta charset="UTF-8" />  
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />  
  <meta name="referrer" content="strict-origin-when-cross-origin" />  
  <title>FırsatRadar - Market İndirimleri</title>  
  <script src="https://cdn.tailwindcss.com"></script>  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />  
  <style>  
    .modal[hidden] { display: none !important; }  
    .modal { display: none; }  
    .modal.flex { display: flex; }  
    button { transition: all 0.2s ease; }  
    button:focus-visible,  
    input:focus-visible,  
    select:focus-visible,  
    textarea:focus-visible {  
      outline: 2px solid rgba(16, 185, 129, 0.5);  
      outline-offset: 2px;  
    }  
  </style>  
</head>  
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col">  
  <header class="bg-white border-b sticky top-0 z-40 shadow-sm">  
    <div class="max-w-4xl mx-auto px-4 h-16 flex items-center justify-between">  
      <div class="flex items-center gap-2">  
        <div class="w-10 h-10 bg-emerald-600 rounded-xl flex items-center justify-center text-white text-xl">  
          <i class="fa-solid fa-tags"></i>  
        </div>  
        <span class="text-xl font-extrabold">Fırsat<span class="text-emerald-600">Radar</span></span>  
      </div>  
      <div id="auth-header-section" class="flex items-center gap-2"></div>  
    </div>  
  </header>    <main class="flex-1 max-w-4xl w-full mx-auto px-4 py-6">  
    <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4 mb-6 bg-gradient-to-r from-emerald-600 to-teal-700 p-6 rounded-2xl text-white shadow-lg">  
      <div>  
        <h1 class="text-2xl font-bold">Çevrenizdeki En Sıcak Fırsatlar 🔥</h1>  
        <p class="text-emerald-100 text-sm mt-1">Marketlerdeki indirimleri paylaşın, bütçenizi koruyun!</p>  
      </div>  
      <button type="button" onclick="openPostModal()" class="bg-white text-emerald-700 font-semibold px-5 py-3 rounded-xl">+ Yeni Fırsat Paylaş</button>  
    </div>  <div class="bg-white p-4 rounded-2xl border mb-4 flex flex-col md:flex-row gap-3">  
  <input id="searchInput" oninput="filterDeals()" placeholder="Ürün, market veya konum ara..." class="flex-1 px-4 py-2.5 bg-slate-50 border rounded-xl text-sm" />  
  <select id="marketFilter" onchange="filterDeals()" class="px-3 py-2 border rounded-xl text-sm">  
    <option value="">Tüm Marketler</option>  
    <option>BİM</option>  
    <option>A101</option>  
    <option>ŞOK</option>  
    <option>Migros</option>  
    <option>CarrefourSA</option>  
    <option>Diğer</option>  
  </select>  
  <select id="categoryFilter" onchange="filterDeals()" class="px-3 py-2 border rounded-xl text-sm">  
    <option value="">Tüm Kategoriler</option>  
    <option>Gıda</option>  
    <option>Temizlik</option>  
    <option>Elektronik</option>  
    <option>Kişisel Bakım</option>  
    <option>Atıştırmalık</option>  
    <option>Ev ve Yaşam</option>  
    <option>Diğer</option>  
  </select>  
</div>  

<p class="text-xs text-amber-700 mb-3">Örnek kayıtlar yalnızca deneme içindir; gerçek indirim ve stok durumu mağazada doğrulanmalıdır.</p>  

<div id="dealsContainer" class="grid grid-cols-1 md:grid-cols-2 gap-4"></div>

  </main>    <div id="postModal" class="modal fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-4 overflow-y-auto">  
    <div class="bg-white rounded-3xl max-w-lg w-full p-6 my-8">  
      <div class="flex justify-between border-b pb-3">  
        <h2 class="font-bold text-lg">Yeni Fırsat Paylaş</h2>  
        <button type="button" onclick="hideModal('postModal')">✕</button>  
      </div>  <form id="postForm" class="space-y-3 pt-4">  
    <label class="block text-xs font-bold">  
      Ürün adı *  
      <input id="postTitle" maxlength="100" required class="block w-full mt-1 p-3 border rounded-xl" />  
    </label>  

    <div class="grid grid-cols-2 gap-3">  
      <label class="text-xs font-bold">  
        Market *  
        <select id="postMarket" required class="block w-full mt-1 p-3 border rounded-xl">  
          <option value="">Seçiniz</option>  
          <option>BİM</option>  
          <option>A101</option>  
          <option>ŞOK</option>  
          <option>Migros</option>  
          <option>CarrefourSA</option>  
          <option>Diğer</option>  
        </select>  
      </label>  

      <label class="text-xs font-bold">  
        Kategori *  
        <select id="postCategory" required class="block w-full mt-1 p-3 border rounded-xl">  
          <option value="">Seçiniz</option>  
          <option>Gıda</option>  
          <option>Temizlik</option>  
          <option>Elektronik</option>  
          <option>Kişisel Bakım</option>  
          <option>Atıştırmalık</option>  
          <option>Ev ve Yaşam</option>  
          <option>Diğer</option>  
        </select>  
      </label>  
    </div>  

    <div class="grid grid-cols-2 gap-3">  
      <label class="text-xs font-bold">  
        Önceki fiyat  
        <input id="postOldPrice" type="number" min="0" max="10000000" step="0.01" class="block w-full mt-1 p-3 border rounded-xl" />  
      </label>  

      <label class="text-xs font-bold">  
        Güncel fiyat *  
        <input id="postNewPrice" type="number" min="0.01" max="10000000" step="0.01" required class="block w-full mt-1 p-3 border rounded-xl" />  
      </label>  
    </div>  

    <label class="block text-xs font-bold">  
      Şehir / mağaza konumu *  
      <input id="postLocation" maxlength="120" required placeholder="Örn. Merkez, Malatya" class="block w-full mt-1 p-3 border rounded-xl" />  
    </label>  

    <label class="block text-xs font-bold">  
      Fotoğraf (isteğe bağlı, en fazla 3 MB)  
      <input id="postImageFile" type="file" accept="image/jpeg,image/png,image/webp" class="block w-full mt-1 text-sm" />  
    </label>  

    <label class="block text-xs font-bold">  
      Açıklama  
      <textarea id="postDesc" maxlength="500" rows="2" class="block w-full mt-1 p-3 border rounded-xl"></textarea>  
    </label>  

    <p id="postError" class="text-sm text-rose-600" role="alert"></p>  
    <button type="submit" class="w-full bg-emerald-600 text-white p-3 rounded-xl font-bold">Fırsatı Paylaş</button>  
    <p class="text-xs text-slate-500">Bu sürüm kayıtları yalnızca bu tarayıcıda saklar; çevrim içi paylaşım için sunucu/veritabanı gerekir.</p>  
  </form>  
</div>

  </div>    <div id="authModal" class="modal fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-4">  
    <div class="bg-white rounded-3xl max-w-sm w-full p-6">  
      <div class="flex justify-between border-b pb-3">  
        <h2 id="authTitle" class="font-bold text-lg">Giriş Yap</h2>  
        <button type="button" onclick="hideModal('authModal')">✕</button>  
      </div>  <p class="text-xs bg-amber-50 text-amber-800 p-3 rounded-lg mt-3">Bu bir demo hesaptır; parola veya gerçek kimlik doğrulama yoktur. Hassas bilgi kullanmayın.</p>  

  <form id="authForm" class="space-y-3 pt-4">  
    <label class="block text-xs font-bold">  
      Kullanıcı adı (3–24 karakter)  
      <input id="authUsername" minlength="3" maxlength="24" pattern="[A-Za-z0-9_ğüşöçıİĞÜŞÖÇ.-]+" required class="block w-full mt-1 p-3 border rounded-xl" />  
    </label>  

    <label id="avatarLabel" class="block text-xs font-bold">  
      Profil fotoğrafı (2 MB'a kadar)  
      <input id="authAvatar" type="file" accept="image/jpeg,image/png,image/webp" class="block w-full mt-1 text-sm" />  
    </label>  

    <p id="authError" class="text-sm text-rose-600"></p>  

    <button id="authSubmit" type="submit" class="w-full bg-emerald-600 text-white p-3 rounded-xl font-bold">Giriş Yap</button>  
    <button type="button" onclick="toggleAuthMode()" id="authSwitch" class="w-full text-sm text-emerald-700">Hesabın yok mu? Kayıt ol</button>  
  </form>  
</div>

  </div>    <div id="detailModal" class="modal fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-4 overflow-y-auto">  
    <div class="bg-white rounded-3xl max-w-xl w-full p-6 my-8 max-h-[90vh] overflow-y-auto">  
      <div class="flex justify-between border-b pb-3">  
        <h2 class="font-bold text-lg">Fırsat detayı ve yorumlar</h2>  
        <button type="button" onclick="hideModal('detailModal')">✕</button>  
      </div>  
      <div id="detailContent" class="pt-4"></div>  
    </div>  
  </div>    <div id="dislikeModal" class="modal fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-4">  
    <div class="bg-white rounded-3xl max-w-sm w-full p-6">  
      <div class="flex justify-between mb-3">  
        <h2 class="font-bold">Olumsuz oy nedeni</h2>  
        <button type="button" onclick="hideModal('dislikeModal')">✕</button>  
      </div>  
      <div class="space-y-2">  
        <button type="button" class="reason w-full text-left p-3 bg-slate-50 rounded-xl" data-reason="Stok bitti">Stok bitti</button>  
        <button type="button" class="reason w-full text-left p-3 bg-slate-50 rounded-xl" data-reason="Fiyat yanıltıcı / bindirim var">Fiyat yanıltıcı / bindirim var</button>  
        <button type="button" class="reason w-full text-left p-3 bg-slate-50 rounded-xl" data-reason="Kasa ve etiket fiyatı farklı">Kasa ve etiket fiyatı farklı</button>  
        <button type="button" class="reason w-full text-left p-3 bg-slate-50 rounded-xl" data-reason="Ürünle ilgili endişe">Ürünle ilgili endişe</button>  
      </div>  
    </div>  
  </div>    <div id="profileModal" class="modal fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-4">  
    <div class="bg-white rounded-3xl max-w-lg w-full p-6 max-h-[90vh] overflow-y-auto">  
      <div class="flex justify-between border-b pb-3">  
        <h2 class="font-bold text-lg">Kullanıcı profili</h2>  
        <button type="button" onclick="hideModal('profileModal')">✕</button>  
      </div>  
      <div id="profileContent" class="pt-4"></div>  
    </div>  
  </div>    <script>  
    'use strict';  
  
    const KEYS = {  
      user: 'fr_user_v2',  
      users: 'fr_users_v2',  
      deals: 'fr_deals_v2'  
    };  
  
    const DEFAULT_IMG = 'https://images.unsplash.com/photo-1542838132-92c53300491e?auto=format&fit=crop&w=600&q=80';  
    const DEFAULT_AVATAR = 'https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?auto=format&fit=crop&w=150&q=80';  
  
    let users = [];  
    let currentUser = null;  
    let deals = [];  
    let registerMode = false;  
    let dislikeId = null;  
    let detailId = null;  
  
    function readStorage(key, fallback) {  
      try {  
        const raw = localStorage.getItem(key);  
        if (raw === null) return fallback;  
        const value = JSON.parse(raw);  
        return value;  
      } catch (error) {  
        console.warn('Storage parse error:', key, error);  
        return fallback;  
      }  
    }  
  
    function saveStorage(key, value) {  
      try {  
        localStorage.setItem(key, JSON.stringify(value));  
        return true;  
      } catch (error) {  
        alert('Tarayıcı depolama alanı dolu. Fotoğrafı küçültüp tekrar deneyin.');  
        console.error('Storage save failed:', error);  
        return false;  
      }  
    }  
  
    function esc(value) {  
      return String(value ?? '').replace(/[&<>"']/g, (char) => ({  
        '&': '&amp;',  
        '<': '&lt;',  
        '>': '&gt;',  
        '"': '&quot;',  
        "'": '&#39;'  
      }[char]));  
    }  
  
    function imgSafe(value) {  
      if (typeof value === 'string' && /^https:\/\/images\.unsplash\.com\//i.test(value)) return value;  
      if (typeof value === 'string' && /^https:\/\/via\.placeholder\.com\//i.test(value)) return value;  
      if (typeof value === 'string' && /^data:image\/(jpeg|png|webp);base64,/i.test(value) && value.length < 4500000) return value;  
      return DEFAULT_IMG;  
    }  
  
    function avatarSafe(value) {  
      if (typeof value === 'string' && (  
        /^https:\/\/images\.unsplash\.com\//i.test(value) ||  
        /^data:image\/(jpeg|png|webp);base64,/i.test(value)  
      )) {  
        return value;  
      }  
      return DEFAULT_AVATAR;  
    }  
  
    function sanitizeText(value, maxLen = 500) {  
      return String(value ?? '').slice(0, maxLen);  
    }  
  
    function normalizeDeal(data) {  
      const oldPrice = Number(data.oldPrice) || 0;  
      const newPrice = Number(data.newPrice) || 0;  
  
      return {  
        id: String(data.id ?? Date.now() + Math.random()),  
        title: sanitizeText(data.title || '', 100).trim(),  
        market: sanitizeText(data.market || 'Diğer', 50).trim() || 'Diğer',  
        category: sanitizeText(data.category || 'Diğer', 50).trim() || 'Diğer',  
        oldPrice: Math.max(0, Number.isFinite(oldPrice) ? oldPrice : 0),  
        newPrice: Math.max(0, Number.isFinite(newPrice) ? newPrice : 0),  
        location: sanitizeText(data.location || '', 120).trim(),  
        image: imgSafe(data.image),  
        desc: sanitizeText(data.desc || '', 500),  
        author: sanitizeText(data.author || 'Demo', 24).trim() || 'Demo',  
        authorAvatar: avatarSafe(data.authorAvatar),  
        likes: Math.max(0, Number(data.likes) || 0),  
        dislikes: Math.max(0, Number(data.dislikes) || 0),  
        likedUsers: Array.isArray(data.likedUsers) ? data.likedUsers.filter(x => typeof x === 'string') : [],  
        dislikedUsers: Array.isArray(data.dislikedUsers) ? data.dislikedUsers.filter(x => typeof x === 'string') : [],  
        comments: Array.isArray(data.comments) ? data.comments.filter(c => c && typeof c.text === 'string').map(c => ({  
          author: sanitizeText(c.author || 'Bilinmeyen', 24).trim() || 'Bilinmeyen',  
          text: sanitizeText(c.text, 500),  
          date: String(c.date || new Date().toLocaleString('tr-TR')),  
          avatar: avatarSafe(c.avatar)  
        })) : [],  
        createdAt: Number(data.createdAt) || Date.now(),  
        demo: !!data.demo  
      };  
    }  
  
    function demoDeals() {  
      return [  
        {  
          id: 1,  
          title: 'Örnek: Kakaolu fındık kreması',  
          market: 'BİM',  
          category: 'Atıştırmalık',  
          oldPrice: 145,  
          newPrice: 99.5,  
          location: 'Örnek konum — İstanbul',  
          image: DEFAULT_IMG,  
          desc: 'Deneme amaçlı örnek kayıt; gerçek indirim değildir.',  
          author: 'DemoKullanıcı',  
          authorAvatar: DEFAULT_AVATAR,  
          likes: 0,  
          dislikes: 0,  
          likedUsers: [],  
          dislikedUsers: [],  
          comments: [],  
          createdAt: Date.now(),  
          demo: true  
        },  
        {  
          id: 2,  
          title: 'Örnek: Çamaşır suyu',  
          market: 'A101',  
          category: 'Temizlik',  
          oldPrice: 180,  
          newPrice: 119.9,  
          location: 'Örnek konum — Ankara',  
          image: DEFAULT_IMG,  
          desc: 'Deneme amaçlı örnek kayıt; gerçek indirim değildir.',  
          author: 'DemoKullanıcı',  
          authorAvatar: DEFAULT_AVATAR,  
          likes: 0,  
          dislikes: 0,  
          likedUsers: [],  
          dislikedUsers: [],  
          comments: [],  
          createdAt: Date.now(),  
          demo: true  
        }  
      ];  
    }  
  
    function loadState() {  
      users = Array.isArray(readStorage(KEYS.users, [])) ? readStorage(KEYS.users, []) : [];  
      currentUser = readStorage(KEYS.user, null);  
      if (currentUser && typeof currentUser.username !== 'string') currentUser = null;  
  
      const rawDeals = readStorage(KEYS.deals, null);  
      if (!Array.isArray(rawDeals) || rawDeals.length === 0) {  
        deals = demoDeals().map(normalizeDeal);  
      } else {  
        deals = rawDeals  
          .filter(d => d && d.id !== undefined && typeof d.title === 'string' && Number.isFinite(Number(d.newPrice)))  
          .map(normalizeDeal);  
      }  
    }  
  
    function money(value) {  
      const num = Number(value) || 0;  
      return num.toLocaleString('tr-TR', { style: 'currency', currency: 'TRY' });  
    }  
  
    function findDeal(id) {  
      return deals.find(d => String(d.id) === String(id));  
    }  
  
    function showModal(id) {  
      const modal = document.getElementById(id);  
      if (!modal) return;  
      modal.classList.remove('hidden');  
      modal.classList.add('flex');  
      modal.setAttribute('aria-hidden', 'false');  
    }  
  
    function hideModal(id) {  
      const modal = document.getElementById(id);  
      if (!modal) return;  
      modal.classList.add('hidden');  
      modal.classList.remove('flex');  
      modal.setAttribute('aria-hidden', 'true');  
    }  
  
    function renderHeader() {  
      const el = document.getElementById('auth-header-section');  
      if (!el) return;  
  
      el.replaceChildren();  
  
      if (currentUser) {  
        const profileBtn = document.createElement('button');  
        profileBtn.type = 'button';  
        profileBtn.className = 'flex items-center gap-2 bg-slate-100 px-3 py-2 rounded-full';  
        profileBtn.onclick = () => openProfile(currentUser.username);  
  
        const image = document.createElement('img');  
        image.src = avatarSafe(currentUser.avatar);  
        image.alt = currentUser.username;  
        image.className = 'w-7 h-7 rounded-full object-cover';  
  
        const name = document.createElement('span');  
        name.textContent = currentUser.username;  
        name.className = 'text-sm font-bold';  
  
        profileBtn.append(image, name);  
  
        const logoutBtn = document.createElement('button');  
        logoutBtn.type = 'button';  
        logoutBtn.textContent = 'Çıkış';  
        logoutBtn.className = 'text-sm text-rose-600';  
        logoutBtn.onclick = () => {  
          currentUser = null;  
          localStorage.removeItem(KEYS.user);  
          renderHeader();  
          renderDeals();  
        };  
  
        el.append(profileBtn, logoutBtn);  
      } else {  
        const actions = [  
          ['Giriş Yap', false],  
          ['Kayıt Ol', true]  
        ];  
        actions.forEach(([label, reg]) => {  
          const btn = document.createElement('button');  
          btn.type = 'button';  
          btn.textContent = label;  
          btn.className = 'px-3 py-2 text-sm font-semibold';  
          btn.onclick = () => openAuth(reg);  
          el.append(btn);  
        });  
      }  
    }  
  
    function openAuth(reg) {  
      registerMode = !!reg;  
      const authTitle = document.getElementById('authTitle');  
      const authSubmit = document.getElementById('authSubmit');  
      const authSwitch = document.getElementById('authSwitch');  
      const avatarLabel = document.getElementById('avatarLabel');  
      const authError = document.getElementById('authError');  
      const authForm = document.getElementById('authForm');  
  
      authTitle.textContent = reg ? 'Kayıt Ol' : 'Giriş Yap';  
      authSubmit.textContent = reg ? 'Kayıt Ol' : 'Giriş Yap';  
      authSwitch.textContent = reg ? 'Zaten hesabın var mı? Giriş yap' : 'Hesabın yok mu? Kayıt ol';  
      avatarLabel.style.display = reg ? 'block' : 'none';  
  
      authError.textContent = '';  
      authForm.reset();  
  
      showModal('authModal');  
    }  
  
    function toggleAuthMode() {  
      openAuth(!registerMode);  
    }  
  
    function fileData(file, maxBytes) {  
      return new Promise((resolve, reject) => {  
        if (!file) return resolve('');  
  
        if (!['image/jpeg', 'image/png', 'image/webp'].includes(file.type)) {  
          return reject(new Error('JPEG, PNG veya WEBP fotoğraf seçin.'));  
        }  
  
        if (file.size <= 0 || file.size > maxBytes) {  
          return reject(new Error(`Fotoğraf boyutu en fazla ${Math.round(maxBytes / 1024 / 1024)} MB olmalıdır.`));  
        }  
  
        const reader = new FileReader();  
        reader.onload = () => resolve(String(reader.result));  
        reader.onerror = () => reject(new Error('Fotoğraf okunamadı.'));  
        reader.readAsDataURL(file);  
      });  
    }  
  
    async function handleAuthSubmit(event) {  
      event.preventDefault();  
  
      const authUsername = document.getElementById('authUsername').value.trim();  
      const authError = document.getElementById('authError');  
  
      const usernamePattern = /^[A-Za-z0-9_ğüşöçıİĞÜŞÖÇ.-]{3,24}$/;  
      if (!usernamePattern.test(authUsername)) {  
        authError.textContent = 'Kullanıcı adı 3–24 karakter olmalı. Türkçe karakterler ve _ . - izinlidir.';  
        return;  
      }  
  
      const normalizedInput = authUsername.toLowerCase();  
  
      if (registerMode) {  
        const existing = users.find(u => String(u.username).toLowerCase() === normalizedInput);  
        if (existing) {  
          authError.textContent = 'Bu kullanıcı adı kayıtlı.';  
          return;  
        }  
  
        try {  
          const avatarFile = document.getElementById('authAvatar').files[0];  
          const avatar = (await fileData(avatarFile, 2 * 1024 * 1024)) || DEFAULT_AVATAR;  
  
          const newUser = { username: authUsername, avatar };  
          users.push(newUser);  
  
          if (!saveStorage(KEYS.users, users)) {  
            users.pop();  
            return;  
          }  
  
          currentUser = { username: authUsername, avatar };  
          if (!saveStorage(KEYS.user, currentUser)) {  
            currentUser = null;  
            return;  
          }  
  
          hideModal('authModal');  
          renderHeader();  
          renderDeals();  
          alert('Demo hesabına giriş yapıldı. Bu gerçek kimlik doğrulama değildir.');  
        } catch (error) {  
          authError.textContent = error.message || 'Kayıt sırasında hata oluştu.';  
        }  
        return;  
      }  
  
      const existingUser = users.find(u => String(u.username).toLowerCase() === normalizedInput);  
      if (!existingUser) {  
        authError.textContent = 'Bu tarayıcıda hesap bulunamadı; önce kayıt olun.';  
        return;  
      }  
  
      currentUser = {  
        username: existingUser.username,  
        avatar: existingUser.avatar || DEFAULT_AVATAR  
      };  
  
      if (!saveStorage(KEYS.user, currentUser)) {  
        currentUser = null;  
        return;  
      }  
  
      hideModal('authModal');  
      renderHeader();  
      renderDeals();  
      alert('Demo hesabına giriş yapıldı. Bu gerçek kimlik doğrulama değildir.');  
    }  
  
    function ensureUserLoggedIn() {  
      if (!currentUser) {  
        alert('Fırsat paylaşmak için önce giriş yapın.');  
        openAuth(false);  
        return false;  
      }  
      return true;  
    }  
  
    async function handlePostSubmit(event) {  
      event.preventDefault();  
  
      if (!ensureUserLoggedIn()) return;  
  
      const title = document.getElementById('postTitle').value.trim();  
      const market = document.getElementById('postMarket').value.trim();  
      const category = document.getElementById('postCategory').value.trim();  
      const location = document.getElementById('postLocation').value.trim();  
      const desc = document.getElementById('postDesc').value.trim();  
      const oldPriceRaw = document.getElementById('postOldPrice').value.trim();  
      const oldPrice = oldPriceRaw === '' ? 0 : Number(oldPriceRaw);  
      const newPrice = Number(document.getElementById('postNewPrice').value);  
      const err = document.getElementById('postError');  
  
      if (!title || !market || !category || !location) {  
        err.textContent = 'Zorunlu alanları doldurun.';  
        return;  
      }  
  
      if (!Number.isFinite(newPrice) || newPrice <= 0 || newPrice > 10000000) {  
        err.textContent = 'Güncel fiyat geçerli olmalıdır.';  
        return;  
      }  
  
      if (!Number.isFinite(oldPrice) || oldPrice < 0 || oldPrice > 10000000) {  
        err.textContent = 'Önceki fiyat geçersiz.';  
        return;  
      }  
  
      if (oldPrice > 0 && oldPrice < newPrice) {  
        err.textContent = 'Önceki fiyat güncel fiyattan düşük olamaz.';  
        return;  
      }  
  
      try {  
        const imageFile = document.getElementById('postImageFile').files[0];  
        const image = (await fileData(imageFile, 3 * 1024 * 1024)) || DEFAULT_IMG;  
  
        const newDeal = normalizeDeal({  
          id: Date.now(),  
          title,  
          market,  
          category,  
          location,  
          desc,  
          oldPrice,  
          newPrice,  
          image,  
          author: currentUser.username,  
          authorAvatar: currentUser.avatar,  
          likes: 0,  
          dislikes: 0,  
          likedUsers: [],  
          dislikedUsers: [],  
          comments: [],  
          createdAt: Date.now(),  
          demo: false  
        });  
  
        deals.unshift(newDeal);  
  
        if (!saveStorage(KEYS.deals, deals)) {  
          deals.shift();  
          return;  
        }  
  
        hideModal('postModal');  
        event.target.reset();  
        renderDeals();  
        alert('Fırsat bu tarayıcıya kaydedildi; diğer kullanıcılarla henüz çevrim içi paylaşılmaz.');  
      } catch (error) {  
        err.textContent = error.message || 'Fırsat paylaşılırken hata oluştu.';  
      }  
    }  
  
    function filterDeals() {  
      const query = document.getElementById('searchInput').value.trim().toLocaleLowerCase('tr-TR');  
      const market = document.getElementById('marketFilter').value;  
      const category = document.getElementById('categoryFilter').value;  
  
      const filtered = deals.filter(d => {  
        const haystack = `${d.title} ${d.market} ${d.location} ${d.desc}`.toLocaleLowerCase('tr-TR');  
        const matchesSearch = haystack.includes(query);  
        const matchesMarket = !market || d.market === market;  
        const matchesCategory = !category || d.category === category;  
        return matchesSearch && matchesMarket && matchesCategory;  
      });  
  
      renderList(filtered);  
    }  
  
    function renderDeals() {  
      filterDeals();  
    }  
  
    function renderList(list) {  
      const root = document.getElementById('dealsContainer');  
      if (!root) return;  
  
      if (!list.length) {  
        root.innerHTML = '<div class="col-span-2 text-center py-12 text-slate-400">Fırsat bulunamadı. İlk fırsatı siz paylaşın!</div>';  
        return;  
      }  
  
      root.innerHTML = list.map(d => {  
        const discountPercent = d.oldPrice > d.newPrice ? Math.round(((d.oldPrice - d.newPrice) / d.oldPrice) * 100) : 0;  
        const id = JSON.stringify(d.id);  
  
        return `  
          <article class="bg-white rounded-2xl border shadow-sm overflow-hidden flex flex-col">  
            ${d.demo ? '<div class=\"bg-amber-50 text-amber-800 text-xs p-2\">ÖRNEK KAYIT — GERÇEK İNDİRİM DEĞİL</div>' : ''}  
            <img src="${esc(imgSafe(d.image))}" alt="${esc(d.title)}" loading="lazy" class="w-full h-44 object-cover">  
            <div class="p-4 flex-1">  
              <div class="text-xs text-slate-500 mb-2">${esc(d.market)} · ${esc(d.category)} · ${esc(d.location)}</div>  
              <button type="button" data-id="${esc(d.id)}" class="deal-link font-bold text-left hover:text-emerald-600">  
                ${esc(d.title)}  
              </button>  
              <div class="mt-2">  
                <strong class="text-xl text-emerald-600">${money(d.newPrice)}</strong>  
                ${d.oldPrice > d.newPrice ? `<del class="text-slate-400 text-sm">${money(d.oldPrice)}</del><span class="text-rose-600 text-xs"> %${discountPercent}</span>` : ''}  
              </div>  
              <p class="text-xs bg-slate-50 p-2 rounded-lg mt-3 whitespace-pre-wrap">${esc(d.desc || 'Açıklama yok.')}</p>  
            </div>  
            <div class="border-t p-3 flex items-center justify-between gap-2">  
              <button type="button" data-username="${esc(d.author)}" class="author-link text-xs font-bold">${esc(d.author)}</button>  
              <div class="flex gap-2">  
                <button type="button" data-id="${esc(d.id)}" class="vote-like text-sm">👍 ${d.likes}</button>  
                <button type="button" data-id="${esc(d.id)}" class="vote-dislike text-sm">👎 ${d.dislikes}</button>  
                <button type="button" data-id="${esc(d.id)}" class="deal-comment text-sm">💬 ${d.comments.length}</button>  
              </div>  
            </div>  
          </article>  
        `;  
      }).join('');  
  
      bindDealInteractions();  
    }  
  
    function bindDealInteractions() {  
      document.querySelectorAll('.deal-link').forEach(button => {  
        button.addEventListener('click', () => {  
          openDetail(button.dataset.id);  
        });  
      });  
  
      document.querySelectorAll('.author-link').forEach(button => {  
        button.addEventListener('click', () => {  
          openProfile(button.dataset.username);  
        });  
      });  
  
      document.querySelectorAll('.vote-like').forEach(button => {  
        button.addEventListener('click', () => {  
          vote(button.dataset.id, true);  
        });  
      });  
  
      document.querySelectorAll('.vote-dislike').forEach(button => {  
        button.addEventListener('click', () => {  
          startDislike(button.dataset.id);  
        });  
      });  
  
      document.querySelectorAll('.deal-comment').forEach(button => {  
        button.addEventListener('click', () => {  
          openDetail(button.dataset.id);  
        });  
      });  
    }  
  
    function vote(id, up) {  
      if (!currentUser) {  
        openAuth(false);  
        return;  
      }  
  
      const d = findDeal(id);  
      if (!d || d.demo) {  
        alert('Örnek kayıtlar değiştirilemez.');  
        return;  
      }  
  
      const userName = currentUser.username;  
  
      if (d.likedUsers.includes(userName)) {  
        d.likedUsers = d.likedUsers.filter(x => x !== userName);  
        d.likes = Math.max(0, d.likes - 1);  
      } else {  
        d.likedUsers.push(userName);  
        d.likes = Math.max(0, d.likes + 1);  
  
        if (d.dislikedUsers.includes(userName)) {  
          d.dislikedUsers = d.dislikedUsers.filter(x => x !== userName);  
          d.dislikes = Math.max(0, d.dislikes - 1);  
        }  
      }  
  
      saveStorage(KEYS.deals, deals);  
      renderDeals();  
  
      if (String(detailId) === String(id)) {  
        openDetail(id);  
      }  
    }  
  
    function startDislike(id) {  
      if (!currentUser) {  
        openAuth(false);  
        return;  
      }  
  
      const d = findDeal(id);  
      if (!d || d.demo) {  
        alert('Örnek kayıtlar değiştirilemez.');  
        return;  
      }  
  
      dislikeId = id;  
      showModal('dislikeModal');  
    }  
  
    document.querySelectorAll('.reason').forEach(button => {  
      button.addEventListener('click', () => {  
        const d = findDeal(dislikeId);  
        if (!d || !currentUser) return;  
  
        const userName = currentUser.username;  
  
        if (!d.dislikedUsers.includes(userName)) {  
          d.dislikedUsers.push(userName);  
          d.dislikes = Math.max(0, d.dislikes + 1);  
  
          if (d.likedUsers.includes(userName)) {  
            d.likedUsers = d.likedUsers.filter(x => x !== userName);  
            d.likes = Math.max(0, d.likes - 1);  
          }  
  
          d.comments.push({  
            author: userName,  
            text: 'Olumsuz bildirim: ' + button.dataset.reason,  
            date: new Date().toLocaleString('tr-TR'),  
            avatar: currentUser.avatar  
          });  
        }  
  
        const id = dislikeId;  
        dislikeId = null;  
        hideModal('dislikeModal');  
  
        saveStorage(KEYS.deals, deals);  
        renderDeals();  
  
        if (String(detailId) === String(id)) {  
          openDetail(id);  
        }  
      });  
    });  
  
    function openDetail(id) {  
      const d = findDeal(id);  
      if (!d) return;  
  
      detailId = d.id;  
  
      const commentsHtml = d.comments.length  
        ? d.comments.map(c => `  
          <div class="bg-slate-50 border rounded-xl p-3 mb-2">  
            <div class="flex justify-between text-xs">  
              <b>${esc(c.author)}</b>  
              <span>${esc(c.date)}</span>  
            </div>  
            <p class="text-sm whitespace-pre-wrap break-words mt-1">${esc(c.text)}</p>  
          </div>  
        `).join('')  
        : '<p class=\"text-sm text-slate-400\">Henüz yorum yok.</p>';  
  
      const detailContent = document.getElementById('detailContent');  
      detailContent.innerHTML = `  
        ${d.demo ? '<p class=\"bg-amber-50 text-amber-800 text-xs p-2 rounded\">Örnek kayıt; gerçek fırsat değildir.</p>' : ''}  
        <img src="${esc(imgSafe(d.image))}" class="w-full h-52 object-cover rounded-xl" alt="${esc(d.title)}">  
        <p class="text-xs text-slate-500 mt-3">${esc(d.market)} · ${esc(d.category)} · ${esc(d.location)}</p>  
        <h3 class="text-xl font-bold mt-1">${esc(d.title)}</h3>  
        <p class="text-xl text-emerald-600 font-black mt-2">  
          ${money(d.newPrice)}  
          ${d.oldPrice > d.newPrice ? `<del class="text-sm text-slate-400">${money(d.oldPrice)}</del>` : ''}  
        </p>  
        <p class="text-sm bg-slate-50 p-3 rounded-xl mt-3 whitespace-pre-wrap">${esc(d.desc || 'Açıklama yok.')}</p>  
        <p class="text-xs text-slate-400 mt-2">Paylaşım: ${new Date(d.createdAt).toLocaleString('tr-TR')}</p>  
        <hr class="my-4">  
        <h4 class="font-bold mb-3">Yorumlar (${d.comments.length})</h4>  
        ${commentsHtml}  
        <form id="commentForm" class="flex gap-2 mt-3">  
          <input id="commentInput" maxlength="500" required class="min-w-0 flex-1 p-3 border rounded-xl text-sm" placeholder="Yorum yaz..." />  
          <button type="submit" class="bg-emerald-600 text-white px-4 rounded-xl text-sm">Gönder</button>  
        </form>  
        <p id="commentError" class="text-sm text-rose-600 mt-2"></p>  
      `;  
  
      const commentForm = document.getElementById('commentForm');  
      if (commentForm) {  
        commentForm.addEventListener('submit', (e) => {  
          e.preventDefault();  
  
          if (!currentUser) {  
            openAuth(false);  
            return;  
          }  
  
          if (d.demo) {  
            const commentError = document.getElementById('commentError');  
            commentError.textContent = 'Örnek kayıtlara yorum eklenemez.';  
            return;  
          }  
  
          const text = document.getElementById('commentInput').value.trim();  
          if (!text) return;  
  
          d.comments.push({  
            author: currentUser.username,  
            text,  
            date: new Date().toLocaleString('tr-TR'),  
            avatar: currentUser.avatar  
          });  
  
          if (saveStorage(KEYS.deals, deals)) {  
            openDetail(id);  
            renderDeals();  
          }  
        });  
      }  
  
      showModal('detailModal');  
    }  
  
    function openProfile(username) {  
      const name = String(username || '').trim();  
      if (!name) return;  
  
      const ownDeals = deals.filter(d => d.author === name && !d.demo);  
      const commentsCount = deals.reduce((total, deal) => {  
        return total + deal.comments.filter(c => c.author === name).length;  
      }, 0);  
  
      const userRecord = users.find(u => u.username === name);  
      const avatar = avatarSafe(userRecord?.avatar || ownDeals[0]?.authorAvatar || DEFAULT_AVATAR);  
  
      const profileContent = document.getElementById('profileContent');  
      profileContent.innerHTML = `  
        <div class="text-center">  
          <img src="${esc(avatar)}" class="w-20 h-20 rounded-full object-cover mx-auto" alt="">  
          <h3 class="text-xl font-bold mt-2">${esc(name)}</h3>  
        </div>  
        <div class="grid grid-cols-2 gap-3 my-4 text-center">  
          <div class="p-3 bg-slate-50 rounded-xl">  
            <b class="block text-xl">${ownDeals.length}</b>  
            <span class="text-xs">Paylaşılan fırsat</span>  
          </div>  
          <div class="p-3 bg-slate-50 rounded-xl">  
            <b class="block text-xl">${commentsCount}</b>  
            <span class="text-xs">Yorum</span>  
          </div>  
        </div>  
        <h4 class="font-bold mb-2">Fırsatları</h4>  
        ${ownDeals.length  
          ? ownDeals.map(d => `  
            <button type="button" class="profileDeal block w-full text-left p-3 border rounded-xl mb-2" data-id="${esc(d.id)}">  
              ${esc(d.title)} — ${money(d.newPrice)}  
            </button>  
          `).join('')  
          : '<p class="text-sm text-slate-400">Henüz fırsat paylaşmamış.</p>'  
        }  
      `;  
  
      document.querySelectorAll('.profileDeal').forEach(button => {  
        button.addEventListener('click', () => {  
          hideModal('profileModal');  
          openDetail(button.dataset.id);  
        });  
      });  
  
      showModal('profileModal');  
    }  
  
    function openPostModal() {  
      if (!ensureUserLoggedIn()) return;  
      const postError = document.getElementById('postError');  
      postError.textContent = '';  
      document.getElementById('postForm').reset();  
      showModal('postModal');  
    }  
  
    document.addEventListener('keydown', (event) => {  
      if (event.key === 'Escape') {  
        document.querySelectorAll('.modal').forEach(modal => hideModal(modal.id));  
      }  
    });  
  
    window.openPostModal = openPostModal;  
    window.hideModal = hideModal;  
    window.showModal = showModal;  
    window.filterDeals = filterDeals;  
    window.openDetail = openDetail;  
    window.openProfile = openProfile;  
    window.startDislike = startDislike;  
    window.vote = vote;  
    window.toggleAuthMode = toggleAuthMode;  
    window.openAuth = openAuth;  
  
    document.getElementById('authForm').addEventListener('submit', handleAuthSubmit);  
    document.getElementById('postForm').addEventListener('submit', handlePostSubmit);  
  
    loadState();  
    renderHeader();  
    renderDeals();  
  </script>  </body>  
</html> 
