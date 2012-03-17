## It's so cute, what is it?

This is a sample hello world application that can be deployed on a
fictional paas called **awsbox**, which is a super thin box around
amazon web services.

The four things that make this hello world app awsbox deployable
include:

  * its written in nodejs
  * its got an `awsbox.json` file which provides information to the
    deployment system (like, what processes should be run?)
  * it binds localhost and defers to a PORT environment variable.
  * it has a `package.json` file and can be npm installed.
