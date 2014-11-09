Devoxx mobile registration app on OpenShift
===========================================

This is the Devoxx html5/mboile registration app.

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a jbosseap-6.0 application

    rhc app create devoxx -t jbosseap-6 
    
    cd devoxx
    
    git remote add upstream -m master git://github.com/eschabell/openshift-devoxx.git
    
    git pull -s recursive -X theirs upstream master
    
    git push

That's it, you can now checkout your application at:

    http://devoxx-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
