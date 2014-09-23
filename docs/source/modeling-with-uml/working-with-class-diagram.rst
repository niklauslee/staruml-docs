.. _uml-class-diagram:

==========================
Working with Class Diagram
==========================

To create a Class Diagram:

1. Select first an element where a new Class Diagram to be contained as a child.
2. Select **Model | Add Diagram | Class Diagram** in Menu Bar or select **Add Diagram | Class Diagram** in Context Menu.

In Class Diagram, you can use following elements.

* :ref:`uml-class`
* :ref:`uml-interface`
* :ref:`uml-association`
* :ref:`uml-aggregation`
* :ref:`uml-composition`
* :ref:`uml-dependency`
* :ref:`uml-generalization`
* :ref:`uml-interface-realization`
* :ref:`uml-signal`
* :ref:`uml-data-type`
* :ref:`uml-primitive-type`
* :ref:`uml-enumeration`
* :ref:`uml-association-class`
* :ref:`uml-package`
* :ref:`uml-model`
* :ref:`uml-subsystem`
* :ref:`uml-containment`

.. seealso::
    `UML Class Diagram <http://www.uml-diagrams.org/class-diagrams-overview.html>`_
        For more information about UML Class Diagram.


.. _uml-class:

Class
=====

To create a Class:

1. Select **Class** in **Toolbox**.
2. Drag on the diagram as the size of Class.

To create a Class (model element only) by Menu:

1. Select an Element where a new Class to be contained.
2. Select **Model | Add | Class** in Menu Bar or **Add | Class** in Context Menu.

To edit a Class, you can do following actions:

* Use :ref:`quick-edit-classifier` by double-click or press :kbd:`Enter` on a selected Class.
* Add Attribute - See :ref:`uml-attribute`.
* Add Operation - See :ref:`uml-operation`.
* Add Template Parameter - See :ref:`uml-template-parameter`.

To suppress Attributes, see :ref:`format-suppress-attributes`.

To suppress Operations, see :ref:`format-suppress-operations`.

To hide Operation signatures, see :ref:`format-show-operation-signature`.

.. _uml-attribute:

Attribute
=========

To add an Attribute:

1. Select a Classifier.
2. Select **Model | Add | Attribute** in Menu Bar or **Add | Attribute** in Context Menu.

To edit an Attribute, you can do following actions:

* Use :ref:`quick-edit-attribute` by double-click or press :kbd:`Enter` on a selected Attribute.

.. _uml-operation:

Operation
=========

To add an Operation:

1. Select a Classifier.
2. Select **Model | Add | Operation** in Menu Bar or **Add | Operation** in Context Menu.

To edit an Operation, you can do following actions:

* Use :ref:`quick-edit-operation` by double-click or press :kbd:`Enter` on a selected Operation.
* Add Parameter - See :ref:`uml-parameter`.

To hide Operation signatures, see :ref:`format-show-operation-signature`.


.. _uml-parameter:

Add Parameter
=============

To add a Parameter:

1. Select an Operation.
2. Select **Model | Add | Parameter** in Menu Bar or **Add | Parameter** in Context Menu.


.. _uml-template-parameter:

Template Parameter
==================

To add a Template Parameter:

1. Select an Element.
2. Select **Model | Add | Template Parameter** in Menu Bar or **Add | Template Parameter** in Context Menu.

To edit an Template Parameter, you can do following actions:

* Use :ref:`quick-edit-template-parameter` by double-click or press :kbd:`Enter` on a selected Template Parameter.


.. _uml-interface:

Interface
=========

To create an Interface:

1. Select **Interface** in **Toolbox**.
2. Drag on the diagram as the size of Interface.

To create an Interface (model element only) by Menu:

1. Select an Element where a new Interface to be contained.
2. Select **Model | Add | Interface** in Menu Bar or **Add | Interface** in Context Menu.

To edit an Interface, you can do following actions:

* Use :ref:`quick-edit-classifier` by double-click or press :kbd:`Enter` on a selected Interface.
* Add Attribute - See :ref:`uml-attribute`
* Add Operation - See :ref:`uml-operation`
* Add Template Parameter - See :ref:`uml-template-parameter`

To show an Interface as Lollipop notation, Interface should be realized (See :ref:`uml-interface-realization`) and then change Stereotype Display to Icon or Icon with Label (See :ref:`format-stereotype-display`).

To show an Interface as Socket notation, Interface should have dependants (See :ref:`uml-dependency`) and then change Stereotype Display to Icon or Icon with Label (See :ref:`format-stereotype-display`).


.. _uml-generalization:

Generalization
==============

To create a Generalization:

1. Select **Generalization** in **Toolbox**.
2. Drag from an element (to be special) and drop on another element (to be general).


.. _uml-association:

Association
===========

To create an Association (or Directed Association):

1. Select **Association** (or **Directed Association**) in **Toolbox**.
2. Drag from an element and drop on another element.


.. _uml-aggregation:

Aggregation
===========

To create an Aggregation:

1. Select **Aggregation** in **Toolbox**.
2. Drag from an element (to be a part) and drop on another element (to be whole).

.. note::
    Aggregation is an association whose ``aggregation`` propery is ``shared``.

.. _uml-composition:

Composition
===========

To create a Composition:

1. Select **Composition** in **Toolbox**.
2. Drag from an element (to be a part) and drop on another element (to be whole).

.. note::
    Composition is an association whose ``aggregation`` propery is ``composite``.

.. _uml-dependency:

Dependency
==========

To create an Dependency:

1. Select **Dependency** in **Toolbox**.
2. Drag from an element (client) and drop on another element (supplier).


.. _uml-interface-realization:

Interface Realization
=====================

To create an Interface Realization:

1. Select **Interface Realization** in **Toolbox**.
2. Drag from an element (realizing) and drop on an interface (to be realized).


.. _uml-signal:

Signal
======

To create a Signal:

1. Select **Signal** in **Toolbox**.
2. Drag on the diagram as the size of Signal.

To create a Signal (model element only) by Menu:

1. Select an Element where a new Signal to be contained.
2. Select **Model | Add | Signal** in Menu Bar or **Add | Signal** in Context Menu.

To edit a Signal, you can do following actions:

* Use :ref:`quick-edit-classifier` by double-click or press :kbd:`Enter` on a selected Signal.
* Add Attribute - See :ref:`uml-attribute`
* Add Operation - See :ref:`uml-operation`
* Add Template Parameter - See :ref:`uml-template-parameter`


.. _uml-data-type:

DataType
========

To create a DataType:

1. Select **DataType** in **Toolbox**.
2. Drag on the diagram as the size of DataType.

To create a DataType (model element only) by Menu:

1. Select an Element where a new DataType to be contained.
2. Select **Model | Add | DataType** in Menu Bar or **Add | DataType** in Context Menu.

To edit a DataType, you can do following actions:

* Use :ref:`quick-edit-classifier` by double-click or press :kbd:`Enter` on a selected DataType.
* Add Attribute - See :ref:`uml-attribute`
* Add Operation - See :ref:`uml-operation`
* Add Template Parameter - See :ref:`uml-template-parameter`


.. _uml-primitive-type:

PrimitiveType
=============

To create a PrimitiveType:

1. Select **PrimitiveType** in **Toolbox**.
2. Drag on the diagram as the size of PrimitiveType.

To create a PrimitiveType (model element only) by Menu:

1. Select an Element where a new PrimitiveType to be contained.
2. Select **Model | Add | PrimitiveType** in Menu Bar or **Add | PrimitiveType** in Context Menu.

To edit a PrimitiveType, you can do following actions:

* Use :ref:`quick-edit-classifier` by double-click or press :kbd:`Enter` on a selected PrimitiveType.
* Add Attribute - See :ref:`uml-attribute`
* Add Operation - See :ref:`uml-operation`
* Add Template Parameter - See :ref:`uml-template-parameter`


.. _uml-enumeration:

Enumeration
===========

To create an Enumeration:

1. Select **Enumeration** in **Toolbox**.
2. Drag on the diagram as the size of Enumeration.

To create an Enumeration (model element only) by Menu:

1. Select an Element where a new Enumeration to be contained.
2. Select **Model | Add | Enumeration** in Menu Bar or **Add | Enumeration** in Context Menu.

To edit a Enumeration, you can do following actions:

* Use :ref:`quick-edit-enumeration` by double-click or press :kbd:`Enter` on a selected Enumeration.
* Add EnumerationLiteral - See :ref:`uml-enumeration-literal`
* Add Attribute - See :ref:`uml-attribute`
* Add Operation - See :ref:`uml-operation`
* Add Template Parameter - See :ref:`uml-template-parameter`

To suppress Literals, see :ref:`format-suppress-literals`.


.. _uml-enumeration-literal:

Enumeration Literal
===================

To add an Enumeration Literal:

1. Select a Classifier.
2. Select **Model | Add | Enumeration Literal** in Menu Bar or **Add | Enumeration Literal** in Context Menu.

To edit an Enumeration Literal, you can do following actions:

* Use :ref:`quick-edit-enumeration-literal` by double-click or press :kbd:`Enter` on a selected Enumeration Literal.


.. _uml-association-class:

AssociationClass
================

To create an Association Class by linking two Classifiers:

1. Select **Association Class** in **Toolbox**.
2. Drag from an element and drop on another element.
3. An Association and a Class connected to the association will be created.


To create an Association Class by linking Association and Class:

1. Select **Association Class** in **Toolbox**.
2. Drag from an Association (or Class) and drop on a Class (or Association).
3. The Class will be connected to the Association.

