# devspaces-side-container


**Open in VSCode**

<a href="https://workspaces.openshift.com/f?url=https://github.com/piyushsn/devspaces-side-container">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" width="100" height="100">
 </a>

 
 **Open in IntelliJ IDEA**


<a href="https://workspaces.openshift.com/f?url=https://github.com/piyushsn/devspaces-side-container&che-editor=che-incubator/che-idea/latest">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/2048px-IntelliJ_IDEA_Icon.svg.png" width="100" height="100">
 </a>
 
 ## How to use
 
 ! IMPORTANT ! Before you demo this, fork it, and change the devspaces URLs references in the above "Open in..." links.
 
 ```bash
 mvn spring-boot:run
 ```
 
 VSCode should give you a pop up which takes you to the browser. If not, simply do
 ```bash
 oc get route | grep 8080
 ```
 
 Once in the browser, make sure `http` prefix is used. Append `/greeting` to the URL and you will see REST API response.
 
 The application connects to the locally running PostgreSQL which is a very powerul concept. There is also h2 profile available, which can be enabled like this:
 ```
 mvn spring-boot:run -Dspring-boot.run.profiles=h2
 ```
 You can then access h2 console by appending `/h2-console` in the browser.
 Application Logs also shows that the sql integration is succesful - you will see User table being created.
 

