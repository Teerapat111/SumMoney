<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>บัญชีค่าห้อง</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@400;500;600;700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --mac-bg: #F0F0F2;
    --mac-titlebar: #ECECEE;
    --mac-panel: #FFFFFF;
    --mac-border: #DEDEE2;
    --mac-divider: rgba(0,0,0,0.08);
    --mac-text: #1D1D1F;
    --mac-text-secondary: #6E6E73;
    --mac-text-tertiary: #A0A0A5;

    --mac-blue: #0A84FF;
    --mac-blue-dark: #0768D1;
    --mac-red: #FF3B30;
    --mac-green: #30B94D;
    --mac-indigo: #5E5CE6;

    --traffic-red: #FF5F57;
    --traffic-yellow: #FEBC2E;
    --traffic-green: #28C840;

    --font: -apple-system, BlinkMacSystemFont, 'Noto Sans Thai', 'Inter', sans-serif;
  }

  *{ box-sizing: border-box; }
  html, body{ margin: 0; padding: 0; }

  html, body{ height: 100%; }

  body{
    background: var(--mac-bg);
    font-family: var(--font);
    min-height: 100vh;
  }

  button, input{ font-family: var(--font); }

  /* ---------------- Window chrome ---------------- */

  .mac-window{
    width: 100vw;
    min-height: 100vh;
    background: var(--mac-bg);
  }

  .title-bar{
    position: relative;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0 14px;
    background: linear-gradient(#F9F9FB, #ECECEE);
    border-bottom: 1px solid var(--mac-divider);
  }

  .window-title{
    font-size: 13px;
    font-weight: 600;
    color: var(--mac-text-secondary);
  }

  .content{
    max-width: 900px;
    margin: 0 auto;
    padding: 28px 32px 60px;
  }

  .layout{
    display: grid;
    grid-template-columns: 1fr 280px;
    gap: 20px;
    align-items: start;
  }

  /* ---------------- Balance card (spans full width, top) ---------------- */

  .balance-card{
    grid-column: 1 / -1;
    background: linear-gradient(155deg, var(--mac-blue) 0%, var(--mac-indigo) 100%);
    border-radius: 10px;
    padding: 18px 22px;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 24px;
    margin-bottom: 4px;
    box-shadow: 0 10px 24px -12px rgba(94,92,230,0.5);
  }

  .balance-main .balance-label{
    font-size: 12.5px;
    font-weight: 600;
    color: rgba(255,255,255,0.8);
    margin-bottom: 4px;
  }

  .balance-amount{
    font-size: 32px;
    font-weight: 700;
    letter-spacing: -0.01em;
    font-variant-numeric: tabular-nums;
  }
  .balance-amount.negative{ color: #FFD4CE; }

  .balance-stats{ display: flex; align-items: center; gap: 22px; flex-shrink: 0; }
  .balance-stat{ text-align: right; }
  .balance-stat .stat-label{
    display: block;
    font-size: 11.5px;
    color: rgba(255,255,255,0.75);
    margin-bottom: 3px;
  }
  .balance-stat .stat-value{
    font-size: 15px;
    font-weight: 600;
    font-variant-numeric: tabular-nums;
  }
  .stat-sep{ width: 1px; height: 28px; background: rgba(255,255,255,0.25); }

  /* ---------------- Grouped panels ---------------- */

  .panel{
    background: var(--mac-panel);
    border: 1px solid var(--mac-border);
    border-radius: 10px;
    box-shadow: 0 1px 1px rgba(0,0,0,0.03);
  }

  .section-label{
    font-size: 13px;
    font-weight: 600;
    color: var(--mac-text-secondary);
    margin: 22px 0 8px;
  }
  .section-label:first-of-type{ margin-top: 0; }

  .field-row{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 12px 16px;
    gap: 12px;
  }

  .field-row span{ font-size: 13px; color: var(--mac-text); }

  .mac-field{
    display: flex;
    align-items: center;
    gap: 6px;
    border: 1px solid var(--mac-border);
    background: #FBFBFC;
    border-radius: 6px;
    padding: 5px 10px;
    transition: box-shadow 0.12s ease, border-color 0.12s ease;
  }
  .mac-field:focus-within{
    border-color: var(--mac-blue);
    box-shadow: 0 0 0 3px rgba(10,132,255,0.18);
    background: #fff;
  }
  .mac-field .currency{ font-size: 13px; color: var(--mac-text-tertiary); }

  #incomeInput{
    border: none;
    background: none;
    font-size: 13.5px;
    font-weight: 500;
    color: var(--mac-text);
    text-align: right;
    width: 110px;
    font-variant-numeric: tabular-nums;
  }
  #incomeInput:focus{ outline: none; }

  /* item rows */

  .items-list .item-row{
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 9px 14px;
    border-bottom: 1px solid var(--mac-divider);
    transition: background 0.1s ease, opacity 0.16s ease;
  }
  .items-list .item-row:last-child{ border-bottom: none; }
  .items-list .item-row:hover{ background: #F7F8FA; }

  .row-main{ flex: 1; min-width: 0; }

  .name-text{
    display: block;
    font-size: 13.5px;
    color: var(--mac-text);
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }

  .name-input{
    width: 100%;
    border: 1px solid var(--mac-blue);
    border-radius: 5px;
    background: #fff;
    font-size: 13.5px;
    color: var(--mac-text);
    padding: 3px 7px;
    box-shadow: 0 0 0 3px rgba(10,132,255,0.18);
  }
  .name-input:focus{ outline: none; }
  .hidden{ display: none !important; }

  .amount-input{
    border: 1px solid var(--mac-border);
    background: #FBFBFC;
    border-radius: 6px;
    font-size: 13.5px;
    font-weight: 500;
    color: var(--mac-text);
    text-align: right;
    width: 84px;
    padding: 5px 8px;
    font-variant-numeric: tabular-nums;
    transition: box-shadow 0.12s ease, border-color 0.12s ease;
  }
  .amount-input:focus{
    outline: none;
    border-color: var(--mac-blue);
    box-shadow: 0 0 0 3px rgba(10,132,255,0.18);
    background: #fff;
  }

  .row-actions{ display: flex; gap: 6px; flex-shrink: 0; }

  .icon-btn{
    width: 24px;
    height: 24px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    border: 1px solid var(--mac-border);
    background: linear-gradient(#FEFEFE, #F3F3F5);
    border-radius: 6px;
    cursor: pointer;
    color: var(--mac-text-secondary);
    box-shadow: 0 1px 0 rgba(0,0,0,0.02);
    transition: all 0.12s ease;
  }
  .icon-btn svg{ width: 13px; height: 13px; }
  .icon-btn:hover{ background: #F0F1F3; }
  .icon-btn:active{ background: #E7E8EA; }

  .rename-btn.editing{ background: var(--mac-blue); border-color: var(--mac-blue-dark); color: #fff; }
  .delete-btn:hover{ color: var(--mac-red); border-color: var(--mac-red); background: #FFF1EF; }

  .list-footer{
    display: flex;
    align-items: center;
    padding: 8px 14px;
    border-top: 1px solid var(--mac-divider);
  }

  #addItemBtn{
    display: inline-flex;
    align-items: center;
    gap: 7px;
    font-size: 13px;
    font-weight: 500;
    color: #fff;
    background: linear-gradient(var(--mac-blue), var(--mac-blue-dark));
    border: 1px solid var(--mac-blue-dark);
    border-radius: 6px;
    padding: 6px 14px 6px 10px;
    cursor: pointer;
    transition: filter 0.12s ease;
  }
  #addItemBtn svg{ width: 14px; height: 14px; }
  #addItemBtn:hover{ filter: brightness(1.06); }
  #addItemBtn:active{ filter: brightness(0.94); }

  .empty-state{
    padding: 22px 14px;
    text-align: center;
    font-size: 13px;
    color: var(--mac-text-tertiary);
  }

  input[type=number]::-webkit-outer-spin-button,
  input[type=number]::-webkit-inner-spin-button{ -webkit-appearance: none; margin: 0; }
  input[type=number]{ -moz-appearance: textfield; }

  @media (max-width: 680px){
    .content{ padding: 20px 18px 24px; }
    .layout{ grid-template-columns: 1fr; }
    .balance-card{ flex-direction: column; align-items: flex-start; gap: 14px; }
    .balance-stats{ align-self: stretch; justify-content: space-between; }
  }
</style>
</head>
<body>
  <div class="mac-window">
    <div class="title-bar">
      <div class="window-title">บัญชีค่าห้อง</div>
    </div>

    <div class="content">
      <div class="layout">

        <div class="balance-card">
          <div class="balance-main">
            <div class="balance-label">คงเหลือหลังหักรายจ่าย</div>
            <div class="balance-amount" id="sumBalance">฿0.00</div>
          </div>
          <div class="balance-stats">
            <div class="balance-stat">
              <span class="stat-label">รับเข้า</span>
              <span class="stat-value" id="sumIncome">฿0.00</span>
            </div>
            <div class="stat-sep"></div>
            <div class="balance-stat">
              <span class="stat-label">จ่ายไปทั้งหมด</span>
              <span class="stat-value" id="sumExpense">฿0.00</span>
            </div>
          </div>
        </div>

        <div>
          <div class="section-label">เงินที่ได้รับ</div>
          <div class="panel">
            <div class="field-row">
              <span>จำนวนเงิน</span>
              <div class="mac-field">
                <span class="currency">฿</span>
                <input type="number" id="incomeInput" placeholder="0.00" inputmode="decimal" step="0.01">
              </div>
            </div>
          </div>

          <div class="section-label">รายการที่ต้องจ่าย</div>
          <div class="panel">
            <div class="items-list" id="itemsList"></div>
            <div class="empty-state" id="emptyState">ยังไม่มีรายการ กด "เพิ่มรายการ" เพื่อเริ่มบันทึก</div>
            <div class="list-footer">
              <button id="addItemBtn" type="button">
                <svg viewBox="0 0 24 24" fill="none"><path d="M12 5v14M5 12h14" stroke="currentColor" stroke-width="2.2" stroke-linecap="round"/></svg>
                เพิ่มรายการ
              </button>
            </div>
          </div>
        </div>

        <div>
          <div class="section-label">&nbsp;</div>
          <div class="panel" style="padding:14px 16px;">
            <div style="font-size:12.5px;color:var(--mac-text-secondary);line-height:1.6;">
              ยอดคงเหลือคำนวณจาก<br>เงินที่ได้รับ − รายการที่ต้องจ่ายทั้งหมด
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>

<script>
  const state = { income: 0, items: [], nextId: 1 };

  const incomeInput = document.getElementById('incomeInput');
  const addItemBtn = document.getElementById('addItemBtn');
  const itemsList = document.getElementById('itemsList');
  const emptyState = document.getElementById('emptyState');
  const sumIncome = document.getElementById('sumIncome');
  const sumExpense = document.getElementById('sumExpense');
  const sumBalance = document.getElementById('sumBalance');

  const ICON_PENCIL = '<svg viewBox="0 0 24 24" fill="none"><path d="M4 20l1-4.2L15.5 5.3a1.5 1.5 0 0 1 2.1 0l1.1 1.1a1.5 1.5 0 0 1 0 2.1L8.2 19 4 20Z" stroke="currentColor" stroke-width="1.8" stroke-linejoin="round"/></svg>';
  const ICON_CHECK = '<svg viewBox="0 0 24 24" fill="none"><path d="M5 12.5 10 17l9-10" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round"/></svg>';
  const ICON_TRASH = '<svg viewBox="0 0 24 24" fill="none"><path d="M5 7h14M9 7V5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2m-8 0 1 13a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1l1-13" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg>';

  function formatMoney(n){
    const v = isFinite(n) ? n : 0;
    return '฿' + v.toLocaleString('en-US', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
  }

  function updateSummary(){
    const totalExpense = state.items.reduce((sum, it) => sum + (it.amount || 0), 0);
    const income = state.income || 0;
    const balance = income - totalExpense;

    sumIncome.textContent = formatMoney(income);
    sumExpense.textContent = formatMoney(totalExpense);
    sumBalance.textContent = formatMoney(balance);
    sumBalance.classList.toggle('negative', balance < 0);
  }

  function updateEmptyState(){
    emptyState.classList.toggle('hidden', state.items.length > 0);
  }

  function createRow(item){
    const row = document.createElement('div');
    row.className = 'item-row';
    row.dataset.id = item.id;

    row.innerHTML = `
      <div class="row-main">
        <span class="name-text"></span>
        <input type="text" class="name-input hidden">
      </div>
      <input type="number" class="amount-input" placeholder="0.00" inputmode="decimal" step="0.01">
      <div class="row-actions">
        <button type="button" class="icon-btn rename-btn" title="เปลี่ยนชื่อ" aria-label="เปลี่ยนชื่อ">${ICON_PENCIL}</button>
        <button type="button" class="icon-btn delete-btn" title="ลบรายการ" aria-label="ลบรายการ">${ICON_TRASH}</button>
      </div>
    `;

    const nameText = row.querySelector('.name-text');
    const nameInput = row.querySelector('.name-input');
    const amountInput = row.querySelector('.amount-input');
    const renameBtn = row.querySelector('.rename-btn');
    const deleteBtn = row.querySelector('.delete-btn');

    nameText.textContent = item.name;
    nameInput.value = item.name;
    if (item.amount) amountInput.value = item.amount;

    function enterEditMode(){
      nameText.classList.add('hidden');
      nameInput.classList.remove('hidden');
      nameInput.value = item.name;
      nameInput.focus();
      nameInput.select();
      renameBtn.innerHTML = ICON_CHECK;
      renameBtn.classList.add('editing');
      renameBtn.title = 'บันทึกชื่อ';
    }
    function saveEdit(){
      const newName = nameInput.value.trim();
      item.name = newName.length ? newName : item.name;
      nameText.textContent = item.name;
      nameInput.classList.add('hidden');
      nameText.classList.remove('hidden');
      renameBtn.innerHTML = ICON_PENCIL;
      renameBtn.classList.remove('editing');
      renameBtn.title = 'เปลี่ยนชื่อ';
    }

    renameBtn.addEventListener('click', () => {
      const editing = !nameInput.classList.contains('hidden');
      editing ? saveEdit() : enterEditMode();
    });
    nameInput.addEventListener('keydown', (e) => {
      if (e.key === 'Enter') saveEdit();
      if (e.key === 'Escape'){ nameInput.value = item.name; saveEdit(); }
    });
    nameInput.addEventListener('blur', saveEdit);

    amountInput.addEventListener('input', () => {
      item.amount = parseFloat(amountInput.value) || 0;
      updateSummary();
    });

    deleteBtn.addEventListener('click', () => {
      row.style.opacity = '0';
      setTimeout(() => {
        const idx = state.items.findIndex(it => it.id === item.id);
        if (idx > -1) state.items.splice(idx, 1);
        row.remove();
        updateEmptyState();
        updateSummary();
      }, 140);
    });

    return row;
  }

  incomeInput.addEventListener('input', () => {
    state.income = parseFloat(incomeInput.value) || 0;
    updateSummary();
  });

  addItemBtn.addEventListener('click', () => {
    const item = { id: state.nextId++, name: 'รายการใหม่', amount: 0 };
    state.items.push(item);
    const row = createRow(item);
    itemsList.appendChild(row);
    updateEmptyState();
    updateSummary();
    row.querySelector('.rename-btn').click();
  });

  updateSummary();
  updateEmptyState();
</script>
</body>
</html>
