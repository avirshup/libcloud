Welcome to Apache Libcloud's documentation!
===========================================

.. note::

   Libcloud v3.0.0 dropped support for Python 2.7 and Python 3.4 and now only
   supports Python version >= 3.5.

   If you still need to us Libcloud with one of the new unsupported versions,
   you can do that by using the latest release of Libcloud which still supports
   those versions (Libcloud v2.8).

Apache Libcloud is a Python library which hides differences between different
cloud provider APIs and allows you to manage different cloud resources through
a unified and easy to use API.

Resource you can manage with Libcloud are divided in the following categories:

* :doc:`Cloud Servers and Block Storage </compute/index>` - services such as Amazon EC2 and
  Rackspace CloudServers
* :doc:`Cloud Object Storage and CDN </storage/index>` - services such as Amazon S3 and
  Rackspace CloudFiles
* :doc:`Load Balancers as a Service </loadbalancer/index>` - services such as Amazon Elastic Load Balancer and GoGrid LoadBalancers
* :doc:`DNS as a Service </dns/index>` - services such as Amazon Route 53 and Zerigo
* :doc:`Container Services </container/index>` - container virtualization like Docker and Rkt as well as container based services
* :doc:`Backup as a Service </backup/index>` - services such as Amazon EBS and OpenStack Freezer

.. figure:: /_static/images/supported_providers.png
    :align: center

    A subset of supported providers in Libcloud.

Documentation
=============

Main
----

.. toctree::
    :glob:
    :maxdepth: 3

    getting_started
    supported_providers
    supported_python_versions
    third_party_drivers
    compute/index
    storage/index
    loadbalancer/index
    dns/index
    container/index
    backup/index
    troubleshooting
    api_docs
    faq
    other/*

Developer Information
---------------------

.. toctree::
    :glob:
    :maxdepth: 3

    developer_information
    development

Committer Guide
---------------

.. toctree::
    :glob:
    :maxdepth: 3

    committer_guide

Other
-----

.. toctree::
    :glob:
    :maxdepth: 3

    changelog
    upgrade_notes
    security

.. note::

    Unless noted otherwise, all of the examples and code snippets in the
    documentation are licensed under the `Apache 2.0 license`_.

.. _`Apache 2.0 license`: https://www.apache.org/licenses/LICENSE-2.0.html
