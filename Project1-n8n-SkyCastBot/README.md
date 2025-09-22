<h1 align="center">🌤️ SkyCastBot - Daily Briefing Telegram Bot</h1>

<p align="center">
  <b>A Telegram bot built with <a href="https://n8n.io/">n8n</a> that delivers daily updates on Weather, News, and Stock Market in one simple message.</b>
</p>

---

<h2>📌 Features</h2>

<ul>
  <li>🌦️ <b>Weather Updates</b> - Fetches live weather data using <a href="https://openweathermap.org/api">OpenWeather API</a>.</li>
  <li>📰 <b>Top 5 News Headlines</b> - Uses <a href="https://newsdata.io/">NewsData API</a> to get latest headlines.</li>
  <li>📈 <b>Stock Market Updates</b> - Pulls financial insights from <a href="https://finnhub.io/">Finnhub API</a>.</li>
  <li>🤖 <b>AI Agent</b> - Summarizes & formats updates using Google Gemini Chat Model.</li>
  <li>💬 <b>Telegram Integration</b> - Sends automated daily briefings to your Telegram bot.</li>
</ul>

---

<h2>⚙️ Workflow Overview</h2>

<p align="center">
  <img src="assets/workflow.png" alt="n8n Workflow" width="700"/>
</p>

<p align="center"><i>The n8n workflow integrates APIs, merges data, processes it via AI, and delivers updates to Telegram.</i></p>

---

<h2>📲 Example Output</h2>

<p align="center">
  <img src="assets/output.png" alt="Telegram Bot Output" width="400"/>
</p>

<pre>
Hey there! 👋 Here's your quick daily rundown:

🌞 Weather: Looks like a pleasant day ahead! Expect partly sunny skies with a comfortable 72°F.

📰 Top Headlines:
1. Tech Innovators Unveil New Solutions
2. Global Climate Talks Show Promising Progress
3. Community Event Draws Record Crowds
4. Health & Wellness Experts Share New Tips
5. Sports Update: Key Match Highlights

📊 Stock Watch: A main market indicator is at 245.5, showing a modest increase of 7.62 points today.

✨ Have a fantastic day!
</pre>

---

<h2>🚀 Getting Started</h2>

<ol>
  <li>Clone this repository.</li>
  <li>Import the workflow into your <a href="https://n8n.io/">n8n instance</a>.</li>
  <li>Set up API keys for:
    <ul>
      <li><a href="https://openweathermap.org/">OpenWeather API</a></li>
      <li><a href="https://newsdata.io/">NewsData API</a></li>
      <li><a href="https://finnhub.io/">Finnhub API</a></li>
    </ul>
  </li>
  <li>Connect your <a href="https://core.telegram.org/bots">Telegram Bot</a>.</li>
  <li>Run the workflow manually or schedule it for daily updates.</li>
</ol>

---

<h2>🛠️ Tech Stack</h2>

<ul>
  <li><b>n8n</b> - Automation workflow engine</li>
  <li><b>OpenWeather API</b> - Weather updates</li>
  <li><b>NewsData API</b> - Latest headlines</li>
  <li><b>Finnhub API</b> - Stock market data</li>
  <li><b>Google Gemini</b> - AI-powered text formatting</li>
  <li><b>Telegram Bot</b> - Message delivery</li>
</ul>

---

<h2>📌 Author</h2>
<p>
👩‍💻 Developed by <b>Akshitha Reddy</b><br/>
⭐ If you like this project, don’t forget to star the repo!
</p>
