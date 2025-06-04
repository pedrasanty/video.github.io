# video.github.io
Assignment 
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 20px;
  background: #f9f9f9;
  color: #333;
}

h1, h2 {
  color: #2a7ae2;
}

.step {
  margin-bottom: 30px;
  background: white;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 0 8px rgba(0,0,0,0.1);
}

.step img {
  display: block;
  max-width: 400px;
  margin-top: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.video-container {
  margin-top: 40px;
  text-align: center;
}

video {
  max-width: 100%;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
}
3. Create your HTML file
Example: index.html

html
Copiar
Editar
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>How to Embed a Video Tutorial</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <h1>How to Embed a Video on Your Webpage</h1>

  <div class="step">
    <h2>Step 1: Prepare Your Video File or URL</h2>
    <p>Make sure you have your video ready. You can use a video file like MP4 or a link from YouTube or another hosting service.</p>
    <img src="step1.png" alt="Preparing the video file" />
  </div>

  <div class="step">
    <h2>Step 2: Open Your HTML File in a Text Editor</h2>
    <p>Open the HTML file where you want to embed the video. Use a text editor like VSCode, Sublime Text, or Notepad.</p>
    <img src="step2.png" alt="Opening HTML file in text editor" />
  </div>

  <div class="step">
    <h2>Step 3: Add the Video Embed Code</h2>
    <p>Insert the following code snippet where you want the video to appear:</p>
    <pre>
&lt;video controls width="600"&gt;
  &lt;source src="your-video.mp4" type="video/mp4"&gt;
  Your browser does not support the video tag.
&lt;/video&gt;
    </pre>
    <img src="step3.png" alt="Inserting video embed code" />
  </div>

  <div class="step">
    <h2>Step 4: Save Your HTML File</h2>
    <p>Save the changes to your HTML file.</p>
    <img src="step4.png" alt="Saving HTML file" />
  </div>

  <div class="video-container">
    <h2>Example Video Embedded</h2>
    <video controls width="600">
      <source src="example-video.mp4" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </div>

</body>
</html>
