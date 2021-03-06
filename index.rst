.. _index:

##############################
The OpenShift Compliance Guide
##############################

******************
Deprecation Notice
******************
This project is deprecated. Please see `ATO Pathways <http://atopathways.redhatgov.io/>`_.

*****
About
*****

OpenShift is a container management platform based on Docker_ containers and the
Kubernetes_ container cluster manager. OpenShift adds developer and operational
centric tools to enable rapid application development, easy deployment and
scaling, and long-term lifecycle maintenance for small and large teams and
applications.

Built atop Red Hat Enterprise Linux (RHEL_), OpenShift is very secure. For users
who must comply with the Federal Information Security Management Act (FISMA_),
there is additional configuration burden.

This guide can help you secure your OpenShift cluster to comply with the FISMA
moderate confidentiality, integrity, and availability requirements.

While the configurations and Security Control Traceability Matrix (SCTM)
documented in this guide could be implemented in any environment, the
reference architecture is `Amazon Web Services`_.

*****************
Table of Contents
*****************
#. :ref:`sec_conops`
#. :ref:`control`
#. :ref:`crm`
#. :ref:`ansible`

**************************
Frequently Asked Questions
**************************

Have questions? Visit our :ref:`faq`.

************
Contributing
************

Security is an ongoing effort, and we appreciate any feedback or recommendations
that you may have. Please use this project's `GitHub <https://github.com/jason-callaway/openshift-compliance>`_
page to submit issues or pull requests.

Authors
=======

* `Nick Sabine`_
* `Ken Evensen`_
* `Mark Shoger`_
* `Mike Epley`_
* `Durell Willoughby`_
* `Tiffany Gray`_
* `Matt Bagnara`_
* `Jason Callaway`_

.. _Docker: https://www.openshift.com/container-platform/containers.html
.. _Kubernetes: https://www.openshift.com/container-platform/kubernetes.html
.. _RHEL: https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux
.. _FISMA: https://en.wikipedia.org/wiki/Federal_Information_Security_Management_Act_of_2002
.. _`Amazon Web Services`: https://aws.amazon.com/
.. _`Nick Sabine`: nsabine@redhat.com
.. _`Ken Evensen`: kevensen@redhat.com
.. _`Mark Shoger`: mshoger@redhat.com
.. _`Mike Epley`: mepley@redhat.com
.. _`Durell Willoughby`: dwilloug@redhat.com
.. _`Tiffany Gray`: tgray@redhat.com
.. _`Matt Bagnara`: mbagnara@redhat.com
.. _`Jason Callaway`: jcallawa@redhat.com
