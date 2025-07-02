<h1>WP Query Analyzer Lite</h1>

<p><strong>WP Query Analyzer Lite</strong> is a lightweight and simple WordPress plugin that lets you monitor all SQL queries executed during a page load in real time.</p>
<p>The plugin highlights duplicate queries, allows filtering queries based on duration (in microseconds), enables exporting the full log as JSON, and includes a toggleable front-end panel visible only to administrators.</p>

<h2>Key Features</h2>
<ul>
  <li>Displays SQL queries with execution times in seconds</li>
  <li>Automatically highlights duplicate queries</li>
  <li>Dynamic filter to show only queries exceeding a customizable threshold (in microseconds)</li>
  <li>Export all queries to JSON for external analysis</li>
  <li>Discreet front-end panel with show/hide toggle</li>
  <li>Works only for users with admin permissions and only if <code>SAVEQUERIES</code> is enabled in WordPress</li>
</ul>

<h2>Installation</h2>
<ol>
  <li>Copy the plugin files into <code>/wp-content/plugins/wp-query-analyzer-lite/</code></li>
  <li>Activate the plugin from the WordPress dashboard</li>
  <li>Make sure to add <code>define('SAVEQUERIES', true);</code> in your <code>wp-config.php</code> file</li>
  <li>Log in as an administrator to see the panel at the bottom right of the frontend</li>
</ol>

<img src="https://github.com/Cata-Giu/wp-query-analyzer/blob/abda311e7da6dd6f9cba2ef6f30f422ee88b0305/PluginQuery%20Images/Screenshot%202025-07-02%20184745.png?raw=true" alt="Dashboard Screenshot" width="500"/>

<img src="https://github.com/Cata-Giu/wp-query-analyzer/blob/abda311e7da6dd6f9cba2ef6f30f422ee88b0305/PluginQuery%20Images/Screenshot%202025-07-02%20184820.png?raw=true" alt="Dashboard Screenshot" width="500"/>

<img src="https://github.com/Cata-Giu/wp-query-analyzer/blob/abda311e7da6dd6f9cba2ef6f30f422ee88b0305/PluginQuery%20Images/Screenshot%202025-07-02%20184839.png?raw=true" alt="Dashboard Screenshot" width="500"/>

<img src="https://github.com/Cata-Giu/wp-query-analyzer/blob/abda311e7da6dd6f9cba2ef6f30f422ee88b0305/PluginQuery%20Images/Screenshot%202025-07-02%20184924.png?raw=true" alt="Dashboard Screenshot" width="500"/>
