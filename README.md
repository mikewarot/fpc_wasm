# fpc_wasm

This is my first crack at the following task, it's a Kludge right now

Free Pascal Source Code --> FPC Compiler --> .wasm file --> web page with results from Pascal program


I've barely got it working (I'm using Windows 10, your milage may vary)

To get to this point - You'll need to install Lazarus 3.0 (its a release candidate #2 as of 10/30/2023)

Then follow all these instructions to get FPC installed, with all the source code to make a cross compiler

https://wiki.freepascal.org/WebAssembly/Compiler

Once you've got that... you should be able to clone this repository and get wasm1.html to load in your browser...

You might get a CORS error... I use chrome, I made a shortcut with this command in it to start Chrome browsing locally with CORS off

"C:\Program Files\Google\Chrome\Application\chrome.exe" --allow-file-access-from-files file:///C:/
