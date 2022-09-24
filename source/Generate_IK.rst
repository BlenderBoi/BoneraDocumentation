Generate IK
===========

.. list-table::

   * - Edit Armature
     - Pose

.. image:: /images/Generate_IK.gif

This Operator Helps Set Up IK for active bone

It Generate IK Controller Bone and Pole Bone if specified

.. image:: /images/Generate_IK.png

This can be useful to Rig IK for Limbs

General Options
---------------

.. image:: /images/Generate_IK_General.png

**Chain Length:** Chain Length the IK Constraint Use

**Generate Pole:** Generate Pole Bone

**Pre Clear Constraint:** Pre Clear Existing Constraint from the active Bone

**Generate Pole:** Generate Pole Bone

**Pre Clear Constraint:** Pre Clear Existing Constraint from the active Bone

IK Controller Options
---------------------

**IK Controller Create Mode:**

   Method of creating ik controller


   - **Generate Bone:** Create Controller at Tail of Active Bone, and Offset Tail from Head by Vector

      **Offset Vector:** The Vector for Bone Tail to Offset from Bone Head

      .. image:: /images/Generate_IK_IK_Controller.png

   - **Use Existing Bone:** Use Existing Bone as IK Controller

      **Bone Picker:** The bone to be use as IK Controller

      .. image:: /images/Generate_IK_IK_Controller_Copy_Child.png

   - **Copy Child:** Copy the First Child of Active Bone and Use it as IK Controller

      **Constraint Child Copy:** Constraint IK Controller to the Reference Child Bone

      .. image:: /images/Generate_IK_IK_Controller_Copy_Child.png

Pole Controller Options
-----------------------

**Pole Mode:**

   .. image:: /images/Generate_IK_Pole_Controller_Bone_Roll.png

   - **Bone Bending:** Create Pole Bone Base on the Bone Bending
   - **Bone Roll:** Create Pole Bone Base on the Bone Roll
   - **Offset Distance:** Distance Offset from the Active bone (Not Consistent)

**Bone Roll and Orientation (Bone Bending):**

   .. image:: /images/Generate_IK_Pole_Controller_Bone_Bending.png

   - **Align Bone Roll:** Align Bone Roll to the Pole Bone (Avoid using this on Already Animated Rig)

**Pole Tail Offset:** Offset amount for Bone Tail From Bone Head
