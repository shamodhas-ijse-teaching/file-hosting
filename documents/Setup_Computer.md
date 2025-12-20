<h1>Setup Computer for React Native CLI</h1>

<h2>1. Install Node.js and npm</h2>
<p>Download Node.js LTS version: <a href="https://nodejs.org/" target="_blank">https://nodejs.org/</a></p>
<pre><code>node -v
npm -v
</code></pre>

<h2>2. Install Java Development Kit (JDK)</h2>
<p>Required for Android development.</p>
<ul>
<li>Download OpenJDK 11 or 17</li>
<li>Set <code>JAVA_HOME</code> environment variable</li>
<li>Verify:</li>
</ul>
<pre><code>java -version
</code></pre>

<h2>3. Install Android Studio</h2>
<p>Download: <a href="https://developer.android.com/studio" target="_blank">Android Studio</a></p>
<ul>
<li>Select Android SDK, SDK Platform, and Android Virtual Device (AVD) during installation</li>
<li>Configure <code>ANDROID_HOME</code> environment variable</li>
<li>Verify:</li>
</ul>
<pre><code>echo $ANDROID_HOME  # macOS/Linux
echo %ANDROID_HOME%  # Windows
</code></pre>

<h2>4. Install Xcode (macOS only)</h2>
<ul>
<li>Download from Mac App Store</li>
<li>Install Xcode Command Line Tools: <code>xcode-select --install</code></li>
<li>Verify: <code>xcodebuild -version</code></li>
</ul>

<h2>5. Install Watchman (macOS only, optional)</h2>
<pre><code>brew install watchman
</code></pre>

<h2>6. Install React Native CLI</h2>
<pre><code>npm install -g react-native-cli
react-native -v
</code></pre>

<h2>7. Optional: Configure Emulator / Device</h2>
<ul>
<li>Android: Use AVD Manager in Android Studio</li>
<li>iOS: Use Simulator in Xcode</li>
</ul>
