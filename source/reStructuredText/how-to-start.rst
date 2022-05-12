How to write a doc
==================

.. _howToStart-cre-table:

Create Tables
=============

Simple Table
------------

===================== ========== ===== ==========
Agent                 Commission Basic Main
===================== ========== ===== ==========
External Agency       No         Yes   Outsource
Indoor                Yes        Yes   Basic
Hybrid                Yes        No    Exibition
===================== ========== ===== ==========

code::

    ===================== ========== ===== ==========
    Agent                 Commission Basic Main
    ===================== ========== ===== ==========
    External Agency       No         Yes   Outsource
    Indoor                Yes        Yes   Basic
    Hybrid                Yes        No    Exibition
    ===================== ========== ===== ==========

This is a simple table:

- Advantage: suitable for immutable data
- Disadvantage: is hard to change the data


CSV Table
---------

.. csv-table:: CSV Table
    :header: Agent,Commission,Basic,Main
    :widths: 35 15 15 20

    External Agency,No,Yes,Outsource
    Indoor,Yes,Yes,Basic
    Hybrid,Yes,No,Exibition

code::

    .. csv-table:: CSV Table
    :header: Agent,Commission,Basic,Main
    :widths: 35 15 15 20

    External Agency,No,Yes,Outsource
    Indoor,Yes,Yes,Basic
    Hybrid,Yes,No,Exibition

This is a complex table:

- Advantage: suitable for mutable data.
- Disadvantage: a bit hard compare to the simple table.

.. _howToStart-cre-links:

Create Hyperlinks
==================

See more:

- `Setia Awan Live <https://go.setiaawan.com/desk/>`_
- `Setia Awan Dev <http://192.168.10.41/desk/>`_
- `iLagenda Dev <http://192.168.10.130/index/>`_

