.. _uml-sequence-diagram:

=============================
Working with Sequence Diagram
=============================


To create a Sequence Diagram:

1. Select first an element where a new Sequence Diagram to be contained as a child.
2. Select **Model | Add Diagram | Sequence Diagram** in Menu Bar or select **Add Diagram | Sequence Diagram** in Context Menu.

In Sequence Diagram, you can use following elements.

* :ref:`uml-lifeline`
* :ref:`uml-message`
* :ref:`uml-endpoint`
* :ref:`uml-gate`
* :ref:`uml-state-invariant`
* :ref:`uml-continuation`
* :ref:`uml-combined-fragment`
* :ref:`uml-interaction-use`

.. seealso::
    `UML Sequence Diagram <http://www.uml-diagrams.org/sequence-diagrams.html>`_
        For more information about UML Sequence Diagram.


.. _uml-lifeline:

Lifeline
========

To create a Lifeline:

1. Select **Lifeline** in **Toolbox**.
2. Drag on the diagram as the size of Lifeline.

To create a Lifeline from a Classifier (Class, Interface, etc.) by Drag-and-Drop:

1. Drag a Classifier from **Explorer**.
2. Drop on the diagram.

To edit a Lifeline, you can do following actions:

* Use :ref:`quick-edit-lifeline` by double-click or press :kbd:`Enter` on a selected Lifeline.


.. _uml-message:

Message
=======

To create a Message (or Self Message):

1. Select **Message** (or **Self Message**) in **Toolbox**.
2. Drag from a Lifeline and drop on another Lifeline. (Just click on a Lifeline if you want to create a self message.)

You can change the kind of message by setting `messageSort` property in **Property Editor**:

* `synchCall` : Synchronous Call
* `asynchCall` : Asynchronous Call
* `asynchSignal` : Asynchronous Signal
* `createMessage` : Create Message
* `deleteMessage` : Delete Message
* `reply` : Reply Message

To edit a Message, you can do following actions:

* Use :ref:`quick-edit-message` by double-click or press :kbd:`Enter` on a selected Message.


.. _uml-endpoint:

Endpoint
========

To create an Endpoint:

1. Select **Endpoint** in **Toolbox**.
2. Click at the position on the diagram.


.. _uml-gate:

Gate
====

To create a Gate:

1. Select **Gate** in **Toolbox**.
2. Click at the position on the diagram.


.. _uml-state-invariant:

State Invariant
===============

To create a State Invariant:

1. Select **State Invariant** in **Toolbox**.
2. Click on a Lifeline where the State Invariant to be attached.


.. _uml-continuation:

Continuation
============

To create a Continuation:

1. Select **Continuation** in **Toolbox**.
2. Drag on the diagram as the size of Continuation.


.. _uml-combined-fragment:

Combined Fragment
=================

To create a Combined Fragment:

1. Select **Combined Fragment** in **Toolbox**.
2. Drag on the diagram as the size of Combined Fragment.

To edit a Combined Fragment, you can do following actions:

* Use :ref:`quick-edit-combined-fragment` by double-click or press :kbd:`Enter` on a selected Combined Fragment.


.. _uml-interaction-use:

Interaction Use
===============

To create a Interaction Use:

1. Select **Interaction Use** in **Toolbox**.
2. Drag on the diagram as the size of Interaction Use.


