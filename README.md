<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Atividade: NR-11, EPI e EPC — SENAI</title>
  <style>
    :root{--accent:#004aad;--muted:#666}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:#f6f8fb; color:#111}
    header{background:white;display:flex;align-items:center;gap:16px;padding:14px 20px;border-bottom:1px solid #e6e9ef}
    header img#logo{height:56px}
    header h1{font-size:18px;margin:0}
    main{max-width:980px;margin:28px auto;padding:20px;background:white;border-radius:10px;box-shadow:0 6px 18px rgba(12,20,40,0.06)}
    .meta{display:flex;gap:12px;align-items:center;margin-bottom:12px}
    label{font-weight:600}

    .section{margin:18px 0}
    .cards{display:grid;grid-template-columns:1fr;gap:12px}
    .card{padding:14px;border:1px solid #e9edf5;border-radius:8px;background:#fff}

    .video-row{display:flex;flex-wrap:wrap;gap:14px}
    .video{flex:1 1 320px}

    .quiz-item{margin:10px 0}
    .options{display:flex;flex-direction:column;gap:8px}

    .btn{display:inline-block;padding:10px 14px;border-radius:8px;background:var(--accent);color:white;text-decoration:none;border:none;cursor:pointer}
    .btn.secondary{background:#e6eefc;color:var(--accent);border:1px solid rgba(0,74,173,0.06)}

    .result{padding:12px;border-radius:8px;margin-top:12px}
    .correct{background:#e6fff3;border:1px solid #7ee6b0;color:#0b6b3e}
    .wrong{background:#fff1f1;border:1px solid #f2a6a6;color:#902020}

    textarea.large{width:100%;height:160px;padding:10px;border-radius:8px;border:1px solid #d7dbe6}

    footer{margin-top:18px;display:flex;gap:8px;align-items:center}

    @media print{header, footer, .no-print{display:none} main{box-shadow:none;border-radius:0;margin:0}}
  </style>
</head>
<body>
  <header>
    <!-- Substitua o src pelo logo oficial do SENAI. -->
    <img id="logo" src="https://cdn.fiemt.ind.br/style/imagens/logo/colorido/senai.png" alt="Logo SENAI"/>
    <div>
      <h1>Atividade: NR-11 — EPI e EPC</h1>
      <div style="color:var(--muted);font-size:13px">Curso EAD — Assistente de Operações em Logística - Professor: Luiz Eduardo Peixoto</div>
    </div>
  </header>

  <main id="activity">
    <div class="meta">
      <label for="studentName">Nome do aluno</label>
      <input id="studentName" type="text" placeholder="Digite seu nome aqui" style="padding:8px;border-radius:8px;border:1px solid #d7dbe6;flex:1" />
      <button class="btn" id="saveJson">Salvar Desempenho (JSON)</button>
    </div>

    <section class="section card">
      <h2>Objetivos de aprendizagem</h2>
      <ul>
        <li>Compreender os princípios da NR-11 (transporte, movimentação e armazenagem).</li>
        <li>Diferenciar EPI (Equipamento de Proteção Individual) e EPC (Equipamento de Proteção Coletiva).</li>
        <li>Aplicar decisões seguras em cenários práticos.</li>
      </ul>
    </section>

    <section class="section card">
      <h2>Situação de Aprendizagem — Cenário</h2>
      <p>Você é responsável pelo setor de recepção de materiais em um centro de distribuição. Ao chegar um pallet com caixas frágeis e pesadas, identifique os riscos e defina quais EPIs e EPCs são necessários para descarregamento e movimentação segura.</p>

      <div style="margin-top:12px">
        <label for="cenarioResp">Descreva em até 250 palavras as ações que tomaria (ex.: sinalização, uso de carrinho, EPI recomendado):</label>
        <textarea id="cenarioResp" class="large" placeholder="Escreva sua resposta aqui..."></textarea>
      </div>
    </section>

    <section class="section card">
      <h2>Vídeos de referência</h2>
      <div class="video-row">
        <!-- Substitua os srcs pelos vídeos relacionados nos documentos anexados. -->
        <div class="video">
          <label>NR-11: Movimentação de cargas — vídeo (exemplo)</label>
          <iframe width="100%" height="200" src="https://www.youtube.com/watch?v=48O64gx8FEI" title="Vídeo exemplo" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="video">
          <label>EPI vs EPC — princípios (exemplo)</label>
          <iframe width="100%" height="200" src="https://www.youtube.com/watch?v=qfbhqPFs4iE" title="Vídeo exemplo 2" frameborder="0" allowfullscreen></iframe>
        </div>
      </div>
      <small style="color:var(--muted)"> Link dos videos: https://www.youtube.com/watch?v=48O64gx8FEI ; https://www.youtube.com/watch?v=qfbhqPFs4iE</small>
    </section>

<aside class="card">
    <h3>Vídeos de referência</h3>
    <ul class="small">
      <li><a href="https://www.youtube.com/watch?v=48O64gx8FEI" target="_blank">NR-11: Movimentação de cargas — vídeo (exemplo)</a></li>
      <li><a href="https://www.youtube.com/watch?v=qfbhqPFs4iE" target="_blank">EPI vs EPC — princípios (exemplo)</a></li>
    </ul>
  </aside>


    <section class="section card">
      <h2>Quiz: NR-11 e Proteções</h2>
      <form id="quizForm">
        <div class="quiz-item">
          <div><strong>1.</strong> A NR-11 trata principalmente de:</div>
          <div class="options">
            <label><input type="radio" name="q1" value="a"> A) Ergonomia no escritório</label>
            <label><input type="radio" name="q1" value="b"> B) Movimentação e transporte de materiais</label>
            <label><input type="radio" name="q1" value="c"> C) Segurança alimentar</label>
          </div>
        </div>

        <div class="quiz-item">
          <div><strong>2.</strong> Qual é a principal diferença entre EPI e EPC?</div>
          <div class="options">
            <label><input type="radio" name="q2" value="a"> A) EPI protege o coletivo; EPC protege individualmente</label>
            <label><input type="radio" name="q2" value="b"> B) EPI protege o indivíduo; EPC protege o coletivo</label>
            <label><input type="radio" name="q2" value="c"> C) Não existe diferença</label>
          </div>
        </div>

        <div class="quiz-item">
          <div><strong>3.</strong> Ao movimentar uma carga muito pesada, qual equipamento é mais indicado:</div>
          <div class="options">
            <label><input type="radio" name="q3" value="a"> A) Uso de luvas e transporte manual</label>
            <label><input type="radio" name="q3" value="b"> B) Empilhadeira ou carrinho (mecanização) — seguir NR-11</label>
            <label><input type="radio" name="q3" value="c"> C) Nenhuma medida necessária</label>
          </div>
        </div>

        <div class="quiz-item">
          <div><strong>4.</strong> Marque quais são exemplos de EPC:</div>
          <div class="options">
            <label><input type="checkbox" name="q4" value="a"> A) Guardas de proteção em máquinas</label>
            <label><input type="checkbox" name="q4" value="b"> B) Sinalização de área</label>
            <label><input type="checkbox" name="q4" value="c"> C) Luvas descartáveis</label>
          </div>
        </div>

        <div class="quiz-item">
          <div><strong>5.</strong> Qual EPI seria obrigatório para manuseio de cargas cortantes?</div>
          <div class="options">
            <label><input type="radio" name="q5" value="a"> A) Óculos de proteção e luvas resistentes</label>
            <label><input type="radio" name="q5" value="b"> B) Protetor auricular apenas</label>
            <label><input type="radio" name="q5" value="c"> C) Máscara respiratória apenas</label>
          </div>
        </div>

        <div style="margin-top:12px;display:flex;gap:8px;align-items:center">
          <button type="button" class="btn" id="gradeBtn">Corrigir quiz</button>
          <div id="scoreBox" style="font-weight:700"></div>
        </div>
      </form>

      <div id="feedback" style="margin-top:12px"></div>
    </section>

    <section class="section card">
      <h2>Autoavaliação e feedback do instrutor</h2>
      <label>Autoavaliação (0-10)</label>
      <input id="selfScore" type="number" min="0" max="10" step="0.5" style="width:96px;padding:8px;border-radius:8px;border:1px solid #d7dbe6" />

      <div style="margin-top:12px">
        <label>Comentário do aluno (opcional)</label>
        <textarea id="studentComment" class="large" placeholder="Escreva aqui sobre o seu progresso no curso..."></textarea>
      </div>
    </section>

    <footer class="no-print">
      <button class="btn" id="exportPdf">Exportar atividade como PDF</button>
      <button class="btn secondary" id="resetBtn">Limpar respostas</button>
    </footer>

  </main>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.9.3/html2pdf.bundle.min.js"></script>
  <script>
    // Respostas gabarito
    const gabarito = {
      q1: 'b',
      q2: 'b',
      q3: 'b',
      q4: ['a','b'], // a e b são EPCs; c é EPI
      q5: 'a'
    };

    function getFormAnswers(){
      const form = document.getElementById('quizForm');
      const data = {};
      const fd = new FormData(form);
      // radio single values
      ['q1','q2','q3','q5'].forEach(k => { data[k] = fd.get(k); });
      // q4 checkboxes
      data.q4 = fd.getAll('q4');
      return data;
    }

    function grade(){
      const ans = getFormAnswers();
      let score = 0; let max = 5; let messages = [];

      // q1..q3,q5
      ['q1','q2','q3','q5'].forEach(q => {
        if(ans[q] === gabarito[q]){ score += 1; messages.push({q,ok:true}); }
        else messages.push({q,ok:false});
      });

      // q4 - set equality (a and b must be present) - partial credit if only one correct
      const got = ans.q4 || [];
      const need = gabarito.q4;
      const correctCount = need.filter(n => got.includes(n)).length;
      if(correctCount === need.length) score += 1;
      else if(correctCount === 1) score += 0.5;
      else score += 0;

      // show score
      const box = document.getElementById('scoreBox');
      box.textContent = `Pontuação: ${score} / ${max}`;

      // feedback text
      const fb = document.getElementById('feedback');
      fb.innerHTML = '';
      messages.forEach(m =>{
        const div = document.createElement('div');
        div.className = m.ok ? 'result correct' : 'result wrong';
        div.textContent = (m.ok? 'Correto: ':'Incorreto: ') + getQuestionText(m.q);
        fb.appendChild(div);
      });

      // highlight suggestions
      const suggestion = document.createElement('div');
      suggestion.style.marginTop = '10px';
      suggestion.innerHTML = `<strong>Sugestão:</strong> Revise a NR-11 para abordagem de equipamentos de movimentação e compare EPI vs EPC. Para mais detalhes, consulte os vídeos de referência.`;
      fb.appendChild(suggestion);

      // persist simple performance object in memory (for export)
      window.__lastPerformance = {
        student: document.getElementById('studentName').value || 'Aluno sem nome',
        timestamp: new Date().toISOString(),
        score: score,
        max: max,
        quizAnswers: ans,
        scenarioText: document.getElementById('cenarioResp').value,
        selfScore: document.getElementById('selfScore').value,
        studentComment: document.getElementById('studentComment').value
      };

      return window.__lastPerformance;
    }

    function getQuestionText(q){
      const map = {
        q1: 'NR-11 trata de... (movimentação e transporte).',
        q2: 'Diferença EPI / EPC.',
        q3: 'Equipamento para cargas muito pesadas (mecanização).',
        q4: 'Exemplos de EPC.',
        q5: 'EPI para cargas cortantes.'
      };
      return map[q] || q;
    }

    document.getElementById('gradeBtn').addEventListener('click', () => {
      grade();
      // small visual cue
      document.getElementById('gradeBtn').textContent = 'Corrigido ✓';
      setTimeout(()=> document.getElementById('gradeBtn').textContent = 'Corrigir quiz', 2000);
    });

    document.getElementById('resetBtn').addEventListener('click', ()=>{
      if(confirm('Deseja realmente limpar todas as respostas?')){
        document.getElementById('quizForm').reset();
        document.getElementById('studentName').value='';
        document.getElementById('cenarioResp').value='';
        document.getElementById('studentComment').value='';
        document.getElementById('selfScore').value='';
        document.getElementById('feedback').innerHTML='';
        document.getElementById('scoreBox').textContent='';
        window.__lastPerformance = null;
      }
    });

    // Export to PDF using html2pdf
    document.getElementById('exportPdf').addEventListener('click', async () => {
      // ensure grading run so score appears in PDF
      grade();
      const element = document.getElementById('activity');
      const opt = {
        margin:       0.5,
        filename:     (document.getElementById('studentName').value || 'atividade') + '.pdf',
        image:        { type: 'jpeg', quality: 0.98 },
        html2canvas:  { scale: 2 },
        jsPDF:        { unit: 'in', format: 'a4', orientation: 'portrait' }
      };
      html2pdf().set(opt).from(element).save();
    });

    // Save performance JSON
    document.getElementById('saveJson').addEventListener('click', ()=>{
      const perf = window.__lastPerformance || grade();
      const dataStr = JSON.stringify(perf, null, 2);
      const blob = new Blob([dataStr], {type: 'application/json'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a');
      a.href = url;
      a.download = (perf.student || 'aluno') + '_desempenho.json';
      a.click();
      URL.revokeObjectURL(url);
    });

    // Accessibility: allow Enter to submit name
    document.getElementById('studentName').addEventListener('keydown', (e)=>{ if(e.key === 'Enter'){ e.preventDefault(); document.getElementById('gradeBtn').click(); }});

    // prefill with sample text if wanted (remove in production)
    // document.getElementById('cenarioResp').value = 'Exemplo: sinalizar área, usar empilhadeira, equipe treinada e EPIs...';
  </script>
</body>
</html>
