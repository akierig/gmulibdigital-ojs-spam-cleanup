# OJS 3.114 Tuneup
some simple database maintenance for cleaning up an OJS 3.11x install.

This started out as a plan to just remove a bunch of spam users, but now I'm using it to hold some other stuff, including documenting how I do the upgrade to OJS 3.121.

Given the large volume of spam users (~38,500!) we needed an agressive approach. If you have somewhat fewer than we did, maybe check out @kaitlinnewson's [OJS Tools](https://github.com/kaitlinnewson/ojs-tools). 

## Important Warning!
Due to the changing nature of OJS's database organization, you should use these as helpful suggestions and adjust accordingly for your own needs. 

And never never never never never do this on your live production database. But you know that, don't you?
