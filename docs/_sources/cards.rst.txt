Cards
=====

.. toctree::
   :maxdepth: 2
   :caption: Contents:


Creating A Simple Card
^^^^^^^^^^^^^^^^^^^^^^
.. code-block:: html

   <div class="cardContainer">
      <div class="card">
      </div>
   </div>

Creating A Card With Custom Round Corners And Padding
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. code-block:: html

   <div class="cardContainer" style="--border-corner: 5px; --padding: 25px;">
      <div class="card">
      </div>
   </div>

Make A Mouse Following Tilted Card
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
.. code-block:: html

   <div class="cardContainer">
      <div class="card followMouse">
      </div>
   </div>

.. note::

   The Card **HAS** To Be Inside A **``div.cardContainer``** In Order To Follow Mouse.

   **Below Is An Example Of The Mouse Following Card**:

   |Mouse Follow Example|
   

.. |Mouse Follow Example| image:: cards.mouse-follow.example.gif
  :width: 400
  :alt: Alternative text