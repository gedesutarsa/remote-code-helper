# remote-code-helper
Helper for remote dev

My problem: 
sometime of most case, development on laptop, was no enougth horse power on laptop. 
So some load need to be take out to another machine. for example coding with react, angular, or project that run using quarkus
We can go with visual studio code remote develoment. But there is some catch, for example: 
1. for javascript development, on each save, application will be reloaded. sometime this is not what we expected
2. for kotlin(quarkus with kotlin for instance), kotlin support on visual studio code is not as good as intellij did. Language server for kotlin still not as good as java Language server

So the idea: 
1. code still done on local laptop, and there will be watcher to watch if file is change
2. small, simple web will be available to show which file is changed. and there is button to send file to server. send file will be done using scp command, 
remote dev will run with linux machine, so no need to install some sort of server


