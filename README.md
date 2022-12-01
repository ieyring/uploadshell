# uploadshell

If you blindly trust the type of the uploaded file, you might end up uploading a PHP script containing a backdoor.

This can be easily simulated using a simple PHP script using the CURLFile object:
