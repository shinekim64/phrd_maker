<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PHRD 만들기 (Plus Human Re-design Document)</title>
  <style>
    :root{
      --bg:#0b0f14;
      --card:#111826;
      --muted:#93a4b8;
      --text:#e8eef6;
      --line:#263246;
      --accent:#66e3a1;
      --accent2:#7aa7ff;
      --danger:#ff6b6b;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, "Noto Sans KR", Arial, sans-serif;
      background: linear-gradient(180deg, #0b0f14 0%, #0b0f14 30%, #0a1220 100%);
      color:var(--text);
    }
    header{
      position:sticky; top:0; z-index:10;
      background: rgba(11,15,20,.85);
      backdrop-filter: blur(10px);
      border-bottom:1px solid var(--line);
    }
    .wrap{max-width:980px; margin:0 auto; padding:18px 16px}
    .title{
      display:flex; gap:12px; align-items:flex-start; justify-content:space-between;
      flex-wrap:wrap;
    }
    h1{margin:0; font-size:20px; letter-spacing:-.2px}
    .sub{margin:6px 0 0; color:var(--muted); font-size:13px; line-height:1.4}
    .actions{display:flex; gap:8px; flex-wrap:wrap; align-items:center}
    button, .btn{
      border:1px solid var(--line);
      background:#0f1725;
      color:var(--text);
      padding:10px 12px;
      border-radius:12px;
      cursor:pointer;
      font-size:13px;
    }
    button:hover{border-color:#3a4a66}
    button.primary{background:linear-gradient(135deg, #1a3a2b, #0f2a20); border-color:#275b44}
    button.primary:hover{border-color:#3c8a67}
    button.ghost{background:transparent}
    button.danger{background:rgba(255,107,107,.08); border-color:rgba(255,107,107,.35); color:#ffd3d3}
    button.danger:hover{border-color:rgba(255,107,107,.6)}
    main{padding:18px 0 36px}
    .grid{
      display:grid;
      grid-template-columns: 1fr;
      gap:14px;
    }
    @media (min-width: 960px){
      .grid{grid-template-columns: 1.1fr .9fr}
      .sticky{position:sticky; top:84px}
    }
    .card{
      background:rgba(17,24,38,.75);
      border:1px solid var(--line);
      border-radius:16px;
      padding:14px;
      box-shadow: 0 10px 30px rgba(0,0,0,.25);
    }
    .card h2{
      margin:0 0 10px;
      font-size:15px;
      letter-spacing:-.2px;
      display:flex; gap:10px; align-items:center;
    }
    .badge{
      font-size:11px;
      padding:3px 8px;
      border-radius:999px;
      border:1px solid var(--line);
      color:var(--muted);
      background:rgba(0,0,0,.1);
    }
    label{
      display:block;
      margin:10px 0 6px;
      font-size:12px;
      color:var(--muted);
    }
    input[type="text"], textarea{
      width:100%;
      padding:10px 12px;
      border-radius:12px;
      border:1px solid var(--line);
      background:#0d1421;
      color:var(--text);
      outline:none;
    }
    textarea{min-height:90px; resize:vertical; line-height:1.45}
    input[type="text"]:focus, textarea:focus{border-color:#3a4a66}
    .row{
      display:grid;
      grid-template-columns: 1fr;
      gap:10px;
    }
    @media (min-width: 720px){
      .row.two{grid-template-columns: 1fr 1fr}
      .row.three{grid-template-columns: 1fr 1fr 1fr}
    }
    .hint{color:var(--muted); font-size:12px; margin-top:8px; line-height:1.5}
    .mini{font-size:11px; color:var(--muted)}
    .toast{
      position:fixed;
      left:50%; transform:translateX(-50%);
      bottom:18px;
      background:#0f1725;
      border:1px solid var(--line);
      color:var(--text);
      padding:10px 12px;
      border-radius:12px;
      box-shadow: 0 10px 30px rgba(0,0,0,.35);
      opacity:0; pointer-events:none;
      transition: opacity .2s ease, transform .2s ease;
      max-width: min(560px, calc(100% - 24px));
      font-size:13px;
    }
    .toast.show{opacity:1; pointer-events:auto; transform:translateX(-50%) translateY(-4px)}
    /* Preview / Print */
    .preview{
      background:#ffffff;
      color:#0b0f14;
      border-radius:16px;
      border:1px solid rgba(0,0,0,.12);
      overflow:hidden;
    }
    .preview .page{
      padding:22px 22px 26px;
      font-family: "Noto Sans KR", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
    }
    .preview h3{
      margin:0;
      font-size:18px;
      letter-spacing:-.3px;
    }
    .preview .p-sub{margin:6px 0 0; color:#334155; font-size:12.5px}
    .hr{height:1px; background:rgba(0,0,0,.12); margin:14px 0 16px}
    .block{margin:0 0 14px}
    .block .b-title{
      display:flex; gap:10px; align-items:center;
      font-weight:700; font-size:13px;
      margin:0 0 6px;
    }
    .block .b-title span{
      background:#eef2ff;
      border:1px solid #c7d2fe;
      padding:2px 8px;
      border-radius:999px;
      font-size:11px;
      font-weight:700;
      color:#3730a3;
    }
    .block .b-body{
      white-space:pre-wrap;
      font-size:12.5px;
      line-height:1.5;
      color:#0b0f14;
      padding:10px 12px;
      border:1px solid rgba(0,0,0,.12);
      border-radius:12px;
      background:#f8fafc;
    }
    .block .empty{color:#64748b}
    .foot{
      margin-top:14px;
      font-size:11.5px;
      color:#334155;
      border-top:1px dashed rgba(0,0,0,.22);
      padding-top:10px;
    }
    @media print{
      body{background:#fff}
      header, .no-print{display:none !important}
      main{padding:0}
      .wrap{max-width:none; padding:0}
      .grid{display:block}
      .card{border:none; box-shadow:none; padding:0}
      .preview{border:none; border-radius:0}
      .preview .page{padding:18mm}
    }
    a.link{color:var(--accent2); text-decoration:none}
    a.link:hover{text-decoration:underline}
    .small-actions{display:flex; gap:8px; flex-wrap:wrap; margin-top:10px}
  </style>
</head>
<body>
<header>
  <div class="wrap title">
    <div>
      <h1>PHRD 만들기 (Plus Human Re-design Document)</h1>
      <p class="sub">양식대로 입력하면, 자동으로 1장짜리 PHRD가 완성됩니다. 데이터는 기본적으로 <b>내 브라우저(localStorage)</b>에 저장돼요.</p>
    </div>
    <div class="actions no-print">
      <button class="primary" id="btnSave">저장</button>
      <button id="btnShare">공유 링크 복사</button>
      <button id="btnDownload">HTML로 다운로드</button>
      <button id="btnPrint">인쇄 / PDF 저장</button>
      <button class="danger" id="btnReset">초기화</button>
    </div>
  </div>
</header>

<main>
  <div class="wrap grid">
    <!-- Form -->
    <section class="card no-print">
      <h2>입력하기 <span class="badge">PHRD 7문항</span></h2>

      <div class="row two">
        <div>
          <label for="name">작성자 이름(선택)</label>
          <input type="text" id="name" placeholder="예: Shine" />
        </div>
        <div>
          <label for="date">작성 날짜(선택)</label>
          <input type="text" id="date" placeholder="예: 2026-02-17" />
        </div>
      </div>

      <label for="q1">① 내가 포기했던 것</label>
      <textarea id="q1" placeholder="내가 진짜 하고 싶었지만 현실 때문에 내려놓은 것은…"></textarea>

      <label for="q2">② 노멀 휴먼 시절의 나</label>
      <textarea id="q2" placeholder="그때 나는 이렇게 생각했다. (예: 시간이 없어서, 혼자라서, 준비가 안 돼서…)"></textarea>

      <label for="q3">③ 플러스 휴먼 전환 질문</label>
      <textarea id="q3" placeholder="이걸 내가 혼자 하지 않는다면, 어떻게 다시 설계할 수 있을까?"></textarea>

      <div class="row two">
        <div>
          <label for="q4a">④ 듀얼 브레인 설계 - 내가 할 역할</label>
          <textarea id="q4a" placeholder="예: 최종 판단, 방향 결정, 고객 이해…"></textarea>
        </div>
        <div>
          <label for="q4b">④ 듀얼 브레인 설계 - AI에게 맡길 역할</label>
          <textarea id="q4b" placeholder="예: 초안 작성, 자료 조사, 체크리스트 만들기…"></textarea>
        </div>
      </div>

      <label for="q5">⑤ 멀티핸즈 설계 (1인 회사 만들기)</label>
      <textarea id="q5" placeholder="예: 기획팀 / 콘텐츠팀 / 실행팀 / 운영팀 / 정리팀 등&#10;(1) ...&#10;(2) ...&#10;(3) ..."></textarea>

      <label for="q6">⑥ 로켓 풋(무대 이동)</label>
      <textarea id="q6" placeholder="이 일을 지금보다 다른 무대로 옮긴다면…&#10;공간 / 역할 / 방식 / 가장 먼저 바꿀 것은?"></textarea>

      <label for="q7">⑦ 7일 실험 선언</label>
      <textarea id="q7" placeholder="7일 안에 실패해도 괜찮은 가장 작은 실험은…"></textarea>

      <p class="hint">
        ✅ 팁: “완벽한 계획”보다 “바로 해볼 수 있는 최소 실험”에 초점을 맞춰 작성해보세요.<br/>
        ✅ 공유 링크는 입력 내용을 URL에 담아 복사합니다. 링크를 열면 자동으로 입력값이 채워져요.
      </p>

      <div class="small-actions">
        <button id="btnFillDemo" class="ghost">예시 채우기</button>
        <button id="btnClearLocal" class="ghost">이 기기 저장만 삭제</button>
        <span class="mini">※ 공유 링크로 채운 내용은 자동 저장되지 않습니다. 저장 버튼을 눌러주세요.</span>
      </div>
    </section>

    <!-- Preview -->
    <section class="card sticky">
      <h2>미리보기 <span class="badge">1장 출력</span></h2>
      <div class="preview" id="preview">
        <div class="page" id="page">
          <div style="display:flex; justify-content:space-between; gap:10px; flex-wrap:wrap">
            <div>
              <h3>PHRD (Plus Human Re-design Document)</h3>
              <p class="p-sub">노멀 휴먼에서 플러스 휴먼으로 전환하기 위한 1장 설계 문서</p>
            </div>
            <div style="text-align:right; min-width:180px">
              <div style="font-size:12px; color:#334155"><b>작성자</b>: <span id="p_name" class="empty">-</span></div>
              <div style="font-size:12px; color:#334155"><b>날짜</b>: <span id="p_date" class="empty">-</span></div>
            </div>
          </div>

          <div class="hr"></div>

          <div class="block">
            <div class="b-title"><span>①</span> 내가 포기했던 것</div>
            <div class="b-body" id="p1"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="block">
            <div class="b-title"><span>②</span> 노멀 휴먼 시절의 나</div>
            <div class="b-body" id="p2"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="block">
            <div class="b-title"><span>③</span> 플러스 휴먼 전환 질문</div>
            <div class="b-body" id="p3"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="block">
            <div class="b-title"><span>④</span> 듀얼 브레인 설계</div>
            <div class="b-body" id="p4"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="block">
            <div class="b-title"><span>⑤</span> 멀티핸즈 설계 (1인 회사)</div>
            <div class="b-body" id="p5"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="block">
            <div class="b-title"><span>⑥</span> 로켓 풋 (무대 이동)</div>
            <div class="b-body" id="p6"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="block">
            <div class="b-title"><span>⑦</span> 7일 실험 선언</div>
            <div class="b-body" id="p7"><span class="empty">아직 입력되지 않았어요.</span></div>
          </div>

          <div class="foot">
            <b>작성 팁</b>: ‘완벽한 계획’보다 ‘바로 해볼 수 있는 최소 실험’에 초점을 맞춰 작성해보세요.
          </div>
        </div>
      </div>

      <p class="hint no-print">
        📌 이 페이지는 단일 HTML 파일입니다. 그대로 업로드/호스팅하면 “일반 유저가 접속해서 작성 → 저장 → PDF로 출력”까지 가능합니다.<br/>
        사이트에 올릴 때는 HTTPS 환경을 권장합니다.
      </p>
    </section>
  </div>
</main>

<div class="toast" id="toast"></div>

<script>
  // ---------- Utilities
  const $ = (id) => document.getElementById(id);
  const toast = (msg) => {
    const t = $("toast");
    t.textContent = msg;
    t.classList.add("show");
    clearTimeout(window.__toastTimer);
    window.__toastTimer = setTimeout(()=>t.classList.remove("show"), 2200);
  };

  const fields = ["name","date","q1","q2","q3","q4a","q4b","q5","q6","q7"];

  function getState(){
    const s = {};
    for (const f of fields) s[f] = ($(f).value || "").trim();
    return s;
  }

  function setState(s){
    for (const f of fields){
      if (typeof s[f] === "string") $(f).value = s[f];
    }
    render();
  }

  function render(){
    const s = getState();
    $("p_name").textContent = s.name || "-";
    $("p_name").className = s.name ? "" : "empty";
    $("p_date").textContent = s.date || "-";
    $("p_date").className = s.date ? "" : "empty";

    const setPreview = (id, value) => {
      const el = $(id);
      if (value){
        el.textContent = value;
      }else{
        el.innerHTML = '<span class="empty">아직 입력되지 않았어요.</span>';
      }
    };

    setPreview("p1", s.q1);
    setPreview("p2", s.q2);
    setPreview("p3", s.q3);

    const dual = [
      s.q4a ? "내 역할: " + s.q4a : "",
      s.q4b ? "AI 역할: " + s.q4b : ""
    ].filter(Boolean).join("\n\n");

    setPreview("p4", dual);
    setPreview("p5", s.q5);
    setPreview("p6", s.q6);
    setPreview("p7", s.q7);
  }

  // ---------- Local Save/Load
  const LS_KEY = "phrdsheet_v1";

  function saveLocal(){
    localStorage.setItem(LS_KEY, JSON.stringify(getState()));
    toast("저장 완료! (이 브라우저에 저장됨)");
  }

  function loadLocal(){
    try{
      const raw = localStorage.getItem(LS_KEY);
      if (!raw) return;
      const s = JSON.parse(raw);
      setState(s);
      toast("이전에 저장한 내용을 불러왔어요.");
    }catch(e){}
  }

  function clearLocal(){
    localStorage.removeItem(LS_KEY);
    toast("이 기기 저장 내용을 삭제했어요.");
  }

  // ---------- Share Link (URL-safe)
  // We store data as JSON -> UTF-8 -> base64url
  function base64UrlEncode(str){
    const bytes = new TextEncoder().encode(str);
    let bin = "";
    bytes.forEach(b => bin += String.fromCharCode(b));
    const b64 = btoa(bin);
    return b64.replace(/\+/g,'-').replace(/\//g,'_').replace(/=+$/,'');
  }
  function base64UrlDecode(b64url){
    const b64 = b64url.replace(/-/g,'+').replace(/_/g,'/')
      + "===".slice((b64url.length + 3) % 4);
    const bin = atob(b64);
    const bytes = Uint8Array.from(bin, c => c.charCodeAt(0));
    return new TextDecoder().decode(bytes);
  }

  function makeShareLink(){
    const s = getState();
    // keep it lean: only include filled fields
    const slim = {};
    for (const f of fields){
      if (s[f]) slim[f] = s[f];
    }
    const payload = base64UrlEncode(JSON.stringify(slim));
    const url = new URL(window.location.href);
    url.searchParams.set("p", payload);
    return url.toString();
  }

  function tryLoadFromUrl(){
    const url = new URL(window.location.href);
    const p = url.searchParams.get("p");
    if (!p) return;
    try{
      const json = base64UrlDecode(p);
      const s = JSON.parse(json);
      setState(s);
      toast("공유 링크에서 내용을 불러왔어요. (저장하려면 '저장'을 눌러주세요)");
    }catch(e){
      toast("공유 링크를 읽는 데 실패했어요.");
    }
  }

  async function copyToClipboard(text){
    try{
      await navigator.clipboard.writeText(text);
      toast("링크를 복사했어요!");
    }catch(e){
      // fallback
      const ta = document.createElement("textarea");
      ta.value = text;
      document.body.appendChild(ta);
      ta.select();
      document.execCommand("copy");
      document.body.removeChild(ta);
      toast("링크를 복사했어요!");
    }
  }

  // ---------- Download as HTML (current state embedded as URL param)
  function downloadHtml(){
    const link = makeShareLink();
    const url = new URL(link);
    // Create a file that, when opened locally, also loads the same "p" payload
    const htmlText = document.documentElement.outerHTML;
    const blob = new Blob([htmlText], {type:"text/html;charset=utf-8"});
    const a = document.createElement("a");
    a.href = URL.createObjectURL(blob);
    a.download = "PHRD_만들기.html";
    a.click();
    URL.revokeObjectURL(a.href);
    toast("HTML 파일을 다운로드했어요.");
  }

  // ---------- Events
  fields.forEach(f => $(f).addEventListener("input", render));

  $("btnSave").addEventListener("click", saveLocal);
  $("btnPrint").addEventListener("click", () => window.print());
  $("btnReset").addEventListener("click", () => {
    if (!confirm("정말 초기화할까요? (입력 내용이 모두 지워집니다)")) return;
    for (const f of fields) $(f).value = "";
    render();
    toast("초기화했어요.");
  });
  $("btnShare").addEventListener("click", async () => {
    const link = makeShareLink();
    await copyToClipboard(link);
  });
  $("btnDownload").addEventListener("click", downloadHtml);
  $("btnClearLocal").addEventListener("click", clearLocal);

  $("btnFillDemo").addEventListener("click", () => {
    setState({
      name: "Shine",
      date: new Date().toISOString().slice(0,10),
      q1: "블로그로 ‘내 경험을 정리해서 누군가에게 도움이 되는 글’을 꾸준히 쓰는 것.",
      q2: "나는 시간이 없고, 글을 잘 못 쓰고, 뭘 써야 할지도 모르겠다고 생각했다.",
      q3: "AI와 같이 한다면, 매일 20분씩 ‘초안 → 다듬기 → 발행’으로 흐름을 만들 수 있을까?",
      q4a: "주제 선택, 내 경험/관점 넣기, 최종 문장 톤 조정, 발행 결정",
      q4b: "목차 제안, 초안 작성, 표현 다듬기, 참고자료 링크 후보 찾기, 체크리스트 제공",
      q5: "기획팀(아이디어/키워드) / 콘텐츠팀(초안/편집) / 정리팀(요약/FAQ) / 운영팀(발행/태그)",
      q6: "공간: 집 책상 → ‘블로그 작업 코너’ 고정\n역할: 혼자 고민 → AI와 역할 분담\n방식: 큰 목표 → 7일 실험 단위\n가장 먼저 바꿀 것: ‘완성 후 시작’이 아니라 ‘초안부터 시작’",
      q7: "7일 동안 매일 1개 주제로 600~900자 초안을 AI와 만들고, 3일차부터는 실제 발행까지 해본다."
    });
    toast("예시를 채웠어요. 내 내용으로 바꿔보세요!");
  });

  // Init
  render();
  tryLoadFromUrl();
  // Load local after URL (so URL wins)
  if (!new URL(window.location.href).searchParams.get("p")) loadLocal();
</script>
</body>
</html>
