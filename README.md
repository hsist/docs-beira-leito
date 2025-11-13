<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="author" content="SIGS - Guia">
  <meta name="description" content="Guia de uso do mÃ³dulo Acompanhamento Enfermagem do SIGS (versÃ£o web)">
  <title>SIGS â€” Acompanhamento Enfermagem (Guia RÃ¡pido)</title>
  <style>
    :root{--bg:#f7fafc;--card:#ffffff;--muted:#6b7280;--accent:#0ea5a4}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;line-height:1.5;background:var(--bg);color:#111;margin:0;padding:24px}
    .container{max-width:960px;margin:0 auto}
    header{display:flex;gap:16px;align-items:center}
    header .brand{font-weight:700;font-size:1.25rem}
    .card{background:var(--card);border-radius:12px;padding:20px;margin-top:18px;box-shadow:0 6px 18px rgba(16,24,40,0.06)}
    h1{margin:0;font-size:1.5rem}
    h2{margin-top:0}
    p{margin:0 0 12px}
    .meta{color:var(--muted);font-size:0.95rem}
    nav{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
    a.button{background:var(--accent);color:#fff;padding:8px 12px;border-radius:8px;text-decoration:none;font-weight:600}
    ul{padding-left:1.1rem}
    pre{background:#0f172a;color:#fff;padding:12px;border-radius:8px;overflow:auto}
    footer{color:var(--muted);font-size:0.9rem;margin-top:18px}
    @media (max-width:600px){body{padding:12px}.card{padding:14px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">SIGS â€” Acompanhamento Enfermagem</div>
      <div class="meta">Guia RÃ¡pido (web)</div>
    </header>

    <section class="card" id="intro">
      <h1>Guia RÃ¡pido â€” Acompanhamento Enfermagem</h1>
      <p class="meta">EndereÃ§o de acesso: <strong>http://sigs.hsist.com.br:8081/beira-leito</strong></p>
      <p>Este documento descreve como acessar e utilizar o mÃ³dulo <strong>Acompanhamento Enfermagem</strong> do SIGS via navegador.</p>
    </section>

    <section class="card" id="acesso">
      <h2>1. Acesso e menu</h2>
      <p><strong>Caminho no menu:</strong></p>
      <pre>GestÃ£o Hospitalar â†’ Acompanhamento ClÃ­nico â†’ InternaÃ§Ã£o â†’ Acompanhamento Enfermagem</pre>
      <p class="meta">ObservaÃ§Ã£o: o usuÃ¡rio precisa ter setores configurados para visualizar pacientes.</p>
    </section>

    <section class="card" id="tela1">
      <h2>2. Tela 1 â€” Lista de Pacientes</h2>
      <p>Exibe pacientes em atendimento (sem alta), filtrados pelos setores associados ao usuÃ¡rio.</p>
      <ul>
        <li>ConfiguraÃ§Ã£o de setores do usuÃ¡rio: <em>GestÃ£o Hospitalar â†’ Utilidades â†’ ConfiguraÃ§Ã£o de UsuÃ¡rios â†’ Setores</em></li>
        <li>Atividade do setor: em <em>GestÃ£o Hospitalar â†’ Arquivos e Tabelas â†’ Setores</em> o setor deve conter a atividade <strong>51 Enfermagem</strong>.</li>
      </ul>
      <h3>Pesquisa</h3>
      <p>O campo de pesquisa busca em qualquer coluna exibida â€” nome do paciente, convÃªnio, etc. Digite o termo e os resultados serÃ£o filtrados.</p>
      <p>Para abrir a Tela 2, clique na seta no canto direito da linha do paciente.</p>
    </section>

    <section class="card" id="tela2">
      <h2>3. Tela 2 â€” PrescriÃ§Ãµes de Enfermagem</h2>
      <p>Mostra prescriÃ§Ãµes das Ãºltimas 24 horas que nÃ£o estejam canceladas.</p>
      <ul>
        <li>BotÃ£o <strong>Incluir</strong>: se o setor estiver parametrizado com <em>Preencher responsÃ¡vel ao incluir</em>, o campo <em>ResponsÃ¡vel pela InclusÃ£o</em> serÃ¡ preenchido automaticamente. Caso contrÃ¡rio, apenas data/hora e usuÃ¡rio serÃ£o preenchidos.</li>
        <li>BotÃ£o <strong>Sinais Vitais</strong>: abre a Tela 3.</li>
        <li>BotÃ£o <strong>Voltar</strong>: retorna Ã  Tela 1.</li>
      </ul>
      <p class="meta">NÃ£o utilize os botÃµes do navegador (voltar/avanÃ§ar) para navegar entre telas â€” use os botÃµes da aplicaÃ§Ã£o.</p>
    </section>

    <section class="card" id="tela3">
      <h2>4. Tela 3 â€” Sinais Vitais</h2>
      <p>Permite a inclusÃ£o de sinais vitais. A visualizaÃ§Ã£o e ediÃ§Ã£o dos sinais existentes devem ser feitas no SIGS (desktop) pelo menu indicado abaixo.</p>
      <pre>GestÃ£o Hospitalar â†’ Acompanhamento ClÃ­nico â†’ InternaÃ§Ã£o â†’ Acompanhamento Enfermagem</pre>
      <p>Nenhum campo Ã© obrigatÃ³rio. Ao finalizar escolha:</p>
      <ul>
        <li><strong>Salvar</strong> â€” grava os dados e volta para a Tela 2.</li>
        <li><strong>Cancelar</strong> â€” descarta a inclusÃ£o e volta para a Tela 2.</li>
      </ul>
    </section>

    <section class="card" id="observacoes">
      <h2>5. ObservaÃ§Ãµes e boas prÃ¡ticas</h2>
      <ul>
        <li>Verifique se o usuÃ¡rio tem os setores configurados corretamente antes de abrir o mÃ³dulo.</li>
        <li>Use sempre os botÃµes da aplicaÃ§Ã£o para navegar entre telas.</li>
        <li>Para treinamento, indique ao time que os sinais vitais sÃ£o inseridos aqui, mas gerenciados/visualizados no sistema principal quando necessÃ¡rio.</li>
      </ul>
    </section>



    <footer>
    </footer>
  </div>
</body>
</html>
