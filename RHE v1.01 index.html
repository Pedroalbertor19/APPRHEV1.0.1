<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Controle Profissional de Horas Extras | Turno Noturno + Diurno</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', 'Inter', system-ui, -apple-system, 'Arial', sans-serif;
            color: #f0f9ff;
            background: linear-gradient(-45deg, #0b1a22, #1e3a47, #1f4e6b, #2d6a8f);
            background-size: 400% 400%;
            animation: bgWave 14s ease infinite;
        }

        @keyframes bgWave {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 1.5rem;
        }

        .card {
            background: rgba(12, 25, 35, 0.85);
            backdrop-filter: blur(2px);
            border-radius: 28px;
            padding: 1.5rem;
            margin-bottom: 2rem;
            box-shadow: 0 20px 35px -12px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(72, 187, 255, 0.25);
            transition: all 0.2s;
        }

        h1 {
            font-weight: 700;
            font-size: 1.9rem;
            margin: 0 0 0.25rem 0;
            display: flex;
            align-items: center;
            gap: 12px;
            flex-wrap: wrap;
        }

        h1 small {
            font-size: 0.75rem;
            background: #0a2e3f;
            padding: 5px 12px;
            border-radius: 60px;
            font-weight: normal;
            letter-spacing: 0.3px;
        }

        h3 {
            margin-top: 0;
            margin-bottom: 1rem;
            font-weight: 600;
            border-left: 4px solid #2bc0ff;
            padding-left: 12px;
        }

        .grid-2col {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 1rem;
        }

        label {
            font-weight: 500;
            font-size: 0.85rem;
            margin-top: 0.5rem;
            display: block;
            letter-spacing: 0.3px;
            opacity: 0.9;
        }

        input, select, textarea, button {
            width: 100%;
            margin-top: 6px;
            padding: 12px 14px;
            border: none;
            border-radius: 18px;
            background: #ecf9ff;
            font-size: 0.95rem;
            font-weight: 500;
            color: #042433;
            transition: all 0.2s;
        }

        textarea {
            resize: vertical;
            font-family: inherit;
        }

        button {
            background: linear-gradient(135deg, #1fa2ff, #0a6cbd);
            color: white;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 5px 12px rgba(0, 120, 210, 0.3);
            border: none;
            transition: 0.2s;
        }

        button:hover {
            background: linear-gradient(135deg, #3bb3ff, #0f7fcf);
            transform: scale(0.98);
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .btn-outline {
            background: rgba(255,255,240,0.1);
            backdrop-filter: blur(4px);
            border: 1px solid #7bceff;
            color: #d9f2ff;
            box-shadow: none;
        }

        .btn-outline:hover {
            background: #1d8fd1;
            color: white;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1rem;
            font-size: 0.85rem;
            overflow-x: auto;
            display: table;
        }

        th, td {
            padding: 12px 6px;
            border-bottom: 1px solid rgba(160, 210, 255, 0.3);
            text-align: center;
            vertical-align: middle;
        }

        th {
            background: #0a374b80;
            font-weight: 600;
            letter-spacing: 0.5px;
        }

        .badge {
            background: #0e5d7a;
            padding: 4px 10px;
            border-radius: 50px;
            font-size: 0.7rem;
            font-weight: bold;
        }

        .total {
            background: #021c28aa;
            padding: 16px;
            border-radius: 28px;
            font-size: 1.2rem;
            font-weight: bold;
            margin-top: 1rem;
            backdrop-filter: blur(5px);
            text-align: center;
        }

        .delete-btn {
            background: #b91c1c99;
            border-radius: 32px;
            padding: 6px 10px;
            color: white;
            font-weight: bold;
            width: auto;
            transition: 0.1s;
        }

        .delete-btn:hover {
            background: #ff4d4d;
            transform: scale(1.02);
        }

        .flex-buttons {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        @media (max-width: 700px) {

            th, td {
                font-size: 0.7rem;
                padding: 6px 3px;
            }
        }

        hr {
            border-color: #2f7ea0;
            margin: 0.5rem 0;
        }

        .info-note {
            font-size: 0.75rem;
            background: #0d2e3d;
            border-radius: 24px;
            padding: 8px 14px;
            margin-top: 10px;
            text-align: center;
        }
    </style>
</head>
<body>
<div class="container">
    <h1>⏱️ Controle Profissional de Horas Extras
        <small>suporte a turnos > 24h | madrugada</small>
    </h1>

    <!-- Configuração Salário -->
    <div class="card">
        <h3>💰 Salário base</h3>
        <div class="grid-2col">
            <div>
                <label>Salário mensal (R$)</label>
                <input type="number" id="salario" placeholder="Ex: 3200" step="100">
            </div>
            <div style="display: flex; align-items: end;">
                <button onclick="salvarSalario()">💾 Salvar salário</button>
            </div>
        </div>
        <div id="salarioStatus" class="info-note" style="margin-top: 8px;">⚙️ Salário atual: R$ 0,00</div>
    </div>

    <!-- Registro com Data Início + Data Saída (suporte a dias diferentes) -->
    <div class="card">
        <h3>📌 Adicionar hora extra (início em um dia, fim no outro)</h3>
        <div class="grid-2col">
            <div>
                <label>📅 Data de INÍCIO</label>
                <input type="date" id="inicioData">
                <label>⏰ Hora de INÍCIO</label>
                <input type="time" id="inicioHora">
            </div>
            <div>
                <label>📅 Data de SAÍDA (pode ser dia seguinte)</label>
                <input type="date" id="fimData">
                <label>⏰ Hora de SAÍDA</label>
                <input type="time" id="fimHora">
            </div>
        </div>
        <div class="grid-2col" style="margin-top: 10px;">
            <select id="tipoExtra">
                <option value="50">50% (dia útil) - padrão</option>
                <option value="100">100% (domingo/feriado) - automático ou manual</option>
            </select>
            <textarea id="descricaoExtra" rows="2" placeholder="Descrição da atividade (ex: manutenção emergencial, atendimento cliente)"></textarea>
        </div>
        <button onclick="adicionarRegistroComDatas()">➕ Adicionar Registro (início → fim)</button>
        <div class="info-note">
            🔁 Suporte a jornadas que cruzam meia-noite: Ex: início 29/04/2026 19:15 → saída 30/04/2026 03:10.<br>
            🧠 Feriados nacionais e domingos são automaticamente considerados 100% (independente da seleção).
        </div>
    </div>

    <!-- Filtro + Exportação -->
    <div class="card">
        <h3>📆 Filtro mensal / ações</h3>
        <div class="grid-2col">
            <div>
                <label>Filtrar por mês/ano</label>
                <input type="month" id="filtroMes" onchange="renderizarTabela()">
            </div>
            <div class="flex-buttons" style="margin-top: 22px;">
                <button onclick="gerarPDFextendido()" style="background:#2c6e9e;">📄 Exportar relatório .txt</button>
                <button onclick="limparFiltro()" class="btn-outline">🗑️ Limpar filtro</button>
            </div>
        </div>
    </div>

    <!-- Tabela de registros -->
    <div class="card">
        <h3>📋 Histórico de horas extras</h3>
        <div style="overflow-x: auto;">
            <table>
                <thead>
                <tr><th>Período (início → fim)</th><th>Horas totais</th><th>Adicional</th><th>Valor (R$)</th><th>Descrição</th><th></th></tr>
                </thead>
                <tbody id="tabelaRegistros"></tbody>
            </table>
        </div>
        <div id="totaisContainer" class="total"></div>
        <div class="info-note">
            📌 Cálculo: Valor hora = Salário / 220. Extra = horas trabalhadas × valor hora × (1 + %adicional). <br>
            🟢 Dias úteis: +50% | 🟠 Domingos/feriados nacionais: +100% (sobrescreve seleção).
        </div>
    </div>
</div>

<script>
    // ----- Estrutura de dados estendida -----
    // cada registro guarda:
    // startDate, startTime, endDate, endTime, horasCalculadas, tipoPercentual (50 ou 100), valorTotal, descricao
    let registros = JSON.parse(localStorage.getItem("horasExtrasPlus")) || [];
    let salarioMensal = parseFloat(localStorage.getItem("salarioPlus")) || 0;

    // Atualizar visual do salário
    function atualizarDisplaySalario() {
        let inputSalario = document.getElementById("salario");
        if (inputSalario) inputSalario.value = salarioMensal;
        const statusSpan = document.getElementById("salarioStatus");
        if (statusSpan) statusSpan.innerHTML = `💰 Salário atual: R$ ${salarioMensal.toFixed(2)} | Valor hora: R$ ${(salarioMensal / 220).toFixed(2)}`;
    }

    function salvarSalario() {
        let valor = parseFloat(document.getElementById("salario").value);
        if (isNaN(valor)) valor = 0;
        salarioMensal = valor;
        localStorage.setItem("salarioPlus", salarioMensal);
        atualizarDisplaySalario();
        renderizarTabela();  // recalcula valores se existir registros
        alert(`✅ Salário definido: R$ ${salarioMensal.toFixed(2)}`);
    }

    // Obter valor da hora extra com adicional (com base no tipo base e verificação feriado/domingo)
    function getValorHoraExtra(horas, dataInicioStr, tipoPercentualSelecionado) {
        if (salarioMensal <= 0) return 0;
        let valorHoraBase = salarioMensal / 220;
        // Verificar se data de início é domingo ou feriado nacional
        let dataObj = new Date(dataInicioStr);
        let isDomingo = dataObj.getDay() === 0;
        let isFeriadoFlag = isFeriadoNacional(dataInicioStr);
        let adicionalPercentual = tipoPercentualSelecionado;
        if (isDomingo || isFeriadoFlag) {
            adicionalPercentual = 100;   // 100% adicional -> multiplicador 2.0
        }
        let multiplicador = 1 + (adicionalPercentual / 100);
        let valorExtra = horas * valorHoraBase * multiplicador;
        return { valorExtra, adicionalUsado: adicionalPercentual };
    }

    // Feriados nacionais fixos (considerar ano atual flexível)
    function isFeriadoNacional(dataISO) {
        if (!dataISO) return false;
        let partes = dataISO.split("-");
        if (partes.length !== 3) return false;
        let mes = parseInt(partes[1]);
        let dia = parseInt(partes[2]);
        let feriados = [
            { mes: 1, dia: 1 },   // Confraternização
            { mes: 4, dia: 21 },  // Tiradentes
            { mes: 5, dia: 1 },   // Dia do Trabalho
            { mes: 9, dia: 7 },   // Independência
            { mes: 10, dia: 12 }, // N.S. Aparecida
            { mes: 11, dia: 2 },  // Finados
            { mes: 11, dia: 15 }, // Proclamação República
            { mes: 12, dia: 25 }  // Natal
        ];
        return feriados.some(f => f.mes === mes && f.dia === dia);
    }

    // Função que calcula horas entre duas datas com horas (precisa respeitar diferença real em horas)
    function calcularDuracaoHoras(startDate, startTime, endDate, endTime) {
        let dataHoraInicio = new Date(`${startDate}T${startTime}:00`);
        let dataHoraFim = new Date(`${endDate}T${endTime}:00`);
        if (isNaN(dataHoraInicio) || isNaN(dataHoraFim)) return 0;
        let diffMs = dataHoraFim - dataHoraInicio;
        if (diffMs <= 0) return 0; // Evita horas negativas
        let horas = diffMs / (1000 * 3600);
        return parseFloat(horas.toFixed(4));
    }

    // Adicionar registro com suporte a datas diferentes + validação
    function adicionarRegistroComDatas() {
        let inicioData = document.getElementById("inicioData").value;
        let inicioHora = document.getElementById("inicioHora").value;
        let fimData = document.getElementById("fimData").value;
        let fimHora = document.getElementById("fimHora").value;
        let tipoSelecionado = parseInt(document.getElementById("tipoExtra").value);
        let descricao = document.getElementById("descricaoExtra").value.trim();

        if (!inicioData || !inicioHora || !fimData || !fimHora) {
            alert("❌ Preencha todas as datas e horários de início e saída.");
            return;
        }

        // Valida se fim é posterior ao início (comparar timestamps)
        let dtIni = new Date(`${inicioData}T${inicioHora}:00`);
        let dtFim = new Date(`${fimData}T${fimHora}:00`);
        if (dtFim <= dtIni) {
            alert("⚠️ A data/hora de saída deve ser posterior à data/hora de início (inclusive turnos noturnos). Verifique.");
            return;
        }

        let horasTrabalhadas = calcularDuracaoHoras(inicioData, inicioHora, fimData, fimHora);
        if (horasTrabalhadas <= 0) {
            alert("⛔ Horas inválidas. Verifique intervalos.");
            return;
        }

        // Usamos a data de início para verificar domingo/feriado na definição de adicional
        let { valorExtra, adicionalUsado } = getValorHoraExtra(horasTrabalhadas, inicioData, tipoSelecionado);

        let novoRegistro = {
            id: Date.now() + Math.random() * 1000,
            startDate: inicioData,
            startTime: inicioHora,
            endDate: fimData,
            endTime: fimHora,
            horas: horasTrabalhadas,
            tipoBaseSelecionado: tipoSelecionado,    // 50 ou 100 original
            adicionalFinal: adicionalUsado,          // pode ser 50/100 ou forçado por domingo/feriado
            valor: valorExtra,
            descricao: descricao || "sem descrição"
        };

        registros.push(novoRegistro);
        salvarRegistros();
        limparFormularioBasico();
        renderizarTabela();
    }

    function limparFormularioBasico() {
        document.getElementById("inicioData").value = "";
        document.getElementById("inicioHora").value = "";
        document.getElementById("fimData").value = "";
        document.getElementById("fimHora").value = "";
        document.getElementById("descricaoExtra").value = "";
        document.getElementById("tipoExtra").value = "50";
        // Opção pré definir data atual para facilitar? não limpar as datas dinamicamente para evitar repetição
    }

    function salvarRegistros() {
        localStorage.setItem("horasExtrasPlus", JSON.stringify(registros));
    }

    function removerRegistro(index) {
        if (confirm("Deseja excluir este registro?")) {
            registros.splice(index, 1);
            salvarRegistros();
            renderizarTabela();
        }
    }

    // Renderizar com filtro mensal (comparando startDate ou endDate? usamos startDate para filtro por início do turno)
    function renderizarTabela() {
        let filtroMes = document.getElementById("filtroMes").value;
        let body = document.getElementById("tabelaRegistros");
        if (!body) return;
        body.innerHTML = "";

        let totalHoras = 0;
        let totalValor = 0;

        let filtered = [...registros];
        if (filtroMes) {
            filtered = registros.filter(reg => {
                // o mês do início do turno
                let dataInicioStr = reg.startDate;
                if (!dataInicioStr) return false;
                return dataInicioStr.startsWith(filtroMes);
            });
        }

        if (filtered.length === 0) {
            body.innerHTML = "<tr><td colspan='6' style='text-align:center;padding:25px;'>📭 Nenhum registro encontrado para o período.</td></tr>";
            document.getElementById("totaisContainer").innerHTML = `📊 Total: 0h | R$ 0,00`;
            return;
        }

        filtered.forEach((reg, idx) => {
            let horasExibidas = reg.horas.toFixed(2);
            let adicionalExibido = reg.adicionalFinal + "%";
            let valorExibido = `R$ ${reg.valor.toFixed(2)}`;
            let periodoLegivel = `${formatarDataBR(reg.startDate)} ${reg.startTime} → ${formatarDataBR(reg.endDate)} ${reg.endTime}`;
            let desc = reg.descricao.length > 35 ? reg.descricao.substring(0, 32) + "..." : reg.descricao;

            totalHoras += reg.horas;
            totalValor += reg.valor;

            let tr = document.createElement("tr");
            tr.innerHTML = `
                <td style="font-weight:500;">${periodoLegivel}</td>
                <td><strong>${horasExibidas}h</strong></td>
                <td><span class="badge">${adicionalExibido}</span></td>
                <td style="color:#c3e88d;">${valorExibido}</td>
                <td>${desc}</td>
                <td><button class="delete-btn" onclick="removerRegistro(${registros.indexOf(reg)})">🗑️</button></td>
            `;
            body.appendChild(tr);
        });

        document.getElementById("totaisContainer").innerHTML = `
            ⏱️ TOTAL HORAS EXTRAS: ${totalHoras.toFixed(2)}h &nbsp;|&nbsp; 💵 TOTAL REMUNERAÇÃO EXTRA: R$ ${totalValor.toFixed(2)}
            <span style="display:inline-block; margin-left:12px; font-size:0.8rem;">🔎 ${filtered.length} registro(s)</span>
        `;
    }

    function formatarDataBR(dataISO) {
        if (!dataISO) return "inválida";
        let partes = dataISO.split("-");
        if (partes.length !== 3) return dataISO;
        return `${partes[2]}/${partes[1]}/${partes[0]}`;
    }

    function limparFiltro() {
        document.getElementById("filtroMes").value = "";
        renderizarTabela();
    }

    // Relatório com detalhes de período (início / fim precisos)
    function gerarPDFextendido() {
        let filtroAtual = document.getElementById("filtroMes").value;
        let dadosFiltrados = [...registros];
        if (filtroAtual) {
            dadosFiltrados = registros.filter(r => r.startDate.startsWith(filtroAtual));
        }

        if (dadosFiltrados.length === 0) {
            alert("Nenhum registro para exportar no período atual.");
            return;
        }

        let cabecalho = "=== RELATÓRIO HORAS EXTRAS (TURNOS CRUZADOS) ===\n";
        cabecalho += `Gerado em: ${new Date().toLocaleString()}\n`;
        cabecalho += `Salário base: R$ ${salarioMensal.toFixed(2)} (valor hora R$ ${(salarioMensal/220).toFixed(2)})\n`;
        cabecalho += `Filtro: ${filtroAtual || "Todos os registros"}\n`;
        cabecalho += "━".repeat(60) + "\n\n";

        let totalHorasGeral = 0;
        let totalValorGeral = 0;

        dadosFiltrados.forEach(reg => {
            let inicioStr = `${formatarDataBR(reg.startDate)} ${reg.startTime}`;
            let fimStr = `${formatarDataBR(reg.endDate)} ${reg.endTime}`;
            let linha = `📅 INÍCIO: ${inicioStr}  →  SAÍDA: ${fimStr}\n` +
                        `   ⏱️ Duração: ${reg.horas.toFixed(2)} horas | Adicional: ${reg.adicionalFinal}% | Valor: R$ ${reg.valor.toFixed(2)}\n` +
                        `   📝 Descrição: ${reg.descricao}\n` +
                        `   ──────────────────────────────────────────\n`;
            cabecalho += linha;
            totalHorasGeral += reg.horas;
            totalValorGeral += reg.valor;
        });

        cabecalho += `\n📊 RESUMO: Total horas extras: ${totalHorasGeral.toFixed(2)}h | Total a receber: R$ ${totalValorGeral.toFixed(2)}\n`;
        cabecalho += "━".repeat(60) + "\n* Sistema inteligente considera domingos e feriados nacionais como 100% extra.";

        let blob = new Blob([cabecalho], { type: "text/plain;charset=utf-8" });
        let link = document.createElement("a");
        let nomeArquivo = `horas_extras_${filtroAtual || "geral"}_${new Date().toISOString().slice(0,10)}.txt`;
        link.href = URL.createObjectURL(blob);
        link.download = nomeArquivo;
        link.click();
        URL.revokeObjectURL(link.href);
    }

    // Inicialização e carregamento de valores
    function inicializar() {
        if (registros.length && typeof registros[0]?.horas === "undefined") {
            // Migração de segurança caso existam estruturas antigas
            registros = registros.filter(r => r.horas !== undefined);
            salvarRegistros();
        }
        atualizarDisplaySalario();
        renderizarTabela();

        // pré definir data atual para facilitar rápido preenchimento (opção amigável)
        let hoje = new Date().toISOString().slice(0, 10);
        let amanha = new Date(Date.now() + 86400000).toISOString().slice(0, 10);
        document.getElementById("inicioData").value = hoje;
        document.getElementById("inicioHora").value = "19:15";
        document.getElementById("fimData").value = amanha;
        document.getElementById("fimHora").value = "03:10";
    }

    window.adicionarRegistroComDatas = adicionarRegistroComDatas;
    window.removerRegistro = removerRegistro;
    window.salvarSalario = salvarSalario;
    window.renderizarTabela = renderizarTabela;
    window.limparFiltro = limparFiltro;
    window.gerarPDFextendido = gerarPDFextendido;

    inicializar();
</script>
</body>
</html>
