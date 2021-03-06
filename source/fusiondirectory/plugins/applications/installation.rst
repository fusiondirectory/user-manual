Installation
============

Install packages
----------------

Debian
^^^^^^

.. code-block:: bash

   apt-get install fusiondirectory-plugin-applications
   apt-get install fusiondirectory-plugin-applications-schema

RHEL
^^^^

.. code-block:: bash

   yum install fusiondirectory-plugin-applications
   yum install fusiondirectory-plugin-applications-schema

Install schemas
---------------

Debian
^^^^^^

.. code-block:: bash

   fusiondirectory-insert-schema -i /etc/ldap/schema/fusiondirectory/applications-fd.schema
   fusiondirectory-insert-schema -i /etc/ldap/schema/fusiondirectory/applications-fd-conf.schema

RHEL
^^^^

.. code-block:: bash

   fusiondirectory-insert-schema -i /etc/ldap/schema/fusiondirectory/applications-fd.schema
   fusiondirectory-insert-schema -i /etc/ldap/schema/fusiondirectory/applications-fd-conf.schema
