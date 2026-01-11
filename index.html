<!DOCTYPE html>

<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gestão de Condomínios - Efetiva</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background: linear-gradient(135deg, #0d3d2f 0%, #1a5c47 100%); min-height: 100vh; padding: 20px; }
        .container { max-width: 1400px; margin: 0 auto; }
        .card { background: white; border-radius: 12px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); padding: 30px; margin-bottom: 20px; }
        .header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 30px; flex-wrap: wrap; gap: 15px; }
        h1 { color: #1f2937; font-size: 28px; }
        .button-group { display: flex; gap: 10px; flex-wrap: wrap; }
        button { padding: 10px 20px; border: none; border-radius: 8px; cursor: pointer; font-size: 14px; font-weight: 600; transition: all 0.3s; display: flex; align-items: center; gap: 8px; }
        .btn-primary { background: #7fb432; color: white; }
        .btn-primary:hover { background: #6a9929; }
        .btn-success { background: #059669; color: white; }
        .btn-success:hover { background: #047857; }
        .btn-warning { background: #eab308; color: white; padding: 8px; }
        .btn-warning:hover { background: #ca8a04; }
        .btn-danger { background: #dc2626; color: white; padding: 8px; }
        .btn-danger:hover { background: #b91c1c; }
        .btn-secondary { background: #6b7280; color: white; }
        .btn-secondary:hover { background: #4b5563; }
        .tabs { display: flex; gap: 10px; margin-bottom: 25px; border-bottom: 2px solid #e5e7eb; flex-wrap: wrap; }
        .tab { padding: 12px 24px; border: none; background: transparent; color: #6b7280; font-weight: 600; cursor: pointer; border-bottom: 3px solid transparent; transition: all 0.3s; }
        .tab:hover { color: #7fb432; }
        .tab.active { color: #7fb432; border-bottom-color: #7fb432; }
        .tab-content { display: none; }
        .tab-content.active { display: block; }
        .stats { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-bottom: 25px; }
        .stat-card { background: linear-gradient(135deg, #7fb432 0%, #6a9929 100%); color: white; padding: 20px; border-radius: 10px; text-align: center; }
        .stat-number { font-size: 36px; font-weight: 700; margin-bottom: 5px; }
        .stat-label { font-size: 14px; opacity: 0.9; }
        .form-container { background: #f9fafb; padding: 25px; border-radius: 8px; border: 2px solid #7fb432; margin-bottom: 25px; display: none; }
        .form-container.active { display: block; }
        .form-title { font-size: 20px; color: #374151; margin-bottom: 20px; }
        .form-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; margin-bottom: 15px; }
        .form-group { display: flex; flex-direction: column; }
        label { font-size: 14px; font-weight: 600; color: #374151; margin-bottom: 5px; }
        input[type="text"], input[type="number"], select { padding: 10px; border: 1px solid #d1d5db; border-radius: 6px; font-size: 14px; }
        input:focus, select:focus { outline: none; border-color: #7fb432; box-shadow: 0 0 0 3px rgba(127, 180, 50, 0.1); }
        .table-wrapper { overflow-x: auto; -webkit-overflow-scrolling: touch; }
        table { width: 100%; border-collapse: collapse; min-width: 800px; }
        thead { background: linear-gradient(135deg, #0d3d2f 0%, #1a5c47 100%); color: white; }
        th { padding: 15px 10px; text-align: left; font-weight: 600; font-size: 14px; white-space: nowrap; }
        th.center, td.center { text-align: center; }
        tr { border-bottom: 1px solid #e5e7eb; }
        tbody tr:nth-child(even) { background: #f9fafb; }
        tbody tr:hover { background: #f3f4f6; }
        td { padding: 15px 10px; font-size: 14px; color: #374151; }
        .badge { display: inline-block; padding: 6px 12px; border-radius: 20px; font-size: 12px; font-weight: 700; }
        .badge-remota { background: #dbeafe; color: #1e40af; }
        .badge-hibrida { background: #fef3c7; color: #92400e; }
        .badge-fisica { background: #d1fae5; color: #065f46; }
        .actions { display: flex; gap: 8px; justify-content: center; }
        .empty-state { text-align: center; padding: 60px 20px; color: #6b7280; }
        .condominio-card { display: none; background: white; border: 1px solid #e5e7eb; border-radius: 10px; padding: 20px; margin-bottom: 15px; box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05); }
        .condominio-card-header { display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 15px; padding-bottom: 15px; border-bottom: 2px solid #e5e7eb; }
        .condominio-card-title { font-size: 16px; font-weight: 700; color: #1f2937; flex: 1; }
        .condominio-card-body { display: flex; flex-direction: column; gap: 12px; }
        .condominio-info-row { display: flex; justify-content: space-between; align-items: center; padding: 8px 0; }
        .condominio-label { font-size: 13px; font-weight: 600; color: #6b7280; }
        .condominio-value { font-size: 14px; color: #1f2937; font-weight: 500; text-align: right; }
        @media (max-width: 768px) {
            body { padding: 10px; }
            .card { padding: 15px; }
            .header { flex-direction: column; align-items: stretch; }
            h1 { font-size: 20px; text-align: center; }
            .button-group { width: 100%; flex-direction: column; }
            .button-group button { width: 100%; justify-content: center; padding: 12px 20px; font-size: 15px; }
            .tab { padding: 10px 16px; font-size: 13px; }
            .stats { grid-template-columns: 1fr; }
            .form-grid { grid-template-columns: 1fr; }
            .form-group input, .form-group select { padding: 12px; font-size: 16px; }
            .table-wrapper { display: none; }
            .condominio-card { display: block; }
        }
        @media (min-width: 769px) {
            .condominio-card { display: none !important; }
            .table-wrapper { display: block; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <div class="header">
                <h1>🏢 Gestão de Condomínios - Efetiva</h1>
                <div class="button-group">
                    <button class="btn-success" onclick="exportCSV()">📥 Exportar</button>
                    <button class="btn-primary" onclick="toggleForm()">➕ Novo</button>
                </div>
            </div>

```
        <div class="stats">
            <div class="stat-card"><div class="stat-number" id="totalCondominios">75</div><div class="stat-label">Total</div></div>
            <div class="stat-card"><div class="stat-number" id="totalRemota">16</div><div class="stat-label">Remota</div></div>
            <div class="stat-card"><div class="stat-number" id="totalHibrida">13</div><div class="stat-label">Híbrida</div></div>
            <div class="stat-card"><div class="stat-number" id="totalFisica">46</div><div class="stat-label">Física</div></div>
        </div>

        <div class="form-container" id="formContainer">
            <h2 class="form-title" id="formTitle">Adicionar Novo Condomínio</h2>
            <div class="form-grid">
                <div class="form-group"><label>Nome *</label><input type="text" id="nomeCondominio"></div>
                <div class="form-group"><label>Endereço</label><input type="text" id="endereco"></div>
                <div class="form-group"><label>Tipo *</label><select id="tipoPortaria"><option value="">Selecione...</option><option value="Remota">Remota</option><option value="Híbrida">Híbrida</option><option value="Física">Física</option></select></div>
            </div>
            <div class="form-grid">
                <div class="form-group"><label>Unidades</label><input type="number" id="numUnidades" min="0"></div>
                <div class="form-group"><label>Responsável</label><input type="text" id="responsavel"></div>
                <div class="form-group"><label>Telefone</label><input type="text" id="telefone"></div>
            </div>
            <div class="button-group">
                <button class="btn-primary" onclick="saveCondominio()">💾 Salvar</button>
                <button class="btn-secondary" onclick="cancelForm()">❌ Cancelar</button>
            </div>
        </div>

        <div class="tabs">
            <button class="tab active" onclick="changeTab('todos')">Todos</button>
            <button class="tab" onclick="changeTab('remota')">Remota</button>
            <button class="tab" onclick="changeTab('hibrida')">Híbrida</button>
            <button class="tab" onclick="changeTab('fisica')">Física</button>
        </div>

        <div id="tabTodos" class="tab-content active">
            <div class="table-wrapper"><table><thead><tr><th>Nome</th><th>Endereço</th><th class="center">Tipo</th><th>Responsável</th><th>Telefone</th><th class="center">Ações</th></tr></thead><tbody id="tableTodos"></tbody></table></div>
            <div id="cardsTodos"></div>
        </div>

        <div id="tabRemota" class="tab-content">
            <div class="table-wrapper"><table><thead><tr><th>Nome</th><th>Endereço</th><th>Responsável</th><th>Telefone</th><th class="center">Ações</th></tr></thead><tbody id="tableRemota"></tbody></table></div>
            <div id="cardsRemota"></div>
        </div>

        <div id="tabHibrida" class="tab-content">
            <div class="table-wrapper"><table><thead><tr><th>Nome</th><th>Endereço</th><th>Responsável</th><th>Telefone</th><th class="center">Ações</th></tr></thead><tbody id="tableHibrida"></tbody></table></div>
            <div id="cardsHibrida"></div>
        </div>

        <div id="tabFisica" class="tab-content">
            <div class="table-wrapper"><table><thead><tr><th>Nome</th><th>Endereço</th><th>Responsável</th><th>Telefone</th><th class="center">Ações</th></tr></thead><tbody id="tableFisica"></tbody></table></div>
            <div id="cardsFisica"></div>
        </div>
    </div>
</div>

<script>
    let condominios = JSON.parse('[{"id":1,"nomeCondominio":"QUINTANARES","endereco":"AVENIDA BAGÉ, Nº900, PETROPOLIS, CEP 90.460-080","tipoPortaria":"Física","numUnidades":0,"responsavel":"ANTÔNIO / SILVIO","telefone":""},{"id":2,"nomeCondominio":"VILA DE ROMA","endereco":"ATANASIO BELMONTE 450","tipoPortaria":"Física","numUnidades":0,"responsavel":"CARLA PIVA","telefone":"51-99385-2998"},{"id":3,"nomeCondominio":"SANTA MONICA","endereco":"AV GRECIA 1050","tipoPortaria":"Física","numUnidades":0,"responsavel":"CHRISTIAN","telefone":"51-98138-2228"},{"id":4,"nomeCondominio":"SAINT PAUL","endereco":"TRAV. CEL. ANTONIO CARNEIRO PINTO, Nº63","tipoPortaria":"Física","numUnidades":0,"responsavel":"CHRYSTIAN","telefone":""},{"id":5,"nomeCondominio":"SAINT PETER","endereco":"TRAV. CEL. ANTONIO CARNEIRO PINTO Nº165","tipoPortaria":"Física","numUnidades":0,"responsavel":"CLARICE","telefone":"51-9849-3312"},{"id":6,"nomeCondominio":"HENRI MATISSE","endereco":"FELIPE NERI 148","tipoPortaria":"Física","numUnidades":0,"responsavel":"CRISTIANE","telefone":""},{"id":7,"nomeCondominio":"ORLEANS","endereco":"VENANCIO AIRES 1001","tipoPortaria":"Física","numUnidades":0,"responsavel":"EDMUNDO","telefone":""},{"id":8,"nomeCondominio":"MONTMATRE","endereco":"RUA ARTHUR ROCHA, Nº590","tipoPortaria":"Física","numUnidades":0,"responsavel":"HAMILTON","telefone":""},{"id":9,"nomeCondominio":"QUEBEC","endereco":"RUA CARLOS TREIN FILHO, Nº550","tipoPortaria":"Física","numUnidades":0,"responsavel":"IRENE","telefone":""},{"id":10,"nomeCondominio":"NAUTILUS","endereco":"RUA VIGÁRIO JOSÉ INÁCIO 295","tipoPortaria":"Física","numUnidades":0,"responsavel":"LEONILDA","telefone":""},{"id":11,"nomeCondominio":"MONT BLANC","endereco":"RUA CARLOS TREIN FILHO, Nº1271","tipoPortaria":"Física","numUnidades":0,"responsavel":"LUCIA","telefone":"99989-1685"},{"id":12,"nomeCondominio":"VANGARD","endereco":"RUA SÃO LUIZ 662","tipoPortaria":"Física","numUnidades":0,"responsavel":"LUCIANA","telefone":"98598-4704"},{"id":13,"nomeCondominio":"SPECIAL PLACE","endereco":"GOMES JARDIM 1188","tipoPortaria":"Física","numUnidades":0,"responsavel":"LUCIANA","telefone":"98598-4704"},{"id":14,"nomeCondominio":"MARQUIS MOINHOS","endereco":"RUA MARQUES DO HERVAL, Nº75","tipoPortaria":"Física","numUnidades":0,"responsavel":"LUIS ANTÔNIO","telefone":"51-9981-8895"},{"id":15,"nomeCondominio":"THE SUN","endereco":"RUA WHASHINGTON LUIZ, Nº238","tipoPortaria":"Física","numUnidades":0,"responsavel":"MELÂNIA","telefone":"54-99608-3397"},{"id":16,"nomeCondominio":"SANTAI","endereco":"GENERAL RONDON 1000","tipoPortaria":"Física","numUnidades":0,"responsavel":"NUBIANE","telefone":"51-9951-5357"},{"id":17,"nomeCondominio":"SANTORINI","endereco":"RUA PORTUGUESA, Nº460","tipoPortaria":"Física","numUnidades":0,"responsavel":"RODRIGO","telefone":""},{"id":18,"nomeCondominio":"ILE DE LA CITE","endereco":"AV. CAVALHADA 5075","tipoPortaria":"Física","numUnidades":0,"responsavel":"ROSALINO","telefone":"51-98585-9650"},{"id":19,"nomeCondominio":"CLINOSOM","endereco":"MOSTARDEIRO 265","tipoPortaria":"Física","numUnidades":0,"responsavel":"ROSANA","telefone":"99967-2652"},{"id":20,"nomeCondominio":"CRISTAL TOWER","endereco":"AV DIÁRIO DE NOTÍCIAS 200","tipoPortaria":"Física","numUnidades":0,"responsavel":"TABORDA","telefone":""},{"id":21,"nomeCondominio":"RESERVA PETROPOLIS","endereco":"RUA MARIO LEITAO, Nº60","tipoPortaria":"Física","numUnidades":0,"responsavel":"VANESSA","telefone":""},{"id":22,"nomeCondominio":"SANTORINI 2","endereco":"RUA SÃO FRANCISCO 222","tipoPortaria":"Física","numUnidades":0,"responsavel":"","telefone":""},{"id":23,"nomeCondominio":"VILA VERDE","endereco":"CEL. TENENTE PILAR 363","tipoPortaria":"Física","numUnidades":0,"responsavel":"","telefone":""},{"id":24,"nomeCondominio":"MICHELANGELO","endereco":"RUA CABRAL 829","tipoPortaria":"Física","numUnidades":0,"responsavel":"","telefone":""},{"id":25,"nomeCondominio":"ELENITÁ","endereco":"AV GETÚLIO VARGAS 673","tipoPortaria":"Física","numUnidades":0,"responsavel":"ALESSANDRO","telefone":""},{"id":26,"nomeCondominio":"BOSQUES DA GLORIA","endereco":"RUA DOM VITAL, 249","tipoPortaria":"Física","numUnidades":0,"responsavel":"ANTÔNIA","telefone":""},{"id":27,"nomeCondominio":"ESCOLA PROJETO","endereco":"AV IPIRANGA 585","tipoPortaria":"Física","numUnidades":0,"responsavel":"BERNADETE","telefone":""},{"id":28,"nomeCondominio":"BELLE VUE","endereco":"CASEMIRO DE ABREU 1557","tipoPortaria":"Física","numUnidades":0,"responsavel":"CARLA PIVA","telefone":"51-99385-2998"},{"id":29,"nomeCondominio":"FAMÍLIA CEEE","endereco":"RUA DOS ANDRADAS 702","tipoPortaria":"Física","numUnidades":0,"responsavel":"CHRISTIAN","telefone":""},{"id":30,"nomeCondominio":"VISTA COMFORT","endereco":"RUA ADÃO BAINO 61","tipoPortaria":"Física","numUnidades":0,"responsavel":"DAIANE","telefone":"51-98634-0917"},{"id":31,"nomeCondominio":"DORRINGTON","endereco":"RUA FARNESE, Nº210","tipoPortaria":"Física","numUnidades":0,"responsavel":"ELIZ","telefone":""},{"id":32,"nomeCondominio":"BOTTICELLI","endereco":"AV BAGÉ, Nº919","tipoPortaria":"Física","numUnidades":0,"responsavel":"FLÁVIA","telefone":"98529-8888"},{"id":33,"nomeCondominio":"ALVEAR","endereco":"AV BAGÉ, Nº1301","tipoPortaria":"Física","numUnidades":0,"responsavel":"LEANDRO","telefone":""},{"id":34,"nomeCondominio":"DI BENTO","endereco":"RUA JOSÉ DO PATROCÍNIO 913","tipoPortaria":"Física","numUnidades":0,"responsavel":"LUCIANO","telefone":""},{"id":35,"nomeCondominio":"CLINICA CHEFFE","endereco":"ALAMEDA MAJOR BARCELOS 76","tipoPortaria":"Física","numUnidades":0,"responsavel":"MARCELO","telefone":""},{"id":36,"nomeCondominio":"GUARIGLIA","endereco":"RUA SÃO FRANCISCO 329","tipoPortaria":"Física","numUnidades":0,"responsavel":"MURILO","telefone":""},{"id":37,"nomeCondominio":"CFL NILO","endereco":"AV NILO PEÇANHA, 2800","tipoPortaria":"Física","numUnidades":0,"responsavel":"NORBERTO","telefone":""},{"id":38,"nomeCondominio":"FRA BARTOLOMEU","endereco":"AV DR. NILO PEÇANHA, Nº350","tipoPortaria":"Física","numUnidades":0,"responsavel":"RENATO MACIEL","telefone":""},{"id":39,"nomeCondominio":"BOA ESPERANÇA","endereco":"RUA VASCO DA GAMA, Nº575","tipoPortaria":"Física","numUnidades":0,"responsavel":"RICARDO","telefone":"99122-9495"},{"id":40,"nomeCondominio":"GLASS MOINHOS","endereco":"RUA MARQUES DO HERVAL, Nº600","tipoPortaria":"Física","numUnidades":0,"responsavel":"RODRIGO","telefone":""},{"id":41,"nomeCondominio":"DOM RODRIGO","endereco":"RUA GENERAL LIMA E SILVA 1010","tipoPortaria":"Física","numUnidades":0,"responsavel":"RODRIGO","telefone":""},{"id":42,"nomeCondominio":"CARLOS GOMES","endereco":"AV CARLOS GOMES 1610","tipoPortaria":"Física","numUnidades":0,"responsavel":"SILVIO","telefone":""},{"id":43,"nomeCondominio":"JARDIM DE FRANCE","endereco":"RUA CARLOS TREIN FILHO, Nº1171","tipoPortaria":"Física","numUnidades":0,"responsavel":"SILVIO","telefone":""},{"id":44,"nomeCondominio":"ARACHANE","endereco":"PRAÇA DR. MAURICIO CARDOSO, Nº56","tipoPortaria":"Física","numUnidades":0,"responsavel":"VANESSA","telefone":""},{"id":45,"nomeCondominio":"GETÚLIO VARGAS","endereco":"AV. GETÚLIO VARGAS 1594","tipoPortaria":"Física","numUnidades":0,"responsavel":"","telefone":""},{"id":46,"nomeCondominio":"GOLDEN GATE","endereco":"ALAMEDA EMÍLIO DE MENEZES 140","tipoPortaria":"Física","numUnidades":0,"responsavel":"","telefone":""},{"id":47,"nomeCondominio":"14 BIS","endereco":"RUA DR. FREIRE ALEMÃO, Nº677","tipoPortaria":"Remota","numUnidades":0,"responsavel":"NIVEA","telefone":"99512-5750"},{"id":48,"nomeCondominio":"ATHENS VILLAGE","endereco":"RUA MORENO LOUREURIO LIMA, 100","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":49,"nomeCondominio":"GARAGEM BOM FIM","endereco":"RUA FERNANDES VIEIRA, Nº39","tipoPortaria":"Remota","numUnidades":0,"responsavel":"EDUARDO","telefone":"99977-1517"},{"id":50,"nomeCondominio":"GENERAL OLIVEIRA","endereco":"RUA DEMÉTRIO RIBEIRO, 961","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":51,"nomeCondominio":"HARI MENINO DEUS","endereco":"TRAVESSA DIRCEU 80","tipoPortaria":"Remota","numUnidades":0,"responsavel":"ARIANE","telefone":"51-99643-0213"},{"id":52,"nomeCondominio":"JARDIM AMERICA","endereco":"R. Dr. João de Deus Vaz 35","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":53,"nomeCondominio":"KADESH","endereco":"RUA SANTO ANTONIO, Nº238","tipoPortaria":"Remota","numUnidades":0,"responsavel":"LUCIANO","telefone":""},{"id":54,"nomeCondominio":"KOBLENZ","endereco":"RUA RIVEIRA, Nº520","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":55,"nomeCondominio":"L HERMITAGE","endereco":"FABRICIO PILAR ESQ FREI ALEMÃO","tipoPortaria":"Remota","numUnidades":0,"responsavel":"JULIO","telefone":""},{"id":56,"nomeCondominio":"LIBERTÁ","endereco":"RUA FELIPE NERI 240","tipoPortaria":"Remota","numUnidades":0,"responsavel":"SANDRA","telefone":""},{"id":57,"nomeCondominio":"LIFE.CO","endereco":"RUA SÃO MATEUS 611","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":58,"nomeCondominio":"LUXEMBURGO","endereco":"DR VALE 523","tipoPortaria":"Remota","numUnidades":0,"responsavel":"PAULO","telefone":""},{"id":59,"nomeCondominio":"MARIA CRISTINA","endereco":"RUA MONTENEGRO 82","tipoPortaria":"Remota","numUnidades":0,"responsavel":"ANTONELA","telefone":""},{"id":60,"nomeCondominio":"MOUNT MORIAH","endereco":"RUA ALVAREZ CABRAL, 314","tipoPortaria":"Remota","numUnidades":0,"responsavel":"LEANDRO","telefone":""},{"id":61,"nomeCondominio":"SAINT VERMONT","endereco":"RUA BORDINI 379","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":62,"nomeCondominio":"VIVÁ","endereco":"BARÃO DO AMAZONAS 1757","tipoPortaria":"Remota","numUnidades":0,"responsavel":"","telefone":""},{"id":63,"nomeCondominio":"JOSE RICALDONE","endereco":"RUA SANTO ANTONIO, Nº50","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"CLAUDIA","telefone":""},{"id":64,"nomeCondominio":"MARSEILLE","endereco":"AV BAGÉ, Nº1400","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"CLAUDIO","telefone":"51-9939-2229"},{"id":65,"nomeCondominio":"FORTUNE","endereco":"RUA FELIPE NERI 287","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"FERNANDO","telefone":""},{"id":66,"nomeCondominio":"VISTA","endereco":"ENG. ADOLFO STERN 62","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"FLAVIA","telefone":""},{"id":67,"nomeCondominio":"IIBAUA","endereco":"RUA BARÃO DE UBA, Nº459","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"FLÁVIA","telefone":"5198529-8888"},{"id":68,"nomeCondominio":"ARTUR","endereco":"RUA ARTUR ROCHA 505","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"JOUBERT","telefone":""},{"id":69,"nomeCondominio":"ROYAL CENTER","endereco":"RUA DOM PEDRO II, Nº124","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"PAULO","telefone":""},{"id":70,"nomeCondominio":"VILLAGIO MARINETTI","endereco":"AV G. BARRETO VIANA","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"RODRIGO","telefone":""},{"id":71,"nomeCondominio":"PLAZA MIRO","endereco":"ERICO VERISSIMO 240","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"ROSANA","telefone":""},{"id":72,"nomeCondominio":"GOLDEN","endereco":"RUA DOM PEDRO II, Nº367","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"SILVIO","telefone":""},{"id":73,"nomeCondominio":"LANDMARK","endereco":"MARQUES DO POMBAL, 450","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"","telefone":""},{"id":74,"nomeCondominio":"SOLAR DI FIRENZE","endereco":"RUA ADÃO BAINO 261","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"","telefone":""},{"id":75,"nomeCondominio":"ALVEAR HIBRIDO","endereco":"","tipoPortaria":"Híbrida","numUnidades":0,"responsavel":"","telefone":""}]');
    let editingId = null;
    let currentTab = 'todos';

    function updateStats() {
        document.getElementById('totalCondominios').textContent = condominios.length;
        document.getElementById('totalRemota').textContent = condominios.filter(c => c.tipoPortaria === 'Remota').length;
        document.getElementById('totalHibrida').textContent = condominios.filter(c => c.tipoPortaria === 'Híbrida').length;
        document.getElementById('totalFisica').textContent = condominios.filter(c => c.tipoPortaria === 'Física').length;
    }

    function getBadgeClass(tipo) {
        return tipo
```
