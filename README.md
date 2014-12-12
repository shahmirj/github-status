github-status
=============

A small script to Call github status. Very useful to use within Jenkins. An
example call can be:

    ./notify-github-status shahmirj/github-status \
        <TOKEN> \
        <COMMITREF> \
        pending\
        http://myjenkins/jobs/myjob/1337
        "Starting the build"
        "jenkins/notify-github-status"

See https://developer.github.com/v3/repos/statuses/ for detailed status types
