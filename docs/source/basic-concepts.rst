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

Model Element, View Element, and Diagram
========================================

*Element* is building block constitutes a software model. There are three kinds of *Elements*: *Model Element*, *View Element*, and *Diagram*.

You need to have a clear conceptual distinction between Model Element, View Element and Diagram. A *Model Element* is an element that contains information for a software model. A *View Element* is a visual representation of a particular a *Model Element*. A *Diagram* is a collection of *View Elements* in order to represent a particular perspective of the system.

.. _concept-fragment:

Fragment
========

A fragment is a part of a project saved as a separate file with the extension name ``.umlf``. Any element can be exported as a fragment, but typically *UMLPackage*, *UMLModel*, and *UMLSubsystem* are the candidates. Once a fragment is exported as a file, the fragment can be reused by importing in a project.

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
