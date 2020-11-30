# Common-Utils-for-URI-path-
In Android when we pick an image, video, or any other type of file from the gallery, documents folder, or capture directly from the camera, we receive a URI object in intent. We have different ways to get a full file path from URI based on content providers. In this article, we will discuss how to get a file path from URI in Android for the coming files picked through Storage, Documents, as well as depending upon the _data field for the MediaStore and other file-based ContentProviders.


## For Java :
##### We follow below Step :

String filePathFromURI = UtilsURIPath.getPathFromUri(context,"YOUR CONTENT URI");

## For Kotlin :
##### We follow below Step :

val utilsURIPath = UtilsURIPath()
val filePathFromURI = utilsURIPath.getPath(context,"YOUR CONTENT URI")
