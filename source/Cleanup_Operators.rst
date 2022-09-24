
Cleanup Operators
=================

Operators that helps cleans up Armature or Object to start a Object or Armature a New Clean Slate

Remove Custom Property
----------------------

Operator that removes Custom Property from Object, Armature Data, or Bones

.. image:: /images/Remove_Custom_Property.png

Parameter
   - **armature:** Removes Custom Property from active Object's Armature Data
   - **object:** Removes Custom Property from active Object
   - **editbone:** Remove Custom Property from all Pose Bones in Pose Mode
   - **posebone:** Removes Custom Property from all Edit Bones in Edit Mode

Remove Animation Data
---------------------

Operator that Clear your Animation Data from the Active Object

that means it will:
   1. Detach the object's current Action
   2. Remove All Drivers on the objects
   3. and Remove NLA Tracks from the object

.. admonition:: Info

   This Operator will Execute immediately without Any Pop Ups


Remove Non Deform Bone
----------------------

Remove all Non Deform Bone from Armature

.. image:: /images/RemoveNonDeformBone.png

**Move Bones to Layer 1**
   Move All Remaining Bone to Layer 1

**Clear Constraints**
   Remove Constraints from All Bone

**Unlock Transform**
   Unlock All Transform


Remove Bone Shapes
------------------

Remove Bone Shape from All bone in Active Armature

.. admonition:: Info

   This Operator will Execute immediately without Any Pop Ups
