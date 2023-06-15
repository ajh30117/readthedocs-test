About OpenPTC
=====

.. _installation:

What is OpenPTC?
------------
OpenPTC is a community source Positive Train Control (PTC) software. OpenPTC is leading the next generation of PTC software and giving the control back to the customer by providing a community source solution for your I-ETMS key management system.

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
----------------

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

