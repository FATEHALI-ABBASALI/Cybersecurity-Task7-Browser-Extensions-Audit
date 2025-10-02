<h1>🌐 Task 7 — Browser Extensions Audit 🔍</h1>

<table>
  <tr>
    <td>
<h3>🎯 Objective</h3>
<p>Identify and remove suspicious browser extensions.</p>
    </td>
    </tr>
  <tr>
    <td>
<h3>💻 Browser tested</h3>
<p>Google Chrome</p>
</td>
</tr>
</table>

<h3>📝 Summary</h3>
<p>I audited installed extensions, examined permissions and store information, removed suspicious items, and documented evidence.</p>

<h3>📦 What I included in this package</h3>
<table>
  <tr>
    <td><p>📄 <strong>README.md</strong> — overview and instructions</p></td>
  </tr>
  <tr>
    <td><p>🌍 <strong>report.html</strong> — human-friendly HTML report</p></td>
  </tr>
  <tr>
    <td><p>🖨️ <strong>report.pdf</strong> — printable PDF report</p></td>
  </tr>
  <tr>
    <td><p>⚠️ <strong>suspicious-extensions.csv</strong> — CSV table of flagged extensions</p></td>
  </tr>
  <tr>
    <td><p>🖼️ <strong>evidence/</strong> — place screenshots here (placeholders provided)</p></td>
  </tr>
  <tr>
    <td><p>🗒️ <strong>analysis/notes.md</strong> — short analysis notes</p></td>
  </tr>
</table>

<h3>🔧 Steps performed (detailed)</h3>
<pre>1️⃣ Opened chrome://extensions/ and captured a before screenshot (evidence/01_extensions_list_before.png).
2️⃣ Inspected each extension details: permissions, developer, store page, reviews, last update.
3️⃣ Flagged and removed suspicious extensions (see suspicious-extensions.csv).
4️⃣ Cleared cache, restarted browser, scanned system for malware.
5️⃣ Captured after screenshot (evidence/03_extensions_list_after.png) and saved manifest snippets in analysis/.
</pre>

<h3>🖼️ How to add your screenshots</h3>
<pre>📂 Save screenshots as PNG inside the evidence/ folder.
   - 01_extensions_list_before.png — initial full list of extensions
   - 02_removed_<name>.png — screenshot after removing an extension
   - 03_extensions_list_after.png — final state
📌 Commit and push to your repository.
</pre>

<h3>🚀 How to use this repo</h3>
<pre>✅ Replace placeholder CSV rows with real data gathered during your audit.
✅ Add real screenshots to evidence/.
✅ Update analysis/notes.md with findings and manifest snippets.
✅ Push to GitHub and provide the link on the submission form.
</pre>
