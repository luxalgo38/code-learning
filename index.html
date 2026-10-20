<!DOCTYPE html>
<html lang="si">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>lib/database.js — README + Copy Code</title>

<link rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/styles/atom-one-dark.min.css" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.9.0/highlight.min.js"></script>

<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background: #0d1117;
    color: #c9d1d9;
    line-height: 1.7;
    padding: 20px 16px 60px;
  }

  .wrap {
    max-width: 980px;
    margin: 0 auto;
  }

  /* ============ TOP MAIN CODE CARD ============ */
  .main-card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 14px;
    overflow: hidden;
    margin-bottom: 40px;
    box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
  }

  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 14px 20px;
    background: #0d1117;
    border-bottom: 1px solid #30363d;
  }

  .header-left { display: flex; align-items: center; gap: 10px; }

  .dots { display: flex; gap: 6px; }
  .dot { width: 12px; height: 12px; border-radius: 50%; }
  .dot.red { background: #ff5f56; }
  .dot.yellow { background: #ffbd2e; }
  .dot.green { background: #27c93f; }

  .filename {
    font-family: 'Consolas', monospace;
    font-size: 14px;
    color: #8b949e;
    margin-left: 10px;
  }

  .copy-btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    background: #238636;
    color: #fff;
    border: none;
    padding: 9px 16px;
    border-radius: 8px;
    font-size: 13px;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.2s ease;
    font-family: inherit;
  }
  .copy-btn:hover { background: #2ea043; transform: translateY(-1px); }
  .copy-btn:active { transform: translateY(0); }
  .copy-btn.copied { background: #1f6feb; }
  .copy-btn svg { width: 16px; height: 16px; }

  .code-wrap {
    max-height: 70vh;
    overflow: auto;
  }

  pre {
    margin: 0;
    padding: 20px 24px;
    background: transparent !important;
    font-family: 'Consolas', 'Monaco', 'Courier New', monospace;
    font-size: 14px;
    line-height: 1.65;
    overflow-x: auto;
  }

  code.hljs {
    background: transparent !important;
    padding: 0 !important;
  }

  /* Scrollbars */
  .code-wrap::-webkit-scrollbar,
  pre::-webkit-scrollbar { width: 10px; height: 10px; }
  .code-wrap::-webkit-scrollbar-track,
  pre::-webkit-scrollbar-track { background: #0d1117; }
  .code-wrap::-webkit-scrollbar-thumb,
  pre::-webkit-scrollbar-thumb { background: #30363d; border-radius: 5px; }
  .code-wrap::-webkit-scrollbar-thumb:hover,
  pre::-webkit-scrollbar-thumb:hover { background: #484f58; }

  /* ============ README CONTENT ============ */
  .readme {
    background: #0d1117;
    border: 1px solid #30363d;
    border-radius: 14px;
    padding: 32px 36px 40px;
  }

  .readme h1 {
    font-size: 28px;
    color: #f0f6fc;
    padding-bottom: 14px;
    border-bottom: 1px solid #30363d;
    margin-bottom: 20px;
  }

  .readme h2 {
    font-size: 22px;
    color: #f0f6fc;
    margin-top: 40px;
    margin-bottom: 16px;
    padding-bottom: 10px;
    border-bottom: 1px solid #21262d;
  }

  .readme h3 {
    font-size: 17px;
    color: #f0f6fc;
    margin-top: 26px;
    margin-bottom: 12px;
  }

  .readme p {
    margin: 12px 0;
    font-size: 15px;
    color: #c9d1d9;
  }

  .readme blockquote {
    border-left: 4px solid #1f6feb;
    background: #161b22;
    padding: 12px 18px;
    margin: 16px 0;
    border-radius: 0 8px 8px 0;
    color: #8b949e;
    font-size: 14px;
  }

  .readme ul, .readme ol {
    margin: 12px 0 12px 24px;
    font-size: 15px;
  }

  .readme li { margin: 6px 0; }

  .readme a {
    color: #58a6ff;
    text-decoration: none;
  }
  .readme a:hover { text-decoration: underline; }

  .readme hr {
    border: none;
    border-top: 1px solid #30363d;
    margin: 30px 0;
  }

  .readme code:not(.hljs) {
    background: #161b22;
    padding: 2px 6px;
    border-radius: 4px;
    font-family: 'Consolas', monospace;
    font-size: 0.9em;
    color: #ff7b72;
  }

  /* Code block inside README */
  .code-block {
    position: relative;
    margin: 16px 0;
    border-radius: 10px;
    overflow: hidden;
    background: #161b22;
    border: 1px solid #30363d;
  }

  .code-block pre {
    padding: 16px 60px 16px 20px;
    font-size: 13.5px;
    max-height: 500px;
    overflow: auto;
  }

  .copy-mini {
    position: absolute;
    top: 8px;
    right: 8px;
    background: #21262d;
    color: #c9d1d9;
    border: 1px solid #30363d;
    padding: 5px 10px;
    border-radius: 6px;
    font-size: 11px;
    cursor: pointer;
    font-family: inherit;
    display: inline-flex;
    align-items: center;
    gap: 5px;
    transition: 0.2s;
    z-index: 2;
  }
  .copy-mini:hover { background: #30363d; color: #fff; }
  .copy-mini.copied { background: #1f6feb; color: #fff; border-color: #1f6feb; }
  .copy-mini svg { width: 12px; height: 12px; }

  /* Tables */
  .readme table {
    width: 100%;
    border-collapse: collapse;
    margin: 16px 0;
    font-size: 14px;
    background: #161b22;
    border-radius: 8px;
    overflow: hidden;
  }

  .readme th {
    background: #21262d;
    color: #f0f6fc;
    padding: 10px 14px;
    text-align: left;
    border: 1px solid #30363d;
    font-weight: 600;
  }

  .readme td {
    padding: 9px 14px;
    border: 1px solid #30363d;
  }

  .readme tr:hover td { background: #1c2128; }

  /* Toast */
  .toast {
    position: fixed;
    bottom: 30px;
    left: 50%;
    transform: translateX(-50%) translateY(100px);
    background: #238636;
    color: #fff;
    padding: 12px 24px;
    border-radius: 10px;
    font-size: 14px;
    font-weight: 600;
    box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    opacity: 0;
    transition: all 0.3s ease;
    pointer-events: none;
    z-index: 9999;
  }
  .toast.show {
    transform: translateX(-50%) translateY(0);
    opacity: 1;
  }

  @media (max-width: 640px) {
    body { padding: 12px 8px 40px; }
    .readme { padding: 20px 16px 28px; }
    .readme h1 { font-size: 22px; }
    .readme h2 { font-size: 18px; }
    .readme h3 { font-size: 15px; }
    .readme table { font-size: 12px; }
    .readme th, .readme td { padding: 6px 8px; }
  }
</style>
</head>
<body>

<div class="wrap">

  <!-- ============ MAIN CODE CARD ============ -->
  <div class="main-card">
    <div class="header">
      <div class="header-left">
        <div class="dots">
          <span class="dot red"></span>
          <span class="dot yellow"></span>
          <span class="dot green"></span>
        </div>
        <span class="filename">lib/database.js</span>
      </div>
      <button class="copy-btn" id="copyMainBtn">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
             stroke-linecap="round" stroke-linejoin="round">
          <rect x="9" y="9" width="13" height="13" rx="2" ry="2"></rect>
          <path d="M5 15H4a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v1"></path>
        </svg>
        <span id="mainBtnText">Copy Full Code</span>
      </button>
    </div>
    <div class="code-wrap">
<pre><code class="language-javascript" id="mainCode">const Sequelize = require('sequelize');

class DatabaseManager {
    static instance = null;

    static getInstance() {
        if (!DatabaseManager.instance) {
            const DATABASE_URL = process.env.DATABASE_URL || './database.db';

            DatabaseManager.instance =
                DATABASE_URL === './database.db'
                    ? new Sequelize({
                            dialect: 'sqlite',
                            storage: DATABASE_URL,
                            logging: false,
                      })
                    : new Sequelize(DATABASE_URL, {
                            dialect: 'postgres',
                            ssl: true,
                            protocol: 'postgres',
                            dialectOptions: {
                                native: true,
                                ssl: { require: true, rejectUnauthorized: false },
                            },
                            logging: false,
                      });
        }
        return DatabaseManager.instance;
    }
}

const DATABASE = DatabaseManager.getInstance();

DATABASE.sync()
    .then(() => {
        console.log('Database synchronized successfully.');
    })
    .catch((error) => {
        console.error('Error synchronizing the database:', error);
    });

module.exports = { DATABASE };</code></pre>
    </div>
  </div>

  <!-- ============ README CONTENT ============ -->
  <div class="readme">

    <h1>📘 lib/database.js — Sequelize Database Connection</h1>

    <blockquote>
      <strong>Bot එකේ database connection එක setup කරන module එක.</strong>
      Sequelize ORM පාවිච්චි කරලා SQLite (local) හෝ Postgres (cloud) database එකකට
      connect වෙනවා. Singleton pattern එකෙන් එකම connection එක විතරයි හදන්නේ.
    </blockquote>

    <hr />

    <h2 id="toc">📑 Table of Contents</h2>
    <ul>
      <li><a href="#overview">Overview</a></li>
      <li><a href="#features">Features</a></li>
      <li><a href="#source">Full Source Code</a></li>
      <li><a href="#explanation">Line-by-Line Explanation</a></li>
      <li><a href="#flow">How It Works</a></li>
      <li><a href="#config">Configuration</a></li>
      <li><a href="#install">Installation</a></li>
      <li><a href="#usage">Usage Examples</a></li>
      <li><a href="#compare">SQLite vs Postgres</a></li>
      <li><a href="#issues">Common Issues</a></li>
      <li><a href="#best">Best Practices</a></li>
    </ul>

    <hr />

    <h2 id="overview">🎯 Overview</h2>
    <p><code>lib/database.js</code> එක bot එකේ <strong>database layer</strong> එකේ පදනම. මේකෙන්:</p>
    <ol>
      <li><strong>Connection එකක් හදනවා</strong> — SQLite හෝ Postgres (env var එකෙන් තීරණය)</li>
      <li><strong>Singleton pattern</strong> — එකම connection එක විතරයි, memory leak නෑ</li>
      <li><strong>Tables sync කරනවා</strong> — Models define කරලා තිබ්බොත් auto-create</li>
      <li><strong>Export කරනවා</strong> — අනිත් files වලට <code>DATABASE</code> object එක දෙනවා</li>
    </ol>

    <h2 id="features">✨ Features</h2>
    <table>
      <thead>
        <tr><th>Feature</th><th>විස්තරය</th></tr>
      </thead>
      <tbody>
        <tr><td>🗄️ Dual database support</td><td>SQLite (local file) සහ Postgres (cloud)</td></tr>
        <tr><td>🔒 Singleton pattern</td><td>එකම connection instance එක</td></tr>
        <tr><td>⚙️ Environment-based config</td><td><code>DATABASE_URL</code> env var එකෙන් switch</td></tr>
        <tr><td>🌐 SSL support</td><td>Cloud DB වලට (Neon, Supabase, Railway)</td></tr>
        <tr><td>🧹 Silent logging</td><td>Clean console output</td></tr>
        <tr><td>🔄 Auto-sync</td><td>Tables auto-create</td></tr>
      </tbody>
    </table>

    <h2 id="source">📄 Full Source Code</h2>
    <div class="code-block">
      <button class="copy-mini" data-copy="sourceCode">Copy</button>
<pre><code class="language-javascript" id="sourceCode">const Sequelize = require('sequelize');

class DatabaseManager {
    static instance = null;

    static getInstance() {
        if (!DatabaseManager.instance) {
            const DATABASE_URL = process.env.DATABASE_URL || './database.db';

            DatabaseManager.instance =
                DATABASE_URL === './database.db'
                    ? new Sequelize({
                            dialect: 'sqlite',
                            storage: DATABASE_URL,
                            logging: false,
                      })
                    : new Sequelize(DATABASE_URL, {
                            dialect: 'postgres',
                            ssl: true,
                            protocol: 'postgres',
                            dialectOptions: {
                                native: true,
                                ssl: { require: true, rejectUnauthorized: false },
                            },
                            logging: false,
                      });
        }
        return DatabaseManager.instance;
    }
}

const DATABASE = DatabaseManager.getInstance();

DATABASE.sync()
    .then(() => {
        console.log('Database synchronized successfully.');
    })
    .catch((error) => {
        console.error('Error synchronizing the database:', error);
    });

module.exports = { DATABASE };</code></pre>
    </div>

    <h2 id="explanation">🔍 Line-by-Line Explanation</h2>

    <h3>1️⃣ Import Sequelize</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c1">Copy</button>
<pre><code class="language-javascript" id="c1">const Sequelize = require('sequelize');</code></pre>
    </div>
    <p><code>sequelize</code> npm package එක load කරනවා. Sequelize = <strong>Node.js ORM</strong> එකක්.</p>

    <h3>2️⃣ Class Definition</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c2">Copy</button>
<pre><code class="language-javascript" id="c2">class DatabaseManager {
    // ...
}</code></pre>
    </div>

    <h3>3️⃣ Singleton Instance Variable</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c3">Copy</button>
<pre><code class="language-javascript" id="c3">static instance = null;</code></pre>
    </div>
    <table>
      <thead><tr><th>කොටස</th><th>තේරුම</th></tr></thead>
      <tbody>
        <tr><td><code>static</code></td><td>Class එකට අයිති (instance එකට නෙවෙයි)</td></tr>
        <tr><td><code>instance</code></td><td>Connection එක තියෙන variable</td></tr>
        <tr><td><code>= null</code></td><td>මුලින්ම හිස් (connection නෑ)</td></tr>
      </tbody>
    </table>

    <h3>4️⃣ Get Instance Method (හදවත ❤️)</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c4">Copy</button>
<pre><code class="language-javascript" id="c4">static getInstance() {
    if (!DatabaseManager.instance) {
        // ... create connection
    }
    return DatabaseManager.instance;
}</code></pre>
    </div>
    <p><strong>මොකද වෙන්නේ:</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="c4b">Copy</button>
<pre><code class="language-text" id="c4b">Call 1: instance = null  →  !null = true   →  CREATE new connection
Call 2: instance = conn  →  !conn = false  →  SKIP (return same)
Call 3: instance = conn  →  !conn = false  →  SKIP (return same)</code></pre>
    </div>

    <h3>5️⃣ Environment Variable Check</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c5">Copy</button>
<pre><code class="language-javascript" id="c5">const DATABASE_URL = process.env.DATABASE_URL || './database.db';</code></pre>
    </div>
    <table>
      <thead><tr><th>Case</th><th>DATABASE_URL අගය</th><th>Database</th></tr></thead>
      <tbody>
        <tr><td>env var set නෑ</td><td><code>./database.db</code></td><td>SQLite</td></tr>
        <tr><td>env var <code>postgres://...</code></td><td><code>postgres://...</code></td><td>Postgres</td></tr>
      </tbody>
    </table>

    <h3>6️⃣ SQLite Configuration</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c6">Copy</button>
<pre><code class="language-javascript" id="c6">new Sequelize({
    dialect: 'sqlite',
    storage: DATABASE_URL,
    logging: false,
})</code></pre>
    </div>

    <h3>7️⃣ Postgres Configuration</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c7">Copy</button>
<pre><code class="language-javascript" id="c7">new Sequelize(DATABASE_URL, {
    dialect: 'postgres',
    ssl: true,
    protocol: 'postgres',
    dialectOptions: {
        native: true,
        ssl: { require: true, rejectUnauthorized: false },
    },
    logging: false,
})</code></pre>
    </div>

    <h3>8️⃣ Create Singleton Instance</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c8">Copy</button>
<pre><code class="language-javascript" id="c8">const DATABASE = DatabaseManager.getInstance();</code></pre>
    </div>

    <h3>9️⃣ Sync Database</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c9">Copy</button>
<pre><code class="language-javascript" id="c9">DATABASE.sync()
    .then(() => {
        console.log('Database synchronized successfully.');
    })
    .catch((error) => {
        console.error('Error synchronizing the database:', error);
    });</code></pre>
    </div>

    <h3>🔟 Export</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="c10">Copy</button>
<pre><code class="language-javascript" id="c10">module.exports = { DATABASE };</code></pre>
    </div>

    <h2 id="flow">🔄 How It Works — Full Flow</h2>
    <div class="code-block">
      <button class="copy-mini" data-copy="flowCode">Copy</button>
<pre><code class="language-text" id="flowCode">Step 1: node index.js
    ↓
Step 2: index.js → require('./lib/database')
    ↓
Step 3: database.js execute වෙනවා:
    ├── Sequelize import
    ├── DatabaseManager class
    ├── getInstance() call
    │   ├── instance = null → true
    │   ├── DATABASE_URL check
    │   │   ├── env එකේ නෑ → SQLite
    │   │   └── env එකේ තියෙනවා → Postgres
    │   └── new Sequelize(...) → connection
    ├── DATABASE = instance
    ├── DATABASE.sync() start (async)
    └── module.exports = { DATABASE }
    ↓
Step 4: index.js → require('./store')
    ↓
Step 5: store.js → require('./lib/database')
    └── database.js cache එකේ → instance ✅
    └── same DATABASE return (singleton)
    ↓
Step 6: Bot ready ✅</code></pre>
    </div>

    <h2 id="config">⚙️ Configuration</h2>

    <h3>.env File Examples</h3>

    <p><strong>SQLite (Development):</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="env1">Copy</button>
<pre><code class="language-bash" id="env1">DATABASE_URL=./database.db</code></pre>
    </div>

    <p><strong>Postgres — Neon:</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="env2">Copy</button>
<pre><code class="language-bash" id="env2">DATABASE_URL=postgres://user:password@ep-xxx.neon.tech/neondb?sslmode=require</code></pre>
    </div>

    <p><strong>Postgres — Supabase:</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="env3">Copy</button>
<pre><code class="language-bash" id="env3">DATABASE_URL=postgres://postgres:password@db.xxx.supabase.co:5432/postgres</code></pre>
    </div>

    <p><strong>Postgres — Railway:</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="env4">Copy</button>
<pre><code class="language-bash" id="env4">DATABASE_URL=postgresql://postgres:password@containers-us-west-xxx.railway.app:5432/railway</code></pre>
    </div>

    <p><strong>Postgres — Local:</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="env5">Copy</button>
<pre><code class="language-bash" id="env5">DATABASE_URL=postgres://postgres:password@localhost:5432/mydb</code></pre>
    </div>

    <h2 id="install">📦 Installation</h2>

    <p><strong>1. Install dependencies</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="inst1">Copy</button>
<pre><code class="language-bash" id="inst1"># SQLite විතරයි ඕනේ නම්:
npm install sequelize sqlite3

# Postgres ඕනේ නම්:
npm install sequelize sqlite3 pg pg-hstore</code></pre>
    </div>

    <p><strong>2. Folder structure</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="inst2">Copy</button>
<pre><code class="language-text" id="inst2">your-bot/
├── lib/
│   └── database.js        ← මේ file එක
├── store.js
├── index.js
├── .env
├── package.json
└── database.db            ← auto-create (SQLite)</code></pre>
    </div>

    <p><strong>3. Test connection</strong></p>
    <div class="code-block">
      <button class="copy-mini" data-copy="inst3">Copy</button>
<pre><code class="language-javascript" id="inst3">const { DATABASE } = require('./lib/database');

DATABASE.authenticate()
    .then(() => console.log('✅ DB connected'))
    .catch(err => console.error('❌ DB error:', err));</code></pre>
    </div>

    <h2 id="usage">💡 Usage Examples</h2>

    <h3>Example 1 — Model Define කරනවා</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="u1">Copy</button>
<pre><code class="language-javascript" id="u1">const { DATABASE } = require('../lib/database');
const { DataTypes } = require('sequelize');

const Contact = DATABASE.define('Contact', {
    jid:  { type: DataTypes.STRING, primaryKey: true },
    name: { type: DataTypes.STRING, allowNull: true },
});

module.exports = Contact;</code></pre>
    </div>

    <h3>Example 2 — Data Save කරනවා</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="u2">Copy</button>
<pre><code class="language-javascript" id="u2">async function saveContact(jid, name) {
    await Contact.upsert({ jid, name });
}</code></pre>
    </div>

    <h3>Example 3 — Data ගන්නවා</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="u3">Copy</button>
<pre><code class="language-javascript" id="u3">async function getName(jid) {
    const contact = await Contact.findOne({ where: { jid } });
    return contact ? contact.name : jid.split('@')[0];
}</code></pre>
    </div>

    <h3>Example 4 — Transaction</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="u4">Copy</button>
<pre><code class="language-javascript" id="u4">return await DATABASE.transaction(async (t) => {
    await Message.create({ jid: from, ...message }, { transaction: t });
    await Message.create({ jid: to,   ...message }, { transaction: t });
});</code></pre>
    </div>

    <h3>Example 5 — Await Sync (recommended)</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="u5">Copy</button>
<pre><code class="language-javascript" id="u5">async function main() {
    const { DATABASE } = require('./lib/database');
    await DATABASE.sync();
    console.log('Database ready ✅');
    await startBot();
}
main().catch(console.error);</code></pre>
    </div>

    <h2 id="compare">📊 Comparison: SQLite vs Postgres</h2>
    <table>
      <thead>
        <tr><th>Feature</th><th>SQLite</th><th>Postgres</th></tr>
      </thead>
      <tbody>
        <tr><td>Setup</td><td>✅ ලේසි (file)</td><td>⚠️ Server ඕනේ</td></tr>
        <tr><td>Speed (small data)</td><td>✅ Fast</td><td>✅ Fast</td></tr>
        <tr><td>Speed (large data)</td><td>❌ Slow</td><td>✅ Fast</td></tr>
        <tr><td>Concurrent writes</td><td>❌ Weak</td><td>✅ Strong</td></tr>
        <tr><td>Backup</td><td>✅ File copy</td><td>⚠️ pg_dump</td></tr>
        <tr><td>Cost</td><td>✅ Free</td><td>Free tier / Paid</td></tr>
      </tbody>
    </table>

    <h2 id="issues">🐛 Common Issues & Fixes</h2>

    <h3>❌ Issue 1: Please install sqlite3 package manually</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="i1">Copy</button>
<pre><code class="language-bash" id="i1">npm install sqlite3</code></pre>
    </div>

    <h3>❌ Issue 2: Cannot find module 'pg'</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="i2">Copy</button>
<pre><code class="language-bash" id="i2">npm install pg pg-hstore</code></pre>
    </div>

    <h3>❌ Issue 3: Table doesn't exist</h3>
    <p><strong>හේතුව:</strong> <code>sync()</code> await කරලා නෑ</p>
    <div class="code-block">
      <button class="copy-mini" data-copy="i3">Copy</button>
<pre><code class="language-javascript" id="i3">await DATABASE.sync();
// ඊට පස්සේ queries</code></pre>
    </div>

    <h2 id="best">✅ Best Practices</h2>

    <h3>1. sync() await කරන්න</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="b1">Copy</button>
<pre><code class="language-javascript" id="b1">// ❌
DATABASE.sync();

// ✅
await DATABASE.sync();</code></pre>
    </div>

    <h3>2. Absolute path පාවිච්චි කරන්න</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="b2">Copy</button>
<pre><code class="language-javascript" id="b2">// ❌
storage: './database.db'

// ✅
const path = require('path');
storage: path.join(process.cwd(), 'database.db')</code></pre>
    </div>

    <h3>3. .gitignore එකට add කරන්න</h3>
    <div class="code-block">
      <button class="copy-mini" data-copy="b3">Copy</button>
<pre><code class="language-gitignore" id="b3">database.db
database.db-journal
.env
node_modules/</code></pre>
    </div>

    <hr />

    <h2>📋 Summary</h2>
    <blockquote>
      <code>lib/database.js</code> එක Sequelize database connection එකේ <strong>singleton factory</strong> එකක්.
      <code>DATABASE_URL</code> env var එකේ තියෙන අගය අනුව SQLite හෝ Postgres එකට connect වෙනවා.
      <code>getInstance()</code> method එකෙන් එකම connection එක විතරයි හදන්නේ.
      <code>DATABASE.sync()</code> tables auto-create කරනවා.
      Export කරන <code>DATABASE</code> object එකෙන් models define කරන්න, queries දාන්න,
      transactions කරන්න පුළුවන්.
    </blockquote>

    <hr />

    <p style="text-align:center; color:#8b949e; font-size:13px;">
      📚 README — <code>lib/database.js</code> · JawadTechX bot project
    </p>

  </div>
</div>

<!-- Toast -->
<div class="toast" id="toast">✅ Copied to clipboard!</div>

<script>
  // Syntax highlight
  hljs.highlightAll();

  const toast = document.getElementById('toast');

  function showToast(msg) {
    toast.textContent = msg || '✅ Copied to clipboard!';
    toast.classList.add('show');
    clearTimeout(toast._t);
    toast._t = setTimeout(() => toast.classList.remove('show'), 2000);
  }

  async function copyText(text) {
    try {
      await navigator.clipboard.writeText(text);
      return true;
    } catch {
      const ta = document.createElement('textarea');
      ta.value = text;
      ta.style.position = 'fixed';
      ta.style.opacity = '0';
      document.body.appendChild(ta);
      ta.select();
      try { document.execCommand('copy'); } catch {}
      document.body.removeChild(ta);
      return true;
    }
  }

  // Main copy button
  const copyMainBtn = document.getElementById('copyMainBtn');
  const mainBtnText = document.getElementById('mainBtnText');
  const mainCode = document.getElementById('mainCode');

  copyMainBtn.addEventListener('click', async () => {
    await copyText(mainCode.textContent);
    copyMainBtn.classList.add('copied');
    mainBtnText.textContent = 'Copied!';
    showToast('✅ Full database.js copied!');
    setTimeout(() => {
      copyMainBtn.classList.remove('copied');
      mainBtnText.textContent = 'Copy Full Code';
    }, 2000);
  });

  // All mini copy buttons
  document.querySelectorAll('.copy-mini').forEach((btn) => {
    btn.addEventListener('click', async () => {
      const id = btn.getAttribute('data-copy');
      const el = document.getElementById(id);
      if (!el) return;
      await copyText(el.textContent);
      const orig = btn.textContent;
      btn.classList.add('copied');
      btn.textContent = '✅ Copied';
      showToast('✅ Copied!');
      setTimeout(() => {
        btn.classList.remove('copied');
        btn.textContent = orig;
      }, 1500);
    });
  });
</script>

</body>
</html>
