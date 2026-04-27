# moddalar-va-jinoyat-kodeksi
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>Jinoyat Kodeksi (30 ta modda)</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, sans-serif; background-color: #f4f6f7; padding: 20px; }
        .container { max-width: 800px; margin: auto; background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
        h1 { color: #2c3e50; text-align: center; }
        .modda-box { border-bottom: 1px solid #ddd; padding: 15px 0; }
        .modda-id { color: #c0392b; font-weight: bold; font-size: 1.1em; }
        .modda-nom { font-weight: bold; }
    </style>
</head>
<body>

<div class="container">
    <h1>Jinoyat Kodeksi: 30 ta modda</h1>
    <div id="display-area"></div>
</div>

<script>
    const moddalar = [
        { id: 1, nom: "Vazifalar", matn: "Jinoyat kodeksining vazifalari..." },
        { id: 2, nom: "Prinsiplar", matn: "Jinoyat kodeksining asosiy prinsiplari..." },
        { id: 3, nom: "Qonun", matn: "Jinoyat to‘g‘risidagi qonunlar..." },
        { id: 97, nom: "Qasddan odam o‘ldirish", matn: "Qasddan odam o‘ldirish..." },
        { id: 104, nom: "Badanga og‘ir shikast yetkazish", matn: "Qasddan badanga og‘ir shikast yetkazish..." },
        { id: 105, nom: "Badanga o‘rtacha og‘ir shikast yetkazish", matn: "Badanga o‘rtacha og‘ir shikast yetkazish..." },
        { id: 164, nom: "Bosqinchilik", matn: "O‘zganing mulkini talon-toroj qilish..." },
        { id: 167, nom: "O‘zlashtirish", matn: "Ishonib topshirilgan mulkni o‘zlashtirish..." },
        { id: 168, nom: "Firibgarlik", matn: "Aldash yoki ishonchni suiiste'mol qilish..." },
        { id: 169, nom: "O‘g‘rilik", matn: "O‘zganing mulkini yashirin talon-toroj qilish..." },
        { id: 170, nom: "Aldash yo‘li bilan mulkiy zarar yetkazish", matn: "Aldash yoki ishonchni suiiste'mol qilish..." },
        { id: 171, nom: "Qarzni to‘lashdan bo‘yin tovlash", matn: "Qarzni to‘lashdan qasddan bo‘yin tovlash..." },
        { id: 172, nom: "Pul mablag‘larini qonunga xilof ravishda o‘zlashtirish", matn: "Pul mablag‘larini noqonuniy o‘zlashtirish..." },
        { id: 173, nom: "Qasddan mulkni nobud qilish", matn: "Mulkni qasddan nobud qilish yoki shikastlantirish..." },
        { id: 174, nom: "Ehtiyotsizlik orqasida mulkni nobud qilish", matn: "Ehtiyotsizlik orqasida zarar yetkazish..." },
        { id: 175, nom: "Iqtisodiy jinoyatlar", matn: "Iqtisodiy sohadagi jinoyatlar..." },
        { id: 176, nom: "Qalbaki pul, aksiz markasi yasash", matn: "Qalbaki pul yasash yoki o‘tkazish..." },
        { id: 177, nom: "Valyuta qimmatliklarini qonunga xilof olish", matn: "Valyuta qimmatliklarini noqonuniy sotib olish..." },
        { id: 178, nom: "Qimmatli qog‘ozlar bozorida firibgarlik", matn: "Qimmatli qog‘ozlar bozoridagi qoidabuzarliklar..." },
        { id: 179, nom: "Qishloq xo‘jaligi yerlarini egallash", matn: "Yerlarni o‘zboshimchalik bilan egallash..." },
        { id: 180, nom: "Savdo qoidalarini buzish", matn: "Xaridorlarni aldash yoki savdo qoidalarini buzish..." },
        { id: 181, nom: "Monopoliyaga qarshi qoidalarni buzish", matn: "Monopolistik faoliyat..." },
        { id: 182, nom: "Bojxona qoidalarini buzish", matn: "Bojxona nazoratidan yashirib tovar olib o‘tish..." },
        { id: 183, nom: "Tijorat sirlarini oshkor qilish", matn: "Tijorat yoki bank sirini oshkor qilish..." },
        { id: 184, nom: "Soliqlar yoki yig‘imlarni to‘lashdan bo‘yin tovlash", matn: "Soliq to‘lashdan qasddan bo‘yin tovlash..." },
        { id: 185, nom: "Elektr, issiqlik energiyasidan foydalanish qoidalarini buzish", matn: "Noqonuniy foydalanish..." },
        { id: 186, nom: "Xavfsizlik talablariga javob bermaydigan tovarlarni o‘tkazish", matn: "Sifatsiz tovarlarni o‘tkazish..." },
        { id: 187, nom: "Giyohvandlik vositalari bilan bog‘liq jinoyatlar", matn: "Giyohvandlik vositalari savdosi..." },
        { id: 188, nom: "Noqonuniy tadbirkorlik", matn: "Litsenziyasiz faoliyat yuritish..." },
        { id: 189, nom: "Savdo qoidalarini muntazam buzish", matn: "Savdo qoidalarini bir necha bor buzish..." }
    ];

    const container = document.getElementById('display-area');
    moddalar.forEach(m => {
        container.innerHTML += `
            <div class="modda-box">
                <span class="modda-id">${m.id}-modda.</span> 
                <span class="modda-nom">${m.nom}</span>
                <p>${m.matn}</p>
            </div>
        `;
    });
</script>

</body>
</html>
