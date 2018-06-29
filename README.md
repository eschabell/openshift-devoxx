Update: June 2018 moved to [Gitlab](https://gitlab.com/masteringxpaas)


Devoxx mobile registration app on OpenShift
===========================================

This is the Devoxx html5 mobile registration app.


Manual setup on OpenShift
-------------------------

Create an account at http://openshift.redhat.com/

Create a jbosseap-6.0 application

    rhc app create devoxx -t jbosseap-6 --from-code https://github.com/masteringxpaas/openshift-devoxx
    
That's it, you can now checkout your application at:

    http://devoxx-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
