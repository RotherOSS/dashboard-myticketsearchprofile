.. image:: ../images/otobo-logo.png
   :align: center

.. toctree::
    :maxdepth: 2
    :caption: Contents

Overview
========
Summary
-------
This package adds a widget to the Dashboard with the tickets returned by a given customer ticket search template

Configuration
=============

System requirements
-------------------

Framework
^^^^^^^^^
OTOBO 11.0.x

Packages
--------
\-

Third-party software
--------------------
\-

Basic Usage
-------------------
Install by opening the Package Manager module from the Administration group in the Agent Interface. Select the package named Dashboard-MyTicketSearchProfile from the Online Repository. Click the associated  *Install* link on that line and respond affirmatively to any confirmation questions that follow.

In the Dasboard view, move the mouse pointer to the top right corner of the *Tickets Profile Search* widget, and click on the gear icon that will appear. Select the search template from the *Stored Search Profiles* field list and click on the *Save Changes* button. The widget will then display the corresponding tickets (see Figure 2.1).


 .. figure:: images/search_templates_dropdown.png
    :scale: 40%
    :alt: Dropdown input field for search templates in the dashboard *Stored Search Profiles* widget.

    Dropdown input field for search templates in the dashboard *Stored Search Profiles* widget.


Custom Configuration and Advanced Features
------------------------------------------
Not applicable

Configuration Reference
-----------------------
Frontend::Agent::View::Dashboard
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

DashboardBackend###0150-TicketSearchTemplate
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
Parameters for the dashboard backend of the tickets overview by search template of the agent interface. "Limit" is the number of entries shown by default. "Default" determines if the plugin is enabled by default or if the user needs to enable it manually. "CacheTTLLocal" is the cache time in minutes for the plugin. "Mandatory" determines if the plugin is always shown and can not be removed by agents. Note: Only Ticket attributes and Dynamic Fields (DynamicField_NameX) are allowed for DefaultColumns.

About
=======

Contact
-------
| Rother OSS GmbH
| Email: hello@otobo.io
| Web: https://otobo.io

Version
-------
Author: |doc-vendor| / Version: |doc-version| / Date of release: |doc-datestamp|
