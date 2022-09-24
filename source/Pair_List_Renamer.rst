.. _pair_list_renamer:

Pair List Renamer
=================

.. image:: /images/Pair_List_Renamer.gif



Pair List Renamer is a Tool to Rename a list of name to another pair of list of name. This tool can rename Bone Name, Vertex Group, and Shapekeys

This tool is useful if you have two Naming Convention and you want to match rename multiple file of it.

You can Export the Renamer List as JSON file to be imported into other file for use.


.. image:: /images/PairRenamerList.png

Initial
-------

.. image:: /images/Pair_List_Renamer_Init.png

When You First time Open the Panel, there is no Renamer List, and you need to Create One

Renamer List
------------

.. image:: /images/Renamer_List_List.png

Renamer List is a way to organize your renamer

Operator
--------

**Rename List**

   Using the List to Match Rename the Name on the Left to the Name on the Right

   .. image:: /images/PLR_Rename_List.png

  **Object**
      Object to be Rename

  **Mode**
      - **Bones (Armature Object):** Match Rename the Bone using the Pair List
      - **Vertex Groups (Mesh Object):** Match Rename the Vertex Groups using the Pair List
      - **Shapekeys (Mesh Object):** Match Rename the Shapekeys using the Pair List

**Load Name**

   Load Vertex Groups / Bones / Shapekeys Name into the list

   .. image:: /images/PLR_Load_Name.png

   **Object**
      Object to be Rename

   **Mode**
      - **Bones (Armature Object):** Match Rename the Bone using the Pair List
      - **Vertex Groups (Mesh Object):** Match Rename the Vertex Groups using the Pair List
      - **Shapekeys (Mesh Object):** Match Rename the Shapekeys using the Pair List

**Export & Import**

Export or Import the List into Json File to be use in other blender file
