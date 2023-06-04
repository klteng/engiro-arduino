# engiro-arduino
Repository for Arduino related files and custom board definition.
<p dir="auto">Repository for storing Arduino related files and custom board definition.</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-arduino-ide" class="anchor" aria-hidden="true" href="#arduino-ide"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Arduino IDE</h2>
<p dir="auto">Copy and paste the following URL into the File &gt; Preferences &gt; "Additional Boards Manager" textbox.</p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto" data-snippet-clipboard-copy-content="https://raw.githubusercontent.com/robotics-masters/mm1-hat-arduino/master/custom_board/package_robohat_index.json"><pre class="notranslate"><code>https://raw.githubusercontent.com/robotics-masters/mm1-hat-arduino/master/custom_board/package_robohat_index.json
</code></pre></div>
<p dir="auto">The latest version is 0.0.26</p>
<p dir="auto">Make sure to also install the Arduino SAMD Library at the same time.</p>
<p dir="auto">Boards &gt; "Add board definition" &gt; Search for "Robotics Masters" &gt; Install Robo HAT Library</p>
<p dir="auto">Boards &gt; "Add board definition" &gt; Search for "SAMD" &gt; Install Arduino SAMD Library</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-serial-ports" class="anchor" aria-hidden="true" href="#serial-ports"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Serial Ports</h2>
<p dir="auto">A number of predefined serial ports are in the Robo HAT MM1 M4 boards.</p>
<ul dir="auto">
<li>Serial - USB</li>
<li>Serial1 - Raspberry Pi Serial Ports (SERCOM1)</li>
<li>Serial2 - GPS Serial Port (SERCOM5)</li>
<li>Serial3 - GROVE Serial Port (SERCOM0)</li>
</ul>
