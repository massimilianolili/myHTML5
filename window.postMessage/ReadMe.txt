window.postMessage: far parlare iframe su domini diversi con HTML5

http://html5today.it/tutorial/window-postmessage-far-parlare-iframe-su-domini-diversi-con-html5/

http://html5today.it/labs/window.postmessage/window.postmessage.html


EXAMPLE : 
// il domino esatto su cui si trova il destinatario
var domain = 'http://domain.com';
 
// nota che prendiamo il "contentWindow", non solo il nodo
var iframe = document.getElementById('id-iframe').contentWindow;
 
// è tutto qui!
iframe.postMessage(message, domain);