<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Painel de Acesso Rápido - Acelera Obra</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f2f5;
      margin: 0;
      padding: 20px;
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      color: #2d3748;
    }

    .kanban-board {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .kanban-column {
      border-radius: 10px;
      width: 320px;
      padding: 20px;
      background-color: #ffffff;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .kanban-column h2 {
      font-size: 18px;
      margin-bottom: 15px;
      padding: 10px;
      border-radius: 8px;
      color: #fff;
    }

    .ferramentas h2 {
      background: linear-gradient(to right, #4299e1, #3182ce);
    }

    .relatorios h2 {
      background: linear-gradient(to right, #48bb78, #38a169);
    }

    .pagamentos h2 {
      background: linear-gradient(to right, #ed8936, #dd6b20);
    }

    .contratos h2 {
      background: linear-gradient(to right, #a830cd, #a830cd);
    }

    .card {
      background-color: #f7fafc;
      border-left: 5px solid #e2e8f0;
      border-radius: 8px;
      padding: 12px 16px;
      margin-bottom: 10px;
      transition: 0.2s;
      cursor: pointer;
    }

    .card:hover {
      background-color: #ebf4ff;
      transform: scale(1.02);
    }

    .card-title {
      font-weight: bold;
      font-size: 16px;
      margin-bottom: 4px;
      color: #2d3748;
    }

    .card-info {
      font-size: 14px;
      color: #4a5568;
    }

    a {
      text-decoration: none;
    }

    #toast {
      position: fixed;
      bottom: 30px;
      left: 50%;
      transform: translateX(-50%);
      background: #38a169;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      display: none;
      font-weight: bold;
      box-shadow: 0 2px 6px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>

  <h1>📌 Painel de Acesso Rápido Acelera Obra - Carlos Amaral</h1>

  <div class="kanban-board">

    <!-- Ferramentas -->
    <div class="kanban-column ferramentas">
      <h2>📅 Ferramentas</h2>


      <a href="https://meu.businessdigital360.com.br/v2/location/gbkhVMNStgwRjHc3NUZY/opportunities/list" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">BD360 CRM</div>
          <div class="card-info">Acompanhe os leads e oportunidades</div>
        </div>
      </a>

      <a href="https://web.whatsapp.com/" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">WhatsApp Web</div>
          <div class="card-info">Comunicação com leads e clientes</div>
        </div>
      </a>

      <a href="https://calendar.google.com/calendar/u/0/r/week" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">Google Agenda</div>
          <div class="card-info">Agenda semanal de reuniões</div>
        </div>
      </a>

      <a href="https://docs.google.com/presentation/d/1SP91Qj3OsemyplTHPjusSB0JUliD_7Zgw6AT9iFVRo4/edit?slide=id.g37064a72edb_0_0#slide=id.g37064a72edb_0_0" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">Apresentação</div>
          <div class="card-info">Material para lojas de materiais de construção</div>
        </div>
      </a>


      <a href="https://docs.google.com/presentation/d/1cEdNRIEPDLUo4A-UdtoO9ml-K7ga_eVLYTX2oquPBhY/edit?slide=id.p#slide=id.p" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">Sessão Consultoria</div>
          <div class="card-info">Apresentação da Consultoria Acelera</div>
        </div>
      </a>

      <a href="https://forms.clickup.com/36963815/f/1381f7-13553/42YWKRQ1J7FGV3LNCR" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
        <div class="card-title">Formulário ClickUP</div>
        <div class="card-info">Formulário para preenchimento de dados</div>
        </div>
      </a>

          <a href="https://app.clickup.com/36963815/v/l/sh/36963815" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
        <div class="card-title">ClickUP</div>
        <div class="card-info">Painel</div>
        </div>
      </a>

      <a href="https://doc.clickup.com/36963815/p/h/1381f7-8333/02c02111d7b9b94" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">Playbook Closer</div>
          <div class="card-info">Manual do Closer</div>
        </div>
      </a>

      <a href="https://ia.aceleraobra.com.br/conversas" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">IA Acelera</div>
          <div class="card-info">Painal da IA de Atendimento</div>
        </div>
      </a>

     
      <div class="card" style="border-left-color: #3182ce;" onclick="copyToClipboard('financeiro@aceleraobra.com.br')">
        <div class="card-title">Financeiro Acelera Obra</div>
        <div class="card-info">Chave Pix E-mail</div>
      </div>    

      <a href="https://doc.clickup.com/36963815/p/h/1381f7-14853/5c67072a29fdc39" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">Calendário Novembro</div>
          <div class="card-info">Apresentação do Calendário</div>
        </div>
      </a>

            <a href="https://docs.google.com/spreadsheets/d/1-eMzfI3PCEcPC-hVKjlqWCrEhcjiFi7CX-xXkg_Fy2o/edit?gid=528233429#gid=528233429" target="_blank">
        <div class="card" style="border-left-color: #3182ce;">
          <div class="card-title">PGM Acacio</div>
          <div class="card-info">Apresentação do PGM</div>
        </div>
      </a>

<div class="card" style="border-left-color: #3182ce;" onclick="openTranscriptionPopup()">
  <div class="card-title">🎙️ Transcritor de Áudio</div>
  <div class="card-info">Transcreva reuniões ou áudios do sistema</div>
</div>

           
    </div>

    <!-- Relatórios Diários -->
    <div class="kanban-column relatorios">
      <h2>📈 Relatórios Diários</h2>

      <a href="https://docs.google.com/document/u/0/?tgif=d" target="_blank">
        <div class="card" style="border-left-color: #38a169;">
          <div class="card-title">Google Docs</div>
          <div class="card-info">Transcrição de reuniões</div>
        </div>
      </a>

      <a href="https://gemini.google.com/gem/73dea6720d32" target="_blank">
        <div class="card" style="border-left-color: #38a169;">
          <div class="card-title">Assistente Gemini</div>
          <div class="card-info">Resumos, propostas e checklists</div>
        </div>
      </a>

          <a href="https://docs.google.com/spreadsheets/d/1a0-B6UfHhRCrn3dYy6lGvuFeEOh5zV80GMk816sgWhI/edit?gid=1830719344#gid=1830719344" target="_blank">
        <div class="card" style="border-left-color: #38a169;">
          <div class="card-title">Resultados Mensais</div>
          <div class="card-info">Registro de Resultados Mensais Carlos</div>
        </div>
      </a>

       <a href="https://docs.google.com/document/d/1XAfbgVhLLJ-ELWKvIi-shIP7RTx2Eobob5-UmTW_0hc/edit?tab=t.0" target="_blank">
        <div class="card" style="border-left-color: #38a169;">
          <div class="card-title">Acompanhamento</div>
          <div class="card-info">Acompanhamento Follow-Up em tempo real</div>
        </div>
      </a>

      <a href="https://docs.google.com/spreadsheets/d/1aXwXtdTKjf3aJIG_zXbGBZ8Xd2-9INIBZq6YWSZXcpc/edit?gid=0#gid=0" target="_blank">
        <div class="card" style="border-left-color: #38a169;">
          <div class="card-title">Reuniões Feitas</div>
          <div class="card-info">Atualizar Diariamente sem falta</div>
        </div>
      </a>
      
