===============================================
OpenStack-Ansible role for Zookeeper deployment
===============================================

This role installs a Zookeeper cluster that is part of OpenStack infratructure
and used as a coordination service by multiple services through Tooz.

To clone or view the source code for this repository, visit the role repository
for `zookeeper <https://opendev.org/openstack/ansible-role-zookeeper>`_.

To install role requirements, please run

.. code::

    ansible-galaxy install -r requirements.yml


Default variables
~~~~~~~~~~~~~~~~~

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.


Example playbook
~~~~~~~~~~~~~~~~

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml
