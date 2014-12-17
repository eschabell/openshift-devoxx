Devoxx mobile registration app on OpenShift
===========================================

This is the Devoxx html5/mboile registration app.


Install with one click
----------------------
[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to
install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=jbosseap-6&initial_git_url=https://github.com/eschabell/openshift-devoxx.git&name=devoxx)


Manual setup on OpenShift
-------------------------

Create an account at http://openshift.redhat.com/

Create a jbosseap-6.0 application

    rhc app create devoxx -t jbosseap-6 --from-code https://github.com/eschabell/openshift-devoxx
    
That's it, you can now checkout your application at:

    http://devoxx-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
