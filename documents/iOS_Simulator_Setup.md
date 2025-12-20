<h1>iOS Simulator Setup for React Native CLI (macOS only)</h1>

<!-- Logos -->
<p align="center">
<img src="../logos/ios_logo.png" alt="iOS Logo" width="50"/>
<img src="../logos/react_native_logo.png" alt="React Native Logo" width="50"/>
</p>

<h2>1. Open Xcode</h2>
<p>Ensure Xcode is installed from the Mac App Store.</p>

<h2>2. Install Command Line Tools</h2>
<pre><code>xcode-select --install
</code></pre>

<h2>3. Launch iOS Simulator</h2>
<ul>
<li>Open Xcode → <b>Xcode → Open Developer Tool → Simulator</b></li>
<li>Choose the desired device (iPhone 14, iPhone 13, etc.)</li>
</ul>

<h2>4. Run React Native App on Simulator</h2>
<p>Open your project folder in terminal and run:</p>
<pre><code>npx react-native run-ios
</code></pre>

<p>The Metro bundler will start automatically, and the app will launch in the simulator.</p>

<h2>5. Optional: Use Physical iPhone/iPad</h2>
<ul>
<li>Connect your device via USB</li>
<li>Trust the computer on the device</li>
<li>Select the device in Xcode → Run the project</li>
</ul>

<h2>6. Tips</h2>
<ul>
<li>Press <b>Cmd + R</b> in the simulator to reload the app</li>
<li>Press <b>Cmd + D</b> to open the React Native developer menu</li>
<li>Keep Xcode updated to avoid simulator issues</li>
</ul>
