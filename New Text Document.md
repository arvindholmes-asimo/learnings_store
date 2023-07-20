Introduction to the Java Collections Framework.
Working with collections such as ArrayList, LinkedList, HashSet, and HashMap.
Iterating over collections using loops and iterators.
Sorting and searching elements in collections.
Understanding the concept of Generics.
File Input/Output:

Reading and writing data to files.
Using FileReader, FileWriter, BufferedReader, BufferedWriter, etc.
Handling file operations using try-catch-finally blocks.
Understanding file paths and directories.
Multithreading:

Introduction to concurrent programming.
Creating and managing threads in Java.
Thread synchronization and coordination.
Understanding concepts like deadlock, race conditions, and thread safety.
Utilizing synchronization mechanisms such as locks and semaphores.


C:\Users\Admin\AppData\Local\Android\Sdk\platform-tools

./adb reverse tcp:8081 tcp:8081   

npx react-native start --reset-cache 

npx react-native run-android 

npm save --list 
npm i react-native-device-info  

npm i @react-native-async-storage/async-storage

npm i react-native-keyboard-aware-scroll-view

npm i formik


  npm install --save react-native-sqlite-storage

### Array methods 

const fruits = ["Banana", "Orange", "Apple", "Mango"];

> fruits.pop();` removes the last element & returns` it     'Mango'  and 
> fruits.shift() ` removes the first array element and  "shifts" all other elements to a lower index == returns the value that was "shifted out" `


> fruits.push("Kiwi");  ` adds a new element to an array (at the end)`

> fruits.unshift('Lemon') `adds a new element to an array (at the beginning), and "unshifts" older elements`

>



sqlite 


react-native.config.js


module.exports = {
    dependencies: {
        "react-native-sqlite-storage": {
            platforms: {
                android: {
                    sourceDir: "../node_modules/react-native-sqlite-storage/platforms/android-native",
                    packageImportPath: "import io.liteglue.SQLitePluginPackage;",
                    packageInstance: "new SQLitePluginPackage()"
                }
            }
        }
    }
}


## before using any attribute or properties of any tag check their definition to find available choices 
