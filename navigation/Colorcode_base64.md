---
layout: page
title: Color Codes and Base 64
permalink: /ColorCodes/
---

<h2 style="color: #FFB3BA;">🎨💻 Understanding Color Codes, Digital Images, and Base64</h2>

<div style="font-size: 1.2em; color: #fefefe;">

<h2 style="color: #FFDFBA;">1️⃣ Color Codes: The Language of Digital Color</h2>

Colors on screens aren’t just picked out of thin air—they’re created using specific codes that computers understand.

<h3 style="color: #FFFFBA;">💡 Main Color Code Formats</h3>

<ul>
  <li><strong>Hex Codes</strong>
    <ul>
      <li>Written as <code>#RRGGBB</code> (or <code>#RRGGBBAA</code> when transparency is added)</li>
      <li>Uses hexadecimal (base-16), with digits from 0–9 and A–F</li>
      <li>Example:
        <ul>
          <li><code>#000000</code> → Black</li>
          <li><code>#FFFFFF</code> → White</li>
          <li><code>#FF5733</code> → Reddish-orange</li>
        </ul>
      </li>
    </ul>
  </li>
  <li><strong>RGB</strong>
    <ul>
      <li>Format: <code>rgb(R, G, B)</code></li>
      <li>Each value ranges from 0 to 255</li>
      <li>Example: <code>rgb(255, 87, 51)</code> is the same as <code>#FF5733</code></li>
    </ul>
  </li>
  <li><strong>RGBA</strong>
    <ul>
      <li>Adds an alpha (transparency) channel to RGB</li>
      <li>Format: <code>rgba(R, G, B, A)</code> where A ranges from 0 (invisible) to 1 (fully visible)</li>
      <li>Example: <code>rgba(255, 87, 51, 0.5)</code> = 50% transparent orange</li>
    </ul>
  </li>
</ul>

<table>
  <thead>
    <tr>
      <th>Color</th>
      <th>Hex</th>
      <th>RGB</th>
      <th>RGBA</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Red</td>
      <td>#FF0000</td>
      <td>rgb(255, 0, 0)</td>
      <td>rgba(255, 0, 0, 1)</td>
    </tr>
    <tr>
      <td>Blue</td>
      <td>#0000FF</td>
      <td>rgb(0, 0, 255)</td>
      <td>rgba(0, 0, 255, 0.3)</td>
    </tr>
    <tr>
      <td>White</td>
      <td>#FFFFFF</td>
      <td>rgb(255, 255, 255)</td>
      <td>rgba(255, 255, 255, 1)</td>
    </tr>
  </tbody>
</table>

<hr />

<h2 style="color: #BAFFC9;">🖼️ 2️⃣ What Makes a Digital Image?</h2>

A digital image is made of <strong>pixels</strong>, tiny colored squares arranged in a grid.

Each pixel stores color data using RGB (or RGBA), forming a mosaic of color that makes up the full image.

<h3 style="color: #BAE1FF;">🧊 Pixel Matrix Example (3x3)</h3>

<table>
  <tbody>
    <tr>
      <td>🔴 Red</td>
      <td>🔵 Blue</td>
      <td>🟢 Green</td>
    </tr>
    <tr>
      <td>⚪ White</td>
      <td>⚫ Black</td>
      <td>🟠 Orange</td>
    </tr>
    <tr>
      <td>🟡 Yellow</td>
      <td>💗 Pink</td>
      <td>⚙️ Gray</td>
    </tr>
  </tbody>
</table>

<p>Each pixel is a bundle of color values—like:</p>

<ul>
  <li>Pixel 1 → R: 255, G: 87, B: 51 → #FF5733</li>
  <li>Pixel 2 → R: 0, G: 0, B: 0 → #000000</li>
  <li>Pixel 3 → R: 255, G: 255, B: 255 → #FFFFFF</li>
</ul>

<hr />

<h2 style="color: #D5BAFF;">🗂️ 3️⃣ Types of Image File Formats</h2>

<table>
  <thead>
    <tr>
      <th>Format</th>
      <th>Best Use</th>
      <th>Supports Transparency</th>
      <th>Compression Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>JPG</strong></td>
      <td>Photographs, web images</td>
      <td>❌ No</td>
      <td>Lossy</td>
    </tr>
    <tr>
      <td><strong>PNG</strong></td>
      <td>Graphics, logos</td>
      <td>✅ Yes</td>
      <td>Lossless</td>
    </tr>
    <tr>
      <td><strong>GIF</strong></td>
      <td>Simple animations</td>
      <td>✅ Yes (limited)</td>
      <td>Lossless (limited)</td>
    </tr>
    <tr>
      <td><strong>SVG</strong></td>
      <td>Icons, illustrations</td>
      <td>✅ Yes</td>
      <td>Vector (scales cleanly)</td>
    </tr>
  </tbody>
</table>

<h3 style="color: #FFB3BA;">📝 Format Breakdown</h3>

<ul>
  <li><strong>JPG</strong>: Good for realistic images like photos. Smaller file sizes, but some detail is lost due to compression.</li>
  <li><strong>PNG</strong>: Retains full quality, great for transparency and sharp edges (like logos).</li>
  <li><strong>GIF</strong>: Used for animations and very simple graphics. Limited to 256 colors.</li>
  <li><strong>SVG</strong>: Text-based format that stays sharp at any size. Ideal for web icons and responsive design.</li>
</ul>

<hr />

<h2 style="color: #FFDFBA;">🔢 4️⃣ Behind the Scenes: How Images Store Color</h2>

<p>Each pixel in a digital image stores color values using three main components:</p>

<ul>
  <li><strong>R (Red)</strong>: 0–255</li>
  <li><strong>G (Green)</strong>: 0–255</li>
  <li><strong>B (Blue)</strong>: 0–255</li>
  <li><strong>(Sometimes) A (Alpha)</strong>: 0.0–1.0 for transparency</li>
</ul>

<h3 style="color: #FFFFBA;">🧠 Example Pixel</h3>

<ul>
  <li>Pixel color: R: 76, G: 175, B: 80</li>
  <li>Hex code: #4CAF50</li>
  <li>RGBA: rgba(76, 175, 80, 1)</li>
</ul>

<hr />

<h2 style="color: #BAFFC9;">🍿 Popcorn Hacks</h2>

<details>
<summary>1️⃣ Which image format is best for logos and transparency?</summary>
✅ <strong>Answer:</strong> PNG  
<em>(PNG supports transparency and preserves image quality.)</em>
</details>

<details>
<summary>2️⃣ Which format loses quality to make the file size smaller?</summary>
✅ <strong>Answer:</strong> JPG / JPEG  
<em>(JPEG uses lossy compression to shrink file size.)</em>
</details>

<details>
<summary>3️⃣ Which format is used for simple animations, like memes?</summary>
✅ <strong>Answer:</strong> GIF  
<em>(GIF supports basic animations and limited color.)</em>
</details>

<hr />

<h2 style="color: #BAE1FF;">🔐 5️⃣ Base64: Turning Binary into Text</h2>

<h3 style="color: #D5BAFF;">What is Base64?</h3>

<p>Base64 is a way to encode binary data (like an image file) into a plain-text format using only letters, numbers, and a few symbols.</p>
<p>This makes it safe to embed in HTML, CSS, or JSON—without breaking anything.</p>

<h3 style="color: #FFB3BA;">Why Use It?</h3>

<ul>
  <li>📦 <strong>Embed images directly in websites</strong> (no separate files!)</li>
  <li>🌐 <strong>Safer for sending across the internet</strong></li>
  <li>📁 <strong>Makes code more self-contained</strong></li>
</ul>

<h3 style="color: #FFDFBA;">🔠 Base64 Encoding in Action</h3>

<ol>
  <li><strong>Convert each character to binary:</strong>
    <ul>
      <li><code>H</code> = ASCII 72 → <code>01001000</code></li>
      <li><code>i</code> = ASCII 105 → <code>01101001</code></li>
    </ul>
  </li>
  <li><strong>Join the binary:</strong> <code>0100100001101001</code></li>
  <li><strong>Split into 6-bit chunks:</strong> <code>010010</code>, <code>000110</code>, <code>1001</code> (pad with zeros)</li>
  <li><strong>Look up in the Base64 alphabet:</strong> Result: <code>SGl=</code></li>
</ol>

<hr />

<h2 style="color: #FFFFBA;">📚 9️⃣ Quick Recap</h2>

<ul>
  <li>🎨 Digital colors use hex, RGB, and RGBA codes</li>
  <li>🧱 Images are made of pixels that store color data</li>
  <li>📦 File types (JPG, PNG, GIF, SVG) serve different purposes</li>
  <li>🔤 Base64 encodes binary into readable text for web use</li>
</ul>

<hr />

<h2 style="color: #BAFFC9;">🎨 Homework Hack: Make a Mood Board with Hex Colors</h2>

<ul>
  <li>Pick 5 colors that represent your mood or personality.</li>
  <li>Use a site like <a href="https://coolors.co/" target="_blank">coolors.co</a> to find and copy their hex codes.</li>
  <li>Create a simple HTML page that shows each color in a styled div block.</li>
</ul>

<hr />

<h2 style="color: #BAE1FF;">🎒 Homework Hack: Turn Your Profile Pic into Base64!</h2>

<ul>
  <li>Go to <a href="https://www.base64-image.de/" target="_blank">base64-image.de</a></li>
  <li>Upload a small image of yourself (or a favorite icon).</li>
  <li>Copy the Base64 string it generates.</li>
  <li>Create a simple HTML file and embed your image inline.</li>
</ul>

</div>

### Homework Link Submission: 

[Google Form Link](https://docs.google.com/forms/d/e/1FAIpQLSdmi_y0JAKd6qFcDFCSetfeDUEI4d4XfqWo6Y292O7B1oYQpg/viewform?usp=header)

