There are just some exploit scripts that i use for roblox

<h3>Click below to copy the text to the clipboard:</h3>

<input type="text" value="Text to copy" id="copyText" readonly>
<button onclick="copyToClipboard()">Copy</button>

<script>
  function copyToClipboard() {
    var copyText = document.getElementById("copyText");
    copyText.select();
    document.execCommand("copy");
    alert("Copied the text: " + copyText.value);
  }
</script>
