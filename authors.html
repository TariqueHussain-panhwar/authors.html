<!DOCTYPE html>
<html lang="sd" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ليکڪن جي لسٽ - ڊجيٽل ڪتاب گھر</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Lateef&display=swap" rel="stylesheet">
    <style>body { font-family: 'Lateef', serif; background-color: #0f172a; color: white; }</style>
</head>
<body>
    <nav class="p-6 border-b border-gray-700 bg-slate-900 sticky top-0 z-50">
        <div class="max-w-6xl mx-auto flex justify-between items-center">
            <h1 class="text-3xl font-bold text-orange-500">ليکڪن جو تعارف</h1>
            <a href="user.html" class="bg-gray-700 px-4 py-2 rounded-lg text-sm">واپس ڪتابن تي وڃو</a>
        </div>
    </nav>

    <main class="max-w-6xl mx-auto p-6">
        <div id="authorsGrid" class="grid grid-cols-1 md:grid-cols-2 gap-6">
            </div>
    </main>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
        import { getFirestore, collection, onSnapshot } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js";

        const firebaseConfig = {
            apiKey: "AIzaSyBUqkNMDmZEpdQtk26qk_bpPVpBPmK8OY8",
            authDomain: "digital-kitab-ghar.firebaseapp.com",
            projectId: "digital-kitab-ghar",
            storageBucket: "digital-kitab-ghar.firebasestorage.app",
            messagingSenderId: "806280436680",
            appId: "1:806280436680:web:da2956efd6b3a3333abefd"
        };
        const app = initializeApp(firebaseConfig);
        const db = getFirestore(app);

        onSnapshot(collection(db, "books"), (snap) => {
            const authorsMap = {};
            snap.forEach(doc => {
                const b = doc.data();
                if (!authorsMap[b.author]) {
                    authorsMap[b.author] = { bio: b.authorBio || 'تعارف موجود ناهي.', books: [] };
                }
                authorsMap[b.author].books.push(b.title);
            });

            const grid = document.getElementById('authorsGrid');
            grid.innerHTML = "";
            for (const name in authorsMap) {
                grid.innerHTML += `
                <div class="bg-slate-800 p-6 rounded-2xl border border-gray-700 shadow-xl">
                    <h3 class="text-2xl font-bold text-orange-400 mb-2">${name}</h3>
                    <p class="text-gray-300 text-sm mb-4 leading-relaxed">${authorsMap[name].bio}</p>
                    <div class="border-t border-gray-700 pt-3">
                        <p class="text-xs text-gray-400 mb-2">هن ليکڪ جا ڪتاب:</p>
                        <div class="flex flex-wrap gap-2">
                            ${authorsMap[name].books.map(title => `<span class="bg-blue-900 text-xs px-2 py-1 rounded">${title}</span>`).join('')}
                        </div>
                    </div>
                </div>`;
            }
        });
    </script>
</body>
</html>
