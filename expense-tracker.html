<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Spendly — Smart Expense Tracker</title>
<link href="https://fonts.googleapis.com/css2?family=Cabinet+Grotesk:wght@400;500;700;800;900&family=Instrument+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #f5f2ee;
    --surface: #ffffff;
    --surface2: #f0ece6;
    --ink: #1a1714;
    --ink2: #6b6460;
    --ink3: #a8a3a0;
    --green: #2d6a4f;
    --green-light: #d8f3dc;
    --red: #c1121f;
    --red-light: #fde8ea;
    --amber: #b5830a;
    --amber-light: #fef3c7;
    --blue: #1e40af;
    --blue-light: #dbeafe;
    --accent: #e76f51;
    --accent-light: #fde8df;
    --border: rgba(26,23,20,0.1);
    --shadow: 0 2px 12px rgba(26,23,20,0.08);
    --r: 16px;
    --font-h: 'Cabinet Grotesk', sans-serif;
    --font-b: 'Instrument Sans', sans-serif;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: var(--font-b);
    background: var(--bg);
    color: var(--ink);
    min-height: 100vh;
  }

  /* LAYOUT */
  .app { display: grid; grid-template-columns: 260px 1fr; min-height: 100vh; }

  /* SIDEBAR */
  .sidebar {
    background: var(--ink);
    color: #fff;
    padding: 2rem 1.5rem;
    display: flex; flex-direction: column; gap: 2rem;
    position: sticky; top: 0; height: 100vh;
  }
  .brand {
    display: flex; align-items: center; gap: 10px;
  }
  .brand-icon {
    width: 36px; height: 36px; border-radius: 10px;
    background: var(--accent);
    display: flex; align-items: center; justify-content: center;
    font-size: 18px;
  }
  .brand-name {
    font-family: var(--font-h); font-size: 1.4rem;
    font-weight: 900; letter-spacing: -0.5px; color: #fff;
  }

  .nav-label {
    font-size: 0.68rem; font-weight: 600; letter-spacing: 1.5px;
    color: rgba(255,255,255,0.35); text-transform: uppercase; margin-bottom: 0.5rem;
  }
  .nav-item {
    display: flex; align-items: center; gap: 10px;
    padding: 10px 12px; border-radius: 10px; cursor: pointer;
    font-size: 0.9rem; color: rgba(255,255,255,0.6);
    transition: all 0.2s; margin-bottom: 2px;
  }
  .nav-item:hover { background: rgba(255,255,255,0.07); color: #fff; }
  .nav-item.active { background: var(--accent); color: #fff; }
  .nav-icon { font-size: 1rem; width: 20px; text-align: center; }

  .balance-card {
    background: rgba(255,255,255,0.06);
    border: 1px solid rgba(255,255,255,0.1);
    border-radius: var(--r); padding: 1.25rem; margin-top: auto;
  }
  .balance-label { font-size: 0.75rem; color: rgba(255,255,255,0.5); margin-bottom: 4px; }
  .balance-amount {
    font-family: var(--font-h); font-size: 1.8rem;
    font-weight: 900; letter-spacing: -1px;
    color: #fff;
  }
  .balance-sub { font-size: 0.75rem; color: rgba(255,255,255,0.4); margin-top: 6px; }

  /* MAIN */
  .main { padding: 2rem 2.5rem; overflow-y: auto; }

  .topbar {
    display: flex; align-items: center; justify-content: space-between;
    margin-bottom: 2rem; flex-wrap: wrap; gap: 1rem;
  }
  .page-title {
    font-family: var(--font-h); font-size: 1.7rem;
    font-weight: 900; letter-spacing: -0.5px;
  }
  .add-btn {
    background: var(--accent); color: #fff;
    border: none; padding: 10px 20px;
    border-radius: 10px; font-family: var(--font-b);
    font-size: 0.9rem; font-weight: 600; cursor: pointer;
    display: flex; align-items: center; gap: 6px;
    transition: all 0.2s;
  }
  .add-btn:hover { background: #cf5c3d; transform: translateY(-1px); }

  /* STAT CARDS */
  .stats-grid {
    display: grid; grid-template-columns: repeat(3, 1fr);
    gap: 1rem; margin-bottom: 2rem;
  }
  .stat-card {
    background: var(--surface); border-radius: var(--r);
    padding: 1.25rem 1.5rem; border: 1px solid var(--border);
    position: relative; overflow: hidden;
    animation: slideUp 0.4s ease both;
  }
  .stat-card:nth-child(2) { animation-delay: 0.08s; }
  .stat-card:nth-child(3) { animation-delay: 0.16s; }
  @keyframes slideUp {
    from { opacity: 0; transform: translateY(16px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .stat-icon {
    width: 38px; height: 38px; border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.1rem; margin-bottom: 0.75rem;
  }
  .stat-icon.income { background: var(--green-light); }
  .stat-icon.expense { background: var(--red-light); }
  .stat-icon.savings { background: var(--amber-light); }
  .stat-label { font-size: 0.8rem; color: var(--ink2); margin-bottom: 4px; }
  .stat-value {
    font-family: var(--font-h); font-size: 1.6rem;
    font-weight: 900; letter-spacing: -1px;
  }
  .stat-value.income { color: var(--green); }
  .stat-value.expense { color: var(--red); }
  .stat-value.savings { color: var(--amber); }
  .stat-change {
    font-size: 0.73rem; margin-top: 4px;
    color: var(--ink3);
  }

  /* TWO COL */
  .two-col { display: grid; grid-template-columns: 1fr 340px; gap: 1.5rem; margin-bottom: 2rem; }

  /* CHART CARD */
  .card {
    background: var(--surface); border-radius: var(--r);
    border: 1px solid var(--border); padding: 1.5rem;
    animation: slideUp 0.4s ease 0.2s both;
  }
  .card-header {
    display: flex; align-items: center; justify-content: space-between;
    margin-bottom: 1.25rem;
  }
  .card-title {
    font-family: var(--font-h); font-size: 1rem;
    font-weight: 800; letter-spacing: -0.3px;
  }
  .filter-tabs { display: flex; gap: 4px; }
  .filter-tab {
    padding: 4px 12px; border-radius: 8px; border: none;
    font-size: 0.75rem; font-family: var(--font-b); cursor: pointer;
    background: transparent; color: var(--ink2);
    transition: all 0.2s;
  }
  .filter-tab.active { background: var(--ink); color: #fff; }
  .filter-tab:hover:not(.active) { background: var(--surface2); }

  /* BAR CHART */
  .bar-chart { height: 180px; display: flex; align-items: flex-end; gap: 8px; }
  .bar-group { flex: 1; display: flex; gap: 3px; align-items: flex-end; flex-direction: column; }
  .bar-wrap { flex: 1; display: flex; flex-direction: column; align-items: center; gap: 6px; width: 100%; }
  .bar-col { width: 100%; display: flex; gap: 3px; align-items: flex-end; height: 150px; }
  .bar {
    flex: 1; border-radius: 6px 6px 0 0;
    transition: height 0.6s cubic-bezier(0.34, 1.56, 0.64, 1);
    cursor: pointer; position: relative;
  }
  .bar.income-bar { background: var(--green-light); }
  .bar.income-bar:hover { background: var(--green); }
  .bar.expense-bar { background: var(--red-light); }
  .bar.expense-bar:hover { background: var(--red); }
  .bar-month { font-size: 0.7rem; color: var(--ink3); text-align: center; margin-top: 6px; }

  /* DONUT */
  .donut-wrap { display: flex; flex-direction: column; align-items: center; gap: 1rem; }
  svg.donut { transform: rotate(-90deg); }
  .donut-center {
    position: absolute; top: 50%; left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
  }
  .donut-container { position: relative; width: 130px; height: 130px; }
  .donut-legend { width: 100%; }
  .legend-item {
    display: flex; align-items: center; justify-content: space-between;
    padding: 6px 0; font-size: 0.8rem; border-bottom: 1px solid var(--border);
  }
  .legend-item:last-child { border-bottom: none; }
  .legend-dot { width: 8px; height: 8px; border-radius: 50%; }
  .legend-name { display: flex; align-items: center; gap: 6px; color: var(--ink2); }
  .legend-pct { font-weight: 600; font-family: var(--font-h); color: var(--ink); }

  /* TRANSACTION LIST */
  .txn-list-card { animation: slideUp 0.4s ease 0.28s both; }
  .txn-filters {
    display: flex; gap: 8px; margin-bottom: 1rem; flex-wrap: wrap;
  }
  .txn-filter {
    padding: 5px 14px; border-radius: 20px; border: 1px solid var(--border);
    font-size: 0.78rem; font-family: var(--font-b); cursor: pointer;
    background: transparent; color: var(--ink2); transition: all 0.2s;
  }
  .txn-filter.active { background: var(--ink); color: #fff; border-color: var(--ink); }
  .txn-item {
    display: flex; align-items: center; gap: 12px;
    padding: 12px 0; border-bottom: 1px solid var(--border);
    animation: fadeIn 0.3s ease both;
  }
  .txn-item:last-child { border-bottom: none; }
  @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
  .txn-emoji {
    width: 40px; height: 40px; border-radius: 12px;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.1rem; flex-shrink: 0;
  }
  .txn-info { flex: 1; }
  .txn-name { font-size: 0.88rem; font-weight: 600; margin-bottom: 2px; }
  .txn-date { font-size: 0.73rem; color: var(--ink3); }
  .txn-cat {
    font-size: 0.68rem; font-weight: 600; letter-spacing: 0.5px;
    padding: 3px 8px; border-radius: 6px; text-transform: uppercase;
  }
  .txn-amount { font-family: var(--font-h); font-size: 0.95rem; font-weight: 800; text-align: right; }
  .txn-amount.credit { color: var(--green); }
  .txn-amount.debit { color: var(--red); }
  .txn-actions { display: flex; gap: 4px; }
  .txn-del {
    background: none; border: none; cursor: pointer;
    color: var(--ink3); font-size: 0.85rem; padding: 4px;
    border-radius: 6px; transition: all 0.2s;
  }
  .txn-del:hover { background: var(--red-light); color: var(--red); }

  /* MODAL */
  .modal-overlay {
    position: fixed; inset: 0; background: rgba(26,23,20,0.5);
    display: flex; align-items: center; justify-content: center;
    z-index: 1000; opacity: 0; pointer-events: none; transition: opacity 0.2s;
  }
  .modal-overlay.open { opacity: 1; pointer-events: all; }
  .modal {
    background: var(--surface); border-radius: 20px;
    padding: 2rem; width: 420px; max-width: 95vw;
    transform: translateY(20px); transition: transform 0.3s;
    max-height: 90vh; overflow-y: auto;
  }
  .modal-overlay.open .modal { transform: translateY(0); }
  .modal-title {
    font-family: var(--font-h); font-size: 1.3rem;
    font-weight: 900; margin-bottom: 1.5rem;
    display: flex; justify-content: space-between; align-items: center;
  }
  .modal-close {
    background: var(--surface2); border: none; border-radius: 8px;
    width: 30px; height: 30px; cursor: pointer; font-size: 1rem;
    display: flex; align-items: center; justify-content: center;
    color: var(--ink2); transition: all 0.2s;
  }
  .modal-close:hover { background: var(--red-light); color: var(--red); }
  .form-group { margin-bottom: 1rem; }
  .form-label { font-size: 0.8rem; font-weight: 600; color: var(--ink2); display: block; margin-bottom: 6px; }
  .form-input, .form-select {
    width: 100%; padding: 10px 14px;
    border: 1.5px solid var(--border); border-radius: 10px;
    font-family: var(--font-b); font-size: 0.9rem; color: var(--ink);
    background: var(--surface); outline: none; transition: border 0.2s;
  }
  .form-input:focus, .form-select:focus { border-color: var(--accent); }
  .type-toggle {
    display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-bottom: 1rem;
  }
  .type-btn {
    padding: 10px; border-radius: 10px; border: 1.5px solid var(--border);
    font-family: var(--font-b); font-size: 0.88rem; font-weight: 600;
    cursor: pointer; background: transparent; transition: all 0.2s; color: var(--ink2);
  }
  .type-btn.income.active { background: var(--green-light); border-color: var(--green); color: var(--green); }
  .type-btn.expense.active { background: var(--red-light); border-color: var(--red); color: var(--red); }
  .submit-btn {
    width: 100%; padding: 12px; border-radius: 12px; border: none;
    background: var(--ink); color: #fff; font-family: var(--font-h);
    font-size: 1rem; font-weight: 800; cursor: pointer; transition: all 0.2s;
    margin-top: 0.5rem;
  }
  .submit-btn:hover { background: var(--accent); transform: translateY(-1px); }

  /* BUDGET SECTION */
  .budget-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(240px,1fr)); gap: 1rem; }
  .budget-card {
    background: var(--surface); border: 1px solid var(--border);
    border-radius: var(--r); padding: 1.25rem;
    animation: slideUp 0.3s ease both;
  }
  .budget-header { display: flex; align-items: center; gap: 10px; margin-bottom: 1rem; }
  .budget-emoji { font-size: 1.4rem; }
  .budget-cat { font-family: var(--font-h); font-size: 0.95rem; font-weight: 800; }
  .budget-amounts { display: flex; justify-content: space-between; font-size: 0.78rem; color: var(--ink2); margin-bottom: 6px; }
  .budget-bar-wrap { height: 6px; background: var(--surface2); border-radius: 10px; overflow: hidden; }
  .budget-bar-fill {
    height: 100%; border-radius: 10px; transition: width 0.6s;
  }
  .budget-pct { font-size: 0.73rem; color: var(--ink3); margin-top: 5px; text-align: right; }

  /* EMPTY STATE */
  .empty { text-align: center; padding: 2rem; color: var(--ink3); }
  .empty-icon { font-size: 2.5rem; margin-bottom: 0.5rem; }
  .empty p { font-size: 0.85rem; }

  /* TOAST */
  .toast {
    position: fixed; bottom: 2rem; right: 2rem;
    background: var(--ink); color: #fff;
    padding: 12px 20px; border-radius: 12px;
    font-size: 0.85rem; z-index: 2000;
    transform: translateY(80px); opacity: 0; transition: all 0.3s;
    pointer-events: none;
  }
  .toast.show { transform: translateY(0); opacity: 1; }

  /* RESPONSIVE */
  @media (max-width: 900px) {
    .app { grid-template-columns: 1fr; }
    .sidebar { height: auto; position: relative; flex-direction: row; flex-wrap: wrap; padding: 1rem; }
    .stats-grid { grid-template-columns: 1fr 1fr; }
    .two-col { grid-template-columns: 1fr; }
    .main { padding: 1.5rem 1rem; }
  }
  @media (max-width: 600px) {
    .stats-grid { grid-template-columns: 1fr; }
  }

  /* PAGES */
  .page { display: none; }
  .page.active { display: block; }
</style>
</head>
<body>

<div class="app">
  <!-- SIDEBAR -->
  <aside class="sidebar">
    <div class="brand">
      <div class="brand-icon">💸</div>
      <span class="brand-name">Spendly</span>
    </div>

    <nav>
      <div class="nav-label">Menu</div>
      <div class="nav-item active" onclick="showPage('dashboard', this)">
        <span class="nav-icon">📊</span> Dashboard
      </div>
      <div class="nav-item" onclick="showPage('transactions', this)">
        <span class="nav-icon">📋</span> Transactions
      </div>
      <div class="nav-item" onclick="showPage('budget', this)">
        <span class="nav-icon">🎯</span> Budget
      </div>
    </nav>

    <div class="balance-card">
      <div class="balance-label">Net Balance</div>
      <div class="balance-amount" id="sidebar-balance">₹0</div>
      <div class="balance-sub" id="sidebar-balance-sub">Income − Expenses</div>
    </div>
  </aside>

  <!-- MAIN CONTENT -->
  <main class="main">

    <!-- DASHBOARD PAGE -->
    <div class="page active" id="page-dashboard">
      <div class="topbar">
        <div class="page-title">Dashboard</div>
        <button class="add-btn" onclick="openModal()">+ Add Transaction</button>
      </div>

      <div class="stats-grid">
        <div class="stat-card">
          <div class="stat-icon income">💰</div>
          <div class="stat-label">Total Income</div>
          <div class="stat-value income" id="total-income">₹0</div>
          <div class="stat-change" id="income-count">0 transactions</div>
        </div>
        <div class="stat-card">
          <div class="stat-icon expense">💳</div>
          <div class="stat-label">Total Expenses</div>
          <div class="stat-value expense" id="total-expense">₹0</div>
          <div class="stat-change" id="expense-count">0 transactions</div>
        </div>
        <div class="stat-card">
          <div class="stat-icon savings">🏦</div>
          <div class="stat-label">Savings Rate</div>
          <div class="stat-value savings" id="savings-rate">0%</div>
          <div class="stat-change">of income saved</div>
        </div>
      </div>

      <div class="two-col">
        <!-- BAR CHART -->
        <div class="card">
          <div class="card-header">
            <div class="card-title">Income vs Expenses</div>
            <div class="filter-tabs">
              <button class="filter-tab active" onclick="setChartFilter('6m',this)">6M</button>
              <button class="filter-tab" onclick="setChartFilter('3m',this)">3M</button>
            </div>
          </div>
          <div class="bar-chart" id="bar-chart"></div>
          <div style="display:flex;gap:12px;margin-top:10px">
            <div style="display:flex;align-items:center;gap:5px;font-size:0.73rem;color:var(--ink2)">
              <div style="width:10px;height:10px;border-radius:3px;background:var(--green-light);border:1.5px solid var(--green)"></div> Income
            </div>
            <div style="display:flex;align-items:center;gap:5px;font-size:0.73rem;color:var(--ink2)">
              <div style="width:10px;height:10px;border-radius:3px;background:var(--red-light);border:1.5px solid var(--red)"></div> Expenses
            </div>
          </div>
        </div>

        <!-- DONUT CHART -->
        <div class="card">
          <div class="card-header">
            <div class="card-title">Spending by Category</div>
          </div>
          <div class="donut-wrap">
            <div class="donut-container">
              <svg class="donut" width="130" height="130" viewBox="0 0 130 130" id="donut-svg"></svg>
              <div class="donut-center">
                <div style="font-family:var(--font-h);font-size:1.1rem;font-weight:900;color:var(--ink)" id="donut-center-val">₹0</div>
                <div style="font-size:0.65rem;color:var(--ink3)">total spent</div>
              </div>
            </div>
            <div class="donut-legend" id="donut-legend">
              <div class="empty"><div class="empty-icon">🍩</div><p>Add expenses to see breakdown</p></div>
            </div>
          </div>
        </div>
      </div>

      <!-- RECENT TRANSACTIONS -->
      <div class="card txn-list-card">
        <div class="card-header">
          <div class="card-title">Recent Transactions</div>
          <button class="add-btn" style="font-size:0.78rem;padding:6px 14px" onclick="showPage('transactions', document.querySelector('.nav-item:nth-child(2))'))">View All</button>
        </div>
        <div id="recent-list"></div>
      </div>
    </div>

    <!-- TRANSACTIONS PAGE -->
    <div class="page" id="page-transactions">
      <div class="topbar">
        <div class="page-title">Transactions</div>
        <button class="add-btn" onclick="openModal()">+ Add Transaction</button>
      </div>
      <div class="card">
        <div class="txn-filters">
          <button class="txn-filter active" onclick="filterTxns('all',this)">All</button>
          <button class="txn-filter" onclick="filterTxns('income',this)">Income</button>
          <button class="txn-filter" onclick="filterTxns('expense',this)">Expense</button>
          <button class="txn-filter" onclick="filterTxns('Food',this)">🍕 Food</button>
          <button class="txn-filter" onclick="filterTxns('Transport',this)">🚌 Transport</button>
          <button class="txn-filter" onclick="filterTxns('Shopping',this)">🛒 Shopping</button>
          <button class="txn-filter" onclick="filterTxns('Entertainment',this)">🎮 Entertainment</button>
        </div>
        <div id="all-txn-list"></div>
      </div>
    </div>

    <!-- BUDGET PAGE -->
    <div class="page" id="page-budget">
      <div class="topbar">
        <div class="page-title">Budget Tracker</div>
        <button class="add-btn" onclick="openBudgetModal()">+ Set Budget</button>
      </div>
      <div class="budget-grid" id="budget-grid"></div>
    </div>

  </main>
</div>

<!-- ADD TRANSACTION MODAL -->
<div class="modal-overlay" id="modal">
  <div class="modal">
    <div class="modal-title">
      Add Transaction
      <button class="modal-close" onclick="closeModal()">✕</button>
    </div>
    <div class="type-toggle">
      <button class="type-btn income active" id="type-income" onclick="setType('income')">💰 Income</button>
      <button class="type-btn expense" id="type-expense" onclick="setType('expense')">💳 Expense</button>
    </div>
    <div class="form-group">
      <label class="form-label">Description</label>
      <input class="form-input" id="txn-desc" placeholder="e.g. Salary, Groceries..." />
    </div>
    <div class="form-group">
      <label class="form-label">Amount (₹)</label>
      <input class="form-input" id="txn-amount" type="number" placeholder="0.00" min="0" />
    </div>
    <div class="form-group">
      <label class="form-label">Category</label>
      <select class="form-select" id="txn-cat">
        <option value="Salary">💼 Salary</option>
        <option value="Freelance">🧑‍💻 Freelance</option>
        <option value="Food">🍕 Food</option>
        <option value="Transport">🚌 Transport</option>
        <option value="Shopping">🛒 Shopping</option>
        <option value="Entertainment">🎮 Entertainment</option>
        <option value="Health">❤️ Health</option>
        <option value="Bills">🏠 Bills</option>
        <option value="Education">📚 Education</option>
        <option value="Other">📦 Other</option>
      </select>
    </div>
    <div class="form-group">
      <label class="form-label">Date</label>
      <input class="form-input" id="txn-date" type="date" />
    </div>
    <button class="submit-btn" onclick="addTransaction()">Add Transaction</button>
  </div>
</div>

<!-- BUDGET MODAL -->
<div class="modal-overlay" id="budget-modal">
  <div class="modal">
    <div class="modal-title">
      Set Budget Limit
      <button class="modal-close" onclick="closeBudgetModal()">✕</button>
    </div>
    <div class="form-group">
      <label class="form-label">Category</label>
      <select class="form-select" id="budget-cat">
        <option value="Food">🍕 Food</option>
        <option value="Transport">🚌 Transport</option>
        <option value="Shopping">🛒 Shopping</option>
        <option value="Entertainment">🎮 Entertainment</option>
        <option value="Health">❤️ Health</option>
        <option value="Bills">🏠 Bills</option>
        <option value="Education">📚 Education</option>
        <option value="Other">📦 Other</option>
      </select>
    </div>
    <div class="form-group">
      <label class="form-label">Monthly Budget (₹)</label>
      <input class="form-input" id="budget-amount" type="number" placeholder="Enter budget limit" />
    </div>
    <button class="submit-btn" onclick="saveBudget()">Save Budget</button>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
  // DATA
  const STORAGE_KEY = 'spendly_txns';
  const BUDGET_KEY = 'spendly_budgets';

  let transactions = JSON.parse(localStorage.getItem(STORAGE_KEY) || '[]');
  let budgets = JSON.parse(localStorage.getItem(BUDGET_KEY) || '{}');
  let currentType = 'income';
  let txnFilter = 'all';
  let chartFilter = '6m';

  // Sample data if empty
  if (transactions.length === 0) {
    const today = new Date();
    const fmt = (d) => d.toISOString().split('T')[0];
    const d = (days) => { const x = new Date(today); x.setDate(x.getDate()-days); return fmt(x); };
    transactions = [
      { id: 1, desc: 'Monthly Salary', amount: 45000, type: 'income', cat: 'Salary', date: d(2) },
      { id: 2, desc: 'Groceries', amount: 2800, type: 'expense', cat: 'Food', date: d(3) },
      { id: 3, desc: 'Uber Ride', amount: 350, type: 'expense', cat: 'Transport', date: d(4) },
      { id: 4, desc: 'Netflix', amount: 649, type: 'expense', cat: 'Entertainment', date: d(5) },
      { id: 5, desc: 'Freelance Project', amount: 12000, type: 'income', cat: 'Freelance', date: d(6) },
      { id: 6, desc: 'Electricity Bill', amount: 1800, type: 'expense', cat: 'Bills', date: d(7) },
      { id: 7, desc: 'Zomato Order', amount: 480, type: 'expense', cat: 'Food', date: d(8) },
      { id: 8, desc: 'Amazon Shopping', amount: 3200, type: 'expense', cat: 'Shopping', date: d(10) },
      { id: 9, desc: 'Medical Checkup', amount: 1200, type: 'expense', cat: 'Health', date: d(12) },
      { id: 10, desc: 'Course Subscription', amount: 2999, type: 'expense', cat: 'Education', date: d(14) },
    ];
    localStorage.setItem(STORAGE_KEY, JSON.stringify(transactions));

    budgets = { Food: 5000, Transport: 2000, Shopping: 5000, Entertainment: 2000, Bills: 3000, Education: 4000 };
    localStorage.setItem(BUDGET_KEY, JSON.stringify(budgets));
  }

  // CATEGORY CONFIG
  const catConfig = {
    Salary: { emoji: '💼', color: '#2d6a4f', bg: '#d8f3dc' },
    Freelance: { emoji: '🧑‍💻', color: '#1e40af', bg: '#dbeafe' },
    Food: { emoji: '🍕', color: '#b5830a', bg: '#fef3c7' },
    Transport: { emoji: '🚌', color: '#5b21b6', bg: '#ede9fe' },
    Shopping: { emoji: '🛒', color: '#be185d', bg: '#fce7f3' },
    Entertainment: { emoji: '🎮', color: '#065f46', bg: '#d1fae5' },
    Health: { emoji: '❤️', color: '#c1121f', bg: '#fde8ea' },
    Bills: { emoji: '🏠', color: '#92400e', bg: '#fef3c7' },
    Education: { emoji: '📚', color: '#1e40af', bg: '#dbeafe' },
    Other: { emoji: '📦', color: '#374151', bg: '#f3f4f6' },
  };

  const donutColors = ['#e76f51','#2a9d8f','#264653','#e9c46a','#f4a261','#457b9d','#1d3557','#a8dadc'];

  // HELPERS
  function fmt(n) { return '₹' + Math.round(n).toLocaleString('en-IN'); }
  function save() { localStorage.setItem(STORAGE_KEY, JSON.stringify(transactions)); }
  function saveBudgets() { localStorage.setItem(BUDGET_KEY, JSON.stringify(budgets)); }

  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg; t.classList.add('show');
    setTimeout(() => t.classList.remove('show'), 2500);
  }

  // NAV
  function showPage(name, el) {
    document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
    document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));
    document.getElementById('page-' + name).classList.add('active');
    if (el) el.classList.add('active');
    render();
  }

  // MODAL
  function openModal() {
    document.getElementById('txn-date').value = new Date().toISOString().split('T')[0];
    document.getElementById('modal').classList.add('open');
  }
  function closeModal() { document.getElementById('modal').classList.remove('open'); }
  function openBudgetModal() { document.getElementById('budget-modal').classList.add('open'); }
  function closeBudgetModal() { document.getElementById('budget-modal').classList.remove('open'); }

  function setType(t) {
    currentType = t;
    document.getElementById('type-income').classList.toggle('active', t === 'income');
    document.getElementById('type-expense').classList.toggle('active', t === 'expense');
    const cat = document.getElementById('txn-cat');
    if (t === 'income') {
      cat.value = 'Salary';
    } else {
      cat.value = 'Food';
    }
  }

  function addTransaction() {
    const desc = document.getElementById('txn-desc').value.trim();
    const amount = parseFloat(document.getElementById('txn-amount').value);
    const cat = document.getElementById('txn-cat').value;
    const date = document.getElementById('txn-date').value;
    if (!desc || !amount || amount <= 0 || !date) { showToast('⚠️ Please fill all fields'); return; }
    transactions.unshift({ id: Date.now(), desc, amount, type: currentType, cat, date });
    save(); closeModal(); render();
    document.getElementById('txn-desc').value = '';
    document.getElementById('txn-amount').value = '';
    showToast('✅ Transaction added!');
  }

  function deleteTransaction(id) {
    transactions = transactions.filter(t => t.id !== id);
    save(); render();
    showToast('🗑️ Transaction deleted');
  }

  function saveBudget() {
    const cat = document.getElementById('budget-cat').value;
    const amount = parseFloat(document.getElementById('budget-amount').value);
    if (!amount || amount <= 0) { showToast('⚠️ Enter a valid amount'); return; }
    budgets[cat] = amount;
    saveBudgets(); closeBudgetModal(); render();
    document.getElementById('budget-amount').value = '';
    showToast('✅ Budget saved!');
  }

  function filterTxns(f, el) {
    txnFilter = f;
    document.querySelectorAll('.txn-filter').forEach(b => b.classList.remove('active'));
    el.classList.add('active');
    renderAllTxns();
  }

  function setChartFilter(f, el) {
    chartFilter = f;
    document.querySelectorAll('.filter-tab').forEach(b => b.classList.remove('active'));
    el.classList.add('active');
    renderBarChart();
  }

  // RENDER TRANSACTION ITEM
  function txnHTML(t, idx) {
    const cc = catConfig[t.cat] || catConfig.Other;
    const isCredit = t.type === 'income';
    const d = new Date(t.date);
    const dateStr = d.toLocaleDateString('en-IN', { day: 'numeric', month: 'short', year: 'numeric' });
    return `
      <div class="txn-item" style="animation-delay:${idx * 0.04}s">
        <div class="txn-emoji" style="background:${cc.bg}">${cc.emoji}</div>
        <div class="txn-info">
          <div class="txn-name">${t.desc}</div>
          <div class="txn-date">${dateStr}</div>
        </div>
        <span class="txn-cat" style="background:${cc.bg};color:${cc.color}">${t.cat}</span>
        <div class="txn-amount ${isCredit ? 'credit' : 'debit'}">${isCredit ? '+' : '-'}${fmt(t.amount)}</div>
        <div class="txn-actions">
          <button class="txn-del" onclick="deleteTransaction(${t.id})" title="Delete">✕</button>
        </div>
      </div>`;
  }

  // RENDER ALL
  function render() {
    const income = transactions.filter(t => t.type === 'income').reduce((s, t) => s + t.amount, 0);
    const expense = transactions.filter(t => t.type === 'expense').reduce((s, t) => s + t.amount, 0);
    const balance = income - expense;
    const savingsRate = income > 0 ? Math.round((balance / income) * 100) : 0;

    // Sidebar
    document.getElementById('sidebar-balance').textContent = fmt(balance);
    document.getElementById('sidebar-balance-sub').textContent = balance >= 0 ? '✅ You\'re in the green!' : '⚠️ Overspending';

    // Stats
    document.getElementById('total-income').textContent = fmt(income);
    document.getElementById('total-expense').textContent = fmt(expense);
    document.getElementById('savings-rate').textContent = savingsRate + '%';
    document.getElementById('income-count').textContent = transactions.filter(t => t.type === 'income').length + ' transactions';
    document.getElementById('expense-count').textContent = transactions.filter(t => t.type === 'expense').length + ' transactions';

    renderBarChart();
    renderDonut();
    renderRecentTxns();
    renderAllTxns();
    renderBudget();
  }

  function renderBarChart() {
    const months = chartFilter === '6m' ? 6 : 3;
    const data = [];
    const now = new Date();
    for (let i = months - 1; i >= 0; i--) {
      const d = new Date(now.getFullYear(), now.getMonth() - i, 1);
      const m = d.getMonth(); const y = d.getFullYear();
      const inc = transactions.filter(t => { const td = new Date(t.date); return td.getMonth() === m && td.getFullYear() === y && t.type === 'income'; }).reduce((s,t) => s+t.amount, 0);
      const exp = transactions.filter(t => { const td = new Date(t.date); return td.getMonth() === m && td.getFullYear() === y && t.type === 'expense'; }).reduce((s,t) => s+t.amount, 0);
      data.push({ month: d.toLocaleDateString('en-IN', { month: 'short' }), inc, exp });
    }
    const maxVal = Math.max(...data.map(d => Math.max(d.inc, d.exp)), 1);
    const chart = document.getElementById('bar-chart');
    chart.innerHTML = data.map(d => `
      <div class="bar-wrap">
        <div class="bar-col">
          <div class="bar income-bar" style="height:${Math.round((d.inc/maxVal)*140)}px" title="Income: ${fmt(d.inc)}"></div>
          <div class="bar expense-bar" style="height:${Math.round((d.exp/maxVal)*140)}px" title="Expense: ${fmt(d.exp)}"></div>
        </div>
        <div class="bar-month">${d.month}</div>
      </div>
    `).join('');
  }

  function renderDonut() {
    const expenses = transactions.filter(t => t.type === 'expense');
    const total = expenses.reduce((s,t) => s + t.amount, 0);
    const bycat = {};
    expenses.forEach(t => { bycat[t.cat] = (bycat[t.cat] || 0) + t.amount; });
    const cats = Object.entries(bycat).sort((a,b) => b[1]-a[1]);

    document.getElementById('donut-center-val').textContent = fmt(total);
    const svg = document.getElementById('donut-svg');
    const cx = 65, cy = 65, r = 50, strokeW = 18;
    let offset = 0;
    const circ = 2 * Math.PI * r;

    if (cats.length === 0) {
      svg.innerHTML = `<circle cx="${cx}" cy="${cy}" r="${r}" fill="none" stroke="#f0ece6" stroke-width="${strokeW}"/>`;
      document.getElementById('donut-legend').innerHTML = '<div class="empty"><div class="empty-icon">🍩</div><p>Add expenses to see breakdown</p></div>';
      return;
    }

    let svgHtml = `<circle cx="${cx}" cy="${cy}" r="${r}" fill="none" stroke="#f0ece6" stroke-width="${strokeW}"/>`;
    cats.forEach(([ cat, val ], i) => {
      const pct = val / total;
      const dash = circ * pct;
      const color = donutColors[i % donutColors.length];
      svgHtml += `<circle cx="${cx}" cy="${cy}" r="${r}" fill="none" stroke="${color}" stroke-width="${strokeW}" stroke-dasharray="${dash} ${circ - dash}" stroke-dashoffset="${-offset}" stroke-linecap="round"/>`;
      offset += dash;
    });
    svg.innerHTML = svgHtml;

    document.getElementById('donut-legend').innerHTML = cats.slice(0,5).map(([cat, val], i) => {
      const cc = catConfig[cat] || catConfig.Other;
      const pct = Math.round((val/total)*100);
      return `<div class="legend-item">
        <span class="legend-name"><span class="legend-dot" style="background:${donutColors[i%donutColors.length]}"></span>${cc.emoji} ${cat}</span>
        <span class="legend-pct">${pct}%</span>
      </div>`;
    }).join('');
  }

  function renderRecentTxns() {
    const el = document.getElementById('recent-list');
    const recent = transactions.slice(0, 5);
    el.innerHTML = recent.length ? recent.map((t, i) => txnHTML(t, i)).join('') :
      '<div class="empty"><div class="empty-icon">📭</div><p>No transactions yet. Add your first one!</p></div>';
  }

  function renderAllTxns() {
    const el = document.getElementById('all-txn-list');
    let filtered = [...transactions];
    if (txnFilter === 'income') filtered = filtered.filter(t => t.type === 'income');
    else if (txnFilter === 'expense') filtered = filtered.filter(t => t.type === 'expense');
    else if (txnFilter !== 'all') filtered = filtered.filter(t => t.cat === txnFilter);
    filtered.sort((a,b) => new Date(b.date) - new Date(a.date));
    el.innerHTML = filtered.length ? filtered.map((t, i) => txnHTML(t, i)).join('') :
      '<div class="empty"><div class="empty-icon">🔍</div><p>No transactions found for this filter</p></div>';
  }

  function renderBudget() {
    const el = document.getElementById('budget-grid');
    const expByCat = {};
    transactions.filter(t => t.type === 'expense').forEach(t => {
      expByCat[t.cat] = (expByCat[t.cat] || 0) + t.amount;
    });
    const entries = Object.entries(budgets);
    if (entries.length === 0) {
      el.innerHTML = '<div class="empty" style="grid-column:1/-1"><div class="empty-icon">🎯</div><p>Set budget limits to track your spending</p></div>';
      return;
    }
    el.innerHTML = entries.map(([cat, budget], i) => {
      const spent = expByCat[cat] || 0;
      const pct = Math.min(Math.round((spent / budget) * 100), 100);
      const cc = catConfig[cat] || catConfig.Other;
      const over = spent > budget;
      const fillColor = over ? '#c1121f' : pct > 75 ? '#b5830a' : '#2d6a4f';
      return `
        <div class="budget-card" style="animation-delay:${i*0.06}s">
          <div class="budget-header">
            <span class="budget-emoji">${cc.emoji}</span>
            <span class="budget-cat">${cat}</span>
            ${over ? '<span style="font-size:0.7rem;background:#fde8ea;color:#c1121f;padding:3px 8px;border-radius:6px;font-weight:600;margin-left:auto">Over!</span>' : ''}
          </div>
          <div class="budget-amounts">
            <span>Spent: <strong>${fmt(spent)}</strong></span>
            <span>Limit: ${fmt(budget)}</span>
          </div>
          <div class="budget-bar-wrap">
            <div class="budget-bar-fill" style="width:${pct}%;background:${fillColor}"></div>
          </div>
          <div class="budget-pct">${pct}% used</div>
        </div>`;
    }).join('');
  }

  // Close modal on overlay click
  document.getElementById('modal').addEventListener('click', function(e) {
    if (e.target === this) closeModal();
  });
  document.getElementById('budget-modal').addEventListener('click', function(e) {
    if (e.target === this) closeBudgetModal();
  });

  // INIT
  render();
</script>
</body>
</html>
