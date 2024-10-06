
<body>
<h1>Nmap Tutorial: Network Scanning and Exploration</h1>

<h2>Introduction</h2>
<p>Nmap (Network Mapper) is a powerful open-source tool for network scanning and exploration. This tutorial will guide you through Nmap's basic and advanced features.</p>

<h2>Installation</h2>
<p>Nmap is available for Windows, Linux, and macOS. Download and install from <a href="https://nmap.org/download.html">nmap.org</a>.</p>

<h2>Basic Scanning</h2>
<h3>1. Simple Scan</h3>
<code>nmap target_IP</code>
<p>* Replace <code>target_IP</code> with the IP address or hostname.</p>

<h3>2. Scan Specific Ports</h3>
<code>nmap -p port_range target_IP</code>
<p>* <code>-p</code> specifies port range (e.g., 1-100, 80, 443).</p>

<h3>3. Scan Types</h3>
<p>* <code>-sT</code> TCP Connect Scan</p>
<p>* <code>-sS</code> SYN Scan (Stealthy)</p>
<p>* <code>-sU</code> UDP Scan</p>
<code>nmap -sS -p 80 target_IP</code>

<h2>Advanced Scanning</h2>
<h3>1. OS Detection</h3>
<code>nmap -O target_IP</code>

<h3>2. Service Version Detection</h3>
<code>nmap -sV target_IP</code>

<h3>3. Script Scanning</h3>
<code>nmap --script script_name target_IP</code>
<p>* Available scripts: <code>nmap --script-help</code>.</p>

<h2>Additional Options</h2>
<h3>1. Scan Speed</h3>
<p>* <code>-T</code> Set timing template (0-5)</p>
<p>* <code>-T4</code> Fast scan</p>

<h3>2. Output Formats</h3>
<p>* <code>-oN</code> Normal output</p>
<p>* <code>-oX</code> XML output</p>
<p>* <code>-oG</code> Grepable output</p>
<code>nmap -oN output.txt target_IP</code>

<h2>Tips and Precautions</h2>
<p>* Obtain permission before scanning</p>
<p>* Use Nmap responsibly</p>
<p>* Avoid scanning critical infrastructure</p>

<h2>Conclusion</h2>
<p>Nmap is a powerful tool for network exploration and security auditing.</p>

<h2>Additional Resources</h2>
<p>* Nmap documentation: <a href="https://nmap.org/docs.html">nmap.org</a></p>
<p>* Nmap script repository: <a href="https://nmap.org/nsedoc">nmap.org</a></p>

<p>Written by: M. Hamza Sufyan</p>
<p>Edited by: Meta AI</p>
</body>
</html>
