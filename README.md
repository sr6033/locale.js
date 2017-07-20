# locale.js: Locale Javascript Interpreter

Inspired from <a href="http://jsfiddle.net/">JsFiddle</a>, I created this locale javascript interpreter. You don't need to be connected to the internet to interpret your javascript codes. Run it from your local machine and debug your codes.

<figure>
	<a href="{{ site.url }}/img/1.png"><img src="/img/1.png"></a>
</figure>
---
<figure>
	<a href="{{ site.url }}/img/2.png"><img src="/img/2.png"></a>
</figure>
---

## Dependencies

- Node
- Express
- Socket.io
- exec

> Note that the console might require one time internet access on starting the server. This is because, the included libraries are from *cdn* and so it has to fetch the data from the remote server.

## Steps

- `git clone` this repository.
- Start the **Server** by doing `node index.js`.
- Head over to <a href="http://127.0.0.1:4000">http://127.0.0.1:4000</a> to access the console.

Feel free to contribute and add more features to it.
