<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>単勝オッズボード</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Zen+Kaku+Gothic+New:wght@400;500;700;900&family=Space+Mono:wght@400;700&display=swap');

:root{
  --felt: #0b3b2e;
  --felt-dark: #082c22;
  --panel: #0e4536;
  --panel-2: #123f33;
  --line: #2f6b52;
  --cream: #f1eada;
  --cream-dim: #b9c4ba;
  --amber: #f4a93b;
  --amber-dim: #c98f36;
  --red: #d1594f;
  --glow: rgba(244,169,59,0.32);
}

*{box-sizing:border-box;}

body{
  margin:0;
  min-height:100vh;
  background:
    radial-gradient(1200px 600px at 50% -10%, rgba(255,255,255,0.05), transparent 60%),
    repeating-linear-gradient(0deg, rgba(255,255,255,0.012) 0px, rgba(255,255,255,0.012) 1px, transparent 1px, transparent 3px),
    var(--felt);
  color:var(--cream);
  font-family:'Zen Kaku Gothic New', sans-serif;
  padding-bottom:96px;
}

#app{ max-width:520px; margin:0 auto; padding:16px 14px 24px; }

/* ---- header ---- */
.board-header{
  display:flex; align-items:center; justify-content:space-between;
  padding:14px 16px;
  background:var(--felt-dark);
  border:1px solid var(--line);
  border-radius:6px;
  margin-bottom:16px;
}
.race-tag{
  font-family:'Space Mono', monospace;
  font-weight:700;
  font-size:13px;
  letter-spacing:0.08em;
  color:var(--amber);
  text-shadow:0 0 10px var(--glow);
}
.phase-label{
  font-size:12px;
  color:var(--cream-dim);
  margin-top:2px;
}
.standings-btn{
  background:transparent;
  border:1px solid var(--line);
  color:var(--cream-dim);
  border-radius:4px;
  padding:7px 10px;
  font-size:12px;
  font-family:'Zen Kaku Gothic New', sans-serif;
  cursor:pointer;
}
.standings-btn:active{ background:var(--panel); }

/* ---- generic section ---- */
.section-title{
  font-size:14px;
  font-weight:700;
  color:var(--cream);
  margin:0 0 10px 2px;
}
.hint{
  font-size:12px;
  color:var(--cream-dim);
  margin:-4px 0 12px 2px;
  line-height:1.6;
}

/* ---- tickets ---- */
.ticket{
  position:relative;
  background:var(--panel);
  border:1px solid var(--line);
  border-radius:3px;
  padding:12px 16px;
  margin-bottom:8px;
}
.ticket::before, .ticket::after{
  content:'';
  position:absolute; top:50%; transform:translateY(-50%);
  width:13px; height:13px; border-radius:50%;
  background:var(--felt);
  border:1px solid var(--line);
}
.ticket::before{ left:-8px; }
.ticket::after{ right:-8px; }
.ticket-row{ display:flex; align-items:center; justify-content:space-between; gap:10px; }
.ticket-main{ font-size:14px; }
.ticket-sub{ font-size:11px; color:var(--cream-dim); margin-top:2px; }
.ticket-amount{
  font-family:'Space Mono', monospace;
  font-weight:700;
  color:var(--amber);
  font-size:15px;
  white-space:nowrap;
}
.ticket-x{
  background:none; border:none; color:var(--red);
  font-size:16px; cursor:pointer; padding:2px 6px; line-height:1;
}

/* ---- form controls ---- */
.field-row{ display:flex; gap:8px; margin-bottom:10px; }
.field-row > *{ flex:1; }
input, select{
  width:100%;
  background:var(--panel-2);
  border:1px solid var(--line);
  color:var(--cream);
  border-radius:4px;
  padding:10px 10px;
  font-size:14px;
  font-family:'Zen Kaku Gothic New', sans-serif;
}
input::placeholder{ color:#6f8a7c; }
select{ appearance:none; }
label.small-label{
  font-size:11px;
  color:var(--cream-dim);
  display:block;
  margin-bottom:4px;
}

.btn{
  width:100%;
  padding:13px 16px;
  border-radius:5px;
  border:none;
  font-size:14px;
  font-weight:700;
  font-family:'Zen Kaku Gothic New', sans-serif;
  cursor:pointer;
  letter-spacing:0.02em;
}
.btn-primary{ background:var(--amber); color:#25200f; }
.btn-primary:disabled{ background:#4a4534; color:#8a8570; cursor:not-allowed; }
.btn-ghost{
  background:transparent; border:1px solid var(--line); color:var(--cream-dim);
  margin-top:8px;
}
.btn-small{
  width:auto; padding:8px 12px; font-size:12px; border-radius:4px;
  background:var(--panel-2); border:1px solid var(--line); color:var(--cream);
}

/* ---- racer chip select ---- */
.chip{
  display:flex; align-items:center; justify-content:space-between;
  padding:12px 14px;
  border:1px solid var(--line);
  border-radius:4px;
  background:var(--panel);
  margin-bottom:8px;
  cursor:pointer;
}
.chip.selected{ border-color:var(--amber); box-shadow:0 0 0 1px var(--amber) inset; }
.chip-name{ font-size:14px; }
.chip-points{ font-family:'Space Mono', monospace; font-size:12px; color:var(--cream-dim); }
.chip-mark{
  width:18px; height:18px; border-radius:3px; border:1px solid var(--line);
  display:flex; align-items:center; justify-content:center; margin-right:10px;
  font-size:12px; color:var(--amber);
}

/* ---- odds board ---- */
.odds-card{
  border:1px solid var(--line);
  background:var(--panel);
  border-radius:5px;
  padding:14px 16px;
  margin-bottom:10px;
  cursor:pointer;
}
.odds-card.selected{ border-color:var(--amber); background:var(--panel-2); box-shadow:0 0 0 1px var(--amber) inset; }
.odds-top{ display:flex; justify-content:space-between; align-items:baseline; }
.odds-name{ font-size:15px; font-weight:700; }
.odds-value{
  font-family:'Space Mono', monospace; font-weight:700; font-size:24px;
  color:var(--amber); text-shadow:0 0 10px var(--glow);
}
.odds-value.dash{ color:var(--cream-dim); text-shadow:none; font-size:20px; }
.odds-sub{ font-size:11px; color:var(--cream-dim); margin-top:4px; }
.pool-strip{
  display:flex; justify-content:space-between; align-items:center;
  background:var(--felt-dark); border:1px solid var(--line); border-radius:5px;
  padding:12px 16px; margin-bottom:14px;
}
.pool-label{ font-size:12px; color:var(--cream-dim); }
.pool-value{ font-family:'Space Mono', monospace; font-weight:700; color:var(--amber); font-size:20px; }

/* ---- result ---- */
.winner-banner{
  text-align:center;
  padding:18px 12px;
  border:1px solid var(--amber-dim);
  background:var(--panel-2);
  border-radius:6px;
  margin-bottom:16px;
}
.winner-banner .w-label{ font-size:11px; color:var(--cream-dim); letter-spacing:0.1em; }
.winner-banner .w-name{ font-size:26px; font-weight:900; color:var(--amber); text-shadow:0 0 12px var(--glow); margin-top:4px; }

.standings-row{
  display:flex; justify-content:space-between; align-items:center;
  padding:10px 4px; border-bottom:1px dashed var(--line);
  font-size:14px;
}
.standings-row:last-child{ border-bottom:none; }
.standings-rank{ color:var(--cream-dim); font-family:'Space Mono', monospace; font-size:12px; width:22px; }
.standings-points{ font-family:'Space Mono', monospace; font-weight:700; color:var(--amber); }

.overlay{
  position:fixed; inset:0; background:rgba(4,20,15,0.82);
  display:flex; align-items:flex-start; justify-content:center; padding:40px 16px;
  z-index:50;
}
.overlay-panel{
  background:var(--felt-dark); border:1px solid var(--line); border-radius:6px;
  padding:18px; max-width:440px; width:100%;
}
.overlay-close{
  display:block; margin:14px auto 0; background:none; border:none; color:var(--cream-dim);
  font-size:13px; cursor:pointer;
}

.empty-note{ font-size:13px; color:var(--cream-dim); padding:20px 4px; text-align:center; }
.formula-toggle{ font-size:11px; color:var(--cream-dim); text-decoration:underline; cursor:pointer; margin:0 0 14px 2px; }
.formula-box{ font-size:12px; color:var(--cream-dim); background:var(--felt-dark); border:1px solid var(--line); border-radius:4px; padding:10px 12px; margin:-6px 0 14px; line-height:1.7; font-family:'Space Mono',monospace; }
</style>
</head>
<body>
<div id="app"></div>

<script>
let state = {
  players: [],
  phase: 'setup',
  raceNumber: 0,
  currentRace: null,
  history: [],
  showStandings: false,
  showFormula: false,
  selectedWinner: null,
  nextId: 1,
};

function uid(){ return 'p' + (state.nextId++); }
function fmt(n){ return Math.round(n).toLocaleString('ja-JP'); }
function findPlayer(id){ return state.players.find(p => p.id === id); }

/* ---------- actions ---------- */

function addPlayer(){
  const nameEl = document.getElementById('new-name');
  const ptsEl = document.getElementById('new-points');
  const name = nameEl.value.trim();
  const pts = parseInt(ptsEl.value, 10);
  if(!name){ alert('名前を入力してください'); return; }
  if(isNaN(pts) || pts < 0){ alert('初期ポイントは0以上の数値で入力してください'); return; }
  state.players.push({ id: uid(), name, points: pts });
  render();
}

function removePlayer(id){
  state.players = state.players.filter(p => p.id !== id);
  render();
}

function startFirstRace(){
  if(state.players.length < 2){ alert('プレイヤーは2人以上必要です'); return; }
  state.raceNumber = 1;
  state.currentRace = { racers: [], bets: [], closed:false, oddsMap:null, totalPool:0, winnerId:null };
  state.phase = 'race-setup';
  render();
}

function toggleRacer(id){
  const r = state.currentRace.racers;
  const i = r.indexOf(id);
  if(i >= 0) r.splice(i,1); else r.push(id);
  render();
}

function confirmRacers(){
  if(state.currentRace.racers.length < 2){ alert('出走者は2人以上選んでください'); return; }
  state.phase = 'betting';
  render();
}

function placeBet(){
  const bettorId = document.getElementById('bet-bettor').value;
  const targetId = document.getElementById('bet-target').value;
  const amountEl = document.getElementById('bet-amount');
  const amount = parseInt(amountEl.value, 10);
  const bettor = findPlayer(bettorId);
  if(!bettor){ alert('投票者を選んでください'); return; }
  if(!targetId){ alert('賭ける相手を選んでください'); return; }
  if(isNaN(amount) || amount <= 0){ alert('1以上のポイント数を入力してください'); return; }
  if(amount > bettor.points){ alert(bettor.name + 'の残りポイントが足りません(残り' + fmt(bettor.points) + 'pt)'); return; }
  bettor.points -= amount;
  state.currentRace.bets.push({ id: uid(), bettorId, targetId, amount });
  render();
}

function removeBet(betId){
  const bets = state.currentRace.bets;
  const idx = bets.findIndex(b => b.id === betId);
  if(idx < 0) return;
  const bet = bets[idx];
  const bettor = findPlayer(bet.bettorId);
  if(bettor) bettor.points += bet.amount;
  bets.splice(idx,1);
  render();
}

function closeBetting(){
  const race = state.currentRace;
  if(race.bets.length === 0){ alert('まだ投票がありません'); return; }
  const x = race.bets.reduce((s,b) => s + b.amount, 0);
  const oddsMap = {};
  race.racers.forEach(rid => {
    const y = race.bets.filter(b => b.targetId === rid).reduce((s,b) => s + b.amount, 0);
    oddsMap[rid] = y > 0 ? (1 + 0.1 * ((x / y) - 1)) : null;
  });
  race.totalPool = x;
  race.oddsMap = oddsMap;
  state.phase = 'closed';
  state.selectedWinner = null;
  render();
}

function selectWinner(id){
  state.selectedWinner = id;
  render();
}

function confirmResult(){
  const race = state.currentRace;
  const winnerId = state.selectedWinner;
  if(!winnerId){ return; }
  const odds = race.oddsMap[winnerId];
  const payouts = [];
  const losses = [];
  race.bets.forEach(bet => {
    if(bet.targetId === winnerId){
      const payout = odds ? Math.round(bet.amount * odds) : 0;
      const bettor = findPlayer(bet.bettorId);
      if(bettor) bettor.points += payout;
      payouts.push({ bettorId: bet.bettorId, betAmount: bet.amount, payout });
    } else {
      losses.push({ bettorId: bet.bettorId, betAmount: bet.amount });
    }
  });
  race.winnerId = winnerId;
  race.payouts = payouts;
  race.losses = losses;
  state.history.push(Object.assign({}, race, { raceNumber: state.raceNumber }));
  state.phase = 'result';
  render();
}

function nextRace(){
  state.raceNumber += 1;
  state.currentRace = { racers: [], bets: [], closed:false, oddsMap:null, totalPool:0, winnerId:null };
  state.selectedWinner = null;
  state.phase = 'race-setup';
  render();
}

function toggleStandings(){ state.showStandings = !state.showStandings; render(); }
function toggleFormula(){ state.showFormula = !state.showFormula; render(); }

function resetAll(){
  if(!confirm('すべてのデータをリセットします。よろしいですか?')) return;
  state = { players: [], phase:'setup', raceNumber:0, currentRace:null, history:[], showStandings:false, showFormula:false, selectedWinner:null, nextId:1 };
  render();
}

/* ---------- render helpers ---------- */

function phaseLabel(){
  switch(state.phase){
    case 'setup': return 'プレイヤー登録';
    case 'race-setup': return '出走選択';
    case 'betting': return '投票受付中';
    case 'closed': return 'オッズ確定・着順選択';
    case 'result': return 'レース結果';
  }
  return '';
}

function renderHeader(){
  const raceTag = state.raceNumber > 0 ? '第' + state.raceNumber + 'レース' : '準備中';
  return '<div class="board-header">' +
    '<div><div class="race-tag">' + raceTag + '</div><div class="phase-label">' + phaseLabel() + '</div></div>' +
    '<button class="standings-btn" onclick="toggleStandings()">順位表</button>' +
    '</div>';
}

function renderStandingsOverlay(){
  if(!state.showStandings) return '';
  const sorted = [...state.players].sort((a,b) => b.points - a.points);
  const rows = sorted.map((p,i) =>
    '<div class="standings-row"><span><span class="standings-rank">' + (i+1) + '</span>' + escapeHtml(p.name) + '</span><span class="standings-points">' + fmt(p.points) + 'pt</span></div>'
  ).join('');
  return '<div class="overlay" onclick="if(event.target===this) toggleStandings()">' +
    '<div class="overlay-panel">' +
    '<div class="section-title">現在の順位表</div>' +
    (rows || '<div class="empty-note">プレイヤーがいません</div>') +
    '<button class="overlay-close" onclick="toggleStandings()">閉じる</button>' +
    '</div></div>';
}

function escapeHtml(s){
  return s.replace(/[&<>"']/g, c => ({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
}

function renderSetup(){
  const list = state.players.map(p =>
    '<div class="ticket"><div class="ticket-row">' +
      '<div><div class="ticket-main">' + escapeHtml(p.name) + '</div><div class="ticket-sub">初期ポイント</div></div>' +
      '<div style="display:flex;align-items:center;gap:10px;">' +
        '<span class="ticket-amount">' + fmt(p.points) + 'pt</span>' +
        '<button class="ticket-x" onclick="removePlayer(\'' + p.id + '\')">&times;</button>' +
      '</div>' +
    '</div></div>'
  ).join('');

  return '<div class="section-title">プレイヤーを登録</div>' +
    '<div class="hint">名前と持ちポイントを入力して追加してください。全員そろったらレースを開始します。</div>' +
    (list || '<div class="empty-note">まだ誰も登録されていません</div>') +
    '<div style="margin-top:14px;">' +
      '<div class="field-row">' +
        '<div><label class="small-label">名前</label><input id="new-name" type="text" placeholder="例: たなか"></div>' +
        '<div><label class="small-label">初期ポイント</label><input id="new-points" type="number" min="0" placeholder="例: 1000"></div>' +
      '</div>' +
      '<button class="btn btn-small" onclick="addPlayer()" style="width:100%;">+ プレイヤーを追加</button>' +
    '</div>' +
    '<button class="btn btn-primary" style="margin-top:20px;" ' + (state.players.length < 2 ? 'disabled' : '') + ' onclick="startFirstRace()">レース開始 &rarr;</button>';
}

function renderRaceSetup(){
  const race = state.currentRace;
  const chips = state.players.map(p => {
    const sel = race.racers.includes(p.id);
    return '<div class="chip ' + (sel?'selected':'') + '" onclick="toggleRacer(\'' + p.id + '\')">' +
      '<div style="display:flex;align-items:center;"><span class="chip-mark">' + (sel?'&#10003;':'') + '</span>' +
      '<span class="chip-name">' + escapeHtml(p.name) + '</span></div>' +
      '<span class="chip-points">' + fmt(p.points) + 'pt</span>' +
    '</div>';
  }).join('');

  return '<div class="section-title">第' + state.raceNumber + 'レースの出走者を選択</div>' +
    '<div class="hint">このレースで走る(勝敗の対象になる)プレイヤーを2人以上選んでください。</div>' +
    chips +
    '<button class="btn btn-primary" style="margin-top:16px;" ' + (race.racers.length < 2 ? 'disabled' : '') + ' onclick="confirmRacers()">この' + race.racers.length + '人で投票開始 &rarr;</button>';
}

function renderBetting(){
  const race = state.currentRace;
  const pool = race.bets.reduce((s,b) => s + b.amount, 0);
  const bettorOptions = state.players.map(p => '<option value="' + p.id + '">' + escapeHtml(p.name) + '(残り' + fmt(p.points) + 'pt)</option>').join('');
  const targetOptions = race.racers.map(id => {
    const p = findPlayer(id);
    return '<option value="' + id + '">' + escapeHtml(p.name) + '</option>';
  }).join('');

  const bets = race.bets.map(b => {
    const bettor = findPlayer(b.bettorId);
    const target = findPlayer(b.targetId);
    return '<div class="ticket"><div class="ticket-row">' +
      '<div><div class="ticket-main">' + escapeHtml(bettor.name) + ' &rarr; ' + escapeHtml(target.name) + '</div><div class="ticket-sub">単勝</div></div>' +
      '<div style="display:flex;align-items:center;gap:10px;">' +
        '<span class="ticket-amount">' + fmt(b.amount) + 'pt</span>' +
        '<button class="ticket-x" onclick="removeBet(\'' + b.id + '\')">&times;</button>' +
      '</div>' +
    '</div></div>';
  }).join('');

  return '<div class="pool-strip"><span class="pool-label">投票受付中 &middot; 合計プール</span><span class="pool-value">' + fmt(pool) + 'pt</span></div>' +
    '<div class="section-title">投票を追加</div>' +
    '<div class="field-row">' +
      '<div><label class="small-label">投票者</label><select id="bet-bettor">' + bettorOptions + '</select></div>' +
      '<div><label class="small-label">賭ける相手</label><select id="bet-target">' + targetOptions + '</select></div>' +
    '</div>' +
    '<div class="field-row">' +
      '<div><label class="small-label">ポイント数</label><input id="bet-amount" type="number" min="1" placeholder="例: 100"></div>' +
    '</div>' +
    '<button class="btn btn-small" style="width:100%;" onclick="placeBet()">+ 投票する</button>' +
    '<div class="section-title" style="margin-top:20px;">投票一覧(' + race.bets.length + '件)</div>' +
    (bets || '<div class="empty-note">まだ投票がありません</div>') +
    '<button class="btn btn-primary" style="margin-top:16px;" onclick="closeBetting()">投票締切 &rarr; オッズ発表</button>';
}

function renderClosed(){
  const race = state.currentRace;
  const cards = race.racers.map(id => {
    const p = findPlayer(id);
    const y = race.bets.filter(b => b.targetId === id).reduce((s,b) => s+b.amount,0);
    const odds = race.oddsMap[id];
    const sel = state.selectedWinner === id;
    return '<div class="odds-card ' + (sel?'selected':'') + '" onclick="selectWinner(\'' + id + '\')">' +
      '<div class="odds-top"><span class="odds-name">' + escapeHtml(p.name) + '</span>' +
      '<span class="odds-value ' + (odds===null?'dash':'') + '">' + (odds===null ? '&mdash;' : odds.toFixed(2) + '倍') + '</span></div>' +
      '<div class="odds-sub">賭けられたポイント: ' + fmt(y) + 'pt</div>' +
    '</div>';
  }).join('');

  return '<div class="pool-strip"><span class="pool-label">合計プール</span><span class="pool-value">' + fmt(race.totalPool) + 'pt</span></div>' +
    '<div class="section-title">着順(勝者)を選んでください</div>' +
    cards +
    '<button class="btn btn-primary" style="margin-top:14px;" ' + (!state.selectedWinner ? 'disabled' : '') + ' onclick="confirmResult()">この結果で確定</button>';
}

function renderResult(){
  const race = state.history[state.history.length - 1];
  const winner = findPlayer(race.winnerId);
  const odds = race.oddsMap[race.winnerId];

  const payoutRows = race.payouts.map(pay => {
    const p = findPlayer(pay.bettorId);
    return '<div class="ticket"><div class="ticket-row">' +
      '<div><div class="ticket-main">' + escapeHtml(p.name) + '</div><div class="ticket-sub">賭け金 ' + fmt(pay.betAmount) + 'pt &times; ' + (odds?odds.toFixed(2):'-') + '倍</div></div>' +
      '<span class="ticket-amount">+' + fmt(pay.payout) + 'pt</span>' +
    '</div></div>';
  }).join('');

  const lossRows = race.losses.map(loss => {
    const p = findPlayer(loss.bettorId);
    return '<div class="ticket"><div class="ticket-row">' +
      '<div><div class="ticket-main">' + escapeHtml(p.name) + '</div><div class="ticket-sub">はずれ</div></div>' +
      '<span class="ticket-amount" style="color:var(--red);">&minus;' + fmt(loss.betAmount) + 'pt</span>' +
    '</div></div>';
  }).join('');

  const sorted = [...state.players].sort((a,b) => b.points - a.points);
  const standings = sorted.map((p,i) =>
    '<div class="standings-row"><span><span class="standings-rank">' + (i+1) + '</span>' + escapeHtml(p.name) + '</span><span class="standings-points">' + fmt(p.points) + 'pt</span></div>'
  ).join('');

  return '<div class="winner-banner"><div class="w-label">WINNER</div><div class="w-name">' + escapeHtml(winner.name) + '</div></div>' +
    (payoutRows ? '<div class="section-title">配当</div>' + payoutRows : '<div class="empty-note">この着順に投票はありませんでした</div>') +
    (lossRows ? '<div class="section-title" style="margin-top:16px;">はずれ</div>' + lossRows : '') +
    '<div class="section-title" style="margin-top:20px;">現在の順位表</div>' +
    standings +
    '<button class="btn btn-primary" style="margin-top:20px;" onclick="nextRace()">次のレースへ &rarr;</button>';
}

function render(){
  let body = '';
  if(state.phase === 'setup') body = renderSetup();
  else if(state.phase === 'race-setup') body = renderRaceSetup();
  else if(state.phase === 'betting') body = renderBetting();
  else if(state.phase === 'closed') body = renderClosed();
  else if(state.phase === 'result') body = renderResult();

  const formulaToggle = '<div class="formula-toggle" onclick="toggleFormula()">オッズの計算式について' + (state.showFormula?' ▲':' ▼') + '</div>' +
    (state.showFormula ? '<div class="formula-box">odds = 1 + 0.1 &times; ((x / y) &minus; 1)<br>x = レース全体の合計投票ポイント<br>y = その対象に投票された合計ポイント</div>' : '');

  document.getElementById('app').innerHTML =
    renderHeader() +
    (state.phase !== 'setup' ? formulaToggle : '') +
    body +
    (state.phase === 'setup' ? '' : '<button class="btn btn-ghost" onclick="resetAll()">最初からリセット</button>') +
    renderStandingsOverlay();
}

render();
</script>
</body>
</html>
