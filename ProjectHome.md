Welcome to the home page at Google for the ESAPI for C project. ESAPI (The [OWASP](https://www.owasp.org) Enterprise Security API) is a free, [open source](http://www.opensource.org/licenses/bsd-license.php), application security control library that makes it easier for programmers to write lower-risk applications. The overall ESAPI project has a high level goal of producing these free security libraries for most popular programming languages. This project is the C specific version of that goal. Please view the [ESAPI home page](https://www.owasp.org/index.php/Category:OWASP_Enterprise_Security_API) for more details on the overall project, its philosophy, and to see the other languages that ESAPI libraries have been written for.

The purpose of the ESAPI is to provide a simple interface that provides all the security functions a developer is likely to need in a clear, consistent, and easy to use way. The ESAPI architecture is very simple, just a collection of modules that encapsulate the key security operations most applications need.

Unlike the ESAPI libraries available for other more web-friendly languages, this ESAPI library does NOT provide controls for intrusion detection, web-specific input validation, authentication, or access control.  Also, it does not attempt to provide protection against buffer overflows, which are endemic to the C language.  For help mitigating the risk of buffer overflows in your C projects, see resources like:

http://www.dwheeler.com/secure-programs/Secure-Programs-HOWTO/library-c.html

The mailing list for this project is located at: https://lists.owasp.org/mailman/listinfo/owasp-esapi-c

You can view the latest version of the API documentation here: http://owasp-esapi-c.googlecode.com/svn/trunk/doc/html/index.html.

Source code for the ESAPI for C project is available here in the [Source tree](http://code.google.com/p/owasp-esapi-c/source/checkout).