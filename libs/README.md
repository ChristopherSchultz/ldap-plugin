# libs

Libraries which have been manually installed instead of located via Maven.

You can fetch the libraries necessary to build this plug-in like this:

```
# Extract the required dependencies
$ tar xvzf oie_unix_4_5_2.tar.gz -C libs/ oie/client-lib/mirth-client.jar oie/server-lib/mirth-server.jar oie/cli-lib/mirth-client-core.jar

# Move out of subdirectories
$ mv libs/oie/*/*.jar libs/

# Clean up
$ rm -rf libs/oie
```
