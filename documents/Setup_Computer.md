<h1>React Native CLI Development Environment Setup (npx Approach)</h1>

<!-- Logos -->
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg" alt="React Native Logo" width="50"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d7/Android_robot.svg" alt="Android Logo" width="50"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/MacOS_logo.svg" alt="iOS Logo" width="50"/>
</p>

<h2>1. Install Node.js and npm (Both Android & iOS)</h2>
<p>Download Node.js LTS version: <a href="https://nodejs.org/" target="_blank">https://nodejs.org/</a></p>
<pre><code>node -v
npm -v
</code></pre>

<hr/>

<h2>2. Android Development Setup</h2>

<h3>2.1 Install Java Development Kit (JDK)</h3>
<ul>
<li>Download OpenJDK 11 or 17</li>
<li>Set <code>JAVA_HOME</code> environment variable</li>
<li>Verify installation:</li>
</ul>
<pre><code>java -version
</code></pre>

<h3>2.2 Install Android Studio</h3>
<p>Download: <a href="https://developer.android.com/studio" target="_blank">Android Studio</a></p>
<ul>
<li>Select Android SDK, SDK Platform, and Android Virtual Device (AVD) during installation</li>
<li>Configure <code>ANDROID_HOME</code> environment variable</li>
<li>Verify installation:</li>
</ul>
<pre><code>echo $ANDROID_HOME  # macOS/Linux
echo %ANDROID_HOME%  # Windows
</code></pre>

<h3>2.3 Configure Android Emulator / Device</h3>
<p>For detailed steps on configuring the Android Emulator, see the separate guide:</p>
<ul>
<li><a href="Android_Emulator_Setup.md" target="_blank">Android Emulator Setup Guide</a></li>
<li>Or connect a physical Android device with USB debugging enabled</li>
</ul>

<hr/>

<h2>3. iOS Development Setup (macOS only)</h2>

<h3>3.1 Install Xcode</h3>
<ul>
<li>Download from Mac App Store</li>
<li>Install Xcode Command Line Tools: <code>xcode-select --install</code></li>
<li>Verify installation: <code>xcodebuild -version</code></li>
</ul>

<h3>3.2 Install Watchman (Optional, recommended)</h3>
<pre><code>brew install watchman
</code></pre>

<h3>3.3 Configure iOS Simulator / Device</h3>
<p>For detailed steps on configuring the iOS Simulator, see the separate guide:</p>
<ul>
<li><a href="iOS_Simulator_Setup.md" target="_blank">iOS Simulator Setup Guide</a></li>
<li>Or connect a physical iPhone/iPad</li>
</ul>

<hr/>

<h2>4. React Native CLI via npx (Both Android & iOS)</h2>
<p>No global CLI installation is needed. Use <code>npx</code> to create and run projects:</p>

<h3>Create a new project</h3>
<pre><code>npx react-native init MyApp
cd MyApp
</code></pre>

<h3>Run on Android</h3>
<pre><code>npx react-native run-android
</code></pre>

<h3>Run on iOS (macOS only)</h3>
<pre><code>npx react-native run-ios
</code></pre>

<p>Metro bundler will start automatically. Press <b>R</b> twice in the emulator/simulator to reload or use the developer menu for debugging.</p>
