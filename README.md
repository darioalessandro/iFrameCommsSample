# iFrame comms using Post Message:

1) parentPage.html loads child.html by using an iframe.

2) parentPage sends "Hello" using:
 
```javascript
window.postMessage();
```

3) child receives the message by using:

```javascript
window.addEventListener("message", receiveMessage, false);
```

4) child logs the message.