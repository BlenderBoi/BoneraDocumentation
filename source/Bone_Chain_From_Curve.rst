Bone Chain From Curve
=====================

.. list-table::

   * - Object
     - Edit Curve

.. image:: /images/Bone_Chain_From_Curve_Demo.gif

This Operator Generates a Bone chain from Curve, The Created Curve follows the direction of the curve

.. image:: /images/Create_Bone_Chain_From_Curve.png

Behaviour
   Object Mode
      Create Bone Chain for all Nurb Points and Bezier Points for the Object

   Edit Curve Mode
      Create Bone Chain **selected** Nurb Points and Bezier Points for the Object

General Settings
++++++++++++++++

.. image:: /images/Create_Bone_Chain_From_Curve_General.png

**Prefix:** Add Prefix to Base name Base on Preferences

**Base Name:** Base Name of the Bone

**Suffix:** Add Suffix to Base name Base on Preferences

**Use Deform:** Turn On/Off Deform for created bone

**Connect Bone:** Tries to Connect Bone If Relevant

**Hook:** Hook Curve Points to Created Bones

**Bezier Handle (Edit Curve Only):** Create Bones For Bezier Handle

Tail Option
+++++++++++
For the Last Bone of each Chain

.. image:: /images/CBOH_Tail_Option.png

**Tail Mode**
*************

Set Up Bone's Tail Position

**Offset Tail From Head (Global)**
   Offset the tail from the head by the offset Vector in the Global Space

**Offset Tail From Head (Local)**
   Offset the tail from the head by the offset Vector in the Local Space

**Tail Offset Amount**
**********************

The Vector Used to offset the tail

**Armature Option**
+++++++++++++++++++

**Armature Name / Armature Picker**
***********************************
Name for New Armature or Pick a Existing Armature to Add Bone to

**Armature Choice**
*******************
Choose to create New Armature or Use Existing Armature

   **New:** Create bone to a New Armature that uses the Name Above
      .. image:: /images/CBOH_Armature_Settings.png


   **Exist:** Create bone to existing Armature above
      .. image:: /images/CBOH_Armature_Exist.png

**Update**
**********

Set the Operator to Existing and Use the Created Armature After Creating the Armature
