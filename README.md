<h1>What</h1>
<p><b>InterviewLogger</b> is an HTML-based app for logging video interviews with timecode. It can export those logs as markers for Premiere Pro, synced with your video file.</p>

<h1>Why</h1>
<p><b>It saves you time</b> by letting you quickly see where the best quotes are, so you don’t have to rewatch the entire interview.</p>

<br>

<img width="1911" height="1060" alt="Interview Logger screenshot" src="https://github.com/user-attachments/assets/0c0f4b3f-290c-4c17-9063-d622a4c95ac6" />

<h1>How</h1> 
<ol>
  <li>Set your camera’s timecode to free-run (time of day). If your camera doesn’t support timecode, just make sure its time and date are correct.</li>
  <li>Open <b>InterviewLogger</b> in your browser.</li>
  <li>Enter the interviewee’s name in the top text box.</li>
  <li>Use shortcuts to make marks:<br>
    &nbsp;&nbsp;+ → Good (green marker)<br>
    &nbsp;&nbsp;- → Bad (red marker)<br>
    &nbsp;&nbsp;* → Great (yellow marker)<br>
    &nbsp;&nbsp;Type a note → Custom (blue marker)
    &nbsp;&nbsp;Double click notes to edit them
  </li>
  <li>Export your log to a CSV file.</li>
  <li>Convert the CSV to a Premiere Pro XML using the <a href="https://editingtools.io/marker/" target="_blank">Editing Tools Marker Converter</a> with the following settings:</li>
</ol>

<img width="704" height="208" alt="EditingTools marker conversion settings" src="https://github.com/user-attachments/assets/6d410bb2-4f81-4f35-9a56-0f82ae26b7b6" />

<ul>
  <li>Convert from: CSV</li>
  <li>Convert to: Premiere Pro XML</li>
  <li>Set the same frame rate you used in-camera</li>
  <li>Click <b>Generate</b>, then download the XML file</li>
  <li>(Optional) In “More Options,” set the start time to match your video file’s starting timecode</li>
</ul>

<ol start="7">
  <li>Import the XML into Premiere Pro.</li>
  <li>Align your video footage to the timeline created by the XML (based on timecode).</li>
</ol>

<img width="427" height="300" alt="Premiere Pro timecode sync" src="https://github.com/user-attachments/assets/c0757f4b-5a54-410b-9007-8c0751ec6b89" />
<h2>Extra Info</h2>
<ul>
  <li>It may work with other editing software, but this hasn’t been tested, if you test this and it works, let me know</li>
  <li>The app is mobile-friendly — keyboard shortcuts automatically change into on-screen buttons.</li>
  <li>Since it’s a self-hosted HTML app, it works offline.</li>
</ul>
