Create Empties from Selected
----------------------------
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

.. image:: /images/Create_Empties_Object_Individual.gif

Object Mode (Median)
**************************

.. image:: /images/Create_Empties_Object_Mode_Median.gif

Edit Mesh Mode (Individual)
*********************************

.. image:: /images/Create_Empties_Edit_Mesh_Mode_Individual.gif

Edit Mesh Mode (Individual)
*********************************

.. image:: /images/Create_Empties_Edit_Mesh_Mode_Median.gif

Edit Curve Mode (Individual)
****************************

.. image:: /images/Create_Empties_Edit_Curve_Mode_Individual.gif

Edit Curve Mode (Median)
************************

.. image:: /images/Create_Empties_Edit_Curve_Mode_Median.gif

Edit Armature / Pose Mode (Individual)
**************************************

.. image:: /images/Create_Empties_Edit_Armature_Mode_Individual.gif

Edit Armature / Pose Mode (Median)
**********************************

.. image:: /images/Create_Empties_Edit_Armature_Mode_Median.gif



.. image:: /images/Create_Empties_From_Selected.png

This Operator Create Empty from Selected Objects / Elements base on the context.

This Operator can Create One Empty at the Selected Midpoint or It can Create an Empties for each selected items.

Basic Parameter
+++++++++++++++

**Name:** Base Name of the Empty

**Empty Shape:** Empty's Shape

**Display Size:** Empty's Display Size

.. image:: /images/Create_Empties_From_Basic_Parameter.png

**Mode:**
*********
**Median**
  Create One Empty at the Selected Object / Elements

**Individual**
  Create Empties for each Selected Object / Elements

**Position Mode (Object Mode Only)**
************************************

.. image:: /images/Create_Empties_From_Position_Mode.png

Ways to Calculate Midpoint of the Objects

**Origin**
   Use Object's Origin to create Empty or calculate Median

**Geometry**
   Use Geometry's Midpoint/Median for Mesh, Curve or Armature Object to create Empty or calculate Median, Other type of Object will use it's Origin

**Bounding Box**
   Use Geometry's Bounding Box Center for Mesh, Curve or Armature Object to create Empty or calculate Median, Other type of Object will use it's Origin

**Elements**
************
Elements use to create the Empties

**Edit Mesh (Individual Mode Only)**
   - Vertices
   - Edges
   - Faces

.. image:: /images/Create_Empties_From_Element_Edit_Mesh.png

**Edit Armature / Pose**
   - **Center:** Use Bone Center to Create Bone or to Calculate Median or Bounding Box
   - **Head:** Use Bone Head to Create Bone or to Calculate Median or Bounding Box
   - **Tail:** Use Bone Tail to Create Bone or to Calculate Median or Bounding Box

.. image:: /images/Create_Empties_From_Element_Edit_Armature.png

**Bezier Handle (Edit Curve Only)**
***********************************
.. image:: /images/Create_Empties_From_Bezier_Handle.png

Create Empties For Bezier Handle

**Parent To Objects (Edit Mesh Only)**
**************************************

Parent The Created Empties to it's Reference Object (Useful with Hook)

.. image:: /images/Create_Empties_From_Parent_To_Object.png

**Use Only Orphan (Object Mode Only)**
**************************************

Ignore Objects with parents

.. image:: /images/Create_Empties_From_Use_Only_Orphan.png

**Orientation**
***************

Set Up Bone's Tail Position

**Global**
   Set the Orientation of the Empty to be 0 in the global space

**Local**
   Set the Orientation of the Empty to be 0 in the Local space of the Reference Object

**3D Cursor**
   Use the Orientation of 3D Cursor for the created Empty

**Roll (Edit Armature, Pose)**
   Use the Roll of the bone as Oreintation for the created Empty

**Normal (Edit Mesh Only)**
   Orient the Empty to the Normal of the Selected Vertex, Edge Center or Face

Edit Mesh Mode:
   .. image:: /images/Create_Empties_From_Orientation_Edit_Mesh.png

Edit Armature / Pose Mode:
   .. image:: /images/Create_Empties_From_Orientation_Armature.png

Bind Option
+++++++++++
**Bind Mode**
*************
Method to bind the selected objects/elements to created Empty

**Parent (Object Mode)**
   Parent Reference Object to Created Empty

.. image:: /images/Create_Empty_Bind.png

**Hook (Edit Mesh and Edit Curve)**
   Hook selected Nurb Points, Bezier Points, Vertex, Edge or Face to Created Empty

.. image:: /images/Create_Empty_Bind_Hook.png

**Parent To Bone (Edit Armature and Pose)**
   Parent Created Empties **TO** Reference Bone

.. image:: /images/Create_Empty_Bind_Parent_To_Bone.png
