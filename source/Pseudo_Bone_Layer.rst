.. _pseudo_bone_layer:

Pseudo Bone Layer
=================

**Select Armature Object**

.. image:: /images/Pseudo_Bone_Layer_Panel.png

Pseudo Bone Layer is a Throwaway Layer System made just for temporary Bone Management to Group Bones together for Editing Purpose

This is not meant to be use as a Final Bone Layer System

The Pseudo Bone Layer Stores Bone Name in it's layer and allow you to do different operation easily

Main Operator
-------------
**Assign:** Assign Bone to the Active Layer, Create one if there are no layers

**Unassign:** Unassign Bone from the Active Layer

Icons
-----
   **Layer Icons:**
      .. image:: /images/PBL_Icons.png

   - **Keyframe (Pose Mode Only):** Keyframe the bone in Layer
   - **Visibility:** Toogle Hide / Unhide of the bone in the layer (Similar to pressing H to Hide)
   - **Select:** Toogle Select / Des, Create one if there are no layerselect of the bone in the layer
   - **Deform:** Set the Deform State of the Bone in the Layer
   - **Remove:** Remove Layer


   You Can Enable or Disable the Icons in Icon Expose
      .. image:: /images/PBL_Icon_Expose.png


Bone List
---------

A Listbox that Shows the Bone Name Saved in the Active Layer, you can add or remove bone name manually

   .. image:: /images/Show_Bone_List.png

Icons
-----
- **Visibility:** Visibility of the Bone
- **Select:** Select State of the Bone
- **Deform:** Deform Property for the Bone
- **Reserve:** Prevent this Bone Name to be removed from "Clear Missing Bone" if the bone is missing
- **Rename:** Rename the Bone
- **Remove:** Remove the Bone Name from the Layer

.. admonition:: Missing Bone

   .. image:: /images/PBL_MissingBone.png

   Missing Bone: If there are missing bone, It will look like this, You can change the bone for the slot or Edit the name

Bone List Operator
------------------

.. image:: /images/PBL_Bone_List_Operator.png

- **Add By Name:** Add a Bone Name to the Layer, Regardless if the bone exist or not. (Reserved will be on)
- **Clear Missing Bone:** Remove Missing Bone that are not reserved from the layer
- **Batch Rename:** Batch Rename the Bone in the Layer


.. warning::

   Note: Because it saves bone name only, if you rename your bone then the bone is no longer affected by the layer
