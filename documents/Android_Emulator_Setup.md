<h1>Android Emulator Setup for React Native CLI</h1>

<!-- Logos -->
<p align="center">
<img src="../logos/android_logo.png" alt="Android Logo" width="50"/>
<img src="../logos/react_native_logo.png" alt="React Native Logo" width="50"/>
</p>

<h2>1. Open Android Studio</h2>
<p>Ensure Android Studio is installed and the Android SDK is configured.</p>

<h2>2. Launch AVD Manager</h2>
<ul>
<li>Go to <b>Tools → AVD Manager</b> in Android Studio</li>
<li>Click <b>Create Virtual Device</b></li>
</ul>

<h2>3. Choose Device</h2>
<ul>
<li>Select a hardware device (e.g., Pixel 5, Nexus 6)</li>
<li>Click <b>Next</b></li>
</ul>

<h2>4. Select System Image</h2>
<ul>
<li>Choose a recommended Android version (e.g., Q, R)</li>
<li>Download if not already installed</li>
<li>Click <b>Next</b></li>
</ul>

<h2>5. Configure AVD</h2>
<ul>
<li>Set a name for the emulator</li>
<li>Adjust memory, orientation, scale, etc. (optional)</li>
<li>Click <b>Finish</b></li>
</ul>

<h2>6. Launch Emulator</h2>
<ul>
<li>In AVD Manager, click the <b>Play</b> icon next to your emulator</li>
<li>Wait for the emulator to boot completely</li>
</ul>

<h2>7. Connect React Native CLI</h2>
<p>Once the emulator is running, open your project folder and run:</p>
<pre><code>npx react-native run-android
</code></pre>

<p>The Metro bundler will start and deploy the app to the emulator.</p>

<h2>8. Tips</h2>
<ul>
<li>Enable <b>Hardware Acceleration</b> for better performance (Intel HAXM or Hyper-V)</li>
<li>If the emulator is slow, consider using a physical Android device with USB debugging enabled</li>
<li>To reload the app, press <b>R</b> twice in the emulator</li>
</ul>
