<!DOCTYPE html>
<html lang="ckb" dir="rtl" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ڕێنمایی دەروونی و پەروەردەیی | دەروو جبار قادر</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                        },
                        calm: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0ea5e9',
                            600: '#0284c7',
                            700: '#0369a1',
                        }
                    },
                    fontFamily: {
                        sans: ['system-ui', '-apple-system', 'BlinkMacSystemFont', '"Segoe UI"', 'Roboto', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            color-scheme: light only;
        }
        body {
            background-color: #f8fafc !important;
            color: #1e293b !important;
        }
        ::-webkit-scrollbar {
            width: 8px;
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
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans selection:bg-brand-500 selection:text-white">

    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <div class="flex items-center gap-3">
                    <div class="w-12 h-12 rounded-2xl bg-gradient-to-tr from-brand-600 to-calm-500 flex items-center justify-center text-white shadow-md shadow-brand-500/20">
                        <i class="fa-solid fa-graduation-cap text-2xl"></i>
                    </div>
                    <div>
                        <span class="text-lg sm:text-xl font-bold bg-gradient-to-r from-brand-700 to-calm-600 bg-clip-text text-transparent">دەروونناسی و پەروەردەی تایبەت</span>
                        <p class="text-xs text-slate-500">دەروو جبار قادر • زانکۆی چەرموو</p>
                    </div>
                </div>

                <nav class="hidden lg:flex items-center gap-6 text-sm">
                    <a href="#home" class="font-medium text-brand-600 hover:text-brand-700 transition">سەرەتا</a>
                    <a href="#research" class="font-medium text-slate-600 hover:text-brand-600 transition">بنەما زانستییەکان</a>
                    <a href="#special-education" class="font-medium text-slate-600 hover:text-brand-600 transition">پەروەردەی تایبەت</a>
                    <a href="#exercises" class="font-medium text-slate-600 hover:text-brand-600 transition">ڕاهێنانەکان</a>
                    <a href="#mental-health" class="font-medium text-slate-600 hover:text-brand-600 transition">تەندروستی دەروونی</a>
                    <a href="#books" class="font-medium text-slate-600 hover:text-brand-600 transition">کتێبخانەی PDF</a>
                    <a href="#consultation" class="font-medium text-slate-600 hover:text-brand-600 transition">پەیوەندی</a>
                </nav>

                <div class="flex items-center gap-3">
                    <a href="#consultation" class="hidden sm:inline-flex items-center justify-center px-5 py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-sm shadow-lg shadow-brand-600/20 transition">
                        داوای ڕاوێژ بکە
                    </a>
                    <button id="mobile-menu-btn" class="lg:hidden p-2.5 rounded-xl bg-slate-100 text-slate-600">
                        <i class="fa-solid fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <div id="mobile-menu" class="hidden lg:hidden bg-white border-b border-slate-200 px-4 pt-2 pb-6 space-y-3">
            <a href="#home" class="block px-3 py-2 rounded-lg font-medium text-brand-600 bg-brand-50">سەرەتا</a>
            <a href="#research" class="block px-3 py-2 rounded-lg font-medium text-slate-600 hover:bg-slate-100">بنەما زانستییەکان</a>
            <a href="#special-education" class="block px-3 py-2 rounded-lg font-medium text-slate-600 hover:bg-slate-100">پەروەردەی تایبەت</a>
            <a href="#exercises" class="block px-3 py-2 rounded-lg font-medium text-slate-600 hover:bg-slate-100">ڕاهێنانەکان</a>
            <a href="#mental-health" class="block px-3 py-2 rounded-lg font-medium text-slate-600 hover:bg-slate-100">تەندروستی دەروونی</a>
            <a href="#books" class="block px-3 py-2 rounded-lg font-medium text-slate-600 hover:bg-slate-100">کتێبخانەی PDF</a>
            <a href="#consultation" class="block px-3 py-2 rounded-lg font-medium text-slate-600 hover:bg-slate-100">پەیوەندی</a>
        </div>
    </header>

    <section id="home" class="relative overflow-hidden pt-16 pb-24 lg:pt-24 lg:pb-32 bg-gradient-to-b from-brand-50/60 via-calm-50/30 to-transparent">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-right">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">
                        <i class="fa-solid fa-certificate text-brand-600"></i>
                        پلاتفۆرمی زانستی، توێژینەوە و ڕێنمایی دەروونی
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-slate-900 leading-[1.2]">
                        پەرەپێدانی تواناکان و <span class="bg-gradient-to-r from-brand-600 to-calm-500 bg-clip-text text-transparent">پشتگیری زانستی پەروەردەیی</span>
                    </h1>
                    <p class="text-lg text-slate-600 max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                        ئەم پلاتفۆرمە ئەکادیمی و دەروونییە لەلایەن <span class="font-bold text-brand-600">دەروو جبار قادر</span> (خوێندکاری بەشی پەروەردەی تایبەت لە زانکۆی چەرموو - چەمچەماڵ) سەرپەرشتی دەکرێت. لێرەدا کۆمەڵێک توێژینەوەی قوڵ، ڕێبەری چارەسەری ڕەفتاری، و کەرەستەی فێرکاری دابین کراون.
                    </p>
                    <div class="flex flex-wrap items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#research" class="px-7 py-3.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium shadow-lg shadow-brand-600/25 transition flex items-center gap-2">
                            <span>توێژینەوە و تیۆرەکان</span>
                            <i class="fa-solid fa-arrow-left text-sm"></i>
                        </a>
                        <a href="#books" class="px-7 py-3.5 rounded-xl bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 font-medium shadow-sm transition">
                            کتێبخانەی PDF
                        </a>
                    </div>
                </div>

                <div class="lg:col-span-5 relative">
                    <div class="bg-white rounded-3xl p-6 shadow-xl border border-slate-100 space-y-6">
                        <div class="flex items-center gap-4 p-4 rounded-2xl bg-brand-50">
                            <div class="w-12 h-12 rounded-xl bg-brand-600 text-white flex items-center justify-center text-xl flex-shrink-0">
                                <i class="fa-solid fa-book-bookmark"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-slate-900 text-base">بنەماکانی پیاتژە و ڤایگۆتسکی</h3>
                                <p class="text-xs text-slate-500">گەشەی مەعریفی و ناوچەی پێگەیشتنی نزیک.</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4 p-4 rounded-2xl bg-calm-50">
                            <div class="w-12 h-12 rounded-xl bg-calm-600 text-white flex items-center justify-center text-xl flex-shrink-0">
                                <i class="fa-solid fa-brain"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-slate-900 text-base">چارەسەری ڕەفتاری مەعریفی (CBT)</h3>
                                <p class="text-xs text-slate-500">ڕێکاری زانستی بۆ کەمکردنەوەی دڵەڕاوکێ.</p>
                            </div>
                        </div>
                        <div class="flex items-center gap-4 p-4 rounded-2xl bg-amber-50">
                            <div class="w-12 h-12 rounded-xl bg-amber-600 text-white flex items-center justify-center text-xl flex-shrink-0">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-slate-900 text-base">زانکۆی چەرموو • چەمچەماڵ</h3>
                                <p class="text-xs text-slate-500" dir="ltr">07702122873 • darwjabar@gmail.com</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="research" class="py-20 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">بنەما زانستی و توێژینەوەکان</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">تیۆرە دەروونی و پەروەردەییە ئەکادیمییەکان</h2>
                <p class="text-slate-600 text-base">شیکردنەوەی قووڵی بنەما مەعریفی و ڕەفتارییەکان لەسەر بنەمای توێژینەوە سەردەمییەکان.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-slate-50 rounded-3xl p-8 border border-slate-200 space-y-4 shadow-sm flex flex-col justify-between">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-brand-100 text-brand-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-atom"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">قۆناغەکانی گەشەی پیاتژە (Piaget's Theory)</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">لێکۆڵینەوە لە چۆنیەتی پەرەسەندنی مێشک و بیرکردنەوەی منداڵ لە قۆناغی هەستی-جووڵەییەوە تا فیکری لۆژیکی ئەستوور.</p>
                    </div>
                    <button onclick="openModal('قۆناغەکانی گەشەی پیاتژە', 'ژێن پیاتژە جەخت لەوە دەکاتەوە کە منداڵان لە ڕێگەی کارلێکی چالاک لەگەڵ ژینگەکەیانیدا زانیاری بنیات دەنێن. تێگەیشتن لەم قۆناغە یارمەتی مامۆستایان دەدات وانەکان لەگەڵ تەمەنی مەعریفی قوتابی بگونجێنن.')" class="pt-4 text-brand-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>خوێندنەوەی توێژینەوە</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-slate-50 rounded-3xl p-8 border border-slate-200 space-y-4 shadow-sm flex flex-col justify-between">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-calm-100 text-calm-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-network-wired"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">ناوچەی پێگەیشتنی نزیک (Vygotsky's ZPD)</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">گرنگیدان بە ڕۆڵی هاوکاری کۆمەڵایەتی و ڕێنماییکردن (Scaffolding) لە بەرزکردنەوەی توانای فێربوونی منداڵ.</p>
                    </div>
                    <button onclick="openModal('ناوچەی پێگەیشتنی نزیک (ZPD)', 'ڤایگۆتسکی پێی وابوو فێربوون پرۆسەیەکی کۆمەڵایەتییە. کاتێک کەسێکی شارەزا یان هاوڕێ پشتگیری منداڵ دەکات، تواناکانی دەچنە ئاستێکی باڵاترەوە کە بە تەنها نەیدەتوانی پێی بگات.')" class="pt-4 text-calm-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>خوێندنەوەی توێژینەوە</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-slate-50 rounded-3xl p-8 border border-slate-200 space-y-4 shadow-sm flex flex-col justify-between">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-amber-100 text-amber-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-shield-heart"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">مۆدێلی نۆیرۆدیڤێرسیتی (Neurodiversity)</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">سەیرکردنی ئاوتیزم، ADHD و سەختییەکانی فێربوون وەک جیاوازی بایلۆژی سروشتی نەک وەک نەخۆشی یان کەموکوڕی.</p>
                    </div>
                    <button onclick="openModal('مۆدێلی نۆیرۆدیڤێرسیتی', 'ئەم ڕوانگە زانستییە جەخت لەسەر گونجاندنی ژینگە و سیستەمی فێرکاری دەکاتەوە لەگەڵ جیاوازییەکانی مێشکدا، نەک ناچارکردنی تاک بۆ گۆڕانی ناسک و ناتەندروست.')" class="pt-4 text-amber-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>خوێندنەوەی توێژینەوە</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="special-education" class="py-20 bg-slate-100/50 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">پەروەردەی تایبەت</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">مێتۆدۆلۆژیای تایبەت و پلانی فێرکاری تاکەکەسی (IEP)</h2>
                <p class="text-slate-600 text-base">ڕێکارە پراکتیکییەکان بۆ دابینکردنی ژینگەی یەکسان و گونجاو.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white rounded-3xl p-6 border border-slate-200 flex flex-col justify-between shadow-sm">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-brand-100 text-brand-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-file-lines"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">پلانی فێرکاری تاوانکاری (IEP)</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">دانانی ئامانجی تایبەت بۆ هەر منداڵێک بەپێی توانا و پێویستییە تاکەکەسییەکانی.</p>
                    </div>
                    <button onclick="openModal('پلانی فێرکاری تاکەکەسی (IEP)', 'پلانی فێرکاری تاوانکاری بەڵگەنامەیەکی یاسایی و زانستییە کە لەلایەن تیمی پەروەردەی تایبەتەوە ئامادە دەکرێت بۆ دیاریکردنی پێشکەوتنی قوتابی.')" class="mt-6 text-brand-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>وردەکاری زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-white rounded-3xl p-6 border border-slate-200 flex flex-col justify-between shadow-sm">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-calm-100 text-calm-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-brain"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">دیسلیکسیا و خوێندنەوە</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">ڕێگەی فرە-هەستی (Multi-sensory) بۆ هاندانی تێگەیشتن لە وشە و نووسین.</p>
                    </div>
                    <button onclick="openModal('دیسلیکسیا و سەختی خوێندنەوە', 'بەکارهێنانی شێوازی بینایی، بیستنی و لەمسکردنی پیتەکان یارمەتی مێشکی قوتابی دەکات پەیوەندی نێوان دەنگ و پیتەکان بە ئاسانی دروست بکات.')" class="mt-6 text-calm-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>وردەکاری زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-white rounded-3xl p-6 border border-slate-200 flex flex-col justify-between shadow-sm">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-amber-100 text-amber-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-bolt-lightning"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">کەمبوونی سەرنج (ADHD)</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">دابەشکردنی ئەرکەکان بۆ پارچەی بچووک و پێدانی پشووی کورت بۆ بەرزکردنەوەی تەرکیز.</p>
                    </div>
                    <button onclick="openModal('مدیریتکردنی ADHD', 'منداڵانی خاوەن چالاکی زیادە پێویستیان بە رۆتینێکی ڕوون، ژینگەی کەم ئاژاوە و پاداشتی خێرا هەیە بۆ بەدیهێنانی ئامانجەکان.')" class="mt-6 text-amber-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>وردەکاری زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>

                <div class="bg-white rounded-3xl p-6 border border-slate-200 flex flex-col justify-between shadow-sm">
                    <div class="space-y-4">
                        <div class="w-14 h-14 rounded-2xl bg-emerald-100 text-emerald-600 flex items-center justify-center text-2xl">
                            <i class="fa-solid fa-hands-holding-child"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900">پشتگیری خێزانی</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">ڕێنماییکردنی دایک و باوکان بۆ دروستکردنی هاوسەنگی و ژینگەی ئارام لە ماڵەوە.</p>
                    </div>
                    <button onclick="openModal('پشتگیری خێزانی', 'خێزان فاکتەری سەرەکی سەرکەوتنی منداڵە. هۆشیارکردنەوەی خێزان دەبێتە هۆی کەمکردنەوەی قەلەقی و بەرزکردنەوەی متمانەبەخۆبوون.')" class="mt-6 text-emerald-600 font-semibold text-sm hover:underline inline-flex items-center gap-2">
                        <span>وردەکاری زیاتر</span>
                        <i class="fa-solid fa-arrow-left text-xs"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="exercises" class="py-20 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">پێشانگای ڕاهێنانەکان</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">ڕاهێنانی پراکتیکی و چالاکییە هاندانەکان بۆ منداڵان</h2>
                <p class="text-slate-600 text-base">کۆمەڵێک ڕاهێنانی زانستی بۆ پەرەپێدانی توانای جەستەیی، هەستی و دەروونی.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-slate-50 rounded-3xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="h-48 bg-gradient-to-tr from-brand-600 to-teal-500 relative flex items-center justify-center p-6 text-white">
                        <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                        <div class="text-center space-y-2 relative z-10">
                            <i class="fa-solid fa-hand-dots text-4xl mb-1"></i>
                            <h3 class="text-xl font-bold">کارامەیی وردی ماسولکەکان (Fine Motor)</h3>
                        </div>
                    </div>
                    <div class="p-6 space-y-4">
                        <p class="text-sm text-slate-600 leading-relaxed">ڕاهێنانی بڕینەوە بە مقەست، گرتنی قەڵەم بە شێوازی دروست، و ڕیزکردنی کەرەستە بچووکەکان بۆ بەهێزکردنی پەنجەکان.</p>
                        <div class="pt-2 flex items-center justify-between text-xs text-slate-500 border-t border-slate-200">
                            <span><i class="fa-regular fa-clock ml-1"></i> ١٥ خولەک ڕۆژانە</span>
                            <span class="px-2.5 py-1 rounded-full bg-brand-100 text-brand-700 font-medium">جەستەیی ورد</span>
                        </div>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="bg-slate-50 rounded-3xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="h-48 bg-gradient-to-tr from-calm-600 to-indigo-500 relative flex items-center justify-center p-6 text-white">
                        <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                        <div class="text-center space-y-2 relative z-10">
                            <i class="fa-solid fa-spa text-4xl mb-1"></i>
                            <h3 class="text-xl font-bold">هەناسەدانی هێمنکەرەوە (Deep Breathing)</h3>
                        </div>
                    </div>
                    <div class="p-6 space-y-4">
                        <p class="text-sm text-slate-600 leading-relaxed">ڕاهێنانی هەناسەدانی قوڵ (وەک هەڵمژینی گوڵ و فووکردن لە مۆم) بۆ کەمکردنەوەی دڵەڕاوکێ و ڕێکخستنی سیستەمی دەماری.</p>
                        <div class="pt-2 flex items-center justify-between text-xs text-slate-500 border-t border-slate-200">
                            <span><i class="fa-regular fa-clock ml-1"></i> ١٠ خولەک</span>
                            <span class="px-2.5 py-1 rounded-full bg-calm-100 text-calm-700 font-medium">ئارامی دەروونی</span>
                        </div>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="bg-slate-50 rounded-3xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="h-48 bg-gradient-to-tr from-amber-500 to-orange-500 relative flex items-center justify-center p-6 text-white">
                        <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                        <div class="text-center space-y-2 relative z-10">
                            <i class="fa-solid fa-face-smile text-4xl mb-1"></i>
                            <h3 class="text-xl font-bold">کارتی ناسینەوەی هەستەکان (Emotion Cards)</h3>
                        </div>
                    </div>
                    <div class="p-6 space-y-4">
                        <p class="text-sm text-slate-600 leading-relaxed">بەکارهێنانی وێنە بۆ دەربڕینی هەستەکانی خۆشحاڵی، تورەیی و قەلەقی، بۆ ئەوەی منداڵ فێر ببێت هەستەکانی دەرببڕێت.</p>
                        <div class="pt-2 flex items-center justify-between text-xs text-slate-500 border-t border-slate-200">
                            <span><i class="fa-regular fa-clock ml-1"></i> ٢٠ خولەک</span>
                            <span class="px-2.5 py-1 rounded-full bg-amber-100 text-amber-700 font-medium">سۆزداری</span>
                        </div>
                    </div>
                </div>

                <!-- Card 4 -->
                <div class="bg-slate-50 rounded-3xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="h-48 bg-gradient-to-tr from-emerald-600 to-teal-600 relative flex items-center justify-center p-6 text-white">
                        <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                        <div class="text-center space-y-2 relative z-10">
                            <i class="fa-solid fa-shapes text-4xl mb-1"></i>
                            <h3 class="text-xl font-bold">پازڵ و پاتێرنی هۆشی (Pattern Matching)</h3>
                        </div>
                    </div>
                    <div class="p-6 space-y-4">
                        <p class="text-sm text-slate-600 leading-relaxed">ڕیزکردنی شێوە و ڕەنگ بەپێی پاتێرنی دیاریکراو بۆ بەرزکردنەوەی توانای تەرکیز و بیرکاری لۆژیکی.</p>
                        <div class="pt-2 flex items-center justify-between text-xs text-slate-500 border-t border-slate-200">
                            <span><i class="fa-regular fa-clock ml-1"></i> ٢٥ خولەک</span>
                            <span class="px-2.5 py-1 rounded-full bg-emerald-100 text-emerald-700 font-medium">مەعریفی و تەرکیز</span>
                        </div>
                    </div>
                </div>

                <!-- Card 5 -->
                <div class="bg-slate-50 rounded-3xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="h-48 bg-gradient-to-tr from-purple-600 to-pink-500 relative flex items-center justify-center p-6 text-white">
                        <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                        <div class="text-center space-y-2 relative z-10">
                            <i class="fa-solid fa-comments text-4xl mb-1"></i>
                            <h3 class="text-xl font-bold">ڕاهێنانی زمانەوانی و چیرۆک (Speech Therapy)</h3>
                        </div>
                    </div>
                    <div class="p-6 space-y-4">
                        <p class="text-sm text-slate-600 leading-relaxed">گێڕانەوەی چیرۆکی سادە و ڕاهێنانی لێو و زمان بۆ باشترکردنی توانای قسەکردن و گەیاندنی پەیام.</p>
                        <div class="pt-2 flex items-center justify-between text-xs text-slate-500 border-t border-slate-200">
                            <span><i class="fa-regular fa-clock ml-1"></i> ١٥ خولەک</span>
                            <span class="px-2.5 py-1 rounded-full bg-purple-100 text-purple-700 font-medium">زمانەوانی</span>
                        </div>
                    </div>
                </div>

                <!-- Card 6 -->
                <div class="bg-slate-50 rounded-3xl overflow-hidden border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div class="h-48 bg-gradient-to-tr from-blue-600 to-cyan-500 relative flex items-center justify-center p-6 text-white">
                        <div class="absolute inset-0 opacity-15 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
                        <div class="text-center space-y-2 relative z-10">
                            <i class="fa-solid fa-person-running text-4xl mb-1"></i>
                            <h3 class="text-xl font-bold">هاوسەنگی جەستەی گەورە (Gross Motor)</h3>
                        </div>
                    </div>
                    <div class="p-6 space-y-4">
                        <p class="text-sm text-slate-600 leading-relaxed">پیاسەکردن لەسەر هێڵی ڕاست، بازی سووک و هاوسەنگی جەستەیی بۆ گەشەی ماسولکە گەورەکان.</p>
                        <div class="pt-2 flex items-center justify-between text-xs text-slate-500 border-t border-slate-200">
                            <span><i class="fa-regular fa-clock ml-1"></i> ٣٠ خولەک</span>
                            <span class="px-2.5 py-1 rounded-full bg-blue-100 text-blue-700 font-medium">جەستەیی گشتی</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="mental-health" class="py-20 bg-slate-100/50 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">تەندروستی دەروونی</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">بنەماکانی تەندروستی دەروونی و مۆدێلی CBT</h2>
                <p class="text-slate-600 text-base">شێوازەکانی ڕزگاربوون لە دڵەڕاوکێ و دروستکردنی هاوسەنگی دەروونی لە ژیانی ڕۆژانەدا.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white rounded-3xl p-8 border border-slate-200 space-y-4 shadow-sm">
                    <div class="w-12 h-12 rounded-2xl bg-calm-100 text-calm-600 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-brain"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900">گۆڕینی بیرکردنەوەی نەرێنی</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">بەکارهێنانی چارەسەری مەعریفی-ڕەفتاری (CBT) بۆ ناسینەوەی بیرۆکە زیانبەخشەکان و گۆڕڕینیان بۆ بیرۆکەی پۆزەتیڤ.</p>
                </div>

                <div class="bg-white rounded-3xl p-8 border border-slate-200 space-y-4 shadow-sm">
                    <div class="w-12 h-12 rounded-2xl bg-brand-100 text-brand-600 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-heart-pulse"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900">کەمکردنەوەی دڵەڕاوکێی درێژخایەن</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">پەیڕەوکردنی خشتەی وەرزش، نووستنی ڕێک و گفتوگۆی دەروونی لەگەڵ کەسانی متمانەپێکراودا.</p>
                </div>

                <div class="bg-white rounded-3xl p-8 border border-slate-200 space-y-4 shadow-sm">
                    <div class="w-12 h-12 rounded-2xl bg-amber-100 text-amber-600 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900">خۆشەویستی و چاودێری خودی (Self-Care)</h3>
                    <p class="text-sm text-slate-600 leading-relaxed">دانانی سنووری تەندروست و گرنگیدان بە پشوو وەک بنەمایەکی سەرەکی بۆ بەردەوامبوون.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="books" class="py-20 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="px-3.5 py-1 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">کتێبخانەی دیجیتالی PDF</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-slate-900">سەرچاوە و پەرتووکە دەروونی و پەروەردەیییەکان</h2>
                <p class="text-slate-600 text-base">کۆمەڵەیەکی بەرفراوان لە کتێب و ڕێبەری PDF بۆ توێژەران، مامۆستایان و دایک و باوکان.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Book 1 -->
                <div class="bg-slate-50 rounded-3xl p-6 border border-slate-200 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-brand-600 to-calm-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-book"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-brand-600 font-semibold">پەروەردەی تایبەت</span>
                            <h4 class="font-bold text-slate-900 text-base">بنەماکانی پەروەردەی تایبەت و تێکەڵاو</h4>
                            <p class="text-xs text-slate-500">ئامادەکردنی: دەروو جبار قادر</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">ڕێبەری گشتگیر بۆ ناسینەوەی تێکچوونی فێربوون و چۆنیەتی دانانی پلانی تاکەکەسی (IEP).</p>
                    <button onclick="downloadNotice('بنەماکانی پەروەردەی تایبەت')" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <!-- Book 2 -->
                <div class="bg-slate-50 rounded-3xl p-6 border border-slate-200 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-calm-600 to-indigo-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-book-open"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-calm-600 font-semibold">تەندروستی دەروونی</span>
                            <h4 class="font-bold text-slate-900 text-base">هۆشیاری دەروونی و بەرەنگاربوونەوەی دڵەڕاوکێ</h4>
                            <p class="text-xs text-slate-500">ڕێبەری پڕاکتیکی بۆ ئارامی</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">تەکنیکەکانی چارەسەری مەعریفی-ڕەفتاری بۆ کەمکردنەوەی سترێسی ژیانی ڕۆژانە.</p>
                    <button onclick="downloadNotice('هۆشیاری دەروونی و دڵەڕاوکێ')" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <!-- Book 3 -->
                <div class="bg-slate-50 rounded-3xl p-6 border border-slate-200 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-amber-600 to-orange-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-book-bookmark"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-amber-600 font-semibold">ڕێبەری خێزان</span>
                            <h4 class="font-bold text-slate-900 text-base">مامەڵەکردن لەگەڵ منداڵی خاوەن پێویستی تایبەت</h4>
                            <p class="text-xs text-slate-500">دەستیار بۆ دایک و باوکان</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">ڕێنمایی ڕۆژانە بۆ دروستکردنی پەیوەندی بەهێز و پۆزەتیڤ لە ماڵەوە لەگەڵ منداڵی ئاوتیزم و ADHD.</p>
                    <button onclick="downloadNotice('مامەڵەکردن لەگەڵ منداڵی خاوەن پێویستی تایبەت')" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <!-- Book 4 -->
                <div class="bg-slate-50 rounded-3xl p-6 border border-slate-200 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-purple-600 to-pink-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-graduation-cap"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-purple-600 font-semibold">گەشەی منداڵ</span>
                            <h4 class="font-bold text-slate-900 text-base">دەروونناسی گەشە و قۆناغەکانی تەمەن</h4>
                            <p class="text-xs text-slate-500">سەرچاوەی زانستی بۆ خوێنەران</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">شیکردنەوەی قۆناغەکانی گەشەی دەروونی، زمانەوانی و کۆمەڵایەتی منداڵ لە لەدایکبوونەوە تا مێردمنداڵی.</p>
                    <button onclick="downloadNotice('دەروونناسی گەشە و قۆناغەکانی تەمەن')" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <!-- Book 5 -->
                <div class="bg-slate-50 rounded-3xl p-6 border border-slate-200 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-emerald-600 to-teal-500 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-puzzle-piece"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-emerald-600 font-semibold">ڕێبەری چارەسەر</span>
                            <h4 class="font-bold text-slate-900 text-base">تەکنیکەکانی چارەسەری ڕەفتاری</h4>
                            <p class="text-xs text-slate-500">ڕێبەری کرداری بۆ چارەسەرکاران</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">چۆنیەتی گۆڕینی ڕەفتاری نەگونجاو بۆ ڕەفتاری ئەرێنی لەرێگەی سیستەمی پاداشت و هاندانی دەروونی.</p>
                    <button onclick="downloadNotice('تەکنیکەکانی چارەسەری ڕەفتاری')" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>

                <!-- Book 6 -->
                <div class="bg-slate-50 rounded-3xl p-6 border border-slate-200 flex flex-col justify-between space-y-4 shadow-sm">
                    <div class="flex items-start gap-4">
                        <div class="w-14 h-20 rounded-xl bg-gradient-to-tr from-blue-600 to-indigo-600 text-white flex items-center justify-center text-xl flex-shrink-0 shadow-md">
                            <i class="fa-solid fa-brain"></i>
                        </div>
                        <div class="space-y-1">
                            <span class="text-xs text-blue-600 font-semibold">نۆیروپەروەردە</span>
                            <h4 class="font-bold text-slate-900 text-base">کارکردنی مێشک و سەختییەکانی خوێندنەوە</h4>
                            <p class="text-xs text-slate-500">لێکۆڵینەوەی نوێی دەروونی</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-600 leading-relaxed">تێڕوانینی زانستی بۆ دیسلیکسیا و شێوازەکانی تێپەڕاندنی سەختییەکانی خوێندنەوە لە تەمەنی زوودا.</p>
                    <button onclick="downloadNotice('کارکردنی مێشک و سەختییەکانی خوێندنەوە')" class="w-full py-2.5 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-medium text-xs transition flex items-center justify-center gap-2">
                        <i class="fa-solid fa-download"></i>
                        <span>داگرتنی کتێب (PDF)</span>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section id="consultation" class="py-20 bg-slate-100/50 border-t border-slate-200">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-white rounded-3xl shadow-xl border border-slate-200 p-8 sm:p-12">
                <div class="text-center max-w-xl mx-auto mb-10 space-y-3">
                    <span class="px-3.5 py-1 rounded-full bg-brand-100 text-brand-700 text-sm font-semibold">پەیوەندی و ڕاوێژ</span>
                    <h2 class="text-2xl sm:text-3xl font-extrabold text-slate-900">پرسیار یان داوای ڕاوێژکاریت هەیە؟</h2>
                    <p class="text-sm text-slate-600">فۆرمەکە پڕبکەرەوە یان ڕاستەوخۆ پەیوەندی بکە بە ژمارە مۆبایل و ئیمەیڵی خوارەوە.</p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mb-8">
                    <div class="p-4 rounded-2xl bg-slate-50 border border-slate-200 flex items-center gap-4">
                        <div class="w-10 h-10 rounded-xl bg-brand-600 text-white flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-phone"></i>
                        </div>
                        <div>
                            <span class="text-xs text-slate-500 block">ژمارەی مۆبایل</span>
                            <span class="font-bold text-slate-900 text-sm" dir="ltr">07702122873</span>
                        </div>
                    </div>
                    <div class="p-4 rounded-2xl bg-slate-50 border border-slate-200 flex items-center gap-4">
                        <div class="w-10 h-10 rounded-xl bg-calm-600 text-white flex items-center justify-center flex-shrink-0">
                            <i class="fa-solid fa-envelope"></i>
                        </div>
                        <div>
                            <span class="text-xs text-slate-500 block">ئیمەیڵ</span>
                            <span class="font-bold text-slate-900 text-sm" dir="ltr">darwjabar@gmail.com</span>
                        </div>
                    </div>
                </div>

                <form id="consultation-form" onsubmit="handleFormSubmit(event)" class="space-y-6">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-medium text-slate-700 mb-2">ناوی تەواو</label>
                            <input type="text" id="name" required class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 text-sm" placeholder="ناوی خۆت بنووسە">
                        </div>
                        <div>
                            <label class="block text-sm font-medium text-slate-700 mb-2">ئیمەیڵ یان ژمارەی مۆبایل</label>
                            <input type="text" id="contact" required class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 text-sm" placeholder="0770XXXXXXX یان ئیمەیڵ">
                        </div>
                    </div>

                    <div>
                        <label class="block text-sm font-medium text-slate-700 mb-2">جۆری ڕاوێژکاری یان بابەت</label>
                        <select id="category" class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 text-sm">
                            <option value="special-ed">پەروەردەی تایبەت و کێشەکانی فێربوون</option>
                            <option value="mental-health">تەندروستی دەروونی و دڵەڕاوکێ</option>
                            <option value="child-dev">گەشەی منداڵ و ڕەفتار</option>
                            <option value="other">بابەتی تر</option>
                        </select>
                    </div>

                    <div>
                        <label class="block text-sm font-medium text-slate-700 mb-2">پرسیار یان کێشەکەت بە وردی باس بکە</label>
                        <textarea id="message" rows="4" required class="w-full px-4 py-3 rounded-xl bg-slate-50 border border-slate-200 focus:outline-none focus:ring-2 focus:ring-brand-500 text-slate-800 text-sm" placeholder="لێرە دەتوانیت پرسیارەکەت بنووسیت..."></textarea>
                    </div>

                    <button type="submit" class="w-full py-4 rounded-xl bg-brand-600 hover:bg-brand-700 text-white font-bold shadow-lg shadow-brand-600/25 transition flex items-center justify-center gap-2 text-sm">
                        <span>ناردنی داواکاری</span>
                        <i class="fa-solid fa-paper-plane text-sm"></i>
                    </button>
                </form>

                <div id="success-box" class="hidden mt-6 p-4 rounded-2xl bg-emerald-50 border border-emerald-200 text-emerald-800 text-center font-medium flex items-center justify-center gap-3 text-sm">
                    <i class="fa-solid fa-circle-check text-xl text-emerald-600"></i>
                    <span>سوپاس بۆ داواکارییەکەت! پەیامەکەت بە سەرکەوتوویی گەیشت و لە زوترین کاتدا وەڵامت دەدرێتەوە.</span>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-12">
                <div class="md:col-span-2 space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-xl bg-brand-600 flex items-center justify-center text-white">
                            <i class="fa-solid fa-graduation-cap"></i>
                        </div>
                        <span class="text-lg font-bold text-white">دەروونناسی و پەروەردەی تایبەت</span>
                    </div>
                    <p class="text-sm max-w-sm text-slate-400">
                        پلاتفۆرمی زانستی بۆ هۆشیاری دەروونی و پەروەردەی تایبەت — دابینکراو لەلایەن دەروو جبار قادر (زانکۆی چەرموو، چەمچەماڵ).
                    </p>
                </div>
                <div>
                    <h4 class="text-white font-bold mb-4 text-sm">بەشە سەرەکییەکان</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#research" class="hover:text-white transition">بنەما زانستییەکان</a></li>
                        <li><a href="#special-education" class="hover:text-white transition">پەروەردەی تایبەت</a></li>
                        <li><a href="#exercises" class="hover:text-white transition">ڕاهێنانەکان</a></li>
                        <li><a href="#books" class="hover:text-white transition">کتێبخانەی PDF</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white font-bold mb-4 text-sm">پەیوەندی و زانیاری</h4>
                    <ul class="space-y-2 text-sm">
                        <li><i class="fa-solid fa-envelope ml-2 text-brand-500"></i> darwjabar@gmail.com</li>
                        <li><i class="fa-solid fa-phone ml-2 text-brand-500"></i> 07702122873</li>
                        <li><i class="fa-solid fa-location-dot ml-2 text-brand-500"></i> چەمچەماڵ، زانکۆی چەرموو</li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-slate-800 pt-8 flex flex-col sm:flex-row items-center justify-between text-xs">
                <p>&copy; ٢٠٢٦ ڕێنمایی دەروونی و پەروەردەیی. دروستکراوە لەلایەن دەروو جبار قادر.</p>
                <div class="flex gap-4 mt-4 sm:mt-0">
                    <a href="#" class="hover:text-white transition"><i class="fa-brands fa-facebook-f text-lg"></i></a>
                    <a href="#" class="hover:text-white transition"><i class="fa-brands fa-instagram text-lg"></i></a>
                    <a href="#" class="hover:text-white transition"><i class="fa-brands fa-telegram text-lg"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <div id="article-modal" class="fixed inset-0 z-50 hidden bg-slate-900/60 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 sm:p-8 shadow-2xl border border-slate-200 space-y-4 relative">
            <button onclick="closeModal()" class="absolute top-4 left-4 p-2 rounded-full bg-slate-100 text-slate-500 hover:text-slate-800 transition">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            <h3 id="modal-title" class="text-xl font-bold text-slate-900">ناونیشانی وتار</h3>
            <p id="modal-content" class="text-sm text-slate-600 leading-relaxed">وردەکاری و ناوەڕۆکی وتارەکە...</p>
            <div class="pt-4 flex justify-end">
                <button onclick="closeModal()" class="px-5 py-2.5 rounded-xl bg-brand-600 text-white font-medium text-sm">داخستن</button>
            </div>
        </div>
    </div>

    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Modal Functions
        function openModal(title, content) {
            document.getElementById('modal-title').innerText = title;
            document.getElementById('modal-content').innerText = content;
            document.getElementById('article-modal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('article-modal').classList.add('hidden');
        }

        // Consultation Form Handler
        function handleFormSubmit(event) {
            event.preventDefault();
            const successBox = document.getElementById('success-box');
            successBox.classList.remove('hidden');
            document.getElementById('consultation-form').reset();
            
            setTimeout(() => {
                successBox.classList.add('hidden');
            }, 6000);
        }

        // Download Notice Notification
        function downloadNotice(bookName) {
            alert('کتێبی ("' + bookName + '") بە سەرکەوتوویی داگیرا!');
        }
    </script>
</body>
</html>
