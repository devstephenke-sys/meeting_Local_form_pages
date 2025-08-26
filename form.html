<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Annual Meeting — RSVP & Feedback</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f4f7fb;
      --card:#ffffff;
      --accent:#0b66ff;
      --muted:#6b7280;
      --glass: rgba(255,255,255,0.6);
      --radius:14px;
      --shadow: 0 8px 30px rgba(11,102,255,0.06), 0 1px 3px rgba(16,24,40,0.04);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;color:#0f172a;background:linear-gradient(180deg,var(--bg),#e9eef8);}
    .wrap{max-width:980px;margin:32px auto;padding:28px}

    header{display:flex;align-items:center;gap:16px;margin-bottom:20px}
    .logo{width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#2dd4bf);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:22px;box-shadow:var(--shadow)}
    h1{font-size:20px;margin:0}
    p.lead{margin:4px 0 0;color:var(--muted);font-size:13px}

    .grid{display:grid;grid-template-columns:1fr 420px;gap:26px}

    .card{background:var(--card);border-radius:var(--radius);padding:20px;box-shadow:var(--shadow)}

    form .row{display:flex;gap:12px}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px}
    input[type=text], input[type=email], select, textarea{width:100%;padding:12px 14px;border-radius:10px;border:1px solid #e6eef8;background:linear-gradient(180deg,#fff,#fbfdff);outline:none;font-size:14px}
    input:focus, select:focus, textarea:focus{box-shadow:0 6px 18px rgba(11,102,255,0.08);border-color:var(--accent)}
    textarea{min-height:110px;resize:vertical}

    .actions{display:flex;gap:10px;align-items:center;margin-top:12px}
    .btn{background:var(--accent);color:#fff;padding:10px 14px;border:none;border-radius:10px;cursor:pointer;font-weight:600}
    .btn.ghost{background:transparent;color:var(--accent);border:1px solid rgba(11,102,255,0.12)}
    .small{font-size:13px;padding:8px 10px}

    .muted{color:var(--muted);font-size:13px}
    .hint{font-size:12px;color:#9aa4bd}

    /* responses panel */
    .responses{display:flex;flex-direction:column;gap:12px}
    .table-wrap{overflow:auto}
    table{width:100%;border-collapse:collapse;font-size:14px}
    th,td{padding:10px;border-bottom:1px solid #eef4ff;text-align:left}
    th{background:linear-gradient(180deg,#fbfdff,#f6fbff);position:sticky;top:0}

    .controls{display:flex;gap:8px;align-items:center}
    .search{flex:1}
    .info{font-size:13px;color:var(--muted)}

    footer{margin-top:18px;font-size:13px;color:var(--muted)}

    /* responsive */
    @media (max-width:980px){.grid{grid-template-columns:1fr;}.wrap{padding:16px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">AM</div>
      <div>
        <h1>Annual Meeting — RSVP & Feedback</h1>
        <p class="lead">A clean, quick form for attendees. Submissions are stored in your browser (localStorage) — you can download them as CSV any time.</p>
      </div>
    </header>

    <div class="grid">
      <!-- left: form -->
      <section class="card">
        <h2 style="margin:0 0 10px">RSVP / Feedback</h2>
        <form id="meetingForm">
          <div style="display:flex;gap:12px;flex-wrap:wrap">
            <div style="flex:1;min-width:160px">
              <label for="name">Full name</label>
              <input id="name" type="text" required placeholder="Jane Doe" />
            </div>
            <div style="flex:1;min-width:160px">
              <label for="email">Email</label>
              <input id="email" type="email" required placeholder="jane@example.com" />
            </div>
          </div>

          <div style="margin-top:12px">
            <label for="org">Organization / Dept <span class="hint">(optional)</span></label>
            <input id="org" type="text" placeholder="Finance, Operations..." />
          </div>

          <div style="margin-top:12px">
            <label for="attendance">Will you attend?</label>
            <select id="attendance" required>
              <option value="">-- Select --</option>
              <option>Yes</option>
              <option>No</option>
              <option>Maybe</option>
            </select>
          </div>

          <div style="margin-top:12px">
            <label for="role">Participation Type</label>
            <select id="role">
              <option>Attendee</option>
              <option>Speaker</option>
              <option>Volunteer</option>
              <option>Exhibitor</option>
            </select>
          </div>

          <div style="margin-top:12px">
            <label for="feedback">Feedback / Notes</label>
            <textarea id="feedback" placeholder="Any topics you'd like covered? Accessibility notes? Dietary needs?"></textarea>
          </div>

          <div class="actions">
            <button class="btn" type="submit">Submit Response</button>
            <button type="button" class="btn ghost small" onclick="fillSample()">Quick sample</button>
            <div style="flex:1"></div>
            <div class="muted">Responses saved locally — refresh safe.</div>
          </div>
        </form>

        <div style="margin-top:14px" class="muted">Tip: Share this page link or QR code with attendees. No server required.</div>
      </section>

      <!-- right: responses -->
      <aside>
        <div class="card">
          <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;margin-bottom:10px">
            <div>
              <strong>Responses</strong>
              <div class="info" id="count">0 submissions</div>
            </div>
            <div class="controls">
              <input id="search" class="search" placeholder="Search name, email, org..." />
              <button class="btn small" onclick="downloadCSV()">Download CSV</button>
              <button class="btn ghost small" onclick="clearAll()">Clear</button>
            </div>
          </div>

          <div class="table-wrap" id="tableWrap">
            <table id="responsesTable" aria-live="polite">
              <thead>
                <tr><th>Name</th><th>Email</th><th>Org</th><th>Attend</th><th>Role</th><th>Notes</th></tr>
              </thead>
              <tbody></tbody>
            </table>
          </div>
        </div>

        <div style="height:12px"></div>
        <div class="card" style="text-align:center">
          <div style="font-size:13px;color:var(--muted)">Share & Host</div>
          <p style="margin:6px 0 12px;font-size:14px">To make this available online, host the single HTML file on Netlify or GitHub Pages.</p>
          <div style="display:flex;gap:8px;justify-content:center">
            <a href="https://app.netlify.com/drop" target="_blank" rel="noopener" class="btn small">Netlify (Drag & Drop)</a>
            <a href="https://pages.github.com/" target="_blank" rel="noopener" class="btn ghost small">GitHub Pages</a>
          </div>
        </div>
      </aside>
    </div>

    <footer>
      <div class="muted">Built for fast, professional RSVPs. No signup required. Data stays with whoever hosts the page.</div>
    </footer>
  </div>

  <script>
    // --- local storage keys & helpers
    const STORAGE_KEY = 'annual_meeting_responses_v1';

    function loadResponses(){
      try{const raw = localStorage.getItem(STORAGE_KEY); return raw? JSON.parse(raw):[] }catch(e){return[]} }
    function saveResponses(arr){localStorage.setItem(STORAGE_KEY, JSON.stringify(arr))}

    // --- app state
    let responses = loadResponses();

    // --- elements
    const form = document.getElementById('meetingForm');
    const tbody = document.querySelector('#responsesTable tbody');
    const countEl = document.getElementById('count');
    const searchInput = document.getElementById('search');

    function renderRows(filter){
      tbody.innerHTML = '';
      const list = (filter? responses.filter(r=>matchFilter(r, filter)) : responses);
      for(const r of list){
        const tr = document.createElement('tr');
        tr.innerHTML = `<td>${escapeHtml(r.name)}</td><td>${escapeHtml(r.email)}</td><td>${escapeHtml(r.org||'—')}</td><td>${escapeHtml(r.attendance)}</td><td>${escapeHtml(r.role||'—')}</td><td>${escapeHtml(r.feedback||'')}</td>`;
        tbody.appendChild(tr);
      }
      countEl.textContent = `${responses.length} submission${responses.length!==1?'s':''}`;
    }

    function matchFilter(r, q){
      q = q.toLowerCase();
      return (r.name||'').toLowerCase().includes(q) || (r.email||'').toLowerCase().includes(q) || (r.org||'').toLowerCase().includes(q) || (r.attendance||'').toLowerCase().includes(q) || (r.role||'').toLowerCase().includes(q);
    }

    function escapeHtml(s){ if(!s) return ''; return String(s).replaceAll('&','&amp;').replaceAll('<','&lt;').replaceAll('>','&gt;').replaceAll('\"','&quot;') }

    // --- events
    form.addEventListener('submit', e=>{
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const email = document.getElementById('email').value.trim();
      const org = document.getElementById('org').value.trim();
      const attendance = document.getElementById('attendance').value;
      const role = document.getElementById('role').value;
      const feedback = document.getElementById('feedback').value.trim();

      if(!name || !email || !attendance){
        alert('Please fill in required fields: name, email, and attendance.');
        return;
      }

      const entry = { id: Date.now(), name, email, org, attendance, role, feedback };
      responses.unshift(entry); // newest first
      saveResponses(responses);
      renderRows(searchInput.value.trim());
      form.reset();
    })

    searchInput.addEventListener('input', ()=>renderRows(searchInput.value.trim()));

    // --- sample filler
    function fillSample(){
      document.getElementById('name').value = 'Test Attendee';
      document.getElementById('email').value = 'test@example.com';
      document.getElementById('org').value = 'Operations';
      document.getElementById('attendance').value = 'Yes';
      document.getElementById('role').value = 'Attendee';
      document.getElementById('feedback').value = 'Looking forward to the event.';
    }

    // --- CSV download
    function downloadCSV(){
      if(responses.length===0){ alert('No responses to download.'); return }
      const headers = ['Name','Email','Organization','Attendance','Role','Feedback','SubmittedAt'];
      const lines = [headers.join(',')];
      for(const r of responses){
        const row = [r.name, r.email, r.org||'', r.attendance, r.role||'', r.feedback||'', new Date(r.id).toISOString()];
        lines.push(row.map(cell=>`"${String(cell).replaceAll('"','""')}"`).join(','));
      }
      const csv = lines.join('\n');
      const blob = new Blob([csv], {type:'text/csv;charset=utf-8;'});
      const url = URL.createObjectURL(blob);
      const a = document.createElement('a'); a.href = url; a.download = 'meeting_responses.csv'; document.body.appendChild(a); a.click(); a.remove(); URL.revokeObjectURL(url);
    }

    // --- clear all
    function clearAll(){ if(!confirm('Clear all responses? This cannot be undone.')) return; responses = []; saveResponses(responses); renderRows(); }

    // --- init render
    renderRows();

    // expose some functions to window for HTML buttons
    window.downloadCSV = downloadCSV;
    window.clearAll = clearAll;
    window.fillSample = fillSample;
  </script>
</body>
</html>
