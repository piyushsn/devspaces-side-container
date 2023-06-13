# devspaces-side-container


**Open in VSCode**

<a href="https://devspaces.apps.cluster-sdkjx.sdkjx.sandbox1743.opentlc.com/f?url=https://github.com/agiertli/devspaces-side-container">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png" width="100" height="100">
 </a>
 
 
 **Open in IntelliJ IDEA**


<a href="https://devspaces.apps.cluster-sdkjx.sdkjx.sandbox1743.opentlc.com/f?url=https://github.com/agiertli/devspaces-side-container&che-editor=che-incubator/che-idea/latest">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/2048px-IntelliJ_IDEA_Icon.svg.png" width="100" height="100">
 </a>
 
 ## How to use
 
 ```bash
 mvn spring-boot:run
 ```
 
 VSCode should give you a pop up which takes you to the browser. If not, simply do
 ```bash
 oc get route | grep 8080
 ```
 
 Once in the browser, make sure `http` prefix is used. Append `/greeting` to the URL and you will see REST Api response.
 

