<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RECRUTAMENTO MODERADOR | IMPÉRIO CITY</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Rajdhani:wght@500;700&display=swap" rel="stylesheet">
    <style>
        :root { --blue: #00f2ff; --purple: #9d00ff; --bg: #050507; }
        body { background: var(--bg); color: #fff; font-family: 'Rajdhani', sans-serif; padding: 20px; display: flex; justify-content: center; }
        .card { width: 100%; max-width: 700px; background: rgba(255,255,255,0.03); border: 1px solid var(--blue); padding: 30px; border-radius: 15px; box-shadow: 0 0 30px rgba(0,242,255,0.1); }
        h1 { font-family: 'Orbitron'; color: var(--blue); text-align: center; font-size: 1.4rem; margin-bottom: 5px; }
        .header-sub { text-align: center; color: var(--purple); font-weight: bold; margin-bottom: 20px; }
        .warning { background: rgba(255,0,0,0.1); border: 1px solid red; padding: 10px; font-size: 0.9rem; text-align: center; margin-bottom: 25px; border-radius: 5px; }
        .section { background: rgba(157, 0, 255, 0.1); padding: 8px; margin: 25px 0 15px; color: var(--blue); font-weight: bold; text-transform: uppercase; border-left: 4px solid var(--purple); }
        label { display: block; margin-top: 15px; margin-bottom: 5px; color: #ccc; }
        input, textarea, select { width: 100%; padding: 12px; background: #000; border: 1px solid #333; color: #fff; border-radius: 5px; box-sizing: border-box; }
        .grid-checkbox { display: grid; grid-template-columns: repeat(auto-fill, minmax(120px, 1fr)); gap: 10px; margin-top: 10px; }
        .checkbox-item { display: flex; align-items: center; gap: 8px; font-size: 0.9rem; }
        .checkbox-item input { width: auto; margin: 0; }
        .btn { width: 100%; padding: 20px; background: transparent; border: 2px solid var(--blue); color: var(--blue); font-family: 'Orbitron'; cursor: pointer; font-weight: bold; margin-top: 40px; transition: 0.3s; }
        .btn:hover { background: var(--blue); color: #000; box-shadow: 0 0 20px var(--blue); }
        footer { text-align: center; margin-top: 30px; font-size: 0.8rem; color: #555; }
    </style>
</head>
<body>

<div class="card">
    <h1>🛡️ FORMULÁRIO DE RECRUTAMENTO — MODERADOR</h1>
    <div class="header-sub">👑 IMPÉRIO CITY (ROBLOX)</div>
    
    <div class="warning">
        Este formulário deve ser preenchido com seriedade e honestidade. Respostas troll ou incompletas resultarão em reprovação.
    </div>

    <form id="formImperio">
        <div class="section">👤 INFORMAÇÕES PESSOAIS</div>
        <label>1️⃣ Nome (RP):</label>
        <input type="text" id="q1" required>
        
        <label>2️⃣ Idade (OFF):</label>
        <input type="number" id="q2" required>

        <label>3️⃣ Nick no Roblox:</label>
        <input type="text" id="q3" required>

        <label>4️⃣ Nick no Discord + Tag:</label>
        <input type="text" id="q4" required>

        <label>5️⃣ Fuso horário:</label>
        <input type="text" id="q5" value="Brasília (GMT-3)" required>

        <div class="section">⏱️ DISPONIBILIDADE</div>
        <label>6️⃣ Quantas horas por dia você pode moderar?</label>
        <select id="q6">
            <option value="1-2h">1–2h</option>
            <option value="3-4h">3–4h</option>
            <option value="5h+">5h+</option>
        </select>

        <label>7️⃣ Em quais dias você estará ativo?</label>
        <div class="grid-checkbox">
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Segunda"> Segunda</div>
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Terça"> Terça</div>
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Quarta"> Quarta</div>
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Quinta"> Quinta</div>
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Sexta"> Sexta</div>
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Sábado"> Sábado</div>
            <div class="checkbox-item"><input type="checkbox" name="dias" value="Domingo"> Domingo</div>
        </div>

        <div class="section">📘 EXPERIÊNCIA</div>
        <label>8️⃣ Já foi moderador antes? Onde?</label>
        <textarea id="q8" rows="2"></textarea>

        <label>9️⃣ Cite 2 servidores em que você já trabalhou (se tiver):</label>
        <textarea id="q9" rows="2"></textarea>

        <label>🔟 Você sabe usar bots de moderação (MEE6, Dyno, Wick, etc.)? Explique brevemente.</label>
        <textarea id="q10" rows="2"></textarea>

        <div class="section">🧠 CONHECIMENTO DE REGRAS</div>
        <label>1️⃣1️⃣ O que você faria se um membro estivesse xingando no chat?</label>
        <textarea id="q11" rows="3"></textarea>

        <label>1️⃣2️⃣ O que você faria se um amigo seu quebrasse as regras?</label>
        <textarea id="q12" rows="3"></textarea>

        <label>1️⃣3️⃣ O que é abuso de poder para você?</label>
        <textarea id="q13" rows="3"></textarea>

        <div class="section">🎭 ROLEPLAY & IMPÉRIO CITY</div>
        <label>1️⃣4️⃣ Há quanto tempo você está no Império City?</label>
        <input type="text" id="q14">

        <label>1️⃣5️⃣ Por que quer ser Moderador do Império City? (mín. 5 linhas)</label>
        <textarea id="q15" rows="5" required></textarea>

        <label>1️⃣6️⃣ O que você pode trazer de bom para o servidor?</label>
        <textarea id="q16" rows="3"></textarea>

        <div class="section">⚖️ COMPROMISSO</div>
        <label>1️⃣7️⃣ Você se compromete a ser imparcial, respeitar a staff e não abusar do cargo?</label>
        <select id="q17"><option value="Sim">Sim</option><option value="Não">Não</option></select>

        <label>1️⃣8️⃣ Você aceita que pode ser rebaixado se não cumprir seu dever?</label>
        <select id="q18"><option value="Sim">Sim</option><option value="Não">Não</option></select>

        <div class="section">✍️ DECLARAÇÃO FINAL</div>
        <label>Assinatura (Nome RP):</label>
        <input type="text" id="assinatura" required>

        <button type="submit" class="btn" id="btnEnv">TRANSMITIR CANDIDATURA</button>
    </form>

    <footer>🛡️ IMPÉRIO CITY — Organização • Respeito • Responsabilidade 👑</footer>
</div>

<script>
    document.getElementById('formImperio').addEventListener('submit', function(e) {
        e.preventDefault();
        const WEBHOOK = "https://discord.com/api/webhooks/1462910114800472311/Ss0lztssB9GScoy0MdYGMSj2lh7eYoJvig-IWsoNIj0n535MS0y-1WwRYhtrALyROFju";
        
        const btn = document.getElementById('btnEnv');
        btn.innerText = "ENVIANDO AO COMANDO...";
        btn.disabled = true;

        const dias = Array.from(document.querySelectorAll('input[name="dias"]:checked')).map(d => d.value).join(", ");

        const corpo = {
            content: "🔔 **NOVO RECRUTAMENTO MODERADOR!** <@1395820830847668274>",
            embeds: [{
                title: "🛡️ FICHA DE CANDIDATURA - IMPÉRIO CITY",
                color: 65535,
                fields: [
                    { name: "👤 Nome RP / Idade", value: `${document.getElementById('q1').value} / ${document.getElementById('q2').value} anos`, inline: true },
                    { name: "🎮 Roblox / Discord", value: `${document.getElementById('q3').value} / ${document.getElementById('q4').value}`, inline: true },
                    { name: "⏱️ Disponibilidade", value: `${document.getElementById('q6').value} | Dias: ${dias}`, inline: false },
                    { name: "🧠 Conhecimento (Abuso)", value: document.getElementById('q13').value },
                    { name: "🎭 Motivação", value: document.getElementById('q15').value },
                    { name: "✍️ Assinatura", value: document.getElementById('assinatura').value, inline: true },
                    { name: "📅 Data", value: new Date().toLocaleDateString(), inline: true }
                ],
                footer: { text: "Sistema de Recrutamento Império City" }
            }]
        };

        fetch(WEBHOOK, {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify(corpo)
        }).then(() => {
            alert("✅ Sua declaração foi enviada com sucesso!");
            btn.innerText = "TRANSMITIDO!";
        }).catch(() => {
            alert("❌ Erro na conexão.");
            btn.disabled = false;
            btn.innerText = "TENTAR NOVAMENTE";
        });
    });
</script>
</body>
</html>
