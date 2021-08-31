The CD inventory and review example RESTful web service example is just that an example.  It's not meant to be a tutorial.  However, it does show
some basic setup using Maven and Jersey JAX-RS in the documentation with PNG screenshots of the steps to get started.

The code itself is fairly easy to read and commented where I felt it would help someone without any REST experience. Core Java using Eclipse and a general understanding
of HTTP concepts is also assumed.

This example assumes the developer understands basic HTTP concepts.  Especially the concept of Request, Response objects and the POST and GET HTTP methods which
are used in this example.  Future releases will include PUT and DELETE methods. Also, it'll include HTTP header checks on 200, 201, and 404 headers.

The project name is cdmusic using a package structure of io.github.jjcrowe.cdmusic.

Start by reading the Setup.txt document and the how to run the POST test using Powershell.

You can test the GET processes using your favorite browser.  To test the POST process I'm using Invoke-RestMethod -Method POST on the Powershell command line prompt.
However if you prefer to use Postman or another testing tool that's fine.

Please see the Test_URIs.txt document for general testing URIs.

**************************************************************  Changes  ***********************************************************************

8/24/2021
Added the ability to retrieve individual reviews based on revied IDs.

Added the functionality to update (PUT) the comment and the rating on a review.

