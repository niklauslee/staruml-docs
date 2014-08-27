=============================
Editing Elements and Diagrams
=============================


Create Diagram
==============

To create a Diagram:

1. Select first an element where a new Diagram to be contained as a child in **Explorer**.
2. Select **Model | Add Diagram | <DiagramType>** in Menu Bar or select **Add Diagram | <DiagramType>** in Context Menu.


Managing Working Diagrams
=========================

Open Diagram
------------

Close Diagram
-------------

Change Active Diagram
---------------------




Create Element
==============

You have following options to create Model Elements and View Elements.

Create Element from Toolbox
---------------------------

To create an Element from **Toolbox**:

1. Select **<ElementType>** in **Toolbox**.
2. Drag on the diagram as the size of element, or link two elements if the element is a kind of relationship.

.. note::
	In most cases, creating an element from **Toolbox** means creating the both Model Element and View Element. For example, if you create a Class in a Diagram from Toolbox, a Class Model Element and a Class View Model which referencing the Model Element will be created. See :ref:`concept-element`


Create View Element by Drag-and-Drop
------------------------------------

If you have already Model Elements, you can create View Elements referencing the Model Element on a Diagram.

To create a View Model by Drag-and-Drop:

1. Select a Model Element in **Explorer**.
2. Drag the Model Element and drop on a Diagram.


Create Model Element in Explorer
--------------------------------

To create a Model Element in **Explorer**:

1. Select first an element where a new Model Element to be contained as a child in **Explorer**.
2. Select **Model | Add | <ElementType>** in Menu Bar or select **Add | <ElementType>** in Context Menu.

Delete Elements
===============


.. seealso::
	:ref:`concept-element`
		Before deleting elements, you need to distinguish the difference of Model Element, View Element, and Diagram.


.. _edit-delete:

Delete View Elements
--------------------

To delete View Elements in a Diagram.

1. Select View Elements to be deleted in a Diagram.
2. Press :kbd:`Delete` or Select **Edit | Delete** in Menu Bar or **Delete** in Context Menu.

.. note::
	Deleting View Elements do not delete Model Elements.


.. _edit-delete-from-model:

Delete Model Elements
---------------------

To delete Model Elements:

1. Select Elements to be deleted in a Diagram or in **Explorer**.
2. Press :kbd:`Ctrl+Delete` or Select **Edit | Delete from Model** in Menu Bar or **Delete from Model** in Context Menu.

.. note::
	Model Elements are always deleted with corresponding View Elements.


.. _edit-select-elements:

Select Elements
===============

Select Elements in Diagram
--------------------------

You can select an Element in Diagram just by clicking on an Element. If you want to select additional elements while keeping current selections, click on element with pressing :kbd:`Shift`.
When you drag an area, Elements overlaps the area will be selected. Pressing :kbd:`Shift` also work with dragging.

If you want to select all elements in the Diagram, press :kbd:`Ctrl+A` or select **Edit | Select All** in Menu Bar or **Select All** in Context Menu.

.. note::
	Selecing an Element on a Diagram means selection of the both Model Element and View Element.


Select Model Element in Explorer
--------------------------------

In **Explorer**, you can select a Model Element by clicking on an Element.

If you want to select an element in **Explorer** corresponding to the a selected element in Diagram, press :kbd:`Ctrl+E` or select **Edit | Select In Explorer** in Menu Bar or **Select In Explorer** in Context Menu.


Copy, Cut and Paste
===================

When copying or cutting elements for pasting, a clear distinction has to be made between model elements and view elements. If a model element is copied, it has to be pasted under a model element. In this case, all the sub-elements contained in the selected element are copied together. View elements can be copied within the same diagram or to different diagrams. Copied view elements can be pasted in diagrams only; they cannot be pasted to model elements. Copying and pasting may also be restricted depending on the view element types and diagram types.

Copy and Paste View Elements in Diagram
---------------------------------------

1. Select view elements in a diagram to copy. (You can select multiple elements. See :ref:`edit-select-elements`)
2. Press :kbd:`Ctrl+C` or select **Edit | Copy** in Menu Bar or **Copy** in Context Menu. (To cut view elements, press :kbd:`Ctrl+X` or select **Edit | Cut** in Menu Bar or **Cut** in Context Menu)
3. Open the diagram where the copied view elements to be pasted. (See open diagram??)
4. Press :kbd:`Ctrl+V` or select **Edit | Paste** in Menu Bar or **Paste** in Context Menu. The copied view elements will be pasted to the active diagram.

Copy and Paste Model Elements in Explorer
-----------------------------------------

1. Select a model element to copy in **Explorer**.
2. Press :kbd:`Ctrl+C` or select **Edit | Copy** in Menu Bar or **Copy** in Context Menu. (To cut view elements, press :kbd:`Ctrl+X` or select **Edit | Cut** in Menu Bar or **Cut** in Context Menu)
3. Select a model element where the copied element will be pasted in **Explorer**.
4. Press :kbd:`Ctrl+V` or select **Edit | Paste** in Menu Bar or **Paste** in Context Menu. The copied view elements will be pasted to the active diagram. The copied model element can be pasted in where an element is able to contain.


.. note::
	Some elements are not allowed to copy, cut, and paste.

Undo and Redo
=============

All user actions can be un-executed and re-executed.

To undo actions:

1. Press :kbd:`Ctrl+Z` or select **Edit | Undo** in Menu Bar.

To redo undo-ed actions:

1. Press :kbd:`Ctrl+Y` or select **Edit | Redo** in Menu Bar.


Styling View Elements
=====================

Change Font
-----------

To change font face, size, and color of view elements:

1. Select view elements in diagram.
2. Show **FontDialog** by pressing :kbd:`Ctrl+Shift+F` or selecting **Format | Font...** in Menu Bar or Context Menu.
3. Select font face, size or color and press **OK** button.

You can also use :ref:`ui-style-editor` to change Font face, size, and color.


Change Line Color
-----------------

To change line color of view elements:

1. Select view elements in diagram.
2. Show **ColorDialog** for line color by pressing :kbd:`Ctrl+Shift+L` or selecting **Format | Line Color...** in Menu Bar or Context Menu.
3. Select line color and press **OK** button.

You can also use :ref:`ui-style-editor` to change line color.


Change Fill Color
-----------------

To change fill color of view elements:

1. Select view elements in diagram.
2. Show **ColorDialog** for fill color by pressing :kbd:`Ctrl+Shift+I` or selecting **Format | Fill Color...** in Menu Bar or Context Menu.
3. Select fill color and press **OK** button.

You can also use :ref:`ui-style-editor` to change fill color.


Change Line Style
------------------

Two kinds of line are supported

**Rectilinear**
	Good.


**Oblique**


Set Auto Resize
---------------



Set Word Wrap
-------------



Show Visibility
---------------

Show Namespace
--------------

Show Property
-------------

Stereotype Display
------------------

**None**

**Label**

**Decoration**

**Decoration with Label**

**Icon**

**Icon with Label**




Edit Properties
===============

You can edit properties of model elements in :ref:`ui-property-editor`.


Documenting Elements
====================

You can edit documentation of model elements in :ref:`ui-documentation-editor`.


Add Tags
========

Tag is an element to add extended properties to Model Elements

To create a Tag:

1. Select an Element in **Explorer** or in a Diagram.
2. Select **Model | Add | Tag** in Menu Bar or select **Add | Tag** in Context Menu.

Properties of Tag:

``name``
	Name of Tag

``kind``
	Kind of Tag. ``kind`` could be one of ``string``, ``reference``, ``boolean``, ``number``, or ``hidden``. if ``hidden`` is chosen, this Tag will not be shown on View Element.

``value``
	Value of Tag when ``kind`` is ``string``.

``reference``
	Reference value of Tag when ``kind`` is ``reference``.

``checked``
	Boolean value of Tag when ``kind`` is ``boolean``.

``number``
	Number value of Tag when ``kind`` is ``number``.

To show or hide Tags on View Elements, select **Show Property**


