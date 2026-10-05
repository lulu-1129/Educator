<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>教師專業發展與研習活動網</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Noto Sans TC -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Noto Sans TC"', 'sans-serif'],
                    },
                    colors: {
                        edu: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            500: '#2563eb',
                            600: '#1d4ed8',
                            700: '#1e40af',
                            800: '#1e3a8a',
                            900: '#0f172a',
                        }
                    }
                }
            }
        }
    </script>
    
    <style>
        body {
            font-family: 'Noto Sans TC', sans-serif;
            background-color: #f8fafc;
            color: #334155;
        }
        .card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card-hover:hover {
            transform: translateY(-4px);
            box-shadow: 0 16px 32px -8px rgba(30, 58, 138, 0.15);
        }
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f5f9;
        }
        ::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
        .scrollbar-none::-webkit-scrollbar {
            display: none;
        }
        .scrollbar-none {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col pt-36 md:pt-32">

    <!-- 固定頂部導航列 -->
    <header class="fixed top-0 left-0 right-0 bg-white/95 backdrop-blur-md shadow-sm z-40 border-b border-slate-100">
        <!-- 頂部主標題區域 -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <!-- 品牌標誌 -->
                <div class="flex items-center space-x-3 select-none">
                    <div class="w-10 h-10 rounded-xl bg-edu-600 text-white flex items-center justify-center font-bold text-xl shadow-md shadow-edu-500/20">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <div>
                        <div class="flex items-center space-x-2">
                            <h1 class="text-lg font-bold text-slate-800 leading-tight">教師專業成長研習網</h1>
                            <span id="viewBadge" class="hidden px-2 py-0.5 text-[10px] font-bold rounded-full bg-amber-100 text-amber-800 border border-amber-300">
                                後台管理控制台
                            </span>
                        </div>
                        <p class="text-xs text-slate-500">Educator Professional Development Portal</p>
                    </div>
                </div>

                <!-- 右側操作按鈕區：搜尋與前台/後台狀態 controls -->
                <div class="flex items-center space-x-2 sm:space-x-3">
                    <!-- 前台搜尋框 -->
                    <div id="topSearchBox" class="relative hidden sm:block w-48 lg:w-64">
                        <input type="text" id="searchInput" oninput="handleSearch()" placeholder="搜尋研習主題或講師..." 
                               class="w-full pl-9 pr-4 py-1.5 text-xs lg:text-sm bg-slate-100 border border-transparent rounded-full focus:bg-white focus:border-edu-500 focus:outline-none transition">
                        <i class="fa-solid fa-magnifying-glass absolute left-3 top-2.5 text-xs text-slate-400"></i>
                    </div>

                    <!-- 後台專用：安全登出按鈕 (預設隱藏) -->
                    <button id="logoutBtn" onclick="logoutBackend()" class="hidden px-3.5 py-1.5 bg-slate-800 hover:bg-slate-900 text-white text-xs md:text-sm font-semibold rounded-lg transition flex items-center space-x-1.5 shadow-sm">
                        <i class="fa-solid fa-right-from-bracket text-red-400"></i>
                        <span>登出並返回前台</span>
                    </button>
                </div>
            </div>
        </div>

        <!-- 前台選單 Bar (三個主要場次選單) -->
        <div id="frontendNav" class="bg-slate-50 border-t border-slate-200/60 shadow-inner">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <nav class="flex space-x-2 overflow-x-auto py-2 scrollbar-none" id="tabContainer">
                    <button onclick="switchTab('all')" data-tab="all" class="tab-btn px-5 py-2 text-xs md:text-sm font-medium rounded-lg whitespace-nowrap transition bg-edu-600 text-white shadow-sm">
                        <i class="fa-solid fa-list-ul mr-1.5"></i>所有場次
                    </button>
                    <button onclick="switchTab('online')" data-tab="online" class="tab-btn px-5 py-2 text-xs md:text-sm font-medium rounded-lg whitespace-nowrap transition text-slate-600 hover:bg-slate-200/60">
                        <i class="fa-solid fa-laptop-house mr-1.5 text-blue-500"></i>線上活動
                    </button>
                    <button onclick="switchTab('offline')" data-tab="offline" class="tab-btn px-5 py-2 text-xs md:text-sm font-medium rounded-lg whitespace-nowrap transition text-slate-600 hover:bg-slate-200/60">
                        <i class="fa-solid fa-users-rectangle mr-1.5 text-emerald-500"></i>實體活動
                    </button>
                </nav>
            </div>
        </div>
    </header>

    <!-- 前台畫面：研習活動展示區 -->
    <main id="frontendView" class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 my-6">
        <!-- 行動裝置搜尋框 -->
        <div class="sm:hidden mb-4">
            <div class="relative w-full">
                <input type="text" id="mobileSearchInput" oninput="handleMobileSearch()" placeholder="搜尋研習主題、講師或關鍵字..." 
                       class="w-full pl-9 pr-4 py-2 text-xs bg-white border border-slate-200 rounded-xl focus:border-edu-500 focus:outline-none shadow-sm">
                <i class="fa-solid fa-magnifying-glass absolute left-3 top-3 text-xs text-slate-400"></i>
            </div>
        </div>

        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-3 mb-6 pb-4 border-b border-slate-200">
            <div>
                <h2 id="currentCategoryTitle" class="text-xl font-bold text-slate-800 flex items-center">
                    <i class="fa-solid fa-folder-open mr-2 text-edu-600"></i>所有研習場次
                </h2>
                <p id="currentCategoryDesc" class="text-xs text-slate-500 mt-0.5">點擊報名按鈕即可直接開啟專屬 Google 報名表單</p>
            </div>
            <div class="flex items-center space-x-2 text-xs text-slate-500">
                <span>共計 <strong id="eventCount" class="text-edu-600 font-semibold">0</strong> 個研習場次</span>
            </div>
        </div>

        <!-- 活動卡片 Grid -->
        <div id="eventsGrid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8"></div>

        <!-- 無資料狀態 -->
        <div id="emptyState" class="hidden text-center py-16 bg-white rounded-2xl border border-dashed border-slate-300">
            <div class="w-16 h-16 bg-slate-100 rounded-full flex items-center justify-center mx-auto mb-3 text-slate-400 text-2xl">
                <i class="fa-regular fa-folder-open"></i>
            </div>
            <h3 class="text-base font-medium text-slate-700">未找到符合條件的研習活動</h3>
            <p class="text-xs text-slate-400 mt-1">請切換其他分頁或調整搜尋關鍵字</p>
        </div>
    </main>

    <!-- 後台畫面：研習管理控制台 (預設隱藏，僅登入後可見) -->
    <main id="backendView" class="hidden flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 my-6 space-y-6">
        <!-- 後台頂部 Banner -->
        <div class="bg-gradient-to-r from-slate-900 via-slate-800 to-edu-900 text-white rounded-2xl p-6 shadow-xl flex flex-col md:flex-row items-start md:items-center justify-between gap-4">
            <div>
                <div class="flex items-center space-x-2 mb-1">
                    <span class="px-2.5 py-0.5 rounded-full text-[10px] font-bold bg-amber-400 text-slate-900">後台控制台</span>
                    <span class="text-slate-300 text-xs">Educator Admin Portal</span>
                </div>
                <h2 class="text-2xl font-extrabold tracking-tight">研習場次管理系統</h2>
                <p class="text-xs text-slate-300 mt-1">即時發布與編輯研習活動課程資訊、管理線上與實體研習內容。</p>
            </div>
            <div class="flex items-center space-x-3 shrink-0">
                <button onclick="openAddModal()" class="px-4 py-2 bg-edu-600 hover:bg-edu-500 text-white font-semibold text-xs md:text-sm rounded-xl shadow transition flex items-center space-x-1.5 border border-edu-400/30">
                    <i class="fa-solid fa-plus"></i>
                    <span>發布新研習活動</span>
                </button>
            </div>
        </div>

        <!-- 數據指標概覽 -->
        <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
            <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="text-slate-500 text-xs font-medium">總研習場次</div>
                <div id="statTotalEvents" class="text-2xl font-bold text-slate-800 mt-1">0</div>
            </div>
            <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="text-slate-500 text-xs font-medium">線上研習數</div>
                <div id="statOnlineEvents" class="text-2xl font-bold text-blue-600 mt-1">0</div>
            </div>
            <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="text-slate-500 text-xs font-medium">實體研習數</div>
                <div id="statOfflineEvents" class="text-2xl font-bold text-emerald-600 mt-1">0</div>
            </div>
        </div>

        <!-- 後台研習列表卡片 -->
        <div class="bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden p-4 md:p-6">
            <div class="flex items-center justify-between mb-4 pb-3 border-b border-slate-100">
                <div>
                    <h3 class="font-bold text-slate-800 text-base flex items-center">
                        <i class="fa-solid fa-calendar-days mr-2 text-edu-600"></i>已發布研習場次
                    </h3>
                    <p class="text-xs text-slate-500 mt-0.5">點擊操作按鈕可進行活動內容編輯、預覽報名表單或刪除研習</p>
                </div>
            </div>
            <div id="adminEventsList" class="space-y-3">
                <!-- 動態渲染後台研習列表 -->
            </div>
        </div>
    </main>

    <!-- 頁尾 -->
    <footer class="bg-white border-t border-slate-200 mt-12 py-6">
        <div class="max-w-7xl mx-auto px-4 text-center text-xs text-slate-500 space-y-1.5">
            <p>© 2026 教師專業發展研習資訊網 | 支援 Google 表單線上報名與研習場次管理</p>
            <p class="text-[11px] text-slate-400">旨在為教師提供高品質增能研習與課堂教學賦能工具</p>
        </div>
    </footer>

    <!-- 管理員驗證登入彈窗 (Modal) -->
    <div id="adminLoginModal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-sm w-full shadow-2xl overflow-hidden p-6 text-center border border-slate-100">
            <div class="w-12 h-12 bg-edu-100 text-edu-600 rounded-full flex items-center justify-center mx-auto mb-3 text-xl">
                <i class="fa-solid fa-user-shield"></i>
            </div>
            <h3 class="text-base font-bold text-slate-800 mb-1">管理者權限驗證</h3>
            <p class="text-xs text-slate-500 mb-4">請使用 Supabase 管理員帳號登入控制台</p>
            
            <form onsubmit="handleAdminLogin(event)" class="space-y-3">
                <div class="relative">
                    <input type="email" id="adminEmailInput" placeholder="管理員 Email" required autocomplete="username"
                           class="w-full px-3 py-2 text-xs border border-slate-300 rounded-xl focus:border-edu-500 focus:outline-none">
                </div>
                <div class="relative">
                    <input type="password" id="adminPasswordInput" placeholder="管理員密碼" required autocomplete="current-password"
                           class="w-full px-3 py-2 text-xs border border-slate-300 rounded-xl focus:border-edu-500 focus:outline-none">
                </div>
                <div id="loginErrorMsg" class="hidden text-xs text-red-500 font-medium">Email 或密碼不正確，或此帳號尚未被設定為管理員。</div>
                <div class="flex space-x-2 pt-2">
                    <button type="button" onclick="closeAdminLoginModal()" class="w-1/2 py-2 border border-slate-300 text-slate-600 text-xs font-semibold rounded-xl hover:bg-slate-50 transition">
                        取消
                    </button>
                    <button type="submit" class="w-1/2 py-2 bg-edu-600 hover:bg-edu-700 text-white text-xs font-semibold rounded-xl transition shadow">
                        登入後台
                    </button>
                </div>
            </form>
        </div>
    </div>

    <!-- Google 表單報名彈出視窗 (Modal) -->
    <div id="registerModal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-2 sm:p-4">
        <div class="bg-white rounded-2xl max-w-4xl w-full shadow-2xl overflow-hidden transform transition-all duration-200 scale-95 opacity-0 flex flex-col max-h-[92vh]" id="registerModalBox">
            <!-- Modal Header -->
            <div class="bg-slate-900 text-white p-4 sm:p-5 flex items-center justify-between shrink-0 border-b border-slate-800">
                <div class="pr-4 flex items-center space-x-3">
                    <div class="w-9 h-9 bg-edu-600 rounded-xl flex items-center justify-center text-white font-extrabold text-lg shadow">
                        <i class="fa-solid fa-file-pen"></i>
                    </div>
                    <div>
                        <span class="inline-block px-2 py-0.5 bg-edu-500/20 text-edu-300 border border-edu-500/30 rounded text-[10px] font-semibold mb-0.5">
                            Google 表單線上報名
                        </span>
                        <h3 id="modalEventTitle" class="text-base sm:text-lg font-bold leading-tight">研習課程名稱</h3>
                    </div>
                </div>
                <div class="flex items-center space-x-2 shrink-0">
                    <a id="modalExternalFormBtn" href="#" target="_blank" rel="noopener noreferrer" title="在新分頁開啟表單" class="text-edu-200 hover:text-white bg-edu-600/30 hover:bg-edu-600/50 px-3 py-1.5 rounded-xl text-xs font-semibold transition flex items-center space-x-1.5 border border-edu-400/30">
                        <span>新視窗開啟</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[11px]"></i>
                    </a>
                    <button onclick="closeRegisterModal()" class="text-slate-400 hover:text-white transition p-1.5 rounded-lg hover:bg-white/10">
                        <i class="fa-solid fa-xmark text-xl"></i>
                    </button>
                </div>
            </div>
            
            <!-- Google Form Container -->
            <div class="relative flex-grow bg-slate-100 min-h-[500px] sm:min-h-[600px] overflow-hidden">
                <div id="formLoadingSpinner" class="absolute inset-0 flex flex-col items-center justify-center bg-white text-slate-600 z-10">
                    <i class="fa-solid fa-circle-notch fa-spin text-4xl text-edu-600 mb-3"></i>
                    <span class="text-sm font-medium text-slate-700">正在連結載入 Google 報名表單...</span>
                    <p class="text-xs text-slate-400 mt-1">若載入時間較長，可點選右上角「新視窗開啟」進行填寫</p>
                </div>
                <iframe id="googleFormIframe" src="" class="w-full h-full min-h-[500px] sm:min-h-[600px] border-0"></iframe>
            </div>
        </div>
    </div>

    <!-- 新增/編輯研習 Modal -->
    <div id="addModal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-lg w-full shadow-2xl overflow-hidden max-h-[90vh] flex flex-col">
            <div class="bg-slate-800 text-white p-4 flex items-center justify-between shrink-0">
                <h3 id="modalFormTitle" class="text-base font-bold"><i class="fa-solid fa-calendar-plus mr-2 text-edu-400"></i>發布新研習活動</h3>
                <button onclick="closeAddModal()" class="text-slate-300 hover:text-white transition">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <form id="eventModalForm" onsubmit="handleSaveEvent(event)" class="p-6 space-y-3 overflow-y-auto custom-scrollbar flex-grow text-xs">
                <div>
                    <label class="block font-semibold text-slate-700 mb-1">活動名稱 <span class="text-red-500">*</span></label>
                    <input type="text" required id="newTitle" placeholder="例如：Super Fun 5 備課趴：We Are Team We Can Help 2.0" class="w-full px-3 py-2 border border-slate-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-edu-500">
                </div>

                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block font-semibold text-slate-700 mb-1">活動形式</label>
                        <select id="newMode" class="w-full px-3 py-2 border border-slate-300 rounded-lg focus:ring-2 focus:ring-edu-500">
                            <option value="online">線上活動</option>
                            <option value="offline">實體活動</option>
                        </select>
                    </div>
                    <div>
                        <label class="block font-semibold text-slate-700 mb-1">報名狀態</label>
                        <select id="newIsExpired" class="w-full px-3 py-2 border border-slate-300 rounded-lg focus:ring-2 focus:ring-edu-500">
                            <option value="false">🟢 開放報名中</option>
                            <option value="true">🔴 已截止報名 (卡片反灰/禁用按鈕)</option>
                        </select>
                    </div>
                </div>

                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block font-semibold text-slate-700 mb-1">日期與時間 <span class="text-red-500">*</span></label>
                        <input type="text" required id="newDate" placeholder="例如：08/19(三) 上午 09:30 - 12:30" class="w-full px-3 py-2 border border-slate-300 rounded-lg">
                    </div>
                    <div>
                        <label class="block font-semibold text-slate-700 mb-1">主講人 / 講師 <span class="text-red-500">*</span></label>
                        <input type="text" required id="newSpeaker" placeholder="例如：周儀 Vicky 老師 (宜蘭縣黎明國小)" class="w-full px-3 py-2 border border-slate-300 rounded-lg">
                    </div>
                </div>

                <div class="grid grid-cols-2 gap-3">
                    <div>
                        <label class="block font-semibold text-slate-700 mb-1">報名截止提示</label>
                        <input type="text" id="newDeadline" placeholder="例如：08/12(三) 23:59截止" class="w-full px-3 py-2 border border-slate-300 rounded-lg">
                    </div>
                    <div>
                        <label class="block font-semibold text-slate-700 mb-1">主題標籤 (逗號分隔)</label>
                        <input type="text" id="newTags" placeholder="主題式教學, 暑期備課趴" class="w-full px-3 py-2 border border-slate-300 rounded-lg">
                    </div>
                </div>

                <div>
                    <label class="block font-semibold text-slate-700 mb-1">研習地點 / 上課會議連結</label>
                    <input type="text" id="newLocation" placeholder="例如：Google Meet 線上會議室 / 創客研習中心 A301" class="w-full px-3 py-2 border border-slate-300 rounded-lg">
                </div>

                <div>
                    <label class="block font-semibold text-slate-700 mb-1">Google 表單報名網址 <span class="text-edu-600">(完整的 Google Form 網址)</span></label>
                    <input type="url" required id="newGoogleForm" placeholder="https://docs.google.com/forms/d/e/.../viewform" class="w-full px-3 py-2 border border-slate-300 rounded-lg focus:ring-2 focus:ring-edu-500">
                </div>

                <div>
                    <label class="block font-semibold text-slate-700 mb-1">💡 課堂帶得走技能 / 研習亮點 (一行一項)</label>
                    <textarea id="newSkills" rows="3" placeholder="• 內容涵蓋 Super Fun 5 主題式教學應用&#10;• 培育單字與句型實際溝通與靈活運用" class="w-full px-3 py-2 border border-slate-300 rounded-lg"></textarea>
                </div>

                <div>
                    <label class="block font-semibold text-slate-700 mb-1">研習海報圖片 <span class="text-slate-400 font-normal">(編輯時若未選擇則保留原圖片)</span></label>
                    <input type="file" id="newImageFile" accept="image/*" class="w-full text-xs text-slate-500 file:mr-3 file:py-1.5 file:px-3 file:rounded-lg file:border-0 file:text-xs file:font-semibold file:bg-edu-50 file:text-edu-700 hover:file:bg-edu-100">
                </div>

                <div class="pt-3 flex justify-end space-x-2 border-t border-slate-100">
                    <button type="button" onclick="closeAddModal()" class="px-4 py-2 border border-slate-300 text-slate-600 hover:bg-slate-100 rounded-lg">取消</button>
                    <button type="submit" id="submitModalBtn" class="px-4 py-2 bg-edu-600 hover:bg-edu-700 text-white font-medium rounded-lg shadow-sm">發布研習</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Toast 提示訊息 -->
    <div id="toast" class="fixed bottom-5 right-5 z-50 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none">
        <div class="bg-slate-800 text-white px-4 py-3 rounded-xl shadow-xl flex items-center space-x-3 border border-slate-700">
            <div id="toastIcon" class="text-emerald-400 text-lg"><i class="fa-solid fa-circle-check"></i></div>
            <span id="toastMsg" class="text-xs md:text-sm font-medium">訊息提示</span>
        </div>
    </div>

    <!-- Supabase JS SDK -->
    <script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>

    <script>
        // =========================
        // Supabase 設定
        // =========================
        // 請把下面兩個值換成你的 Supabase Project URL / anon public key。
        const SUPABASE_URL = 'https://jyzylwbsazoymbsheezk.supabase.co';
        const SUPABASE_ANON_KEY = 'sb_publishable_fKuw_r3QzW37P3kw-sbcUQ_aELhZb9V';
        const supabaseClient = window.supabase.createClient(
            SUPABASE_URL,
            SUPABASE_ANON_KEY
        );

        // =========================
        // 前後台模式狀態
        // =========================
        let currentMode = 'frontend';
        let currentTab = 'all';
        let searchQuery = '';
        let editingEventId = null;
        let currentUser = null;

        const defaultEvents = [
            {
                id: 'default-1',
                title: "第三場：We Are Team We Can Help 2.0 (Super Fun 5 備課趴)",
                mode: "online",
                date: "08/19(三) 上午 09:30 - 12:30",
                speaker: "周儀 Vicky 老師 (宜蘭縣黎明國小)",
                location: "Google Meet 線上會議室 (報名完成後發送連結)",
                deadline: "08/12(三) 23:59截止",
                isExpired: true,
                tags: ["主題式教學", "暑期備課趴"],
                skills: [
                    "內容涵蓋 Super Fun 5 主題式教學應用與深度學習",
                    "培育單字與句型實際之溝通與靈活運用",
                    "橫向與縱向架構連結，完美扣合最新教學趨勢"
                ],
                desc: "結合主題式教學帶領學生深度學習，豐富備課資源讓教學更輕鬆！",
                image: "https://images.unsplash.com/photo-1577896851231-70ef18881754?auto=format&fit=crop&w=800&q=80",
                googleFormUrl: "https://docs.google.com/forms/d/e/1FAIpQLSc_Example1/viewform"
            },
            {
                id: 'default-2',
                title: "繪本創客與探索式引導教學工作坊",
                mode: "offline",
                date: "10/18(六) 09:00 - 12:00",
                speaker: "林美玲 老師 (知名繪本教育專家)",
                location: "第一會議室 / 創客研習中心",
                deadline: "10/10 額滿截止",
                isExpired: false,
                tags: ["繪本教學", "創客教育"],
                skills: [
                    "結合圖像學習特點引導學生創造力",
                    "配合動手做實踐跨領域素養教學",
                    "課堂班級常規建立與遊戲化設計"
                ],
                desc: "引導兒童想像力與口語表達，輕鬆打造高互動課堂。",
                image: "https://images.unsplash.com/photo-1503676260728-1c00da094a0b?auto=format&fit=crop&w=800&q=80",
                googleFormUrl: "https://docs.google.com/forms/d/e/1FAIpQLSc_Example2/viewform"
            },
            {
                id: 'default-3',
                title: "AI 生成式工具輔助數學邏輯思維",
                mode: "online",
                date: "10/22(四) 13:30 - 16:30",
                speaker: "陳建宏 博士 (數位教育研究所)",
                location: "Cisco Webex 線上會議室",
                deadline: "10/18 額滿截止",
                isExpired: false,
                tags: ["AI數位教學", "邏輯思維"],
                skills: [
                    "運用 AI 工具設計圖形化數學解題提示",
                    "提升學生自主學習與思考樂趣",
                    "輕鬆生成差異化教學作業與學習單"
                ],
                desc: "探索科技與數學結合的無限可能，賦能教師智慧教學。",
                image: "https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=800&q=80",
                googleFormUrl: "https://docs.google.com/forms/d/e/1FAIpQLSc_Example3/viewform"
            }
        ];

        // 這個陣列現在只作為畫面狀態。
        // 真正資料來源改成 Supabase Database。
        let events = [];

        // 將資料庫欄位轉成目前前端使用的格式
        function normalizeEvent(row) {
            return {
                id: row.id,
                title: row.title || '',
                mode: row.mode || 'online',
                date: row.event_date || '',
                speaker: row.speaker || '',
                location: row.location || '',
                deadline: row.deadline || '',
                isExpired: !!row.is_expired,
                tags: Array.isArray(row.tags) ? row.tags : [],
                skills: Array.isArray(row.skills) ? row.skills : [],
                desc: row.description || row.title || '',
                image: row.image_url || '',
                googleFormUrl: row.google_form_url || ''
            };
        }

        // 將前端資料轉成資料庫欄位
        function eventToRow(ev) {
            return {
                title: ev.title,
                mode: ev.mode,
                event_date: ev.date,
                speaker: ev.speaker,
                location: ev.location || '',
                deadline: ev.deadline || '',
                is_expired: !!ev.isExpired,
                tags: ev.tags || [],
                skills: ev.skills || [],
                description: ev.desc || ev.title || '',
                image_url: ev.image || '',
                google_form_url: ev.googleFormUrl || ''
            };
        }

        async function isCurrentUserAdmin() {
            if (!currentUser) return false;

            const { data, error } = await supabaseClient
                .from('admin_users')
                .select('user_id')
                .eq('user_id', currentUser.id)
                .maybeSingle();

            if (error) {
                console.error('檢查管理員權限失敗:', error);
                return false;
            }

            return !!data;
        }

        // 從 Supabase 載入公開研習資料
        async function loadEventsFromDatabase() {
            try {
                const { data, error } = await supabaseClient
                    .from('events')
                    .select('*')
                    .order('created_at', { ascending: false });

                if (error) throw error;

                events = (data || []).map(normalizeEvent);
                renderEvents();

                if (currentMode === 'backend') {
                    renderBackendEvents();
                    updateBackendStats();
                }
            } catch (error) {
                console.error('無法從 Supabase 載入研習資料:', error);

                // 第一次設定 Supabase 時，如果尚未建立資料，
                // 先顯示原本的預設內容，不會讓官網整頁空白。
                events = [...defaultEvents];
                renderEvents();

                if (currentMode === 'backend') {
                    renderBackendEvents();
                    updateBackendStats();
                }

                showToast('資料庫連線失敗，請檢查 Supabase 設定', 'error');
            }
        }

        async function uploadEventImage(file) {
            if (!file) return null;

            const extension = file.name.split('.').pop().toLowerCase() || 'jpg';
            const filePath = `events/${crypto.randomUUID()}.${extension}`;

            const { error: uploadError } = await supabaseClient
                .storage
                .from('event-images')
                .upload(filePath, file, {
                    cacheControl: '3600',
                    upsert: false
                });

            if (uploadError) throw uploadError;

            const { data } = supabaseClient
                .storage
                .from('event-images')
                .getPublicUrl(filePath);

            return data.publicUrl;
        }

        async function handleAdminLogin(e) {
            e.preventDefault();

            const email = document.getElementById('adminEmailInput').value.trim();
            const password = document.getElementById('adminPasswordInput').value;

            try {
                const { data, error } = await supabaseClient.auth.signInWithPassword({
                    email,
                    password
                });

                if (error) throw error;

                currentUser = data.user;

                const isAdmin = await isCurrentUserAdmin();

                if (!isAdmin) {
                    await supabaseClient.auth.signOut();
                    currentUser = null;
                    throw new Error('此帳號不是管理員');
                }

                closeAdminLoginModal();
                switchToBackend();
                showToast('已成功登入【後台管理控制台】', 'success');
            } catch (error) {
                console.error('管理員登入失敗:', error);
                document.getElementById('loginErrorMsg').classList.remove('hidden');
            }
        }

        function openAdminLoginModal() {
            document.getElementById('adminEmailInput').value = '';
            document.getElementById('adminPasswordInput').value = '';
            document.getElementById('loginErrorMsg').classList.add('hidden');
            document.getElementById('adminLoginModal').classList.remove('hidden');

            setTimeout(() => {
                document.getElementById('adminEmailInput').focus();
            }, 100);
        }

        function closeAdminLoginModal() {
            document.getElementById('adminLoginModal').classList.add('hidden');

            if (currentMode !== 'backend' && window.location.search.includes('admin=')) {
                try {
                    const cleanUrl = window.location.pathname + window.location.hash;
                    window.history.replaceState(
                        { mode: 'frontend' },
                        '',
                        cleanUrl || window.location.pathname
                    );
                } catch (e) {
                    console.warn("無法清除網址參數:", e);
                }
            }
        }

        async function switchToBackend() {
            currentMode = 'backend';

            try {
                const backendUrl = window.location.pathname + '?admin=true' + window.location.hash;
                window.history.pushState({ mode: 'backend' }, '', backendUrl);
            } catch (e) {
                console.warn("無法更新網址為後台狀態:", e);
            }

            document.getElementById('frontendView').classList.add('hidden');
            document.getElementById('frontendNav').classList.add('hidden');
            document.getElementById('topSearchBox').classList.add('hidden');
            document.getElementById('backendView').classList.remove('hidden');

            document.getElementById('viewBadge').classList.remove('hidden');
            document.getElementById('logoutBtn').classList.remove('hidden');

            await loadEventsFromDatabase();
            updateBackendStats();
            renderBackendEvents();
        }

        async function logoutBackend() {
            await supabaseClient.auth.signOut();
            currentUser = null;
            currentMode = 'frontend';

            try {
                const cleanUrl = window.location.pathname + window.location.hash;
                window.history.pushState(
                    { mode: 'frontend' },
                    '',
                    cleanUrl || window.location.pathname
                );
            } catch (e) {
                console.warn("無法更新網址為前台狀態:", e);
            }

            document.getElementById('backendView').classList.add('hidden');
            document.getElementById('frontendView').classList.remove('hidden');
            document.getElementById('frontendNav').classList.remove('hidden');
            document.getElementById('topSearchBox').classList.remove('hidden');

            document.getElementById('viewBadge').classList.add('hidden');
            document.getElementById('logoutBtn').classList.add('hidden');

            await loadEventsFromDatabase();
            showToast('已登出並返回【前台研習活動網】', 'info');
        }

        window.addEventListener('popstate', async () => {
            const urlParams = new URLSearchParams(window.location.search);
            const isAdmin = urlParams.get('admin') === 'true';

            if (isAdmin && currentMode !== 'backend') {
                const isAdminUser = await isCurrentUserAdmin();
                if (isAdminUser) {
                    currentUser = (await supabaseClient.auth.getUser()).data.user;
                    await switchToBackend();
                } else {
                    openAdminLoginModal();
                }
            } else if (!isAdmin && currentMode === 'backend') {
                await logoutBackend();
            }
        });

        // 前台分類
        function switchTab(tabKey) {
            currentTab = tabKey;

            document.querySelectorAll('.tab-btn').forEach(btn => {
                if (btn.getAttribute('data-tab') === tabKey) {
                    btn.className = 'tab-btn px-5 py-2 text-xs md:text-sm font-medium rounded-lg whitespace-nowrap transition bg-edu-600 text-white shadow-sm';
                } else {
                    btn.className = 'tab-btn px-5 py-2 text-xs md:text-sm font-medium rounded-lg whitespace-nowrap transition text-slate-600 hover:bg-slate-200/60';
                }
            });

            const meta = categoryMeta[tabKey] || categoryMeta['all'];
            document.getElementById('currentCategoryTitle').innerHTML =
                `<i class="fa-solid fa-folder-open mr-2 text-edu-600"></i>${meta.title}`;
            document.getElementById('currentCategoryDesc').innerText = meta.desc;
            renderEvents();
        }

        function handleSearch() {
            searchQuery = document.getElementById('searchInput').value.trim().toLowerCase();
            renderEvents();
        }

        function handleMobileSearch() {
            searchQuery = document.getElementById('mobileSearchInput').value.trim().toLowerCase();
            renderEvents();
        }

        // 前台活動卡片
        function renderEvents() {
            const grid = document.getElementById('eventsGrid');
            const emptyState = document.getElementById('emptyState');
            if (!grid || !emptyState) return;

            grid.innerHTML = '';

            const filtered = events.filter(item => {
                let matchTab = (currentTab === 'all') || (item.mode === currentTab);
                let matchQuery = !searchQuery ||
                    (item.title || '').toLowerCase().includes(searchQuery) ||
                    (item.speaker || '').toLowerCase().includes(searchQuery) ||
                    (item.tags || []).some(t => t.toLowerCase().includes(searchQuery));

                return matchTab && matchQuery;
            });

            document.getElementById('eventCount').innerText = filtered.length;

            if (filtered.length === 0) {
                emptyState.classList.remove('hidden');
                return;
            }

            emptyState.classList.add('hidden');

            filtered.forEach(ev => {
                const isExpired = !!ev.isExpired;

                const modeTag = ev.mode === 'online'
                    ? `<span class="bg-blue-600 text-white text-[11px] px-2.5 py-0.5 rounded-full font-bold shadow-sm"><i class="fa-solid fa-video mr-1"></i>線上研習</span>`
                    : `<span class="bg-emerald-600 text-white text-[11px] px-2.5 py-0.5 rounded-full font-bold shadow-sm"><i class="fa-solid fa-location-dot mr-1"></i>實體研習</span>`;

                const statusTag = isExpired
                    ? `<span class="bg-slate-700 text-white text-[11px] px-2.5 py-0.5 rounded-full font-bold shadow-sm"><i class="fa-solid fa-lock mr-1"></i>已截止報名</span>`
                    : '';

                const tagsHtml = (ev.tags || []).map(tag =>
                    `<span class="inline-block bg-pink-100 text-pink-700 font-semibold text-[11px] px-2.5 py-0.5 rounded-full border border-pink-200">#${tag}</span>`
                ).join(' ');

                const skillsHtml = (ev.skills || []).map(s =>
                    `<li class="flex items-start"><span class="text-amber-500 mr-1.5">•</span><span>${s}</span></li>`
                ).join('');

                const deadlineText = ev.deadline ? ` (${ev.deadline})` : '';

                const buttonHtml = isExpired
                    ? `<button disabled class="w-full py-3 px-4 bg-slate-300 text-slate-600 font-bold text-sm md:text-base rounded-xl cursor-not-allowed border border-slate-300 shadow-none flex items-center justify-center">
                        <span>報名已截止${deadlineText}</span>
                       </button>`
                    : `<button onclick="openRegisterModal('${ev.id}')" class="w-full py-3 px-4 bg-edu-600 hover:bg-edu-700 active:bg-edu-800 text-white font-bold text-sm md:text-base rounded-xl shadow-md hover:shadow-lg transition transform active:scale-98 flex items-center justify-center border border-edu-500">
                        <span>點我線上報名${deadlineText}</span>
                       </button>`;

                const safeImage = ev.image || 'https://images.unsplash.com/photo-1524178232363-1fb2b075b655?auto=format&fit=crop&w=800&q=80';

                const card = document.createElement('div');
                card.className = `bg-white rounded-2xl border border-slate-200/80 shadow-sm overflow-hidden flex flex-col relative group ${isExpired ? 'grayscale opacity-70 bg-slate-50' : 'card-hover'}`;
                card.innerHTML = `
                    <div class="relative h-60 bg-slate-100 overflow-hidden">
                        <img src="${safeImage}" alt="${ev.title}" class="w-full h-full object-cover ${isExpired ? '' : 'group-hover:scale-105'} transition-transform duration-500" onerror="this.src='https://images.unsplash.com/photo-1524178232363-1fb2b075b655?auto=format&fit=crop&w=800&q=80'">
                        <div class="absolute inset-0 bg-gradient-to-t from-slate-900/70 via-transparent to-transparent opacity-80"></div>
                        <div class="absolute top-3 left-3 flex space-x-1.5">
                            ${modeTag}
                            ${statusTag}
                        </div>
                    </div>

                    <div class="p-5 flex-grow flex flex-col justify-between space-y-4">
                        <div>
                            <div class="flex flex-wrap gap-1.5 mb-2.5">${tagsHtml}</div>

                            <h3 class="text-lg font-bold text-slate-900 leading-snug mb-3">${ev.title}</h3>

                            <div class="space-y-1.5 text-xs text-slate-700 font-medium mb-4">
                                <div class="flex items-center text-slate-800">
                                    <i class="fa-regular fa-clock w-5 text-slate-500 text-sm"></i>
                                    <span>${ev.date}</span>
                                </div>
                                <div class="flex items-center text-slate-800">
                                    <i class="fa-solid fa-chalkboard-user w-5 text-slate-500 text-sm"></i>
                                    <span>講師：${ev.speaker}</span>
                                </div>
                                <div class="flex items-center text-slate-800">
                                    <i class="fa-solid fa-location-dot w-5 text-slate-500 text-sm"></i>
                                    <span>地點：${ev.location || (ev.mode === 'online' ? '線上會議室' : '實體研習教室')}</span>
                                </div>
                            </div>

                            <div class="bg-slate-50 rounded-xl p-3.5 border border-slate-200/80 text-xs text-slate-700">
                                <div class="font-bold text-slate-800 mb-1.5 flex items-center text-xs">
                                    <span class="text-base mr-1">💡</span>
                                    <span>課堂帶得走技能：</span>
                                </div>
                                <ul class="space-y-1 text-slate-600 leading-relaxed pl-0.5">${skillsHtml}</ul>
                            </div>
                        </div>

                        <div class="pt-2">${buttonHtml}</div>
                    </div>
                `;

                grid.appendChild(card);
            });
        }

        function updateBackendStats() {
            document.getElementById('statTotalEvents').innerText = events.length;
            document.getElementById('statOnlineEvents').innerText = events.filter(e => e.mode === 'online').length;
            document.getElementById('statOfflineEvents').innerText = events.filter(e => e.mode === 'offline').length;
        }

        function renderBackendEvents() {
            const container = document.getElementById('adminEventsList');
            if (!container) return;

            container.innerHTML = '';

            if (events.length === 0) {
                container.innerHTML = `<div class="text-center py-8 text-slate-400 text-xs">目前無任何研習活動，請點選上方「發布新研習活動」</div>`;
                return;
            }

            events.forEach(ev => {
                const modeBadge = ev.mode === 'online'
                    ? `<span class="bg-blue-100 text-blue-700 px-2 py-0.5 rounded text-[11px] font-semibold">線上研習</span>`
                    : `<span class="bg-emerald-100 text-emerald-700 px-2 py-0.5 rounded text-[11px] font-semibold">實體研習</span>`;

                const statusBadge = ev.isExpired
                    ? `<span class="bg-slate-200 text-slate-700 px-2 py-0.5 rounded text-[11px] font-semibold">已截止</span>`
                    : `<span class="bg-emerald-50 text-emerald-600 border border-emerald-200 px-2 py-0.5 rounded text-[11px] font-semibold">開放中</span>`;

                const item = document.createElement('div');
                item.className = "p-3.5 bg-slate-50 rounded-xl border border-slate-200 flex flex-col md:flex-row items-start md:items-center justify-between gap-3 text-xs";
                item.innerHTML = `
                    <div class="flex items-center space-x-3">
                        <img src="${ev.image || 'https://images.unsplash.com/photo-1524178232363-1fb2b075b655?auto=format&fit=crop&w=800&q=80'}" class="w-14 h-14 rounded-lg object-cover shrink-0 border border-slate-200">
                        <div>
                            <div class="flex items-center space-x-2">
                                ${modeBadge}
                                ${statusBadge}
                                <h4 class="font-bold text-slate-800 text-sm">${ev.title}</h4>
                            </div>
                            <div class="text-slate-500 mt-1 space-x-3">
                                <span><i class="fa-regular fa-clock mr-1"></i>${ev.date}</span>
                                <span><i class="fa-solid fa-chalkboard-user mr-1"></i>${ev.speaker}</span>
                            </div>
                        </div>
                    </div>
                    <div class="flex items-center space-x-2 shrink-0">
                        <button onclick="openRegisterModal('${ev.id}')" class="px-2.5 py-1.5 bg-white border border-slate-300 text-slate-700 rounded-lg hover:bg-slate-100 font-medium transition">預覽表單</button>
                        <button onclick="openEditModal('${ev.id}')" class="px-2.5 py-1.5 bg-amber-50 text-amber-700 border border-amber-200 rounded-lg hover:bg-amber-100 font-medium transition flex items-center space-x-1">
                            <i class="fa-solid fa-pen-to-square"></i>
                            <span>編輯研習</span>
                        </button>
                        <button onclick="deleteEvent('${ev.id}')" class="px-2.5 py-1.5 bg-red-50 text-red-600 border border-red-200 rounded-lg hover:bg-red-100 font-medium transition">刪除研習</button>
                    </div>
                `;

                container.appendChild(item);
            });
        }

        async function deleteEvent(eventId) {
            if (!confirm("確定要刪除這場研習活動嗎？")) return;

            try {
                const { error } = await supabaseClient
                    .from('events')
                    .delete()
                    .eq('id', eventId);

                if (error) throw error;

                await loadEventsFromDatabase();
                showToast('已成功刪除該場研習活動', 'info');
            } catch (error) {
                console.error('刪除失敗:', error);
                showToast('刪除失敗，請確認管理員權限與資料庫設定', 'error');
            }
        }

        function openAddModal() {
            editingEventId = null;
            document.getElementById('eventModalForm').reset();
            document.getElementById('newIsExpired').value = 'false';
            document.getElementById('modalFormTitle').innerHTML = `<i class="fa-solid fa-calendar-plus mr-2 text-edu-400"></i>發布新研習活動`;
            document.getElementById('submitModalBtn').innerText = '發布研習';
            document.getElementById('addModal').classList.remove('hidden');
        }

        function openEditModal(eventId) {
            const ev = events.find(item => String(item.id) === String(eventId));
            if (!ev) return;

            editingEventId = eventId;
            document.getElementById('modalFormTitle').innerHTML = `<i class="fa-solid fa-pen-to-square mr-2 text-amber-400"></i>編輯研習活動資訊`;
            document.getElementById('submitModalBtn').innerText = '儲存變更';

            document.getElementById('newTitle').value = ev.title || '';
            document.getElementById('newMode').value = ev.mode || 'online';
            document.getElementById('newIsExpired').value = ev.isExpired ? 'true' : 'false';
            document.getElementById('newDate').value = ev.date || '';
            document.getElementById('newSpeaker').value = ev.speaker || '';
            document.getElementById('newDeadline').value = ev.deadline || '';
            document.getElementById('newTags').value = (ev.tags || []).join(', ');
            document.getElementById('newLocation').value = ev.location || '';
            document.getElementById('newGoogleForm').value = ev.googleFormUrl || '';
            document.getElementById('newSkills').value = (ev.skills || []).map(s => '• ' + s).join('\n');
            document.getElementById('newImageFile').value = '';

            document.getElementById('addModal').classList.remove('hidden');
        }

        function closeAddModal() {
            document.getElementById('addModal').classList.add('hidden');
            editingEventId = null;
        }

        async function handleSaveEvent(e) {
            e.preventDefault();

            const submitButton = document.getElementById('submitModalBtn');
            const originalButtonText = submitButton.innerText;
            submitButton.disabled = true;
            submitButton.innerText = '儲存中...';

            try {
                const title = document.getElementById('newTitle').value.trim();
                const mode = document.getElementById('newMode').value;
                const isExpired = document.getElementById('newIsExpired').value === 'true';
                const date = document.getElementById('newDate').value.trim();
                const speaker = document.getElementById('newSpeaker').value.trim();
                const deadline = document.getElementById('newDeadline').value.trim() || '額滿截止';
                const location = document.getElementById('newLocation').value.trim() ||
                    (mode === 'online' ? '線上會議室' : '實體研習教室');
                const tagsRaw = document.getElementById('newTags').value;
                const googleFormUrl = document.getElementById('newGoogleForm').value.trim();
                const skillsRaw = document.getElementById('newSkills').value;

                const tags = tagsRaw
                    ? tagsRaw.split(',').map(t => t.trim()).filter(Boolean)
                    : ['研習增能'];

                const skills = skillsRaw
                    ? skillsRaw.split('\n')
                        .map(s => s.replace(/^[•\-\*]\s*/, '').trim())
                        .filter(Boolean)
                    : ['精準掌握素養導向教學策略與實務技巧'];

                const fileInput = document.getElementById('newImageFile');
                const oldEvent = editingEventId !== null
                    ? events.find(item => String(item.id) === String(editingEventId))
                    : null;

                let imageUrl = oldEvent?.image || '';

                if (fileInput.files && fileInput.files[0]) {
                    imageUrl = await uploadEventImage(fileInput.files[0]);
                }

                const eventPayload = {
                    title,
                    mode,
                    isExpired,
                    date,
                    speaker,
                    location,
                    deadline,
                    tags,
                    skills,
                    googleFormUrl,
                    desc: title,
                    image: imageUrl || 'https://images.unsplash.com/photo-1524178232363-1fb2b075b655?auto=format&fit=crop&w=800&q=80'
                };

                if (editingEventId !== null) {
                    const { error } = await supabaseClient
                        .from('events')
                        .update(eventToRow(eventPayload))
                        .eq('id', editingEventId);

                    if (error) throw error;

                    showToast('研習活動資料已成功更新！', 'success');
                } else {
                    const { error } = await supabaseClient
                        .from('events')
                        .insert(eventToRow(eventPayload));

                    if (error) throw error;

                    showToast('研習活動已成功發布！', 'success');
                }

                closeAddModal();
                await loadEventsFromDatabase();
            } catch (error) {
                console.error('儲存研習失敗:', error);
                showToast(`儲存失敗：${error.message || '請檢查 Supabase 設定'}`, 'error');
            } finally {
                submitButton.disabled = false;
                submitButton.innerText = originalButtonText;
            }
        }

        function openRegisterModal(eventId) {
            const ev = events.find(item => String(item.id) === String(eventId));
            if (!ev) return;

            document.getElementById('modalEventTitle').innerText = ev.title;

            const formIframe = document.getElementById('googleFormIframe');
            const spinner = document.getElementById('formLoadingSpinner');
            const extBtn = document.getElementById('modalExternalFormBtn');

            if (spinner) spinner.style.display = 'flex';
            formIframe.onload = hideFormSpinner;

            let rawUrl = ev.googleFormUrl || "https://docs.google.com/forms/";
            let embedUrl = rawUrl;

            if (embedUrl.includes('docs.google.com/forms') && !embedUrl.includes('embedded=true')) {
                embedUrl += (embedUrl.includes('?') ? '&' : '?') + 'embedded=true';
            }

            formIframe.src = embedUrl;
            extBtn.href = rawUrl;

            const modal = document.getElementById('registerModal');
            const box = document.getElementById('registerModalBox');
            modal.classList.remove('hidden');

            setTimeout(() => {
                box.classList.remove('scale-95', 'opacity-0');
                box.classList.add('scale-100', 'opacity-100');
            }, 10);
        }

        function hideFormSpinner() {
            const spinner = document.getElementById('formLoadingSpinner');
            if (spinner) spinner.style.display = 'none';
        }

        function closeRegisterModal() {
            const modal = document.getElementById('registerModal');
            const box = document.getElementById('registerModalBox');

            box.classList.remove('scale-100', 'opacity-100');
            box.classList.add('scale-95', 'opacity-0');

            setTimeout(() => {
                modal.classList.add('hidden');
                document.getElementById('googleFormIframe').src = '';
            }, 200);
        }

        function showToast(msg, type = 'success') {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toastMsg');
            const toastIcon = document.getElementById('toastIcon');

            toastMsg.innerText = msg;

            if (type === 'info') {
                toastIcon.innerHTML = `<i class="fa-solid fa-circle-info text-blue-400"></i>`;
            } else if (type === 'error') {
                toastIcon.innerHTML = `<i class="fa-solid fa-circle-exclamation text-red-400"></i>`;
            } else {
                toastIcon.innerHTML = `<i class="fa-solid fa-circle-check text-emerald-400"></i>`;
            }

            toast.classList.remove('translate-y-20', 'opacity-0');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.remove('translate-y-0', 'opacity-100');
                toast.classList.add('translate-y-20', 'opacity-0');
            }, 3000);
        }

        // 啟動網站：前台先讀資料庫；如果網址帶 ?admin=true，
        // 已登入且是管理員就直接進後台，否則開啟登入視窗。
        window.addEventListener('DOMContentLoaded', async () => {
            const { data: sessionData } = await supabaseClient.auth.getSession();
            currentUser = sessionData?.session?.user || null;

            await loadEventsFromDatabase();

            const urlParams = new URLSearchParams(window.location.search);

            if (urlParams.get('admin') === 'true') {
                const isAdmin = await isCurrentUserAdmin();

                if (isAdmin) {
                    await switchToBackend();
                } else {
                    openAdminLoginModal();
                }
            }

            supabaseClient.auth.onAuthStateChange(async (_event, session) => {
                currentUser = session?.user || null;
            });
        });

        const categoryMeta = {
            'all': { title: '所有研習場次', desc: '顯示所有舉辦中的教師成長與專題研習課程，點擊報名按鈕直連 Google 表單' },
            'online': { title: '線上研習活動', desc: '便利彈性的線上同步研習，不受地域限制' },
            'offline': { title: '實體研習活動', desc: '實體工作坊、親身體驗與深度討論' }
        };


    </script>
</body>
</html>
