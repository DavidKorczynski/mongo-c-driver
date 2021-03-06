:man_page: mongoc_apm_server_heartbeat_failed_get_awaited

mongoc_apm_server_heartbeat_failed_get_awaited()
================================================

Synopsis
--------

.. code-block:: c

  bool
  mongoc_apm_server_heartbeat_failed_get_awaited (
     const mongoc_apm_server_heartbeat_failed_t *event);

Returns whether this event came from an awaitable isMaster.

Parameters
----------

* ``event``: A :symbol:`mongoc_apm_server_heartbeat_failed_t`.

Returns
-------

A bool indicating whether the heartbeat event came from an awaitable isMaster.

.. seealso::

  | :doc:`Introduction to Application Performance Monitoring <application-performance-monitoring>`

