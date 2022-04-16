## Let's write better console logs

# **print**

```
// usually everyone is using
print('YOUR MESSAGE IS HERE');
``` 
Let’s try other functions as well.


# **debugPrint()**
Android sometimes discards long log lines, to avoid this we can use debugPrint() which comes from the flutter foundation library.

```
debugPrint('YOUR MESSAGE IS HERE');
debugPrint('WRITE YOUR LONG MESSAGE HERE');
``` 

# **developer.log()**
This function allows adding other information for logging. Like the log message name + error message + Level of logging etc.
```
import 'dart:developer' as developer;

developer.log('YOUR MESSAGE IS HERE',
             name: 'WE CAN DEFINE GROUP OR NAME OF THIS MESSAGE',
             error:'WRITE YOUR LONG MESSAGE HERE',
            );
``` 
