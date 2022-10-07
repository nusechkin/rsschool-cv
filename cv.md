## **Anna Komarova**
#### e-mail: komarova.ao@gmail.com
#### **About me**
I have been working as motion designer for several years now, decided to shift my career path and here I am. 
#### **Skills**
* *Design*: Adobe Photoshop, Adobe Illustrator, Adobe After Effects
* *Version Control Systems*: Tortoise SVN, GIT
* *Programming languages*: TypeScript, Javascrpit 
#### **Courses**
* HTML Basics, https://ru.code-basics.com/languages/html
* CSS Basics, https://ru.code-basics.com/languages/css
* JavaScript, https://ru.code-basics.com/languages/javascript
* Introduction to programming, https://ru.hexlet.io/courses/introduction_to_programming
#### **Code example**
```javascript
﻿var newFile = File.openDialog("Choose file to read"); 

if(newFile != null){ 
    var a = readDocument(newFile, 0).contentArray;
    
    app.beginUndoGroup("Import Text");
        createNewComps(a);
    app.endUndoGroup();
}

function readDocument(inputDoc, linesToSkip){
    var curDoc = new File(inputDoc); 
    if (curDoc.exists){
        var contentArray = new Array();
        curDoc.open("r"); 
        while(!curDoc.eof){ 
            contentArray[contentArray.length] = curDoc.readln();
        }
        curDoc.close();
    }
    contentArray.splice(0, linesToSkip); 
    var contentList = contentArray.join("_dpt_").toString().replace(new RegExp("_dpt_", "g"), "\r"); 
    contentArray = contentArray;
    return{
       'contentArray': contentArray, 
       'contentList': contentList 
    }
}
#### **Work experience**
Some years as motion designer

#### **English level**
C2 (82/100) EF Standard English Test (EF SET) - https://www.efset.org/cert/unW32z