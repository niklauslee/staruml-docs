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
* Add Attribute - See :ref:`uml-attribute`
* Add Operation - See :ref:`uml-operation`
* Add TemplateParameter - See :ref:`uml-template-parameter`


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


.. _uml-template-parameter:

Template Parameter
==================



.. _uml-interface:

Interface
=========

To create an Interface:

1. Select **Interface** in **Toolbox**.
2. Drag on the diagram as the size of Interface.

To create a Interface (model element only) by Menu:

1. Select an Element where a new Interface to be contained.
2. Select **Model | Add | Interface** in Menu Bar or **Add | Interface** in Context Menu.

To show Quick Edit for Interface, double-click or press :kbd:`Enter` on a selected Interface. Quick Edit allows following actions:

* Change ``visibility`` - Select a visibility kind in the dropdown.
* Edit name expression
* Add Attribute - Press Add Attribute button.
* Add Operation - Press Add Operation button.

You can add Attributes, Operations, and Template Parameters to an Interface.

* See :ref:`uml-attribute`
* See :ref:`uml-operation`
* See :ref:`uml-template-parameter`


.. _uml-generalization:

Generalization
==============

To create an Generalization:

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

Aggregation is an association whose ``aggregation`` propery value is ``shared``.

To create an Aggregation:

1. Select **Aggregation** in **Toolbox**.
2. Drag from an element (to be a part) and drop on another element (to be whole).


.. _uml-composition:

Composition
===========

Composition is an association whose ``aggregation`` propery value is ``composite``.

To create a Composition:

1. Select **Composition** in **Toolbox**.
2. Drag from an element (to be a part) and drop on another element (to be whole).


.. _uml-dependency:

Dependency
==========

To create an Dependency:

1. Select **Dependency** in **Toolbox**.
2. Drag from an element (client) and drop on another element (supplier).


.. _uml-interface-realization:

Interface Realization
=====================


.. _uml-signal:

Signal
======


.. _uml-data-type:

DataType
========


.. _uml-primitive-type:

PrimitiveType
=============


.. _uml-enumeration:

Enumeration
===========


.. _uml-association-class:

AssociationClass
================

