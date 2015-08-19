==============
Basic Concepts
==============

.. _concept-project:

Project
=======

*Project* is a top-level element stored as a single file.

Modeling a software system requires describing multiple models because it is not enough to describe the system with a single perspective, so we typically make multiple models such as *Use-Case Model*, *Design Model*, *Component Model*, *Deployment Model*, or others in a *Project*.

Typically *Project* is organized as a set of *UMLModels*, *UMLPackages*, or *UMLSubsystems*. If you want to know more about UML Elements, please refer to OMG UML Specification.

.. seealso::
    :ref:`organizing-project`
        See the Organizing Project section.

.. _concept-element:

Model vs. Diagram
=================

Many users are confusing the difference between *diagramming or drawing* tools such as Microsoft Visio and *modeling* tools such StarUML or Rational Software Architect. First you need to understand a diagram is not a model.

*Model* or *software model* is a description of any aspect of a software system such as structure, behavior, requirement, and so on. A software model can be represented in textual, mathmatical or visual form. A *Model element* is a building block of a software model.

A *Diagram* is a visual geometric symbolic representation of a software model. A software model can be represented in one or more diagrams with different aspects. For example, a diagram can focus on class hierarchical structure while another diagram can focus on interaction between objects. Diagrams consists of *view elements*, which are visual representations of a *model element*.

A *model element* typically has multiple corresponding *view elements*. A model element has its own data such as *name*, *stereotype*, *type*, etc. A view element just renders the corresponding model element in a diagram. View elements may exists multiple times in a diagram or in different diagrams. If the *name* of a model element changed, all corresponding view elements reflect the changes in their diagrams.

.. _concept-fragment:

Fragment
========

A fragment is a part of a project saved as a separate file with the extension name ``.mfj``. Any element can be exported as a fragment, but typically *UMLPackage*, *UMLModel*, and *UMLSubsystem* are the candidates. Once a fragment is exported as a file, the fragment can be reused by importing in a project.

.. seealso::
    :ref:`import-fragment`
        To import a fragment file.

    :ref:`export-fragment`
        To export an element to a fragment file.

.. _concept-profile:

Profile
=======

UML (Unified Modeling Language) is so general-purpose modeling language that could be used to express any kinds of software-intensive systems. In this reason, using UML for a specific domain or platform is not sufficient, so you may need to define UML Profile. StarUML provides UML profiles which can be used to expand UML. For example, UML profiles can be used for the following purposes.

* Profiles for specific programming languages (C/C++, Java, C#, Python, etc.)
* Profiles for specific development methodologies (RUP, Catalysis, UML Components, etc.)
* Profiles for specific domains (EAI, CRM, SCM, ERP, etc.)


.. _concept-extension:

Extension
=========

An extension is a package which adds new features to StarUML. For example, an extension can extend menus, UIs, dialogs, modeling notations, preferences, etc. An extension can be written in JavaScript, CSS3, and HTML5 and can use Node.js integrated in StarUML. Extensions can be easily installed, uninstalled, and updated via the main extension registry.

.. seealso::
    :doc:`managing-extensions`
        To use extensions.
