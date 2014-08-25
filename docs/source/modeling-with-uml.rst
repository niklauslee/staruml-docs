=================
Modeling with UML
=================


Organizing Project
==================

A system is typically described in multiple perspectives. You can start a modeling project by selecting a template. To start a project with a template, select **File | New From Template | <TemplateName>**. StarUML supports 4 default templates:

* **UMLMinimal** - A single model with UML Standard Profile.
* **UMLConventional** - Use Case Model, Analysis Model, Design Model, Implementation Model, and Deployment Model with UML Standard Profile.
* **4+1 View Model** - Pilippe Kruchten's `4+1 Architectural View Model <http://en.wikipedia.org/wiki/4%2B1_architectural_view_model>`_.
* **Rational** : Approach of Rational Rose Tool.

If you don't want to use pre-defined templates, you need to make your own project structure.


.. _uml-class-diagram:

Working with Class Diagram
==========================

In Class Diagram, StarUML supports following elements in **Toolbox**.

* Class
* Interface
* Association
* Directed Association
* Aggregation
* Composition
* Dependency
* Generalization
* Interface Realization

.. seealso::
    `UML Class Diagram <http://www.uml-diagrams.org/class-diagrams-overview.html>`_
        For more information about UML Class Diagram.


.. _uml-class:

Class
-----

To create a Class:

1. Select **Class** in **Toolbox**.
2. Drag on the diagram as the size of Class.

To change Stereotype Display:

1. Select a Class.
2. Select a display kind in **Format | Stereotype Display | <DisplayKind>**.

You can add Attributes, Operations, and Template Parameters to a Class.

* See :ref:`uml-attribute`
* See :ref:`uml-operation`
* See :ref:`uml-template-parameter`

.. _uml-attribute:

Attribute
---------

You can add Attribute to Classifiers (Class, Interface, Signal, DataType, PrimitiveType, Enumeration, Component, Node, Artifact, Use Case, and Actor).

To add Attribute:

1. Select a Classifier.
2. Select **Model | Add | Attribute**.

To add Attribute by Quick Edit:

1. Double-click on a Classifier or select a Classifier and then press :kbd:`Enter` to show Quick Edit.
2. Click **Add Attribute** button.

To add Attribute by Context Menu:

1. Select a Classifier.
2. Right-click to show Context Menu
3. Select **Add | Attribute**.

To edit Attribute in Quick Edit:

1. Double-click on Attribute in the diagram area to show Quick Edit.
2. Enter an attribute expression in the input box.

Attribute Expression: ?

To delete Attribute:

1. Select a Attribute.
2. Press :kbd:`Ctrl+Delete` or select **Edit | Delete from Model**.

Reorder Attributes:

.. _uml-operation:

Operation
---------

To add Operation:

1. Select a Class.
2. Select **Model | Add | Operation**.

To add Operation by Quick Edit:

1. Double-click on a Class to show Quick Edit.
2. Click **Add Operation** button.

To add Operation by Context Menu:

1. Select a Class.
2. Right-click to show Context Menu
3. Select **Add | Operation**.


.. _uml-template-parameter:

Template Parameter
------------------



.. _uml-interface:

Interface
---------

.. _uml-generalization:

Generalization
--------------

To create an Generalization:

1. Select **Generalization** in **Toolbox**.
2. Drag from an element (to be special) and drop on another element (to be general).


.. _uml-association:

Association
-----------

To create an Association (or Directed Association):

1. Select **Association** (or **Directed Association**) in **Toolbox**.
2. Drag from an element and drop on another element.

.. _uml-aggregation:

Aggregation
-----------

Aggregation is an association whose ``aggregation`` propery value is ``shared``.

To create an Aggregation:

1. Select **Aggregation** in **Toolbox**.
2. Drag from an element (to be a part) and drop on another element (to be whole).

.. _uml-composition:

Composition
-----------

Composition is an association whose ``aggregation`` propery value is ``composite``.

To create a Composition:

1. Select **Composition** in **Toolbox**.
2. Drag from an element (to be a part) and drop on another element (to be whole).


.. _uml-dependency:

Dependency
----------

To create an Dependency:

1. Select **Dependency** in **Toolbox**.
2. Drag from an element (client) and drop on another element (supplier).

.. _uml-interface-realization:

Interface Realization
---------------------

.. _uml-package-diagram:

Working with Package Diagram
============================

.. seealso::
    `UML Package Diagram <http://www.uml-diagrams.org/package-diagrams-overview.html>`_
        For more information about UML Package Diagram.

Working with Composite Structure Diagram
========================================

.. seealso::
    `UML Composite Structure Diagram <http://www.uml-diagrams.org/composite-structure-diagrams.html>`_
        For more information about UML Composite Structure Diagram.


Working with Object Diagram
===========================


Working with Component Diagram
==============================


Working with Deployment Diagram
===============================


.. _uml-use-case-diagram:

Working with Use Case Diagram
=============================

.. seealso::
    `UML Use Case Diagram <http://www.uml-diagrams.org/use-case-diagrams.html>`_
        For more information about UML Use Case Diagram.

Create Use Case Diagram
-----------------------

To create a Use Case Diagram, select first an element where a new Use-Case Diagram to be contained as a child, and then select **Model | Add Diagram | Use Case Diagram** in Menu Bar or right-click on the element to show Context Menu and then select **Add Diagram | Use Case Diagram**.


.. _uml-actor:

Actor
-----

To create an Actor:

1. Select **Actor** in **Toolbox**.
2. Drag on the diagram as the size of Actor.

To add Attribute and Operation by Quick Edit:

1. Double-click on an Actor to show Quick Edit.
2. Click **Add Attribute** button or **Add Operation** button.

.. _uml-use-case:

Use Case
--------

To create a Use Case:

1. Select **Use Case** in **Toolbox**.
2. Drag on the diagram as the size of Use Case.


To change stereotype display:

1. Select a Use Case.
2. Select a display kind in **Format | Stereotype Display | <DisplayKind>**.


To add Extension Point by Quick Edit:

1. Double-click on a Use Case to show Quick Edit.
2. Click **Add ExtensionPoint** button.


Generalization
--------------

See :ref:`uml-generalization`.

Association
-----------

See :ref:`uml-association`.

Dependency
----------

See :ref:`uml-dependency`.


.. _uml-include:

Include
-------

To create an Include:

1. Select **Include** in **Toolbox**.
2. Drag from a Use Case and drop on another Use Case (to be included).

.. _uml-extend:

Extend
------

To create an Extend:

1. Select **Extend** in **Toolbox**.
2. Drag from a Use Case (to be extended) and drop on another Use Case.



Working with Sequence Diagram
=============================


Working with Communication Diagram
==================================


Working with Statechart Diagram
===============================

Working with Activity Diagram
=============================





Working with Profile Diagram
============================

* Import Profile
* Writing Profiles
