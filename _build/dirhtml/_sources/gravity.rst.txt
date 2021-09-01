Gravity
=======

.. toctree::
   :maxdepth: 2
   :caption: Contents:


Setting An Orientation
^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: html
    
    <div class="box vertical">


Positioning Children
^^^^^^^^^^^^^^^^^^^^

.. code-block:: html
    
    <div class="box vertical" boxAlign="bottom right">

.. note::

    Available **boxAlign** Attribute Values:

    * top
    * bottom
    * left
    * right
    * verticalCenter
    * horizontalCenter
.. note::

    The Element Needs To Have The Box Class And Have The Orientation Set For The Gravity To Work.

    The **boxAlign** Attribute Values Can Be Directly Put With The Classes For Example: 
    ``<div class="box vertical bottom right">``. Although Keeping It Separate From Other Classes Recommended For Ease Of Development.
