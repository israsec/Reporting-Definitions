The Android app contains an exported activity without a proper content filter. The activity [name_of_activity] is set to android:exported="true"  
Exporting components without setting Intent filters opens the component to be accessed by other, potentially malicious applications. Note that in this case the [name_of_activity] may not be sensitive and exporting it may not be a vulnerability. Therefor this finding has been marked as [Informational].  

For more information see: https://cwe.mitre.org/data/definitions/926.html
