# curl

The curl command in Linux is a powerful command-line tool used for transferring data to or from a server using various network protocols. 

It supports a wide array of protocols, including HTTP, HTTPS, FTP, FTPS, SCP, SFTP, and more, and is widely used for web requests, API testing, and automation.

## options

### data transfer & output
- -O, --remote-name: Downloads a file and saves it with its original remote filename.
- -o <file>, --output <file>: Saves the downloaded data to a specific local file instead of standard output.
- -I, --head: Fetches only the header information of the resource (useful for checking metadata without downloading the body).
- -L, --location: Follows HTTP redirects (by default, curl does not follow redirects).
- -v, --verbose: Provides detailed information about the operation, including headers and connection details, which is useful for debugging.
- -s, --silent: Silences the progress meter and error messages. 

### HTTP methods & data submission
- -X <method>, --request <method>: Specifies the HTTP request method to use (e.g., POST, PUT, DELETE, OPTIONS). If not specified, GET is the default.
- -d <data>, --data <data>: Sends data in an HTTP POST or PUT request. This option will also change the request method to POST unless -X is specified.
- -F <name=content>, --form <name=content>: Submits form data, including file uploads, using multipart/form-data.
- -G, --get: When used with -d, converts the data to a GET request and appends the data to the URL as a query string. 

### authentication & cookies
- -u <user:password>, --user <user:password>: Specifies the user name and password for server authentication (e.g., Basic Authentication).
- -H, --header: Specifies a custom header to include in the request.
- -b, --cookie: Sends cookies to the server.
- -c, --cookie-jar: Writes received cookies to a specified file after the operation completes. 

### connection & security
- -k, --insecure: Allows curl to proceed with insecure SSL connections and certificate warnings (useful for testing self-signed certificates).
- --cacert <file>: Specifies a file of CA certificates to use for SSL verification.
- --proxy <host:port>, -x <host:port>: Connects via a specified proxy.
- --connect-timeout <seconds>: Maximum time allowed for the connection phase to complete. 

## usage
`curl [options] [URL]`  
