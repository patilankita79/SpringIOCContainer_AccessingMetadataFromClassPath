# SpringIOCContainer_AccessingMetadataFromClassPath

The location path or paths supplied to application context constructor are actually resource strings that allow the container to load configuration metadata from a variety of external resources such as the local file system from the Java class path and so on.

Application context is the interface for an advanced factory capable of maintaining a registry for different beans as well as their dependecies.

getBean() is used to retrieve instances of your beans.

Your application call should actually have no calls to the getBean method at all and thus no dependency on Spring API as a result. This is actually a bad practise.
 
