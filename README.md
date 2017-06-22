# FoodMe App — a workshop app built with AngularJS

Simplified meal ordering app for local restaurants built with AngularJS
and node.js backend.

Check out this doc for more info about the app: http://goo.gl/Xa0Ea

Also check out the commit history to see how the app was built piece by piece:

https://github.com/IgorMinar/foodme/commits/master

---

The app is build on top of [angular-seed](http://github.com/angular/angular-seed),
check out seed's README to understand what the scripts under `scripts/` are doing.

---

Fix applied for the error encountered while running the web-server.bat

Issue due to express module showing following error:
      throw new Error('Most middleware (like ' + name + ') is no longer bundled
with Express and must be installed separately. Please see https://github.com/sen
chalabs/connect#middleware.');

Resolution by re-installing the express:
npm install express@">=3.0.0 <4.0.0" --save