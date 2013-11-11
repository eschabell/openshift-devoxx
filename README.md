Devoxx mobile registration app on OpenShift
===========================================

This is the Devoxx html5/mboile registration app.

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a jbosseap-6.0 application

    rhc app create -t jbosseap-6 --from-code git://github.com/eschabell/openshift-devoxx.git devoxx

That's it, you can now checkout your application at:

    http://devoxx-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
