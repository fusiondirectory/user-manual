Installation
============

Install packages
----------------

Debian
^^^^^^

.. code-block:: bash

   apt-get install fusiondirectory-plugin-user-reminder
   apt-get install fusiondirectory-plugin-user-reminder-schema

RHEL
^^^^

.. code-block:: bash

   yum install fusiondirectory-plugin-user-reminder
   yum install fusiondirectory-plugin-user-reminder-schema

Install schemas
---------------

Debian
^^^^^^

.. code-block:: bash

   fusiondirectory-insert-schema -i /etc/ldap/schema/fusiondirectory/user-reminder-fd-conf.schema
   
RHEL
^^^^

.. code-block:: bash

   fusiondirectory-insert-schema -i /etc/openldap/schema/fusiondirectory/user-reminder-fd-conf.schema
  
