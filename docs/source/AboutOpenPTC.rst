About OpenPTC
==============

What is OpenPTC?
------------
OpenPTC is a community source Positive Train Control (:term:`PTC`) software. OpenPTC is leading the next generation of PTC software and giving the control back to the customer by providing a community source solution for your :term:`I-ETMS` key management system.

Why OpenPTC?
----------------

Community Source 
^^^^^^^^^^^^^^^^^^^
OpenPTC allows railroad operation and engineering staff to see the code and feel security, freedom, and comfort in knowing what their system is running. 

Next Generation KMS
^^^^^^^^^^^^^^^^^^^^^
We're leading the market in next-generation KMS solutions, but plan to maintain first-generation capability to allow migrating and interoperating with both generations of systems.

We plan to introduce more pieces of the PTC system to be available in our "open" model.

Installation

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

Glossary
=========

.. glossary::

      AMQP
         Advanced Message Queuing Protocol

      I-ETMS
         Interoperable Electronic Train Management System

      ITCM
         Interoperable Train Control Network

      KMS
         Key Management System

      OCI
         Open Container Initiative

      OPK
         Operational Private Key

      PSA1
         PTC Security Architecture, version 1

      PSA2
         PTC Security Architecture, version 2

      PTC
         Positive Train Control

      RSA
         Rivest-Shamir-Adleman

      TLS
         Transport Layer Security

      UTC
         Coordinated Universal Time

      YAML
         YAML Ain't Markup Language
