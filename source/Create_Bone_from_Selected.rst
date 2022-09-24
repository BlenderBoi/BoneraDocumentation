Create Bone from Selected
-------------------------
.. list-table::

   * - Object
     - Edit Mesh
     - Edit Curve
     - Edit Armature
     - Pose

DEMO
====

Object Mode (Individual)
******************************

.. image:: /images/Create_Bone_Object_Mode_Individual.gif

Object Mode (Median)
**************************

.. image:: /images/Create_Bone_Object_Mode_Median.gif

Edit Mesh Mode (Individual)
*********************************

.. image:: /images/Create_Bone_Edit_Mesh_Mode_Individual.gif

Edit Mesh Mode (Median)
*********************************

.. image:: /images/Create_Bone_Edit_Mesh_Mode_Median.gif

Edit Curve Mode (Individual)
****************************

.. image:: /images/Create_Bone_Edit_Curve_Mode_Individual.gif

Edit Curve Mode (Median)
************************

.. image:: /images/Create_Bone_Edit_Curve_Mode_Median.gif

Edit Armature / Pose Mode (Individual)
**************************************
.. image:: /images/Create_Bone_Edit_Armature_Mode_Individual.gif

Edit Armature / Pose Mode (Median)
**********************************
.. image:: /images/Create_Bone_Edit_Armature_Mode_Median.gif

This Operator Create bone from Selected Objects / Elements base on the context.

This Operator can Create One Bone at the Selected Midpoint or It can Create A Bone for each selected items.

.. image:: /images/Create_Bones_From_Selected_Operator.png

Basic Parameter
+++++++++++++++

**Prefix:** Add Prefix to Base name Base on Preferences

**Base Name:** Base Name of the Bone

**Suffix:** Add Suffix to Base name Base on Preferences

**Deform:** Turn On/Off Deform for created bone

.. image:: /images/Create_Bones_From_Selected_Basic_Parameter.png

**Mode:**
*********
**Median**
  Create One Bone at the Selected Object / Elements

**Individual**
  Create Bones for each Selected Object / Elements

Contextual Option
+++++++++++++++++
**Use Hierarchy (Individual with Object Mode Only)**
****************************************************

.. image:: /images/Create_Bone_Use_Hierarchy.png

Create the Bones with the Hierarchy mimicking the Reference Object's Hierarchy

**Position Mode (Object Mode Only)**
****************************************

.. image:: /images/Create_Bone_Position_Mode.png

Ways to Calculate Midpoint of the Objects

**Origin**
   Use Object's Origin to create bone or calculate Median

**Geometry**
   Use Geometry's Midpoint/Median for Mesh, Curve or Armature Object to create bone or calculate Median, Other type of Object will use it's Origin

**Bounding Box**
   Use Geometry's Bounding Box Center for Mesh, Curve or Armature Object to create bone or calculate Median, Other type of Object will use it's Origin

**Elements**
************
Elements use to create the Bones

**Edit Mesh (Individual Mode Only)**
   - Vertices
   - Edges
   - Faces

.. image:: /images/Create_Bone_Element_Edit_Mesh.png

**Edit Armature / Pose**
   - **Center:** Use Bone Center to Create Bone or to Calculate Median or Bounding Box
   - **Head:** Use Bone Head to Create Bone or to Calculate Median or Bounding Box
   - **Tail:** Use Bone Tail to Create Bone or to Calculate Median or Bounding Box

.. image:: /images/Create_Bone_Element_Edit_Armature.png

**Bezier Handle (Edit Curve Only)**
***********************************
.. image:: /images/Create_Bone_Bezier_Handle.png

Create Bones For Bezier Handle

**Parent Bone (Edit Armature, Individual Mode and Own Armature Settings)**
**************************************************************************

.. image:: /images/Create_Bone_Parent_Bone.png

Parent the created bone to it's reference bone, this only works in Edit Armature Mode, Individual Mode, and Own Armature Settings.

Bind Option
+++++++++++
**Bind Mode**
*************
Method to bind the selected objects/elements to created bones

.. image:: /images/Create_Bone_Bind_Option_One.png

**Weight**
 Create Vertex Group and using the created bones for mesh Object

 Sub Options
    - **Add Armature Modifier:** Add Armature Modifier to relevant objects
    - **Parent To Armature:** Parent relevant object to Armature
    - **Parent None Mesh:** Parent Non Mesh Object to created Bone

**Parent Bone**
 Parent Object / Objects to created Bone

**Hook**
********
Hook Curve Points to selected

.. image:: /images/Create_Bone_Bind_Option_Two.png

Tail Option
+++++++++++

.. image:: /images/Create_Bone_Tail_Options.png

**Tail Mode**
*************

Set Up Bone's Tail Position

**Offset Tail From Head (Global)**
   Offset the tail from the head by the offset Vector in the Global Space

**Offset Tail From Head (Local)**
   Offset the tail from the head by the offset Vector in the Local Space

**3D Cursor**
   Use the position of 3D Cursor as the position of the bone's tail

**Normal (Edit Mesh Only)**
   Offset the tail from the head by the offset Vector in using the Normal of the Edge Center, Face or Vertex as Angle

**Roll (Edit Armature and Pose)**
   Offset the tail from the head by the offset Vector in using the Roll of the Bone as Angle

**Extend (Edit Armature and Pose)**
   Align the Created bone to the Reference Bone's, matching it's orientation and roll

Edit Mesh Mode:
   .. image:: /images/TailMode01.png

Edit Armature / Pose Mode:
   .. image:: /images/Tail_Mode02.png


**Tail Offset Amount**
**********************

.. image:: /images/Create_Bone_Tail_Options.png

The Vector Used to offset the tail

**Flip Bone**
*************

Flip the Position of the Head and Tail of the Created Bones


**Armature Option**
+++++++++++++++++++

.. image:: /images/Create_Bone_Armature_Option_NonArmature.png

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

.. admonition:: Edit Armature Or Pose

   If you are in Edit Armaute or Pose Mode, you have more options

      **Own Armature (Individual Only):** The Bone Created will be created on it's own Armature

      **Active Armature:** The Bone Created will be created on the active Armature Object

      **Choose Armature:** Works the Same way other Mode


   .. image:: /images/Create_Bone_Armature_Option_Armature.png
