<h1>What</h1>
<b>InterviewLogger is an HTML based app for logging video interviews with timecode, capable of exportinging those logs as markings into premiere pro synced with the video file.</b>
<h1>Why</h1>
<b>Saves you time from having to rewatch the entire interview by marking where the good quotes are.</b><br><br>

<img width="1911" height="1060" alt="logger2" src="https://github.com/user-attachments/assets/0c0f4b3f-290c-4c17-9063-d622a4c95ac6" />


<h1>How</h1> 
1. Set timecode of camera to free run time of day (or just make sure your time/date settings are correct if your camera doesn't have timecode) <br>
2. Open InterviewLogger on browser<br>
3. Enter name of interviewee's in top textbox<br>
4. Use shortcuts to make marks:<br>
   "+" for good (green marker)<br>
   "-" for bad (red marker)<br>
   "*" for great (yellow marker)<br>
   Type notes for manual marks (blue marker)<br>
7. Export to csv<br>
8. Convert using <a href="https://editingtools.io/marker/">editingtools</a>  site using following settings:<br>
   
<img width="704" height="208" alt="marker" src="https://github.com/user-attachments/assets/6d410bb2-4f81-4f35-9a56-0f82ae26b7b6" />

   - convert from csv<br>
   - conver to premiere pro XML<br>
   - Set the framerate you used in camera<br>
   - Press Generate, then download the XML<br>
     (Optional) in more options set start time to start timecode of your video file
10. Import xml into Premiere Pro
11. Set video footage to timecode on timeline created by xml<br>
<img width="427" height="300" alt="snip" src="https://github.com/user-attachments/assets/c0757f4b-5a54-410b-9007-8c0751ec6b89" />

