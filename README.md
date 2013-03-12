## It's so cute, what is it?

This is a sample hello world application that can be deployed on a
DIY PaaS called **awsbox**, which is a super thin box around
amazon web services.

The four things that make this hello world app awsbox deployable
include:

  * written in nodejs
  * has an `.awsbox.json` file which provides information to the
    deployment system (like, what processes should be run?)
  * binds localhost and defers to a PORT environment variable.
  * has a `package.json` file and can be npm installed.
