Red Hat JBoss BPM Suite Workshop
================================
This git repository helps you get up and running quickly with a 
Cloud hosted workshop on JBoss BPM Suite that gets you
started building your very own Travel Agency.

Enjoy!

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a PHP application

    rhc app create travelagencyworkshop -t php-5.4 --from-code git://github.com/eschabell/openshift-bpmsuite-travelagency-workshop.git

That's it, you can now start your workshop at:

    http://travelagencyworkshop-$your_domain.rhcloud.com

![Travel Agency Workshop](https://raw.githubusercontent.com/eschabell/openshift-bpmsuite-travelagency-workshop/master/cover.png)

