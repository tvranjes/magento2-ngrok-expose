<h1>Magento 2 ngrok expose</h1>

<p>Usage:</p>
<pre>git clone https://github.com/tvranjes/magento2-ngrok-expose.git</pre>
<pre>chmod +x magento2-ngrok-expose/ngrok-expose</pre>
<pre>sudo cp magento2-ngrok-expose/ngrok-expose /usr/local/bin/</pre>
<pre>source $HOME/.bashrc</pre>
<p>Make sure Your Magento 2 instance is properly installed, Your web server and DB server is running and You have PHP CLI properly set.</p>
<p>Navigate to Your Magento 2 root</p>
<p>To start your ngrok expose:</p>
<pre>ngrok-expose start</pre>
<p>On the first run, script will check if ngrok and n98-magerun2 is properly installed.</p>
<p>If something is missing, the script will attempt to install it. You will be asked for sudo password to set ngrok and n98-magerun2.</p>
<p>When promted, enter Your ngrok api token.</p>
<p>To stop ngrok exposure:</p>
<pre>ngrok-expose stop</pre>
